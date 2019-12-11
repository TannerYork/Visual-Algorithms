# Visual Algorithms

A web app for informing users about how algorythms work through an interactive experience. <br>
Use the app [here](https://visual-algorithms.herokuapp.com/)

## Getting Started

* Clone repository on local system <br>
* Create a new virtual enviroment <br>
* Run ```pip3 install -r requirements.txt``` <br>
* Add local host to allowed host <br>
* Run ```python3 manage.py runserver``` <br>
See deployment for notes on how to deploy the project on a live system.

## Deployment

Install the heroku CLI [here](https://devcenter.heroku.com/articles/heroku-cli)
Create a new heroku server
```
heroku create app-name
```
Test code using local development
```
heroku local web
```
Push code to the heroku app's github
```
git push heroku master
```
Go to your new website's url

## Built With

* [Flask](http://flask.palletsprojects.com/en/1.1.x/) - The web framework used
* [P5js](https://p5js.org/) - Creating the visualizations
* [Heroku](https://devcenter.heroku.com/) - Used to deploy to production

## Contributing

Feel free to make megre request.

## Authors

* **Tanner York** - *Initial work* - [TannerYork](https://github.com/TannerYork)

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details