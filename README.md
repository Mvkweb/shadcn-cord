# shadcn-cord

A Discord theme inspired by the shadcn UI aesthetic.

## Installation

### Vencord

1.  Go to `User Settings > Vencord > Themes`.
2.  Under "Online Themes", paste the following URL:

`https://mvkweb.github.io/shadcn-cord/src/shadcn-cord.css`

## Development

This project uses `theme-scss` to compile the SCSS files.

1.  **Clone the repository:**
    ```bash
    git clone https://github.com/Mvkweb/shadcn-cord.git
    ```
2.  **Install dependencies:**
    ```bash
    npm install
    ```
3.  **Start development server:**
    This will watch for file changes and apply them to Discord for live testing.
    ```bash
    npm run dev
    ```
4.  **Build for production:**
    This will compile the theme into the final `shadcn-cord.css` file.
    ```bash
    npm run build