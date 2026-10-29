HELCUSTUM - get your .exe from GitHub (nothing to install on your PC)

1. Sign in at github.com and click  +  >  New repository.
   Name it "helcustum", then click Create repository.
2. Click "uploading an existing file". Drag in everything from this folder
   (index.html, main.js, package.json, README.txt, and the .github folder).
   Click Commit changes.
3. If the .github folder did not upload (hidden folders are sometimes skipped):
   click Add file > Create new file, type this as the name:
       .github/workflows/build.yml
   paste the contents of build.yml.txt, and click Commit changes.
4. Open the Actions tab. The build "Build Helcustum.exe" starts by itself
   (or click it > Run workflow). It takes about 3-5 minutes.
5. Click the finished run, scroll to Artifacts, download "Helcustum-Windows".
   Unzip it. You get:
     Helcustum-Setup.exe     installer (Start menu + desktop shortcut)
     Helcustum-Portable.exe  runs with no install
