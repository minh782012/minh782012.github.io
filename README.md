
<html>
  <style>
    body {
      background-color: lightblue;
    }
    h1 {
      text-shadow: -1px 0 black, 0 1px black, 1px 0 black, 0 -1px black;
      text-transform: uppercase;
      margin: 0;
      text-align: center;
    }

    header h1 {
      animation: tbu 6s infinite ease-in-out;
    }

    @keyframes tbu {
      0% {
        color: rgb(195, 77, 253);
      }
      50% {
        color: rgb(105, 245, 255);
      }
      100% {
        color: white;
      }
    }
    input[type="text"],
    select {
      width: 100%;
      padding: 12px 20px;
      margin: 8px 0;
      display: inline-block;
      border: 1px solid #ccc;
      border-radius: 4px;
      box-sizing: border-box;
    }

    input[type="submit"] {
      width: 100%;
      background-color: #4caf50;
      color: white;
      padding: 14px 20px;
      margin: 8px 0;
      border: none;
      border-radius: 4px;
      cursor: pointer;
    }

    input[type="submit"]:hover {
      background-color: #45a049;
    }

    div {
      border-radius: 5px;
      background-color: #f2f2f2;
      padding: 20px;
    }
  </style>
  <body>
    <header>
      <h1>Đăng nhập</h1>
    </header>

    <div>
      <form action="https://minh682012.github.io">
        <label for="fname">First Name</label>
        <input
          type="text"
          id="fname"
          name="firstname"
          placeholder="Your name.."
        />

        <label for="lname">Last Name</label>
        <input
          type="text"
          id="lname"
          name="lastname"
          placeholder="Your last name.."
        />

        <label for="country">Password</label>
        <input
          type="text"
          id="Pword"
          name="Password"
          placeholder="Your password...."
        />

        <input type="submit" value="Submit" />
      </form>
    </div>
  </body>
</html>
