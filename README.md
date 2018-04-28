# Ruby on Rails Tutorial sample application

This is the sample application I created for
[*Ruby on Rails Tutorial:
Learn Web Development with Rails*](http://www.railstutorial.org/)
by [Michael Hartl](http://www.michaelhartl.com/). This app was made solely for
educational purposes and but is a fully functioning web application with user 
authorization, authentication, and micropost functionality. Users are also
able to follow each other and see microposts from their followers in a 
"feed", similar to Twitter. 

## Heroku deployment

Want to see this website in action? Go to https://powerful-woodland-31030.herokuapp.com see the application deployed through Heroku with a seeded database (which is why there are many example users already created).
 
## License

All source code in the [Ruby on Rails Tutorial](http://railstutorial.org/)
is available jointly under the MIT License and the Beerware License. See
[LICENSE.md](LICENSE.md) for details.

## Getting started

To get started with the app, clone the repo and then install the needed gems:

```
$ bundle install --without production
```

Next, migrate the database:

```
$ rails db:migrate
```

Finally, run the test suite to verify that everything is working correctly:

```
$ rails test
```

If the test suite passes, you'll be ready to run the app in a local server:

```
$ rails server
```

For more information, see the
[*Ruby on Rails Tutorial* book](http://www.railstutorial.org/book).

Contact the owner of this repository through email at kyleiinwu@gmail.com.

