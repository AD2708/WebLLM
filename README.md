# WebLLM
An offline large language model implementation that runs directly in your browser using the Llama model.

## Overview
WebLLM allows you to use powerful LLM capabilities without an internet connection by downloading and caching the model locally. This project leverages React and Vite for the frontend, with the webllm package handling model loading and inference.

## Features

- 🔌 **Fully Offline Operation:** Run AI inference without an internet connection after initial model download
* 🧠 **Llama Model Support:** Utilizes the Llama language model for high-quality text generation
+ 💻 **Browser-Based:** No backend server required - everything runs directly in your web browser
- 🚀 **Built with React + Vite:** Modern, fast web interface with efficient bundling
* 📦 **Local Caching:** Downloaded models are cached for future use without re-downloading



## Prerequisites

- Node.js (v16+)
* npm or yarn
+ Modern web browser (Chrome, Firefox, or Safari recommended)

## Installation

Clone the repository:
```bash
git clone https://github.com/AD2708/WebLLM.git
cd WebLLM
```

Install dependencies:
```bash
npm install
# or
yarn install
```

Start the development server:
```bash
npm run dev
# or
yarn dev
```

**Open your browser and navigate to:**  http://localhost:5173

## Usage

- Launch the application in your browser
* Wait for the Llama model to download and initialize (first-time only)
+ Start interacting with the model through the chat interface
- All processing happens locally in your browser


## Architecture

- **Frontend:** React with TypeScript for type safety
* **Build Tool:** Vite for fast development and optimized builds
+ **LLM Integration:** WebLLM package to handle model loading and inference
- **Model Storage:** IndexedDB for client-side model caching

## Model Information
This project uses the Llama model, which is downloaded and cached in your browser. The initial download may take some time depending on your internet connection, but subsequent uses will load from the local cache.



## Project Structure
```
WEBLLM/
├── public/           
├── src/               # Source code
│   ├── assets/        # Project assets (images, etc.)
│   ├── App.css        # Styles for App component
│   ├── App.jsx        # Main application component
│   ├── index.css      # Global styles
│   └── main.jsx       # Entry point for React application
├── .gitignore         # Git ignore configuration
├── eslint.config.js   # ESLint configuration
├── index.html         # HTML entry point
├── package-lock.json  
├── package.json       # Project configuration and dependencies
├── README.md          
└── vite.config.js     
```

## Adding Features

- Fork the repository
* Create a feature branch (git checkout -b feature/amazing-feature)
+ Commit your changes (git commit -m 'Add some amazing feature')
- Push to the branch (git push origin feature/amazing-feature)
* Open a Pull Request

## Performance Notes

- Performance depends on your device capabilities
* Initial model download size is substantial (several GB)
+ Memory usage can be high during inference

## Contributing
Contributions are welcome! Please feel free to submit a Pull Request.
