```html
<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width">
    <title>repl.it</title>
  </head>
  <body>
    <form>
      <!--label은 input과 함께여야 작동한다 + for와 id의 값이 동일해야 함.-->
      <!--input 태그 안에 'required' 속성을 넣어야 필수로 작성하도록 조건을 생성해줌.-->
      <label for="first-name">First Name</label>
      <input id="first-name" required placeholder="First Name" type="text" required /> 
      <br>
      <label for="last-name">Last Name</label>
      <input id="last-name" required placeholder="Last Name" type="text" required />
      <br>
      <label for="email">Email</label>
      <input id="email" required placeholder="Email" type="text" required />
      <br>
      <label for="user-name">Username</label>
      <input id="user-name" required placeholder="Username" type="text" required /> 
      <br>
      <label for="Password">Password</label>
      <input id="Password" required placeholder="Password" type="password" minlength="10" required />
      <br>
      <label for="birth-date">Birth date</label>
      <input id="birth-date" required placeholder="Birth date" type="date" required />
      <br>
      <label for="happy-scale">How happy are you?</label>
      <input id="happy-scale" type="range" required />
      <br>
      <label for="color">What is your fav. color?</label>
      <input id="color" type="color" required />
      <br>
      <input type="submit" value="Create Account" />
    </form>
  </body>
</html>
```

<br>

## ⛓ 결과물

<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width">
    <title>repl.it</title>
  </head>
  <body>
    <form>
      <!--label은 input과 함께여야 작동한다 + for와 id의 값이 동일해야 함.-->
      <!--input 태그 안에 'required' 속성을 넣어야 필수로 작성하도록 조건을 생성해줌.-->
      <label for="first-name">First Name</label>
      <input id="first-name" required placeholder="First Name" type="text" required /> 
      <br>
      <label for="last-name">Last Name</label>
      <input id="last-name" required placeholder="Last Name" type="text" required />
      <br>
      <label for="email">Email</label>
      <input id="email" required placeholder="Email" type="text" required />
      <br>
      <label for="user-name">Username</label>
      <input id="user-name" required placeholder="Username" type="text" required /> 
      <br>
      <label for="Password">Password</label>
      <input id="Password" required placeholder="Password" type="password" minlength="10" required />
      <br>
      <label for="birth-date">Birth date</label>
      <input id="birth-date" required placeholder="Birth date" type="date" required />
      <br>
      <label for="happy-scale">How happy are you?</label>
      <input id="happy-scale" type="range" required />
      <br>
      <label for="color">What is your fav. color?</label>
      <input id="color" type="color" required />
      <br>
      <input type="submit" value="Create Account" />
    </form>
  </body>
</html>