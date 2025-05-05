![Art](https://i.postimg.cc/MGQBgGjf/art-web.png)

![GitHub Created At](https://img.shields.io/github/created-at/id-andyyy/IdeaCodeRelease_Web?style=flat&color=00247d)
![Lines Of Code](https://tokei.rs/b1/github/id-andyyy/IdeaCodeRelease_Web?style=flat&category=code&color=78a62d)
![Top Language](https://img.shields.io/github/languages/top/id-andyyy/IdeaCodeRelease_Web?style=flat&color=ca4341)

# Твой ФФ&nbsp;&#127963;

A web service for interaction between students of the MSU Faculty of Physics and university services&nbsp;&#128218;. Created as part of the hackathon [Идея. Код. Релиз&nbsp;&#128104;&#8205;&#128187;](https://codenrock.com/contests/codenrock-idea-code-release).

## Description

The solution combines all the necessary services for students and teachers, and additional features simplify the learning and exam process&nbsp;&#127891;.

Functionality:

- &#128272;&nbsp;**User Authentication and Authorization**
    - Registration, login, password reset
    - Different roles (student, teacher, administrator)
- &#128452;&nbsp;**Knowledge Base with OCR and AI Processing**
  - File uploads (PDF, images, documents)
  - Automatic text recognition (OCR)
  - AI processing, text structuring, and summary creation
  - Storage and organization of educational materials
- &#128172;&nbsp;**Forum**
  - Create and view posts
  - Categorize posts by topics
  - Comments and likes
- &#127881;&nbsp;**Event Calendar**
    - Event creation by administrators (ability to limit the number of participants)
    - Event registration
- &#128240;&nbsp;**News**
    - Administrators and teachers can add announcements
    - Interactive story format
- &#128467;&nbsp;**Class Schedule**
  - View schedules for groups and teachers
  - Filtering and search
  - This service is also available in [Telegram Bot Физик&nbsp;&#129302;](https://github.com/id-andyyy/IdeaCodeRelease_Bot) (separate repository)
- &#127869;&nbsp;**Cafeteria Menu**
  - View menu by day
  - Information about dishes (composition, proteins, fats, carbohydrates, energy value)
- &#128338;&nbsp;**Room Booking**
    - Students can book an available room for a specific time for their needs
- &#11088;&nbsp;**Teacher Reviews**
    - Students share their impressions of teachers
- &#128506;&nbsp;**Campus Map**
- &#129299;&nbsp;**AI Assistant**
  - Interactive assistant Physicist for answering questions
  - Help with site navigation
  - Contextual help - scanning the open page and assisting with any requests (e.g., analyzing teacher reviews to find the most popular one)
  - **Psychologist**&nbsp;&#128524; function - AI assistance in difficult situations or the ability to make an appointment with a professional

Other services, such as the Scholarship Calculator&nbsp;&#129518; or Car Pass&nbsp;&#128663; were added as links to Yandex.Forms due to lack of time for implementation.

## Screenshots

<p align="center">Main Page</p>

![Main Page](https://i.postimg.cc/pdfQcB7n/1.png)

<p align="center">News</p>

![News](https://i.postimg.cc/QNy7bPty/2.png)

<p align="center">Knowledge Base</p>

![Knowledge Base](https://i.postimg.cc/X7BCD8B7/3.png)

<p align="center">Room Booking</p>

![Room Booking](https://i.postimg.cc/Zq4vnz7C/4.png)

<p align="center">Psychologist Services</p>

![Psychologist Services](https://i.postimg.cc/d1Sh5kqy/6.png)

*only the main pages are presented due to the large number of services


## Technologies and Tools

![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffffff)
![FastAPI](https://img.shields.io/badge/FastAPI-005571?style=for-the-badge&logo=fastapi&color=009485&logoColor=white)
![NumPy](https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white)
![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white)
![Postgres](https://img.shields.io/badge/postgres-%23316192.svg?style=for-the-badge&logo=postgresql&logoColor=white)
![Nginx](https://img.shields.io/badge/nginx-%23009639.svg?style=for-the-badge&logo=nginx&logoColor=white)
![HTML5](https://img.shields.io/badge/html-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/css-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=white&color=yellow)
![TypeScript](https://img.shields.io/badge/typescript-%23007ACC.svg?style=for-the-badge&logo=typescript&logoColor=white)
![SvelteKit](https://img.shields.io/badge/sveltekit-%23ff3e00.svg?style=for-the-badge&logo=svelte&logoColor=white)
![Vite](https://img.shields.io/badge/vite-%23646CFF.svg?style=for-the-badge&logo=vite&logoColor=white)
![Docker](https://img.shields.io/badge/docker-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white)
![Figma](https://img.shields.io/badge/figma-%23F24E1E.svg?style=for-the-badge&logo=figma&logoColor=white&color=#6CeA8C)
![Git](https://img.shields.io/badge/git-%23F05033.svg?style=for-the-badge&logo=git&logoColor=white&color=f14e32)
![Deepseek](https://img.shields.io/badge/Deepseek-%23F24E1E.svg?style=for-the-badge&logoColor=white&color=4d6bfe)
![Telegram](https://img.shields.io/badge/Telegram-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white)

The project was written in three days as part of the hackathon [Идея. Код. Релиз&nbsp;&#128104;&#8205;&#128187;](https://codenrock.com/contests/codenrock-idea-code-release)

Telegram bot Физик&nbsp;&#129302; is located in a [separate repository](https://github.com/id-andyyy/IdeaCodeRelease_Bot).

## Getting Started

### Backend Setup

[![Typing SVG](https://readme-typing-svg.herokuapp.com?font=Fira+Code&duration=2500&color=F7F7F7&background=000000&multiline=true&width=800&height=185&lines=%25+git+clone+https%3A%2F%2Fgithub.com%2Fid-andyyy%2FIdeaCodeRelease_Web.git;%25+cd+IdeaCodeRelease_Web%2FBackend;%25+python+-m+venv+venv;%25+source+venv%2Fbin%2Factivate;%25+pip+install+-r+requirements.txt;%25+python+migrations%2Fadd_ocr_fields_to_knowledge.py;%25+uvicorn+server%3Aapp+--reload)](https://git.io/typing-svg)

```sh
git clone https://github.com/id-andyyy/IdeaCodeRelease_Web.git
cd IdeaCodeRelease_Web/Backend
python -m venv venv
source venv/bin/activate
pip install -r requirements.txt
python migrations/add_ocr_fields_to_knowledge.py
uvicorn server:app --reload
```

To work correctly, you need to create a `.env` file and fill it in according to the `.env.example` file, replacing placeholders with secret keys.

### Frontend Setup

[![Typing SVG](https://readme-typing-svg.herokuapp.com?font=Fira+Code&duration=2500&color=F7F7F7&background=000000&multiline=true&width=500&height=90&lines=%25+cd+..%2FFrontend;%25+npm+install;%25+npm+run+dev)](https://git.io/typing-svg)

```sh
cd ../Frontend
npm install
npm run dev
```

## Feedback

I would appreciate it if you give a star&nbsp;&#11088;. If you find a bug or have suggestions for improvement, use the [Issues](https://github.com/id-andyyy/IdeaCodeRelease_Web/issues) section.

## Team

Development team [Mojarung](https://t.me/mojarung):

- [Andrey Obrezkov](https://github.com/id-andyyy) (Backend developer)
- [Kirill Veriyalov](https://github.com/verikirill) (Backend developer)
- [Yaroslav Roldugin](https://github.com/Felicuss) (Backend developer)
- [Vladislav Politsyn](https://github.com/wasbyy) (Frontend developer)
- [Roman Solovyov](https://github.com/Fors1ksx) (Frontend developer)
- [Daria Govorovskaya](https://t.me/daryagovor) (UX/UI designer)

Read in [Russian&nbsp;&#127479;&#127482;](README-ru.md)
