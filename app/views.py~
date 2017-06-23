from flask import render_template
from app import app

@app.route('/')
@app.route('/index')
def index():
    user = {'nickname':'Dan'} #test user
    posts = [ #fake array of posts
        {
            'author':{'nickname':'John'},
            'body':'Beautiful day in Melbourne!'
        },
        {
            'author':{'nickname':'Kate'},
            'body':'Why are things like this?'
        }
    ]
    return render_template('index.html',
                           title='Home',
                           user=user,
                           posts=posts)
