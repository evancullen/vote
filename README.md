# Vote App Frontend 
[![FOSSA Status](https://app.fossa.com/api/projects/git%2Bgithub.com%2Fevancullen%2Fvote.svg?type=shield)](https://app.fossa.com/projects/git%2Bgithub.com%2Fevancullen%2Fvote?ref=badge_shield)


This is a frontend app, part of [Example Voting App](https://github.com/schoolofdevops/example-voting-app).  

To build and run this app as a container, 

  * use `python:alpine3.17` container base image
  * map/expose `container port 80`
  * copy over the source code 
  * run `pip install -r requirements.txt` to install dependencies
  * launch the app with `gunicorn app:app -b 0.0.0.0:80` command

  
  


## License
[![FOSSA Status](https://app.fossa.com/api/projects/git%2Bgithub.com%2Fevancullen%2Fvote.svg?type=large)](https://app.fossa.com/projects/git%2Bgithub.com%2Fevancullen%2Fvote?ref=badge_large)