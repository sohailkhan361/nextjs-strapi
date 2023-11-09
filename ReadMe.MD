## STRAPI
Reference Guide/Documentation: https://strapi.io/blog/how-to-build-a-crud-app-with-react-and-a-headless-cms
Repo: https://github.com/hubertnare/pet-adoption-backend
Repo: https://github.com/hubertnare/pet-adoption

- For Backend:
- Strapi requires Node.js >=18.0.0 <=20.x.x
> nvm install 20.9.0
> nvm use 20.9.0
> npx create-strapi-app@latest pet-adoption-backend --quickstart
  http://localhost:1337/admin

- For Frontend:
> npx create-react-app pet-adoption
> npm install @mui/material @emotion/react @emotion/styled @mui/icons-material axios

 - To set up an instance of Axios (Base Instance)
 - Inside src folder, create https.js (interface with Strapi REST API )
 - Add base API code
 - create context/PetContext.js
 - Wrap <App /> in PetProvider 
 - Create components:
    