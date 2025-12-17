# StoreFlow - The Engine (The Server)

This folder contains the "Back-End" of the project. Think of this as the brain and the filing cabinet of the entire system. 

## Behind the Scenes
- **Data Integrity**: I designed the database to be "relational." This means the app understands that a specific order belongs to a specific customer, and that customer bought a specific product. This prevents data errors.
- **Security Guard**: The server acts as a gatekeeper. It uses a digital "token" system to verify exactly who is asking for data before it sends anything out.
- **Performance Optimization**: I wrote the code to be efficient so that even if the business grows to have thousands of products, the system won't slow down.

## Personal Technical Touch
I spent extra time organizing the "API" (the communication bridge). This makes the system "future-proof"—meaning if I wanted to build a mobile app version of StoreFlow later, it could easily talk to this same server.