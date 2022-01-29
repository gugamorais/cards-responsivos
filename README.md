# cards-responsivos

<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>cards responsivos</title>
    <link rel="stylesheet" href="style.css" type="text/css">
</head>

<body class="colors">
    <main>
        <section class="contact">
            <img src="./Chat.png" height="150px" width="150px" alt="chat">
            <h2>contact us</h2>
            <p class="paragraphe">Lorem ipsum dolor sit amet, consectetur adipiscing elit. </p>
            <button> learn more</button>
        </section>
        <section class="shop">
            <img src="./Bag.png" height="150px" width="150px" alt="bag">
            <h2>shop here</h2>
            <p class="paragraphe">Lorem ipsum dolor sit amet, consectetur adipiscing elit. </p>
            <button id="middle"> learn more</button>
        </section>
        <section class="about">
            <img src="./Play.png" height="150px" width="150px" alt="Play">
            <h2>about us</h2>
            <p class="paragraphe">Lorem ipsum dolor sit amet, consectetur adipiscing elit. </p>
            <button> learn more</button>
        </section>
    </main>

</body>

</html>

* {
  padding: 0;
  margin: 0;
  border: 0;
  box-sizing: border-box;
}

body {
  background: linear-gradient(45deg, #7f7fd5, #86a8e7, #91eae4);
  background-repeat: no-repeat;
  min-height: 100vh;
  min-width: 100vh;
}

main {
  display: flex;
  flex-direction: row;
  align-items: center;
  justify-content: center;
  justify-content: space-evenly;
  padding-top: 150px;
}

.contact {
  background: rgb(255, 248, 220, 0.7);
  height: 320px;
  max-width: 260px;
  padding: 2rem;
  border-radius: 10px;
  display: flex;
  flex-direction: column;
  align-items: center;
}

.shop {
  background: rgb(255, 248, 220, 0.7);
  height: 320px;
  max-width: 260px;
  padding: 2rem;
  border-radius: 10px;
  display: flex;
  flex-direction: column;
  align-items: center;
}

.about {
  background: rgb(255, 248, 220, 0.7);
  height: 320px;
  max-width: 260px;
  padding: 2rem;
  border-radius: 10px;
  display: flex;
  flex-direction: column;
  align-items: center;
}

h2 {
  margin: 10px;
  color: white;
}

.paragraphe {
  margin: 5px;
}

button {
  background: linear-gradient(to right, #7f7fd5, #86a8e7, #91eae4);
  color: white;
  font-size: 20px;
  border-radius: 15px;
  margin-top: 5px;
  height: 50px;
  width: 150px;
}

#middle {
  background: linear-gradient(to right, #91eae4, #86a8e7, #7f7fd5);
}

@media screen and (max-width: 800px) {
  main {
    flex-direction: column;
    display: flex;
    align-items: center;
    padding: 0;
  }

  .contact {
    margin-top: 20px;
  }
  .shop {
    margin: 20px;
  }
  .about {
    margin-bottom: 20px;
  }
}



