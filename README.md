# BlueflyBackend

# Heroku deployment steps #

**step 1** - Add **(process.env.PORT)** in app.listen(port) method in server.js file.
**step 2** - Create file with name of Procfile and add **web: node server.js**
**step 3** - run **git add .**
**step 4** - run **git commit -m "commit message"**
**step 5** - run **git push**
**step 6** - run **heroku login**
**step 7** - run **heroku create yourappname**
**step 8** - run **heroku git:remote -a yourappname**  it is for link git repository to heroku.
**step 9** - run **git push heroku master**
