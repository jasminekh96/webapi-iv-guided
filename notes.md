# Deployment Notes 

# Quote: 

> Developers get paid to deliver value, not lines of code.

> A Pragmatic developer 

# Jargon 
_"Single Responsibility Principle"_

Do one thing really well. Only one reason to change. 

# Deployment 

- extract configuration into environment variables.
- setup Continous deployment from Github to Heroku.
  -commit and push to GitHub and the api gets updated on Heroku 

# Switching Remotes 
- `git remote set-url origin url to new empty repository on GitHub`
- `git remote -v` `to see where your remotes point`