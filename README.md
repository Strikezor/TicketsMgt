##Project Name: Ticket Management App

#Description:

This application empowers users with a comprehensive and streamlined platform for managing tickets. It leverages the robust capabilities of Next.js for a seamless frontend experience and MongoDB for scalable data storage.

#Features:

Ticket Creation: Users can effortlessly create new tickets, providing crucial details such as title, description, priority, and assignee.
Ticket Listing: A well-organized list of all tickets is presented, allowing users to easily view their status (open, closed, in progress), priority, and assigned user.
Ticket Details: Each ticket displays comprehensive information, including title, description, priority, creation date, and any updates.
Ticket Updates: Users can add updates to tickets, fostering a collaborative environment for resolving issues effectively.

##Getting Started:

#Prerequisites:

Node.js and npm (or yarn) installed on your system.
A MongoDB database instance running locally or on a cloud provider.
Clone the Repository:

Bash
git clone https://github.com/Strikezor/TicketsMgt.git
Use code with caution.
Install Dependencies:

Bash
cd ticket-management-app
npm install (or yarn install)
Use code with caution.
Configure MongoDB Connection:
Create a .env.local file in the project root directory and add the following environment variable, replacing <your_mongodb_uri> with your actual MongoDB connection URI:

MONGODB_URI=<your_mongodb_uri>
Start the Development Server:

Bash
npm run dev (or yarn dev)
Use code with caution.
This will launch the Next.js development server, typically accessible at http://localhost:3000.

Deployment:

Build for Production:

Bash
npm run build (or yarn build)
Use code with caution.
This creates an optimized production-ready build of the application in the .next directory.


