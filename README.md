# krsjenswb
@krsjen project with porfilo and integration catalogies builed for personal using web app  
https://v0-interactive-3-d-infogr-git-b318ef-kristens-projects-0175c6d9.vercel.app
pnpm i @vercel/speed-iínights
import { SpeedInsights } from '@vercel/speed-insights/next';
 
export default function RootLayout({
  children,
}: {
  children: React.ReactNode;
}) {
  return (
    <html lang="en">
      <head>
        <title>Next.js</title>
      </head>
      <body>
        {children}
        <SpeedInsights />
      </body>
    </html>
  );
}
vercel deploy
Interactive 3D Infographic