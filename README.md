# Plattsättaren

Det här är ett statiskt webbprojekt baserat på den befintliga HTML-prototypen.

## Publicera med GitHub + Netlify

1. Skapa ett nytt **Public** eller **Private** repository på GitHub, till exempel `plattsattaren`.
2. Ladda upp samtliga filer i den här mappen till repositoryts rot:
   - `index.html`
   - `manifest.webmanifest`
   - `icon.svg`
   - `netlify.toml`
   - `README.md`
3. I Netlify: välj **Add new site / Import an existing project**.
4. Välj **GitHub**, godkänn åtkomst om det efterfrågas och välj repositoryt `plattsattaren`.
5. Bygginställningar:
   - **Build command:** lämna tomt
   - **Publish directory:** `.`
6. Klicka **Deploy site**. Netlify ger webbplatsen en `*.netlify.app`-adress.
7. Testa länken i Safari på iPhone. I Safari kan du välja **Dela → Lägg till på hemskärmen**.

## Framtida uppdateringar

När du ändrar en fil och skickar ändringen (commit/push) till den anslutna GitHub-grenen, ska Netlify automatiskt bygga om och publicera webbplatsen.

## Viktigt om sparade projekt

Prototypen sparar lokalt i webbläsaren och kan exportera/importera projektfiler. Lokal lagring är knuten till webbläsaren/enheten; den är inte automatiskt synkroniserad mellan olika enheter. Exportera viktiga projekt som säkerhetskopia.

Det här är en prototyp under utveckling, inte en färdig produktions-CAD-app.
