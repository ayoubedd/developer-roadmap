# WSA Poll

`WSAPoll` is a method utilized in server side game development, specifically within the Windows Sockets 2 (Winsock) API. `WSAPoll` is designed to determine the status of one or more sockets, allowing the application to monitor multiple sockets in a single function call. Simply put, `WSAPoll` allows sockets to reside in collections, also known as Pollfd arrays. At runtime, the status of these sockets can be checked without blocking the application's execution. Therefore, it is commonly used in network applications where multiple sockets need to be monitored simultaneously.