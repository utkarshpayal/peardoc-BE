**🧩 PREREQUISITES**
Node.js & npm
MongoDB Atlas URI

**INSTALL PACKAGES**:
npm install

**RUN THE BACKEND**
node index.js

**EXPLANATION**

This backend handles the MongoDB database connection and is responsible for authentication, generating JWT tokens for both client and provider sessions. The generated JWT token is then used to open the provider form for GPU registration, establish the client's authenticated connection to the provider's container, and manage session activities.

**Features**

🔐 Modular authentication routes via /auth
🌍 CORS enabled for secure cross-origin requests
📦 Environment-based configuration with dotenv
⚙️ MongoDB connection using Mongoose
🛡️ Advanced security headers (COOP and COEP)