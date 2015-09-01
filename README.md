[NAT] naturecoin 



 




-----------------------------------------------------------------------------------

naturecoin.conf

server=1

listen=1

daemon=1

rpcuser=ether

rpcpassword=ether

rpcport=10550

port=10551

rpcallowip=127.0.0.1

dns=1

maxconnections=32

upnp=1



-----------------------------------------------------------------------------------

Compiling



cd naturecoin/src

make -f makefile.unix

strip naturecoind

./naturecoind

./naturecoind getinfo
