All code in this repository is created by one liner:
```
otree startproject sample_games
```
Then, all files were checked into this repo.

* Demo link: <https://otree-demo-2024-02-4ef562cbb854.herokuapp.com/demo>

## Hosting on Heroku
* On Heroku, first create as an app called `otree-demo-2024-02`.
* A Postgres data base is needed for hosting the demo games.


## Troubleshooting

### When prompted with `psycopg2` error

Run the following:
```
heroku run "otree resetdb" --app otree-demo-2024-02
```


### Python Runtime is not found
There are two types of "Stack" available on Heroku (as of 2024-02). Check this
link for availability of the supported Python runtimes -
<https://devcenter.heroku.com/articles/python-support#supported-runtimes>
