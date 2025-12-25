# CineMap: AI-Assisted Script & Game Narrative Builder

<img width="360" height="220" alt="glasses" src="https://github.com/user-attachments/assets/5aa2a38b-55b9-4fbd-87f7-23571ca77333" />


## 📝 Overview

CineMap is an innovative narrative visualization tool that helps storytellers, game designers, and screenwriters map out complex narratives with AI assistance. It transforms traditional narrative planning into an intuitive visual experience, allowing you to:

- Generate story flowcharts and character arcs using AI
- Visualize narrative structure with interactive node-based diagrams
- Collaborate with AI to develop characters and plotlines
- Export your narratives for use in games, films, or other media

## 🎬 Demo

IN PROGRESS
*Click the image above to watch a demo of CineMap in action*

## 📸 Screenshots

<details>
  <summary>Click to see screenshots</summary>
  <img width="1456" height="686" alt="Screenshot 2025-09-22 at 1 06 40 PM" src="https://github.com/user-attachments/assets/d775d313-2adf-46d9-ae8d-774bf7794ee9" />
  <img width="1454" height="717" alt="Screenshot 2025-09-22 at 1 07 09 PM" src="https://github.com/user-attachments/assets/71c1d687-fb6f-4d52-bb2e-0256f4b09a18" />
  <img width="1455" height="700" alt="Screenshot 2025-09-22 at 1 07 20 PM" src="https://github.com/user-attachments/assets/4e325980-db32-47e3-b523-e939a4f1625e" />
  <img width="1465" height="729" alt="Screenshot 2025-09-22 at 1 07 30 PM" src="https://github.com/user-attachments/assets/4a037e9e-886a-49fb-a494-3e123177a683" />
  <img width="1920" height="1036" alt="cinemap_demo" src="https://github.com/user-attachments/assets/af904012-4276-4e97-ad2a-f888d8d49a1c" />


 

</details>

## 🛠️ Technology Stack

### Frontend (React)
- React 18 with TypeScript
- ReactFlow for interactive node diagrams
- GSAP for animations
- TailwindCSS for styling
- React Router for navigation

### Backend (Django)
- Django REST framework
- Google Gemini API for AI story generation
- Whisper for audio transcription
- Mermaid.js for flowchart generation

### Deployment
- Frontend: Vercel
- Backend: Railway

## 🚀 Getting Started

### Prerequisites
- Node.js 18+
- Python 3.11+
- Google Gemini API key

### Installation

#### Frontend Setup

```bash
# Clone the repository
git clone https://github.com/jonathanywang/cinemap.git
cd cinemap

# Install frontend dependencies
cd stubby-fe
npm install

# Start frontend development server
npm start
```

#### Backend Setup

```bash
# Navigate to backend directory
cd ../plot-ai/backend/plot-backend

# Create a virtual environment
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

# Install dependencies
pip install -r requirements.txt

# Set up environment variables
echo "GEMINI_API_KEY=your_gemini_api_key_here" > .env
echo "DEBUG=True" >> .env
echo "SECRET_KEY=your_secret_key_here" >> .env

# Run migrations
python manage.py migrate

# Start the development server
python manage.py runserver
```

## 📖 How to Use

1. **Create a New Story**
   - Start with a basic premise or genre
   - The AI will guide you through initial worldbuilding

2. **Develop Characters**
   - Add character profiles with traits, goals, and flaws
   - Generate character arcs that show emotional development

3. **Build Story Structure**
   - Visualize your three-act structure
   - Add key plot points and branch narratives
   - Connect nodes to show relationships between scenes

4. **Refine with AI Assistance**
   - Chat with the AI to brainstorm plot solutions
   - Generate alternative scene outcomes
   - Identify plot holes and inconsistencies

5. **Export Your Work**
   - Save as structured data for game engines
   - Export as visual diagrams for presentations
   - Generate script outlines for screenwriting

## 🌟 Key Features

- **Interactive Story Flowcharts**: Visualize your narrative with draggable nodes and connections
- **Character Arc Tracking**: Plot emotional journeys and character development
- **AI Story Assistant**: Get suggestions and feedback on your narrative
- **Voice Input**: Speak your ideas and have them transcribed
- **Multi-format Export**: Use your story in games, films, or other media
- **Collaborative Storytelling**: Work with AI to overcome creative blocks

## 🌐 Presentation

View our [project presentation](https://docs.google.com/presentation/d/11NoVryxy8zZI6ZQoqonoTYbWbkasRNYTRwEAEJYtMAY/edit?slide=id.g36633791f08_1_0#slide=id.g36633791f08_1_0) to learn more about CineMap's development journey and vision.

## 👥 Contributors

- Jonathan Wang - [GitHub](https://github.com/jonathanywang)
- Brandon Lau - [GitHub](https://github.com/BrandonLau8)
- Julius Behner - [Github](https://github.com/Spock1701B)
- David Chen - [Github](https://github.com/dcavid)


## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- Built during BigRedHacks hackathon
