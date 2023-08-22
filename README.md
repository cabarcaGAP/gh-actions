# gh-actions
Add a file called cypress.env.json with this:
  {
    "SECRET_PASS":"Password123"
  }

  Yes, the idea is not to expose that ^ password to the repo, that's why the cypress.env.json is part of the gitignore and does not log the password when typed. 
