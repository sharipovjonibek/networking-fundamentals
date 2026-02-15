## Client-Server Architecture
1. What is Client-Server Architecture
Client-Server is a system where
- Client -> requests someting
- Server -> processes the request
- Server -> sends back the result

Simple idea:
`Client → Request → Server`
`Server → Response → Client`

2. What is a Client?
A client is Laptop, Phone, Tablet, Browser, App
The client:
- Sends requests
- Displays results
- Can perform small/light tasks

3. What is a Server?
A server is a powerful computer located in data centers handles heavy work.
Server does:
- Database operations
- Heavy calculations
- Authentication
- AI processing
- Storing large data

4. What does "Expensive Work" Mean?
Expensive work means operations that use a lot of:
- CPU
- RAM
- Disk I/O
- Network resources
- Time

These tasks are better handled by servers.

5. Why Not Do Everything on Client?
Because:
- Clients have limited resources
- Phones are weaker than servers
- Heavy processing drains battery
- Security is better on server
- Easier to update server than millions of clients

6. Mainframe vs Client-Server
Mainframe (Old Model)
- One giant computer
- Terminals are just screens + keyboard
- All logic runs in mainframe
- If mainframe fails → everything stops
- Terminals cannot work offline
Client–Server (Modern Model)
- Clients are real computers
- Clients have CPU, RAM, OS
- Some logic runs on client
- Heavy tasks run on server
- Client can work offline (partially)

Mainframe → Centralized Intelligence
Client–Server → Distributed Intelligence

7. What is RPC (Remote Procedure Call)?
RPC means:
Calling a function that runs on another machine.
Example of:
`result = calculate()`
You do:
`result = server.calculate()`
Server executes it remotely and returns result.

Modern example:
- REST API
- gRPC

Client–Server is about:
Separating lightweight tasks from heavy tasks
And allowing machines to communicate over a network.