# This Movie Doesn't Exist 🎬  

## Overview  
**This Movie Doesn't Exist** is an interactive **AI-powered quiz game** where players must distinguish between **real** and **AI-generated** movies. The AI generates **fake movie posters and descriptions**, and players must guess which movie actually exists.

## Features  
- **AI-generated movie posters & descriptions**  
- **Quiz mode**: Players select the real movie from two choices  
- **Timer-based gameplay** for added challenge  
- **Leaderboard & scoring system**  
- **Adaptive difficulty**: AI-generated movies become more realistic over time  

## How It Works  
1. **Dataset Collection**: Real movie posters and descriptions are gathered from online sources.  
2. **AI Generation**:  
   - **Stable Diffusion** / **DALL·E** generates fake movie posters.  
   - **GPT-based model** generates fake movie descriptions.  
3. **Game Interface**: Two movie posters & descriptions are shown—one real, one AI-generated.  
4. **User Interaction**: Players select the real movie within a time limit.  
5. **Scoring & Feedback**: Correct answers earn points, and explanations are provided.  

## Tech Stack  
- **AI Models**: Stable Diffusion, GPT (LLM), CLIP for similarity checking  
- **Frontend**: React.js / Next.js  
- **Backend**: Flask / FastAPI  
- **Database**: PostgreSQL / Firebase  
- **Hosting**: Vercel / AWS  

