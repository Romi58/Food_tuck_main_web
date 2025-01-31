
# Functionality Hackathon - UI to Functional Code  

This project is part of the **Functionality Hackathon (Day 3 to Day 7)**, where we convert a **Figma UI design** into a fully functional web application using **Next.js, TypeScript, Headless UI, and APIs**.

## 🚀 Project Overview  

The goal of this hackathon is to transform static UI designs into dynamic, interactive, and production-ready web applications. This includes:  

- Implementing **responsive UI** from Figma designs.  
- Adding **dynamic functionality** with API integrations.  
- Using **Headless UI** for accessible and customizable components.  
- Ensuring **fast performance** with Next.js and server-side rendering.  

## 🛠️ Tech Stack  

- **Frontend**: Next.js, TypeScript, Tailwind CSS  
- **UI Components**: Headless UI, Radix UI (if needed)  
- **State Management**: Context API or Zustand  
- **APIs**: Fetching real-time data using REST or GraphQL  
- **Authentication**: NextAuth.js (if required)  
- **Deployment**: Vercel or other cloud platforms  

## 📌 Key Features  

- **Day 3**: Setting up the Next.js project, TypeScript configuration, and initial UI layout.  
- **Day 4**: Integrating Tailwind CSS and implementing core UI components (Navbar, Footer, Forms).  
- **Day 5**: Adding API functionality and making UI interactive with real-time data.  
- **Day 6**: Enhancing accessibility with Headless UI and optimizing performance.  
- **Day 7**: Final testing, bug fixing, and deployment.  

## 📦 Installation  

Follow these steps to set up the project locally:  

1. **Clone the Repository**  
   ```bash
   git clone https://github.com/Romi58/Food_tuck_main_web.git

Install Dependencies

bash
Copy
Edit
npm install
Run the Development Server

bash
Copy
Edit
npm run dev
Open http://localhost:3000 in your browser.

🔗 API Integration Example
Here’s an example of fetching data from an API in Next.js:

typescript
Copy
Edit
import { useEffect, useState } from 'react';

const useData = () => {
  const [data, setData] = useState([]);

  useEffect(() => {
    fetch('/api/data')
      .then((res) => res.json())
      .then((data) => setData(data));
  }, []);

  return data;
};
📂 Folder Structure
csharp
Copy
Edit
functionality-hackathon/
│
├── pages/               # Next.js pages
│   ├── index.tsx        # Home page
│   ├── about.tsx        # About page
│   ├── features.tsx     # Features page
│   ├── contact.tsx      # Contact page
├── components/          # UI components
│   ├── Navbar.tsx       # Navigation bar
│   ├── Footer.tsx       # Footer section
│   ├── Form.tsx         # Dynamic form component
├── styles/              # Global Tailwind styles
├── public/              # Static assets
├── utils/               # Helper functions
└── api/                 # API routes (if applicable)
🚀 Deployment
The project can be deployed on Vercel:

bash
Copy
Edit
vercel
🤝 Contributing
Contributions are welcome! Follow these steps:

Fork the repository
Create a new branch: git checkout -b feature-name
Make your changes
Commit your changes: git commit -m "Added new feature"
Push to your branch: git push origin feature-name
Open a pull request
📜 License
This project is licensed under the MIT License. See the LICENSE file for details.
