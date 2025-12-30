# Питання для друзів (Conversation Questions App)

A simple, playful app for sparking conversations with friends in Ukrainian. Swipe right to like questions, left to dislike. The app learns from your preferences!

## Features

- 🇺🇦 40 conversation-starting questions in Ukrainian
- 👆 Tinder-like swipe interface (left/right)
- 🧠 Learning algorithm that adapts to your preferences
- 💾 Saves your preferences locally
- 🎨 Naive, hand-drawn aesthetic design
- 📱 Mobile-friendly and responsive

## How It Works

1. **Swipe or Click**: Drag the card left/right, or use the buttons below
2. **Like/Dislike**: Right = like, Left = dislike
3. **Learning**: The app tracks which question categories you prefer and shows more of those
4. **Categories**: Questions are organized by themes (dreams, relationships, growth, etc.)

## Deploy to Vercel

### Option 1: Deploy from local folder

1. Install Vercel CLI:
   ```bash
   npm i -g vercel
   ```

2. Navigate to the project folder and deploy:
   ```bash
   cd conversation-questions-ua
   vercel
   ```

3. Follow the prompts to complete deployment

### Option 2: Deploy via Git

1. Push the project to GitHub
2. Go to [vercel.com](https://vercel.com)
3. Click "Import Project"
4. Select your repository
5. Click "Deploy"

## Local Development

To run locally:

1. Open `index.html` in your browser, or
2. Use a local server:
   ```bash
   npx serve .
   ```

## Technical Details

- **Framework**: React (via CDN)
- **Storage**: localStorage for preferences
- **Styling**: Pure CSS with custom animations
- **Learning Algorithm**: Category-based preference scoring

## Customization

To add more questions, edit the `initialQuestions` array in `index.html`. Each question should have:
- `text`: The question in Ukrainian
- `category`: A category tag for the learning algorithm

## License

MIT
