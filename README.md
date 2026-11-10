# FSC Task Manager (Frontend)

Aplicação web moderna desenvolvida em **React 18** e **Vite** para gerenciamento de tarefas, integrada com uma API backend hospedada de forma serverless na Vercel.

## 🚀 Tecnologias e Ferramentas

* **Core:** React 18, Vite, JavaScript (ESM)
* **Estilização:** Tailwind CSS, Tailwind Merge, Tailwind Variants
* **Gerenciamento de Estado / Dados:** TanStack React Query, Axios
* **Formulários e Validação:** React Hook Form
* **Roteamento:** React Router DOM
* **Feedback Visual:** Sonner (Toasts)
* **Qualidade de Código & Git Hooks:** ESLint, Prettier, Husky, Lint-Staged, Git Commit Msg Linter

---

## 🌐 Integração com a API Backend

O backend desta aplicação foi desmembrado em um repositório dedicado e está rodando em produção na Vercel:

* **URL Base da API:** `https://task-manager-r18-backend.vercel.app/`
* **Endpoints Principais:**
  * `GET /api/tasks` — Listagem de tarefas
  * `GET /api/quotes` — Listagem de frases motivacionais

---

## 📁 Estrutura do Projeto

```text
FSC-TASK-MANAGER/
├── .husky/
│   ├── commit-msg
│   └── pre-commit
├── database/
│   └── db.json
├── public/
│   └── vite.svg
├── src/
│   ├── assets/
│   │   ├── fonts/
│   │   │   ├── Poppins-Black.ttf
│   │   │   ├── Poppins-BlackItalic.ttf
│   │   │   ├── Poppins-Bold.ttf
│   │   │   ├── Poppins-BoldItalic.ttf
│   │   │   ├── Poppins-ExtraBold.ttf
│   │   │   ├── Poppins-ExtraBoldItalic.ttf
│   │   │   ├── Poppins-ExtraLight.ttf
│   │   │   ├── Poppins-ExtraLightItalic.ttf
│   │   │   ├── Poppins-Italic.ttf
│   │   │   ├── Poppins-Light.ttf
│   │   │   ├── Poppins-LightItalic.ttf
│   │   │   ├── Poppins-Medium.ttf
│   │   │   ├── Poppins-MediumItalic.ttf
│   │   │   ├── Poppins-Regular.ttf
│   │   │   ├── Poppins-SemiBold.ttf
│   │   │   ├── Poppins-SemiBoldItalic.ttf
│   │   │   ├── Poppins-Thin.ttf
│   │   │   └── Poppins-ThinItalic.ttf
│   │   ├── icons/
│   │   │   ├── add.svg
│   │   │   ├── arrow-left.svg
│   │   │   ├── check.svg
│   │   │   ├── chevron-right.svg
│   │   │   ├── cloud-sun.svg
│   │   │   ├── details.svg
│   │   │   ├── home.svg
│   │   │   ├── index.js
│   │   │   ├── loader.svg
│   │   │   ├── moon.svg
│   │   │   ├── sun.svg
│   │   │   ├── tasks-2.svg
│   │   │   ├── tasks.svg
│   │   │   └── trash.svg
│   │   └── react.svg
│   ├── components/
│   │   ├── AddTaskDialog.css
│   │   ├── AddTaskDialog.jsx
│   │   ├── Button.jsx
│   │   ├── DashboardCard.jsx
│   │   ├── DashboardCards.jsx
│   │   ├── DashboardGrid.jsx
│   │   ├── Header.jsx
│   │   ├── Input.jsx
│   │   ├── InputErrorMessage.jsx
│   │   ├── InputLabel.jsx
│   │   ├── MotivationalQuote.jsx
│   │   ├── Sidebar.jsx
│   │   ├── SidebarButton.jsx
│   │   ├── TaskItem.jsx
│   │   ├── Tasks.jsx
│   │   ├── TasksSeparator.jsx
│   │   └── TimeSelect.jsx
│   ├── hooks/
│   │   └── data/
│   │       ├── use-create-tasks.js
│   │       ├── use-delete-all-tasks.js
│   │       ├── use-delete-tasks.js
│   │       ├── use-details-task.js
│   │       ├── use-get-quotes.js
│   │       ├── use-get-tasks.js
│   │       └── use-update-tasks.js
│   ├── keys/
│   │   ├── mutations.js
│   │   └── queries.js
│   ├── lib/
│   │   └── axios.js
│   ├── pages/
│   │   ├── Home.jsx
│   │   ├── TaskDetails.jsx
│   │   └── Tasks.jsx
│   ├── index.css
│   └── main.jsx
├── .env.development
├── .env.production
├── .eslintrc.cjs
├── .gitignore
├── .lintstagedrc.json
├── .prettierrc
├── index.html
├── package-lock.json
├── package.json
├── postcss.config.js
├── README.md
├── tailwind.config.js
└── vite.config.js
