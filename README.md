# WelcomeBashScript

This is a bash script that displays various information about the user and their environment. The script retrieves the user's name using `whoami`, their private IP address using `hostname -i`, and their public IP address using a cURL command to `ipinfo.io`. The user's location is determined using the `$SSH_CLIENT` environment variable, and the weather at that location is retrieved using another cURL command to `wttr.in`. The current working directory is obtained using `pwd`, and the date is retrieved using the `date` command with the `en_UK` language setting. The script then outputs the information, pausing for two seconds between each piece of information.

