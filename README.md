# BlueflyBackend

# Heroku deployment steps #

**step 1** - Add **(process.env.PORT)** in app.listen(port) method in server.js file.<br/>
**step 2** - Create file with name of Procfile and add **web: node server.js**. <br/>
**step 3** - run **git add .**. <br/>
**step 4** - run **git commit -m "commit message"**.<br/>
**step 5** - run **git push**.<br/>
**step 6** - run **heroku login**.<br/>
**step 7** - run **heroku create yourappname**.<br/>
**step 8** - run **heroku git:remote -a yourappname**  it is for link git repository to heroku.<br/>
**step 9** - run **git push heroku master**
