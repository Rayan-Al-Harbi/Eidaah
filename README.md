

# (Eidaah) إيضاح  - AI Presentation Explainer

An intelligent tool for analyzing presentations using AI, designed to simplify understanding for students and support presenters.


##  Features



-  **File Support**: Upload PDF and PPTX presentations

 -   * *AI Analysis * *: Get analytical explanations for each slide

 -   * *Real Examples * *: Receive practical, real-world examples

 -   * *Bilingual * *: Full Arabic and English support

 -   * *Fast Processing * *: Quick analysis powered by Qwen AI model



 ##  Project Structure



```

eidaah/

├── backend/          # FastAPI backend

│   ├── main.py       # API endpoints

│   ├── ai _logic.py   # File processing logic

│   ├── Model.py      # AI model integration

│   └── requirements.txt

│

└── frontend/         # React frontend

&nbsp;   ├── src/

&nbsp;   │   ├── pages/    # Upload  & Results pages

&nbsp;   │   ├── App.js

&nbsp;   │   ├── Footer.js

&nbsp;   │   ├── About.js

&nbsp;   │   └── FAQ.js

&nbsp;   └── package.json

```



 ##  Local Setup



 ### Prerequisites



 - Python 3.9+

 - Node.js 16+

 - npm or yarn



 ### Backend Setup



```bash

cd backend (change backend with the folder path)



 # Create virtual environment

python -m venv venv



 # Activate virtual environment

 # Windows:

venv  Scripts  activate

 # Mac/Linux:

source venv/bin/activate



 # Install dependencies

pip install -r requirements.txt



 # Run server on terminal

uvicorn main:app --reload --port 8000

```



The backend will be available at `http://localhost:8000`



 * *Note: * * First run will download the AI model (~3GB), which takes 5-10 minutes.



 ### Frontend Setup



open another terminal:

```bash

cd frontend (change frontend with the folder path)



 # Create .env.local file

echo "REACT _APP _API _URL=http://localhost:8000" > .env.local



 # Install dependencies

npm install



 # Start development server

npm start

```



The frontend will be available at `http://localhost:3000`



 ##  Technology Stack



 ### Backend

 - FastAPI - Web framework

 - Qwen 2 (1.5B) - AI language model

 - PyTorch - ML framework

 - pdfplumber - PDF processing

 - python-pptx - PowerPoint processing



 ### Frontend

 - React - UI framework

 - React Router - Navigation

 - Cairo Font - Arabic typography

 - Tailwind CSS - Styling



 ## 👥 Team



 * *Enjaz Club - AI Team * *  

Imam Muhammad ibn Saud Islamic University



 -  * *Club Leader * *: Layan Al-Mutaiwie

 -  * *Project Manager * *: Turki Al-Dajani

 -  * *Team Lead  & AI/NLP Engineer * *: Rayan Al-Harbi

 -  * *UI/UX Design * *: Nahid Al-Mutairi, Layan Al-Qabbani

 -  * *Frontend * *: Abdulaziz Al-Dhaif, Raseel Al-Samaani

 -  * *Backend * *: Abdulaziz Al-Qahtani, Sultan Al-Rajeh

 -  * *AI/NLP Engineers * *: Ziyad Al-Moneef, Yasser Al-Shareef

 -  * *QA * *: Faisal Al-Tuwaijri



 ## License



This project is a student initiative developed by the Enjaz Club AI Team.



 ## Contributing



This is a closed student project. For questions or feedback, please contact the team through the university.



 ##  Contact



For inquiries about this project, please reach out through Imam Muhammad ibn Saud Islamic University - Enjaz Club.





 * *Made by ambitious students leveraging AI to serve knowledge * *

