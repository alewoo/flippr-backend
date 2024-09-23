# Flippr – Personalized Book Recommendation App

**Devpost Link**: [Flippr on Devpost](https://devpost.com/software/flippr-8dm5xc)
**Backend Github Link**: ([https://devpost.com/software/flippr-8dm5xc](https://github.com/alewoo/flippr-backend](https://github.com/alewoo/flippr)))

## Introduction

Flippr is a mobile app designed to help users discover books tailored to their preferences. The app lets users swipe through book recommendations, like or skip books, and receive personalized suggestions based on their interactions and reading habits.

Leveraging AI, Flippr analyzes user data to deliver accurate book suggestions, enhancing the reading discovery process. The app's main features include AI-powered recommendations, seamless book browsing, and a user-friendly swiping interface.

## Technologies Used

### Frontend:
- **React Native**: For building the mobile app interface.
- **Expo**: A platform for rapid development and deployment of React Native apps.

### Backend:
- **Node.js**: Provides the runtime environment for the server-side logic.
- **Express.js**: A minimalist framework for building robust web and mobile applications.
- **MongoDB**: NoSQL database used to store user data, book interactions, and preferences.

### AI Integration:
- **OpenAI GPT-4**: Analyzes user interactions (liked books, skipped books) to infer reading preferences and provide personalized book recommendations.

### APIs Used:
- **OpenLibrary Search API**: Fetches book details (cover, title, author) for recommendations displayed in the app.

## Key Features

- **User Authentication**: Secure user login and registration, implemented using JWT (JSON Web Tokens).
- **Personalized Recommendations**: AI-backed suggestions based on users' preferences and interactions with books.
- **Interest Inference**: AI analyzes liked and disliked books to fine-tune future recommendations.
- **Swipe to Like/Dislike**: Users can swipe to like or skip book recommendations.
- **View Liked Books**: Users can view all their liked books in a separate section of the app.
- **Custom Onboarding**: Users fill out a reading preferences questionnaire during onboarding for better personalized recommendations.
- **Detailed Book Info**: Users can click on a book title to view more information such as the author, title, and a brief summary.

## How It Works

1. **User Onboarding**: Upon first use, users fill out a brief questionnaire about their reading habits and preferences.
2. **Swipe to Discover**: Users swipe through book recommendations—right for "like," left for "skip."
3. **Tailored Suggestions**: The AI refines recommendations over time, learning from user interactions.
4. **Explore Liked Books**: Users can view their liked books in a dedicated section of the app.

## More Information

- **Book Details**: Click on a book to get more information, including the title, author, and a summary.
- **Data Storage**: All user preferences, interactions, and book data are stored securely in MongoDB.

## Contact

For more information or to contribute, visit the [Devpost project page](https://devpost.com/software/flippr-8dm5xc).
