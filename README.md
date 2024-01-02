# AuthJs (Next-Auth v5)

This is a repository for Next-Auth v5: Next.js 13.5, React, PostgreSQL, TailwindCSS, ShadCN UI.

Key Features:

- Real-time database
- Next-auth v5 (Auth.js)
- Next.js 14 with server actions
- Credentials Provider
- OAuth Provider (Social login with Google & GitHub)
- Forgot password functionality
- Email verification
- Two factor verification
- User roles (Admin & User)
- Login component (Opens in redirect or modal)
- Register component
- Forgot password component
- Verification component
- Error component
- Login button
- Logout button
- Role Gate
- Extending next-auth session
- Using next-auth callbacks
- Change email with new verification in Settings page
- Change password with old password confirmation in Settings page
- Enable/disable two-factor auth in Settings page

# Final Version

To visit the website, [click here.](https://auth-ss.vercel.app)

### Prerequisites

Node version 18.7.x

### Cloning the repository

```shell
git clone https://github.com/ShethSamarth/authjs.git
```

### Setup .env file

```js
DATABASE_URL=
DIRECT_URL=

AUTH_SECRET=

GOOGLE_CLIENT_ID=
GOOGLE_CLIENT_SECRET=

GITHUB_CLIENT_ID=
GITHUB_CLIENT_SECRET=

RESEND_API_KEY=

NEXT_PUBLIC_APP_URL=
```

### Install packages

```shell
npm install
```

### Setup prisma

```shell
npx prisma db push
```

### Start the app

```shell
npm run dev
```
