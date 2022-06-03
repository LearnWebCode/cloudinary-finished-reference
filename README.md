# Important Note

Please, please, please do **not** accidentally leak your environment variables in your .env file on your Github / GitLab / elsewhere.

99.99% of the time you should use .gitignore to exclude your .env file from your repository.

I only included it in this example because it's super common for people following lessons to include a typo in the variable name for environment variables, and then never be able to figure out why there example is not working.
