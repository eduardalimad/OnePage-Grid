<template>
  <div class="container">
    <div class="header">
      <div class="header-left">
        <h3>Lorem ipsum dolor sit amet</h3>
        <p>
          Lorem ipsum dolor sit amet, consectetur adipiscing elit. Maecenas eu
          massa sit amet augue consectetur ullamcorper non ac massa.
        </p>
        <button class="btn-purple">click-me</button>
      </div>
      <div class="header-right">
        <img
          src="..\public\img\imgHeader.svg"
          alt="imagem de caixas "
          style="width: auto; max-width: 70%"
        />
      </div>
    </div>
    <div class="main">
      <div class="grid-container">
        <div class="grid-item">
          <div
            class="wallpaper-purpple"
            style="background-color: blueviolet; width: 200px; height: 8rem"
          ></div>
          <h3>Título do card</h3>
          <p>
            Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vestibulum
            in neque et nisl.
          </p>
        </div>
        <div class="grid-item">
          <div
            class="wallpaper-red"
            style="background-color: red; width: 200px; height: 8rem"
          ></div>
          <h3>Título do card</h3>
          <p>
            Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vestibulum
            in neque et nisl.
          </p>
        </div>
        <div class="grid-item">
          <div
            class="wallpaper-green"
            style="background-color: green; width: 200px; height: 8rem"
          ></div>
          <h3>Título do card</h3>
          <p>
            Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vestibulum
            in neque et nisl.
          </p>
        </div>
        <div class="grid-item">
          <div
            class="wallpaper-yellow"
            style="background-color: yellow; width: 200px; height: 8rem"
          ></div>
          <h3>Título do card</h3>
          <p>
            Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vestibulum
            in neque et nisl.
          </p>
        </div>
        <div class="grid-item">
          <div
            class="wallpaper-blue"
            style="
              background-color: rgba(102, 99, 255, 1);
              width: 200px;
              height: 8rem;
            "
          ></div>
          <h3>Título do card</h3>
          <p>
            Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vestibulum
            in neque et nisl.
          </p>
        </div>
        <div class="grid-item">
          <div
            class="wallpaper-pink"
            style="
              background-color: rgba(243, 99, 255, 1);
              width: 200px;
              height: 8rem;
            "
          ></div>
          <h3>Título do card</h3>
          <p>
            Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vestibulum
            in neque et nisl.
          </p>
        </div>
      </div>
    </div>
    <div class="footer">
      <h2>Entre em Contato</h2>
      <form action="" class="form-email">
        <input type="text" class="input-name" placeholder="Nome:" />
        <input type="text" class="input-email" placeholder="Email:" />
        <input type="text" class="input-fone" placeholder="Telefone:" />
        <textarea
          type="text"
          class="input-mensagem"
          placeholder="Mensagem"
          style="height: 70px"
        >
        </textarea>
        <button class="button-Enviar">enviar</button>
      </form>
    </div>
  </div>
</template>
<style >
html,
body {
  padding: 0px;
  margin: 0px;
  font-family: Arial, Helvetica, sans-serif;
}
.container {
  width: 100%;
}
.header {
  display: flex;
  background-color: rgba(215, 212, 255, 1);
}
.header-left,
.header-right {
  width: 40%;
  padding: 2%;
  margin: auto;
}
.btn-purple {
  width: 35%;
  height: 2.5rem;
  background-color: rgba(108, 99, 255, 1);
  border: none;
  border-radius: 0.3rem;
  color: white;
}
.main {
  height: auto;
  padding: 5%;
}
.grid-container {
  display: grid;
  grid-template-columns: repeat(3, auto);
  grid-template-rows: 1fr 1fr;
  justify-content: center;
  grid-gap: 5rem;
}
.grid-item {
  width: 200px;
  height: auto;
  font-size: small;
  background: #ffffff;
  box-shadow: 0px 0px 20px rgba(0, 0, 0, 0.3);
}
p,
h3 {
  padding: 2%;
  margin-left: 2%;
}
.footer {
  display: grid;
  width: 100%;
  height: 40rem;
  align-items: center;
  background-color: #d7d5ff;
  justify-items: center;
  justify-content: center;
  align-content: center;
}
.form-email {
  display: grid;
  margin: auto;
  gap: 7%;
  justify-items: center;
}
input {
  width: 470px;
  height: 40px;
  border: none;
  padding: 2%;
  background: #ffffff;
  border-radius: 6px;
}
.input-mensagem {
  width: 470px;
  height: 40px;
  border: none;
  padding: 2%;
  background: #ffffff;
  border-radius: 6px;
}
.button-Enviar {
  width: 480px;
  height: 3rem;
  background-color: rgba(108, 99, 255, 1);
  color: white;
  border: none;
  box-shadow: 0px 5px 5px rgba(23, 23, 23, 0.1);
  border-radius: 5px;
}

@media only screen and (max-width: 740px) {
  .header,
  .header-left,
  .header-right {
    background-color: lightblue;
    display: block;
    width: auto;
  }
  .grid-container {
    display: flex;
    flex-wrap: wrap;
  }
  input {
    width: 270px;
    height: 30px;
  }
  .button-Enviar {
    width: 270px;
    height: 30px;
  }
}
</style>