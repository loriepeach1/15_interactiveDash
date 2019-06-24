# Belly Button Biodiversity
## Javascript, HTML, Flask, Python
#### The coolest study of biodiversity on the human body on the planet!
The belly button is one of the habitats closest to us, and yet it remains relatively unexplored. In January 2011, we launched Belly Button Biodiversity to investigate the microbes inhabiting our navels and the factors that might influence the microscopic life calling this protected, moist patch of skin home. In addition to inspiring scientific curiosity, Belly Button Biodiversity inspired conversations about the beneficial roles microbes play in our daily lives.

This project built an interactive dashboard to explore the [Belly Button Biodiversity DataSet](http://robdunnlab.com/projects/belly-button-biodiversity/)  and host the live dashboard on Heroku.

###  Libraries Used

* from sqlalchemy import create_engine
* from sqlalchemy import inspect

* from flask_sqlalchemy import SQLAlchemy
* from flask import (
    Flask,
    render_template,
    jsonify,
    redirect)

* import pandas as pd
* import os

###  Screen Images

![Landing](ReadMeImages/landing.png)

![Search](ReadMeImages/searchSingle.png)

    
![route](ReadMeImages/route.png)

 

###  Heroku Link
https://lgbiodiv.herokuapp.com/

(NOTE:   page loads, but database table cannot be found.   See .pdf for more information.   Worked with TAs and instructors and we are not sure why it works locally, but not when deployed to Heroku.   Lack of heroku SME within the group.   Needs further investigation.)


