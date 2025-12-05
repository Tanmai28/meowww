<img width="1883" height="866" alt="image" src="https://github.com/user-attachments/assets/6fd5dd68-a444-4a33-9eb3-ea597a73713f" /># Meowww

A minimal single-page React app that uses the Cat as a Service API (https://cataas.com/) to fetch and display cat images and GIFs.

  
**Implemented APIs:**
 - **GET /api/tags**: Fetches all available tags.
 - **GET /api/count**: Fetches the total number of cats in the database.
 - **GET /cat**: Fetches a random cat image.
 - **GET /cat/gif**: Fetches a random cat GIF.
 - **GET /cat/**:tag: Fetches a random cat image or GIF with a specific tag.
 - **GET /cat/says/:text**: Fetches a cat image or GIF with custom text overlay.
 - **GET /cat/:tag/says/:text**: Fetches a cat image or GIF with both a tag and custom text.
 - **GET /cat/:id**: Fetches a specific cat by its ID.
