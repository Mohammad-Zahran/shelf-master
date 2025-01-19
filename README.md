# Shelf-Master

<img src="./readme/title1.svg"/>

<br><br>

<!-- project philosophy -->
<img src="./readme/title2.svg"/>

> Our philosophy is to empower customers with innovative tools to find and design the perfect shelving solutions for their spaces. By leveraging AI-driven recommendations, 3D planners, and customization options, we aim to make the shopping experience seamless, engaging, and tailored to individual needs.
>
> We believe great shelving transforms spaces, and our mission is to make that transformation simple and accessible for everyone.

### User Stories

#### Client

- As a client, I want to use an AI-driven 3D planner to visualize shelves in my space, so I can design and customize the perfect layout before purchasing.
- As a client, I want to receive personalized recommendations based on my preferences and past purchases, so I can quickly discover shelves that match my needs.
- As a client, I want to use AR in order to visualize the 3d Shelves in a real life enviroment.

#### Admin

- As an admin, I want to access real-time inventory analytics, so I can proactively restock popular items and avoid disruptions.
- As an admin, I want to moderate customer reviews and feedback to ensure the platform maintains a trustworthy and positive reputation.
- As an admin, I want to use sales analytics to identify top-performing products, so I can optimize promotional campaigns and maximize revenue.

<br><br>

<!-- Tech stack -->
<img src="./readme/title3.svg"/>

### Shelf Master is built using the following technologies:

- ### Frontend

  - [React](https://react.dev/) - Enables a dynamic and responsive user interface.

  - [JavaScript](https://developer.mozilla.org/en-US/docs/Web/JavaScript) - Serves as the core programming language to create interactive and functional components.

  - [Tailwind CSS](https://tailwindcss.com/) - A utility-first CSS framework that simplifies styling by providing pre-designed classes, enabling rapid and consistent UI development.

  - [IMGBB](https://imgbb.com/) - An image hosting platform used for efficiently uploading and managing images within the application.

  - The app uses the font ["Poppin Sans"](https://fonts.google.com/specimen/Poppins) as its main font, and used [DaisyUI](https://daisyui.com/) as the main plugin for Design.

- ### Backend

  - [Node.js](https://nodejs.org/en) - Offers a scalable runtime for handling multiple requests efficiently.
  - [Express.js](https://expressjs.com/) - simplifies building RESTful APIs and routing.
  - [MongoDB](https://www.mongodb.com/) - Serves as the primary database, providing a flexible and scalable NoSQL solution for storing and managing the core data of the application.

  - [FireBase](https://firebase.google.com/?gad_source=1&gclid=CjwKCAiAnKi8BhB0EiwA58DA4Q8M6q_nZuR5AKCYlwd7skyDlMdtWfrsDAzGluq7pkHqDHERskEnphoC4rEQAvD_BwE&gclsrc=aw.ds) - Used specifically for authentication, enabling secure and seamless user management, including Google Sign-In functionality.

  - [SupaBase](https://supabase.com/) - Dedicated to storing and managing 3D models, offering a streamlined and developer-friendly solution for handling these assets.

  - [Stripe](https://stripe.com/gb) - A secure and developer-friendly payment processing platform used for handling transactions, subscriptions, and payments seamlessly within the application.

  - [NodeMailer](https://www.nodemailer.com/) - A reliable email-sending library used for managing and delivering emails directly from the application.

  - [OpenAI](https://openai.com/) - Integrated to build an intelligent shelf recommender system, leveraging AI-powered tools to enhance user experience and provide personalized recommendations.

- ### Mobile & AR FEATURES

  - [Flutter](https://flutter.dev/?gad_source=1&gclid=CjwKCAiAnKi8BhB0EiwA58DA4aTUZMIz0HSSL121CAyasZ0bBiXzO27DWdHw2ZMsvdxqhBV3Y0_ExBoCooAQAvD_BwE&gclsrc=aw.ds) - A versatile cross-platform framework used for building high-performance mobile applications with a single codebase.

  - [Google ARCore](https://developers.google.com/ar) - An augmented reality SDK that enables immersive and interactive AR experiences within the app.

<br><br>

<!-- UI UX -->
<img src="./readme/title4.svg"/>

> We designed Shelf Master using wireframes and mockups, iterating on the design until we reached the ideal layout for easy navigation and a seamless user experience.

- Project Figma design [figma](https://www.figma.com/design/RaPx3W2H4clVwELt8NcfVk/Final-Project?node-id=0-1&node-type=canvas&t=vy9IcsK5jJ0Y8OcS-0)

### Mockups

| Home screen                                | Product Details Screen                          |
| ------------------------------------------ | ----------------------------------------------- |
| ![Landing](./readme/figma/HeroSection.png) | ![fsdaf](./readme/figma/ProductDetailsPage.png) |

<br><br>

<!-- Database Design -->
<img src="./readme/title5.svg"/>

### Architecting Data Excellence: Innovative Database Design Strategies:

| **User Model**                                | **Product Model**                                   | **Payment Model**                                   | **3D Model**                              |
| --------------------------------------------- | --------------------------------------------------- | --------------------------------------------------- | ----------------------------------------- |
| ![User Model](./readme/models/user_model.png) | ![Product Model](./readme/models/product_model.png) | ![Payment Model](./readme/models/payment_model.png) | ![3D Model](./readme/models/3d_model.png) |

<br><br>

<!-- Implementation -->
<img src="./readme/title6.svg"/>

### Client Screens (Mobile)

| Login screen                              | Register screen                         | Landing screen                          | Loading screen                          |
| ----------------------------------------- | --------------------------------------- | --------------------------------------- | --------------------------------------- |
| ![Landing](https://placehold.co/900x1600) | ![fsdaf](https://placehold.co/900x1600) | ![fsdaf](https://placehold.co/900x1600) | ![fsdaf](https://placehold.co/900x1600) |
| Home screen                               | Menu Screen                             | Order Screen                            | Checkout Screen                         |
| ![Landing](https://placehold.co/900x1600) | ![fsdaf](https://placehold.co/900x1600) | ![fsdaf](https://placehold.co/900x1600) | ![fsdaf](https://placehold.co/900x1600) |

### Client Screens (Web)

| Register Screen                                    | Login Screen                                     |
| -------------------------------------------------- | ------------------------------------------------ |
| ![RegisterScreen](./readme/gifs/signup_screen.gif) | ![LoginScreen](./readme/images/login_screen.png) |

| Landing Screen                                       | Home Screen                                  |
| ---------------------------------------------------- | -------------------------------------------- |
| ![LandingScreen](./readme/images/update_profile.png) | ![HomeScreen](./readme/gifs/home_screen.gif) |

| Products Screen                                       | Checkout Screen                                  |
| ----------------------------------------------------- | ------------------------------------------------ |
| ![ProductsScreen](./readme/images/product_screen.png) | ![CheckoutScreen](./readme/gifs/cart_screen.gif) |

| 3D Floor Planner Screen                            | 2D Floor Planner Screen                               |
| -------------------------------------------------- | ----------------------------------------------------- |
| ![3DFloorPlanner](./readme/gifs/floor_planner.gif) | ![2DFloorPlanner](./readme/gifs/2d_floor_planner.gif) |

| Reviews Screen Updated                            |
| -------------------------------------------- | 
| ![ReviewsScreen](./readme/images/review.png) |

### Admin Screens

| Admin Dashboard                              | Manage Users                                 |
| -------------------------------------------- | -------------------------------------------- |
| ![Landing](./readme/images/dashboard.png)    | ![fsdaf](./readme/images/users.png)          |
| Add Products                                 | Manage Reviews                               |
| ![Landing](./readme/images/add_product.png)  | ![fsdaf](./readme/images/manage_reviews.png) |
| Manage Products                              | Update Product                               |
| ![Landing](./readme/images/manage_items.png) | ![fsdaf](./readme/images/update_product.png) |
| Add Model                                    | Manage Models                                |
| ![Landing](./readme/images/add_model.png)    | ![fsdaf](./readme/images/manage_models.png)  |

<br><br>

<!-- Prompt Engineering -->
<img src="./readme/title7.svg"/>

### Shelfie AI: Smart Shelf Recommendations:

- This project utilizes OpenAI's GPT models and advanced prompt engineering to deliver highly personalized and insightful shelf recommendations. Users simply provide their budget and preferences, and Shelfie AI suggests the most suitable shelves, highlighting key features and providing direct links to product details.

<br><br>

<!-- AWS Deployment -->
<img src="./readme/title8.svg"/>

### Efficient AI Deployment: Unleashing the Potential with AWS Integration:

- This project leverages AWS deployment strategies to seamlessly integrate and deploy natural language processing models. With a focus on scalability, reliability, and performance, we ensure that AI applications powered by these models deliver robust and responsive solutions for diverse use cases.

<br><br>

<!-- Unit Testing -->
<img src="./readme/title9.svg"/>

### Precision in Development: Harnessing the Power of Unit Testing:

- This project employs rigorous unit testing methodologies to ensure the reliability and accuracy of code components. By systematically evaluating individual units of the software, we guarantee a robust foundation, identifying and addressing potential issues early in the development process.

<br><br>

<!-- How to run -->
<img src="./readme/title10.svg"/>

> To set up Shelf Master locally, follow these steps:

### Prerequisites

1.  Ensure that Node.js and npm are installed on your system. If not, you can download them from Node.js.
    Install the latest npm version:

    ```sh
    npm install npm@latest -g
    ```

2.  Ensure that you login inside Atlas and create a new project and after naming the project, create a new cluster then setup your connection inside the backend.

3.  Ensure Git is installed for cloning the repository. Install it from [Git's official site](https://git-scm.com/) if not already installed.

4.  Install Flutter by following the [Flutter installation guide](https://docs.flutter.dev/get-started/install?gad_source=1&gclid=Cj0KCQiAv628BhC2ARIsAIJIiK9y0hS6ELyGH0Wd9N23HPs00gtG68X5gThq-MiRRQCDDFgKD5s2RZsaAqThEALw_wcB&gclsrc=aw.ds).
    Verify the installation by running:

    ```sh
    flutter doctor
    ```

5.  Create an account on [Supabase](https://supabase.com/) to manage your API and storage buckets.

6.  Create an account on [Firebase](https://firebase.google.com/?gad_source=1&gclid=Cj0KCQiAv628BhC2ARIsAIJIiK_6Art_kC4VIxYq4uOci8NzOiEGvyaMJfdK51PxjMw5iXOpFxb95PUaAhvtEALw_wcB&gclsrc=aw.ds) to manage authentication and singn in with google.

7.  Create an account on [Stripe](https://stripe.com/) to manage payment processing inside the website.

### Installation

_Below is an example of how you can instruct your audience on installing and setting up your app. This template doesn't rely on any external dependencies or services._

### shelf-master-backend

1. Clone the repo git clone https://github.com/Mohammad-Zahran/shelf-master.git
2. At your terminal change the directory to your backend
   ```sh
   cd shelf-master-backend
   ```
3. Install NPM packages
   ```sh
   npm install
   ```
4. Configure Environment Variables Create a .env file in the root directory and provide the necessary values as follows:

   ```sh
   SERVER_PORT=your server port you want to work with recommend(8080)
   DB_USER = database username
   DB_PASSWORD = database password
   ACCESS_TOKEN_SECRET="Generate JWT Secret"
   STRIPE_SECRET_KEY="Get the Stripe Secret Key inside the Stripe website"

   EMAIL_USER=Add_A_VALID_EMAIL
   EMAIL_PASS=EMAIL_PASS
   OPENAI_API_KEY=API_KEY
   ```

5. After completing the Setup go to your terminal and type this inside the terminal hence be sure you are inside the shelf-master-backend:

   ```sh
   nodemon src/index.js
   ```

   if the message appeared like this inside your terminal then the backend connection is correct:

   ```sh
   MongoDB connected Succesfully!
   (node:3224) [DEP0040] DeprecationWarning: The `punycode` module is deprecated. Please use a userland alternative instead.
   (Use `node --trace-deprecation ...` to show where the warning was created)
   Server running on port 8080
   ```

### Aditional Notes:

- Update the MongoDB cluster name in the mongoose.connect URL in index.js if needed.

- To get the Stripe Secret Key sign up inside [Stripe Dashboard](https://dashboard.stripe.com/test/dashboard) website and create a new account after creating an account search Developers and Find API keys there are two keys one for the frontend called Publishable Key and one for the backend which is the Secret Key copy and paste the secret key inside the .env file.

- Generate a secure JWT secret key using the following command:
  ```sh
  "console.log(require('crypto').randomBytes(64).toString('hex'))"
  ```

### shelf-master-frontend

1. Clone the repo git clone https://github.com/Mohammad-Zahran/shelf-master.git if you have already cloned skip this step.

2. At your terminal change the directory to your fronetnd

   ```sh
   cd shelf-master-frontend
   ```

3. Install NPM packages

   ```sh
   npm install
   ```

4. Configure Environment Variables Create a .env.local file in the root directory and provide the necessary values as follows:

   ```sh
   VITE_FIREBASE_API_KEY=apiKey
   VITE_FIREBASE_AUTH_DOMAIN=authDomain
   VITE_FIREBASE_PROJECT_ID=projectId
   VITE_FIREBASE_STORAGE_BUCKET=storageBucket
   VITE_FIREBASE_MESSAGING_SENDER_ID=messagingSenderId
   VITE_FIREBASE_APP_ID=appId


   VITE_IMAGE_HOSTING_KEY=imgbbAPI
   VITE_Stripe_PK=Stripe_Publishible_Key

   VITE_SUPABASE_URL=Subase_URL
   VITE_SUPABASE_API_KEY=SUPABASE_API_KEY
   ```

5. After completing the Setup go to your terminal and type this inside the terminal hence be sure you are inside the shelf-master-backend:

   ```sh
   npm run dev
   ```

   if the message appeared like this inside your terminal then the fronend connection is correct:

   ```sh
   > vite-project@1.0.0 dev
   > vite


   VITE v6.0.3  ready in 1020 ms

   ➜  Local:   http://localhost:5173/
   ➜  Network: use --host to expose
   ➜  press h + enter to show help
   ```

### Aditional Notes

- To get the Firebase SDK, sign in to Firebase, and then press the Go to Console button at the top right. Create a new project and enter your project name. After navigating to the project overview, press the </> icon inside the Get Started by Adding Firebase to Your App section. Add the app nickname, copy and paste the Firebase SDK inside the .env.local and you are good to go.

- To get the Stripe Publishable Key sign up inside [Stripe Dashboard](https://dashboard.stripe.com/test/dashboard) website and create a new account after creating an account search Developers and Find API keys there are two keys one for the frontend called Publishable Key and one for the backend which is the Secret Key copy and paste the publishible key inside the .env.local file.

- To get the IMAGE_HOSTING_KEY go to [imgbb](https://imgbb.com/) and after singing in there is an About button at the top left where the there is an API Link, after navigating, add the API and copy paste inside the.env.local.

- To get the [Supabase](https://supabase.com/) URL and API_KEY sign in into supabase and there should be a button called Dashboard at the top right press it and after navigating you to the dashboard create the project after creating the project Under API, you will find the URL and anon key (API key) for your project.

- At SupaBase inside your project please add two Buckets one is called Models3d and another called Images. After creating the Buckets please go to Policies and update them to public.

### shelf-master-mobile

1. Clone the repo git clone https://github.com/Mohammad-Zahran/shelf-master.git if you have already cloned skip this step.

2. At your terminal change the directory to your mobile application

   ```sh
   cd shelf-master-mobile
   ```

3. Open the pubspec.yaml file in the project root and run the following command to fetch the necessary dependencies:
   ```sh
   flutter pub get
   ```

### Aditional Notes:

- Make sure you have Flutter installed and properly configured on your system.

- Check that all packages in the pubspec.yaml file are compatible with your Flutter version.

- At dio_service.dart in the BASEURL change it to your ipV4 address to make the application work inside your physical phone and change 8080 to the port you are working on inside the backend.
