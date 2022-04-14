# Nowerse

## Backend deployment

I have made a few changes, also added new things, feel free to follow this and make the changes in your repository.

### Before deployment!

-   Added an `.env.example` file, it's for the people inspecting your repository, makes it easier for them to keep track of the envs

-   As I mentioned earlier on the meet, I've made some changes to the method types ( You can find them clearly mentioned in the commit messages )

-   I have added `PORT` environment variable support, because, hopefully backend should be deployed to heroku, so heroku doesnt allow you to choose your custom port, thus you are bound to the port you are assigned. They basically create a `PORT` env var in your instance which you can access
