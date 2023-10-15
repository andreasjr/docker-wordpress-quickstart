# docker-wordpress-quickstart
A quick way to set up a local WordPress dev environment.

This docker-compose script and collection of folders will create a new, blank WordPress install that can be managed independently of other installs.

Built solely for **local development**, this package should not be used on production servers. It's meant to be a tool to develop plugins and themes. Specifically, it's a tool *I* built for *my* basic and specific needs as a developer. If you have any ideas, please open an Issue!

As a result, it does not contain any default WordPress plugins or themes. This means that, when run, the package will render what appears to be a blank website.

Finally: this package is built in such a way where the database will not be transferable. This might be changed in the future.

# Getting Started
1. Download this repo as a ZIP
2. Extract the ZIP where you want, rename the folder
3. Change the settings in the `docker-compose.yml` file (port, default usernames and passwords, if it starts on reboot)
4. Terminal into the folder and run `docker compose up`
5. Add your plugins and themes into the wp-content folder