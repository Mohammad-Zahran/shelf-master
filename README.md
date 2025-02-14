# Shelf-Master

<img src="./readme/title1.svg"/>

<br><br>

<!-- project philosophy -->
<img src="./readme/title2.svg"/>

> Our Philosphy is to encourage users to have a new and unique experience in buying shelves by testing theese shelves in a simulation and real life using there own camera.
>
> We believe great shelving transforms spaces, and our mission is is rooted in empowering users to make confident and informed decisions by providing immersive, interactive experiences.

### User Stories

## Users

- As a user, I want to use an AI-driven 3D planner to visualize shelves in my space, so I can design and customize the perfect layout before purchasing.
- As a user, I want to receive personalized recommendations based on my preferences and past purchases, so I can quickly discover shelves that match my needs.
- As a user, I want to use AR in order to visualize the 3d Shelves in a real life enviroment.

## Admin

- As an admin, I want to access real-time inventory analytics, so I can proactively restock popular items and avoid disruptions and add new 3d models inside the AR application.
- As an admin, I want to moderate customer reviews and feedback to ensure the platform maintains a trustworthy and positive reputation.
- As an admin, I want to use sales analytics to identify top-performing products, so I can optimize promotional campaigns and maximize revenue.

<br><br>

<!-- Tech stack -->
<img src="./readme/title3.svg"/>

### Shelf Master is built using the following technologies:

- The frontend is used using [React](https://react.dev/), a [JavaScript](https://developer.mozilla.org/en-US/docs/Web/JavaScript) Library for bulding user interfaces and it uses [useContext](https://react.dev/reference/react/useContext) for state management.

- The 3D models are rendered using [Three.js](https://threejs.org/docs/), ensuring interactive and visually engaging experiences for users."

- [Tailwind CSS](https://tailwindcss.com/) is used as a utility-first CSS framework that simplifies styling by providing pre-designed classes, enabling rapid and consistent UI development.

- The images are hosted using [IMGBB](https://imgbb.com/) which is a platform used for efficiently uploading and managing images within the application.

- The app uses the font ["Poppin Sans"](https://fonts.google.com/specimen/Poppins) as its main font, and used [DaisyUI](https://daisyui.com/) as the main plugin for Design.

- [Node.js](https://nodejs.org/en) is used to integrate AI features via the OpenAI API for chatbot functionality.

- [Express.js](https://expressjs.com/) is used to simplify the building of RESTful APIs and routing.

- [MongoDB](https://www.mongodb.com/) serves as the primary database, providing a flexible and scalable NoSQL solution for storing and managing the core data of the application.

- [JWT](https://jwt.io/) is utilized for authentication and session management.

- [FireBase](https://firebase.google.com/?gad_source=1&gclid=CjwKCAiAnKi8BhB0EiwA58DA4Q8M6q_nZuR5AKCYlwd7skyDlMdtWfrsDAzGluq7pkHqDHERskEnphoC4rEQAvD_BwE&gclsrc=aw.ds) is used specifically for authentication, enabling secure and seamless user management, including Google Sign-In functionality.

- [SupaBase](https://supabase.com/) is dedicated to storing and managing 3D models, offering a streamlined and developer-friendly solution for handling these assets.

- [Stripe](https://stripe.com/gb) is used as a secure and developer-friendly payment processing platform used for handling transactions, subscriptions, and payments seamlessly within the application.

- [NodeMailer](https://www.nodemailer.com/) is used as a reliable email-sending library used for managing and delivering emails directly from the application.

- [OpenAI](https://openai.com/) is Integrated by Node.js service to build an intelligent shelf recommender system, leveraging AI-powered tools to enhance user experience and provide personalized recommendations.

- The mobile application is created using [Flutter](https://flutter.dev/?gad_source=1&gclid=CjwKCAiAnKi8BhB0EiwA58DA4aTUZMIz0HSSL121CAyasZ0bBiXzO27DWdHw2ZMsvdxqhBV3Y0_ExBoCooAQAvD_BwE&gclsrc=aw.ds) which is a versatile cross-platform framework used for building high-performance mobile applications with a single codebase.

- [Google ARCore](https://developers.google.com/ar) is used for the rendering of the 3D models inside the mobile application which is an augmented reality SDK that enables immersive and interactive AR experiences within the app.

<br><br>

<!-- UI UX -->
<img src="./readme/title4.svg"/>

> We designed Shelf Master using wireframes and mockups, iterating on the design until we reached the ideal layout for easy navigation and a seamless user experience.

- Project Figma design [figma](https://www.figma.com/design/RaPx3W2H4clVwELt8NcfVk/Final-Project?node-id=0-1&node-type=canvas&t=vy9IcsK5jJ0Y8OcS-0)

### Mockups

| Home screen                                | Product Details Screen                                   |
| ------------------------------------------ | -------------------------------------------------------- |
| ![Landing](./readme/figma/HeroSection.png) | ![ProductDetails](./readme/figma/ProductDetailsPage.png) |

<br><br>

<!-- Database Design -->
<img src="./readme/title5.svg"/>

### MongoDB Schemas for Managing the Data of the Website:

| **User Model**                                | **Product Model**                                   | **Payment Model**                                   | **3D Model**                              |
| --------------------------------------------- | --------------------------------------------------- | --------------------------------------------------- | ----------------------------------------- |
| ![User Model](./readme/models/user_model.png) | ![Product Model](./readme/models/product_model.png) | ![Payment Model](./readme/models/payment_model.png) | ![3D Model](./readme/models/3d_model.png) |

<br><br>

<!-- Implementation -->
<img src="./readme/title6.svg"/>

### User Screens (Mobile)

| Home screen                                      | AR screen                                           |
| ------------------------------------------------ | --------------------------------------------------- |
| <img src="./readme/images/ar.jpg" width="300" /> | <img src="./readme/gifs/ar_demo.gif" width="300" /> |

### User Screens (Web)

| Register Screen                                       | Login Screen                                                |
| ----------------------------------------------------- | ----------------------------------------------------------- |
| ![RegisterScreen](./readme/gifs/signup_screen.gif)    | ![LoginScreen](./readme/images/login_screen.png)            |
| Hero Screen                                           | Contact Us Screen                                           |
| ![HeroScreen](./readme/gifs/hero.gif)                 | ![ContactUsScreen](./readme/images/contact.png)             |
| Model Viewer Screen                                   | Company Screen                                              |
| ![ModelViewer](./readme/gifs/model_viewer.gif)        | ![CompanyScreen](./readme/images/company.png)               |
| Testimonials Screen                                   | FAQ Screen                                                  |
| ![Testimonials](./readme/images/testimonials.png)     | ![FAQScreen](./readme/images/faq.png)                       |
| Products Screen                                       | Checkout Screen                                             |
| ![ProductsScreen](./readme/images/product_screen.png) | ![CheckoutScreen](./readme/images/checkout.png)             |
| 3D Floor Planner Screen                               | 2D Floor Planner Screen                                     |
| ![3DFloorPlanner](./readme/gifs/floor_planner.gif)    | ![2DFloorPlanner](./readme/gifs/2d_floor_planner.gif)       |
| ChatBot Screen                                        | Products Details Screen                                     |
| ![ChatBotScreen](./readme/gifs/chatbot_screen.gif)    | ![ProductDetailScreen](./readme/images/product_details.png) |

### Admin Screens

| Admin Dashboard                              | Manage Users                                 |
| -------------------------------------------- | -------------------------------------------- |
| ![Landing](./readme/images/dashboard.png)    | ![fsdaf](./readme/images/users.png)          |
| Add Model                                    | Manage Reviews                               |
| ![fsdaf](./readme/images/manage_models.png)  | ![fsdaf](./readme/images/manage_reviews.png) |
| Manage Products                              | Add Products                                 |
| ![Landing](./readme/images/manage_items.png) | ![Landing](./readme/images/add_product.png)  |

<br><br>

<!-- Prompt Engineering -->
<img src="./readme/title7.svg"/>

### Shelfie AI: Smart Shelf Recommender:

- This project utilizes OpenAI's GPT models and advanced prompt engineering to deliver highly personalized and insightful shelf recommendations. Users simply provide their budget and preferences, and Shelfie AI suggests the most suitable shelves, highlighting key features and providing direct links to product details.

<img src="./readme/images/openai.png"/>

<br><br>

<!-- AWS Deployment -->
<img src="./readme/title8.svg"/>

### Deployment Description:

- This project leverages AWS deployment strategies to seamlessly integrate and deploy the Shelf Master's backend. Additionally, the MongoDB database is connected to the server using MongoDB Atlas, eliminating the need for local configuration.

| Register API                        | Get Cart By Email API           |
| ----------------------------------- | ------------------------------- |
| ![Register](./readme/images/d3.png) | ![Cart](./readme/images/d1.png) |
| Add Product API                     | AI API                          |
| ![Product](./readme/images/d4.png)  | ![AI](./readme/images/d2.png)   |

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

Follow the steps below to install and set up the Shelf Master app in both the website and the mobile application.

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
   SERVER_PORT=your server port you want to work with recommend(8000)
   FRONTEND_PORT=your frontend port you want to run the frontend with.
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
   Server running on port 8000
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

2. At your terminal change the directory to your fronetend

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

- At dio_service.dart in the BASEURL change it to your ipV4 address to make the application work inside your physical phone and change 8000 to the port you are working on inside the backend.
