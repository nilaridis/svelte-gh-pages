<script>
  import logo from "./lib/images/logo.png";
</script>

<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="utf-8" />
    <link rel="icon" href="./favicon.ico" />
    <meta name="viewport" content="width=device-width" />
    <title>Your Svelte App Title</title> <!-- Αντικαταστήστε με τον τίτλο της εφαρμογής σας -->
    <link rel="stylesheet" href="/global.css" />
    <!-- Προσθέστε εδώ οποιαδήποτε εξωτερικά CSS αρχεία χρειάζονται -->
    <link rel="stylesheet" href="/build/bundle.css" />
  </head>
  <body data-sveltekit-preload-data="hover">
    <div style="display: contents">%svelte.body%</div>
    <script src="/build/bundle.js"></script>
  </body>
</html>