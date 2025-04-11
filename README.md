![](https://i.imgur.com/nKX45bv.jpg)
  
## Running the Application

1.  **Install Dependencies:**
    ```bash
    npm install
    ```

2.  **Start the Development Server:**

    *   **If using PowerShell (Windows):**
        ```powershell
        $env:NODE_OPTIONS='--openssl-legacy-provider'; npm start
        ```
        *(This sets an environment variable needed to resolve an OpenSSL compatibility issue with newer Node.js versions)*

    *   **If using cmd.exe (Windows) or other terminals (macOS/Linux):**
        ```bash
        npm start
        ```
        *(Note: If you encounter an OpenSSL error, you might need to set the `NODE_OPTIONS=--openssl-legacy-provider` environment variable before running `npm start`)*

The application will be available at http://localhost:3000.

Live demo: http://mountainous-father.surge.sh/

## Attributions

Original by Tom Bogner [@dastom](https://twitter.com/dastom) on Dribble: https://dribbble.com/shots/6767548-The-Three-Graces-Concept

The GLTF used in this example was made by 3DLadnik: https://sketchfab.com/3DLadnik

Released as CC-BY-4.0 by Sketchfab: https://sketchfab.com/3d-models/3d-printable-the-three-graces-58e0ae19e2984b86883edc41bf43415a
