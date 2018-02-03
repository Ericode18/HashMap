# HashMap

This application is a multithreaded network hashmap.

## Running the Server
First compile the server with make clean all. To run the server, execute the command below.
```
./cream [-h] NUM_WORKERS PORT_NUMBER MAX_ENTRIES
-h            Displayed this help menu and returns EXIT_SUCCESS.
NUM_WORKERS   The number of worker threads used to service requests.
PORT_NUMBER   Port number to listen on for incomming connections.
MAX_ENTRIES   The maximum number of entries that can be stored in `creams`'s underlying data store.
```

After you launch the server, you can [**download**](https://github.com/ebaisch/CREAM) and make the cream (Cache Rules Everything Around Me) client to send requests to the server.
