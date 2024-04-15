# svg-plotter

This tool is designed to convert SVG files to GeoJSON, making it easier to work with SVG data in geographic applications. This README provides instructions on how to set up and run the project locally.

Prerequisites
Before you start, you need to have the following installed on your system:

Node.js: Required to run the project. Download Node.js
Yarn: This project uses Yarn for package management. Install Yarn
Installation
Follow these steps to set up the project on your local machine:

Clone the Repository

Use Git to clone the project's repository to your local machine:
bash
Copy code
git clone https://github.com/yourusername/svg-plotter.git
cd svg-plotter
Install Dependencies

Run the following command in the root of the project to install the necessary dependencies:
bash
Copy code
yarn install
Running the Development Server
To run the development server and view the project in your web browser:

Start the Server

Use the following command to start the development server:
bash
Copy code
yarn serve
This command will start a local server using browser-sync, which serves the files located in the demo directory and watches for any changes.
Access the Application

After starting the server, browser-sync will automatically open your default web browser to the URL where the project is running (typically http://localhost:3000). If it does not open automatically, you can manually navigate to this URL in your browser.
Live Reloading

Any changes made to the files in the demo directory will automatically trigger a reload of the web page, allowing you to see your changes in real-time.
Troubleshooting
Dependency Issues: If you encounter issues related to dependencies, make sure that Yarn has properly installed all packages. Try running yarn install again.
Port Conflicts: If browser-sync cannot start due to port conflicts, you can specify a different port in the serve script in your package.json:
json
Copy code
"serve": "browser-sync start --server 'demo' --files 'demo/*' --port 4000"
Contributing
Contributions to the SVG Plotter project are welcome! Please feel free to submit pull requests or create issues on GitHub if you have suggestions or encounter bugs.

License
This project is licensed under the MIT License - see the LICENSE.md file for details.
