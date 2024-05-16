# Text Enhancer Application

This project is a Ruby on Rails application that integrates with the OpenAI GPT-4o API to enhance and correct text content. This README provides a comprehensive guide on how to set up, configure, and deploy the application.

## Prerequisites

- Ruby 3.2.2
- Rails 7.1.2
- Node.js >= v16.5.0
- Yarn >= 1.22.19


## Getting Started

Follow these instructions to get a copy of the project running on your local machine for development and testing purposes.

### Installation 🛠️

1. **Clone the repository:**

```bash
   git clone git@github.com:illuminaki/TextEnhancer.git
   cd TextEnhancer
```
Install dependencies:
```bash
bundle install
yarn install
Database setup:
```
    
Configure your database settings in config/database.yml and then create and migrate the database:

```bash
rails db:create
rails db:migrate
```

Create a .env file in the root directory and add your OpenAI API key:

plaintext
Copiar código
OPENAI_API_KEY=your_openai_api_key

```bash
rails s
```

Visit the application:

Open your web browser and go to http://localhost:3000.



## Licencia 📄
Este proyecto está licenciado bajo la Licencia MIT, lo que significa que puedes utilizarlo libremente en tus propios proyectos personales o comerciales.

## Contacto 📧
Si tienes preguntas o necesitas más información, puedes contactarme a través de illuminaki.online


Acknowledgements
OpenAI for providing the API.
Tailwind CSS for the styling framework.
Ruby on Rails




```markdown
![TikTok](https://res.cloudinary.com/dpyf60gb8/image/upload/v1715894369/TIKTOK-LOGO_bvxtll.png)
![Linkedin](https://res.cloudinary.com/dpyf60gb8/image/upload/v1715894432/linkedin-logo_gv17yd.png)
```

## Demo

![Text Enhancer Demo](https://res.cloudinary.com/dpyf60gb8/image/upload/v1715894292/tutorial-openAI_hja9hf.gif)