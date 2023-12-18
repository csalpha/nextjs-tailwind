1.  Create Next App

    1. npx create-next-app nextjs-tailwind
    2. cd nextjs-tailwind
    3. Install NVM
        - **It's important that you remove any node version that you may have installed before installing nvm**
        - In Windows (you will need admin privileges): https://github.com/coreybutler/nvm-windows
        - In Linux / Unix: `curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.3/install.sh | bash`
    4. Install version 18 of Node.js\
        **Note**: For windows users, please make sure that after installing NVM you are able to use it in your user (and **not** as admin).\
        All the following steps **must** be executed in your user and not as admin (nor at any other admin console)!
        - `nvm install 18`
        - `nvm alias default 18` (in windows you may need to write the exact version name, like: 16.18.0)
        - `nvm use default`
    5. npm run dev

2. Install Tailwind (CSS Framework)

    1. npm install -D tailwindcss postcss autoprefixer
    2. npx tailwindcss init -p



    
