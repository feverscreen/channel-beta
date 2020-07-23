This is the beta channel for release

To add a device to this channel run the following command:

`curl -L https://github.com/feverscreen/channel-beta/releases/download/feverscreen/apt-add-repo | sh`

Then add the following to your system crontab to make sure updates are requested:

```0 * * * *   root     apt-get update && apt-get -y --only-upgrade install feverscreen```

