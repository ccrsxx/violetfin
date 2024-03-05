# My Jellyfin Theme

Just my personal Jellyfin theme.

## Installation

How to install the theme.

1. Go to the Jellyfin `Settings > Dashboard > General > Custom CSS`
1. Paste this CSS code into the Custom CSS input:

   ```css
   @import url('https://ccrsxx.github.io/violetfin/public/style.css');
   ```

1. Click Save

Optional: this theme make a heavy use of Backdrops on the library, it has cool moving animations on the library background. You can enable it by going to `Settings > Display > Backdrops`. There's also a way to enable the backdrop on all users, you can follow the tutorial [here](https://github.com/BobHasNoSoul/jellyfin-mods#force-backdrops-for-all-users-108x).

## Development

Here are the steps to run the project locally.

1. Clone the repository

   ```bash
   git clone https://github.com/ccrsxx/violetfin.git
   ```

1. Change directory to the project

   ```bash
   cd violetfin
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
