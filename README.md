# DDEV Template

A drupal repo ready to do Drupal using GitHub Codespaces and DDEV.

# First install

To create a new repository from this template:

1. Create a new repository and choose this repository as the template
2. In the new repository, choose to start a Codespace
3. Wait! This bit takes a while as Codespaces creates your environment. Hang in there until Visual Studio has appeared, wait a little longer for the postCreateCommand to begin and complete and you reach a terminal prompt
4. Honestly, it takes a while on first build - go make a cup of tea
5. Start DDEV and install all the required Drupal components with the command `ddev composer install`
6. In the Ports tab above the terminal, you will see the ports listed for things like the webserver, the database server etc. Click on the World icon next to the *web https (8443)* port for the webserver and a new tab will open, inviting you to "install Drupal"
7. Install Drupal

# Codespaces restarts

If the codespace is restarted, the docker pieces that hold the webserver etc need to be started with the command `ddev start`.
