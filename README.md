# Random my IP
This is a script to change the location of NordVPN by obtaining a new IP automatically.

### way of use

Grant execution permission

`
sudo chmod +x ./run
`

This script was created specifically for the use of nordvpn in unix environments.

To use it you need a Nordvpn account

The script receives only one parameter, which is the time in seconds that it will take until the next connection.

`
run 500
`

If the time parameter is omitted, the default time is 60 seconds
