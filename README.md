# TianGong LCA NEXT

## Debug locally

1. Install dependencies:

   ```bash
   curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.7/install.sh | bash

   nvm install
   nvm use
   
   npm install
   ```

2. Rename `.env.example` to `.env.local` and update the following:

   ```bash
   NEXT_PUBLIC_SUPABASE_URL=[INSERT SUPABASE PROJECT URL]
   NEXT_PUBLIC_SUPABASE_ANON_KEY=[INSERT SUPABASE PROJECT API ANON KEY]
   ```

   Both `NEXT_PUBLIC_SUPABASE_URL` and `NEXT_PUBLIC_SUPABASE_ANON_KEY` can be found in [your Supabase project's API settings](https://app.supabase.com/project/_/settings/api)

3. You can now run the Next.js local development server:

   🚀 **Use VSCode Launch Next.js configuration to Debug!** 🚀

   The app should now be running on [localhost:3000](http://localhost:3000/).
