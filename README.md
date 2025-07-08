# social_media_app
A full stack social media application inspired by platforms like Instagram but built with a unique touch. Users can create profiles, share posts, follow others, and engage through likes and comments — with additional features that offer a more personalized and intuitive experience.

**Cloning the Repository**
git clone https://github.com/anjalidaheriya/social_media_app.git
cd social_media_app 

**Installation**

Install the project dependencies using npm:

```bash
npm install
```
**Set Up Environment Variables**

Create a new file named `.env` in the root of your project and add the following content:

```env
VITE_APPWRITE_URL=
VITE_APPWRITE_PROJECT_ID=
VITE_APPWRITE_DATABASE_ID=
VITE_APPWRITE_STORAGE_ID=
VITE_APPWRITE_USER_COLLECTION_ID=
VITE_APPWRITE_POST_COLLECTION_ID=
VITE_APPWRITE_SAVES_COLLECTION_ID=
```

Replace the placeholder values with your actual Appwrite credentials. You can obtain these credentials by signing up on the [Appwrite website](https://appwrite.io/).

**Running the Project**

```bash
npm start
```

Open [http://localhost:3000](http://localhost:3000) in your browser to view the project.
