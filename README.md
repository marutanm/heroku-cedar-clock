```
# clone project
$ git clone git://github.com/marutanm/heroku-cedar-clock.git

# test locally
$ foreman start 

# test on heroku
$ heroku create --stack cedar
$ git push heroku master
$ heroku scale web=0 clock=1
$ heroku logs --tail
```
