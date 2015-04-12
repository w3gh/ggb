# GGB
Ghost++ Games Broadcaster

Tool to broadcast the games that ghost creates ( included the admin game ofc ) to any computer running this tool.
It works by connecting to ghost and wait for a specific packet that ghost sends it ( The W3GS_GAMEINFO packet ) and then broadcasts it on lan.
Then the program waits for a connection request from lan and then proxies it to the ghost bot.If the game supports reconnection the tool will enabled it.And a luxury feature.....game coloring for games that support reconnection ( like gproxy does ,Color = Blue ).
The program is based on gproxy's source code.
The ghost servers needs to be modified to work with this tool.
Patch for the latest svn and a compiled version of ghost++ included

### Usage
1.Open the program
2.Input the ghost server ip/hostname when prompted
3.Input the ghost server port for ggb clients when prompted
4.Check your lan screen Cheesy

It uses tcp so it doesn't require port forward on the client's side

Author: LdayGaGa
