# 7 Days to Die Server on Docker

Runs a 7DtD server inside a Docker container. The server will be exposed onto port 26900.
The save files will be saved in a mounted directory. The path inside the container is: */home/steam/.local/share/7DaysToDie/Saves/*

## Known errors

You might get a message that you can't write to disk when downloading the server files.
I'm not sure what causes that. Running it on Windows works fine while running it on a Linux server doesn't.

Eventually I copied the server files downloaded on my Windows PC onto my Linux server inside the mount directory.
This is a workaround, but might get difficult when there are updates.