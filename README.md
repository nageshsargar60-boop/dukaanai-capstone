# DukaanAI

DukaanAI is a software project focused on improving shop and retail workflows. This repository currently contains two web application folders: a Vite-based frontend and a Next.js web application.

## Repository Structure

```text
Dukaan ai/
├── frontend/       # Vite frontend application
├── web/            # Next.js web application
├── .gitignore
├── CLAUDE.md       # AI coding guidance
├── LICENSE
├── README.md
├── WORKFLOW.md
└── vercel.json
```

## Prerequisites

- Node.js LTS and npm
- Git
- A code editor such as Cursor or VS Code

Check your installation:

```powershell
node --version
npm --version
git --version
```

## Run the Frontend

Open PowerShell in the repository root and run:

```powershell
cd frontend
npm install
npm run dev
```

Follow the local URL printed by Vite in the terminal.

## Run the Next.js Application

Open a separate terminal from the repository root:

```powershell
cd web
npm install
npm run dev
```

Open the local URL printed by Next.js in the terminal. The default is usually `http://localhost:3000`, unless that port is already in use.

## Production Build Checks

Run these commands from the relevant application directory:

```powershell
npm run build
```

For the frontend, run it inside `frontend/`. For the Next.js application, run it inside `web/`.

Available scripts can be checked in each folder's `package.json`.

## Environment Variables and Security

- Check the relevant application's documentation and configuration before setting environment variables.
- Use a local `.env` file only when required by the application.
- Never commit API keys, passwords, access tokens, or other secrets.
- Keep example configuration free of real credentials.
- Do not upload `node_modules` or generated build output.

## AI-Assisted Development

`CLAUDE.md` contains project guidance for AI-assisted coding. Before accepting AI-generated changes:

1. Review the proposed diff.
2. Confirm commands and features against the existing code.
3. Run the relevant build or checks.
4. Update documentation when behavior or setup changes.

## Contributing

Keep changes focused, use clear commit messages, and test affected applications before submitting changes.

Conventional Commit examples:

- `docs: improve project setup instructions`
- `chore: update development configuration`
- `fix: correct an application issue`

## License

See [LICENSE](LICENSE) for the license terms.
