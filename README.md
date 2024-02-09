# My Jellyfin Theme

Just my personal Jellyfin theme.

## Installation

How to install the theme.

1. Go to the Jellyfin `Settings > Dashboard > General > Custom CSS`
1. Paste this CSS code into the Custom CSS input:

   ```css
   @import url('https://ccrsxx.github.io/jellyfin/public/style.css');
   ```

1. Click Save

## Development

Here are the steps to run the project locally.

1. Clone the repository

   ```bash
   git clone https://github.com/ccrsxx/jellyfin.git
   ```

1. Change directory to the project

   ```bash
   cd jellyfin
   ```

1. Install dependencies

   ```bash
   npm i
   ```

1. Run the project

   ```bash
   npm run dev
   ```

1. Go to the `Settings > Dashboard > General > Custom CSS`, or go to `Settings > Display > Custom CSS`. This way you don't override the entire server's CSS, only on your current client. Make sure to enable `Disable server-provided custom CSS code` to prevent the server's CSS from overriding your custom CSS.

1. Paste the development CSS code into the Custom CSS input:

   ```css
   @import url('http://localhost:3000/public/style.css');
   ```
