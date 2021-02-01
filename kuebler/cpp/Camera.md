# Summary

 Members                        | Descriptions                                
--------------------------------|---------------------------------------------
`class `[`TCPServer`](#classTCPServer) | A simple TCP server class.

# class `TCPServer` 

A simple TCP server class.

A TCP server that provides simple but robust functionalities for networking.

## Summary

 Members                        | Descriptions                                
--------------------------------|---------------------------------------------
`public  `[`TCPServer`](#classTCPServer_1a7d5e52f194a5aba475977cc2b76329c2)`(int port)` | Server constructor.
`public  `[`~TCPServer`](#classTCPServer_1abc497ac52355e53986a6a1bd1acb9581)`()` | Server destructor.
`public bool `[`isConnected`](#classTCPServer_1aefcb72cd126cb714528a553bf03f4a3c)`()` | Connection verification.
`public void `[`send`](#classTCPServer_1a59bea4956cfb952d1f8dbb27b5a01afb)`(std::string msg)` | Sends message to client.
`public std::string `[`receive`](#classTCPServer_1a40550aecb75b978f06362f1439ba633b)`(int buff_size)` | Receives message from client.

## Members

#### `public  `[`TCPServer`](#classTCPServer_1a7d5e52f194a5aba475977cc2b76329c2)`(int port)` 

Server constructor.

Creates and initializes all necessary sockets, file descriptors and connections.

#### Parameters
* `port` Network server port

#### `public  `[`~TCPServer`](#classTCPServer_1abc497ac52355e53986a6a1bd1acb9581)`()` 

Server destructor.

Frees all server related memory.

#### `public bool `[`isConnected`](#classTCPServer_1aefcb72cd126cb714528a553bf03f4a3c)`()` 

Connection verification.

Checks if the connection is still activ.

#### Returns
If server is connected to a client

#### `public void `[`send`](#classTCPServer_1a59bea4956cfb952d1f8dbb27b5a01afb)`(std::string msg)` 

Sends message to client.

Sends a message from server to client while providing error and fault detection.

#### Parameters
* `msg` Message to send

#### `public std::string `[`receive`](#classTCPServer_1a40550aecb75b978f06362f1439ba633b)`(int buff_size)` 

Receives message from client.

Receives a message from client while providing error and fault detection.

#### Parameters
* `buff_size` Buffer size for incoming messages 

#### Returns
Received message

Generated by [Moxygen](https://sourcey.com/moxygen)