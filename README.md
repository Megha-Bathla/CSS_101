# CSS_101
Experimenting styles in CSS
<!DOCTYPE html>
<html>
  <head>
    <title>My Personal Website</title>
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <meta charset="UTF-8" />
    <link rel="stylesheet" href="https://unpkg.com/chota@latest" />

    <style>
      body {
        font-family: "Happy Monkey", cursive;
        margin: 0;
        padding: 0;
      }
      h1 {
        background-color: #c2b4da;
        color: white;
        text-align: center;
        padding: 2rem;
      }

      main {
        padding: 20px;
      }
      section {
        margin-bottom: 20px;
      }
      footer {
        background-color: #c2b4da;
        color: white;
        text-align: center;
        padding: 1rem;
        position: fixed;
        bottom: 0;
        width: 100%;
      }
    </style>
  </head>

  <body>
    <header>
      <h1>Welcome to My Page</h1>
    </header>
    <main>
      <section>
        <h2>About Me</h2>
        <p>Hello, World! My name is Megha Bathla. I love coding. I am here to learn CSS.</p>
      </section>
      <section>
        <h2>My Interests</h2>
        <ul>
          <li>Coding</li>
          <li>Writing</li>
          <li>Reading books</li>
        </ul>
      </section>
    </main>
    <footer>
      <p>&copy; 2023 My Page. All rights reserved.</p>
    </footer>
  </body>
</html>
