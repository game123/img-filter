# Image Filtering Microservice

Dev branch

## Tasks

### Setup Node Environment

Create a new node server. Open a new terminal within the project directory and run:

1. Initialize a new project: `npm i`
2. run the development server with `npm run dev`

### Create a new endpoint in the server.ts file

An endpoint in `./src/server.ts` which uses query parameter to download an image from a public URL, filter the image, and return the result.

Provided Helper functions to handle some of these concepts and imported it at the top of the `./src/server.ts` file.

```typescript
import { filterImageFromURL, deleteLocalFiles } from "./util/util";
```

### Deploying your system

Use `eb init` to create a new application and `eb create` a new environment to deploy the image-filter service! Use `eb deploy` to push changes.
