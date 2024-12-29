# File Metadata Microservice

This is a simple file metadata microservice built with Node.js and Express. It allows users to upload a file and receive metadata about the file, such as its name, type, and size.

## Project Structure
.gitignore
package.jso
public/style.css
server.js
vercel.json
views/index.html

- **.gitignore**: Specifies files and directories to be ignored by Git.
- **package.json**: Contains project metadata and dependencies.
- **public/**: Contains static files like CSS.
  - **style.css**: The main stylesheet for the application.
- **server.js**: The main server file that sets up the Express server and handles routes.
- **vercel.json**: Configuration file for deploying the project on Vercel.
- **views/**: Contains HTML files for the application.
  - **index.html**: The main HTML file for the application.

## Installation

1. Clone the repository:
    ```sh
    git clone <repository-url>
    cd filemetadata
    ```

2. Install dependencies:
    ```sh
    npm install
    ```

## Usage

1. Start the server:
    ```sh
    npm start
    ```

2. For development with live reloading:
    ```sh
    npm run dev
    ```

3. Open your browser and navigate to `http://localhost:3000` to access the application.

## Deployment

This project is configured to be deployed on Vercel. The [vercel.json](http://_vscodecontentref_/5) file specifies the build and routing configuration.

## Routes

- **GET /**: Serves the main HTML file.
- **POST /api/fileanalyse**: Endpoint to upload a file and receive its metadata.

## Technologies Used

- Node.js
- Express
- Multer (for handling file uploads)
- Cors (for handling cross-origin requests)

## License

This project is licensed under the ISC License.