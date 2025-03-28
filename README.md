fullstack-nextjs-app-template/
├── README.md
├── CHANGELOG.md
├── LICENSE
├── next.config.js
├── server.js
├── ecosystem.config.js
├── middleware.ts
├── tsconfig.json
├── package-lock.json
├── package.json 
├── .dockerignore
├── Dockerfile
├── docker-compose.yml
├── out/                # Folder generated by export command which contains the HTML/CSS/JS assets for your application
├── backend@nest/       # NestJS server
├── backend/            # Express server
│   ├── server-php.js 
│   └── ...             # All other files are optional
├── scripts/            # Node Script Library
├── public/             # Contains static resources, PHP remote test files, .md files for markdown rendering, etc.
├── app/                # App Router Demo Template
├── @pages/             # Pages Router Demo Template (Enabling it requires renaming the folder `@pages` to `pages`, and deleting `app`.)
│   ├── api/
│   └── *.tsx
├── src/
│   ├── config/
│   ├── data/
│   ├── contexts/
│   ├── interfaces/
│   ├── components/
│   ├── styles/
│   ├── utils/
│   └── store/
└──
