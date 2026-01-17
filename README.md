# Mintplay-x
app/
  page.tsx
  layout.tsx
styles/
  globals.css
  export default function Home() {
  return (
    <main style={{ padding: 40 }}>
      <h1>MintPlay X</h1>
      <p>Create once. Earn when others use your work.</p>
    </main>
  );
}
export default function RootLayout({
  children,
}: {
  children: React.ReactNode;
}) {
  return (
    <html>
      <body>{children}</body>
    </html>
  );
}
