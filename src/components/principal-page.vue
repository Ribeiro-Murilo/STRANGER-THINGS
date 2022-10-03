<template>
  <div class="conteiner">
    <div class="home">
      <logo />
      <h2>
        Uma jornada para quem não tem medo do desconhecido. O caminho para o
        Mundo invertido é incerto, repleto de obstáculos e perigos. Porém, a
        recompensa é grande: salvar Hawkings e o mundo todo das garras de Vecna.
        Você está preparado? Então clique no botão abaixo para entrar no Mundo
        Invertido!
      </h2>
      <button>Inverter Mundo</button>
    </div>
    <div class="sobre">
      <div class="sobre--text">
        <h1>O MUNDO INVERTIDO</h1>
        <p>
          O Mundo Invertido parece uma cópia do nosso mundo, mas com criaturas
          horrendas, tempestades assustadoras, muita escuridão e entidades
          malignas. Um reino controlado por Vecna, que tem planos de trazer tudo
          isso ao nosso mundo.
        </p>
      </div>
      <div class="sobre--img">
        <img src="../assets/imagens/inverted-world.png" alt="" />
      </div>
    </div>
    <div class="treiler">
      <div class="treiler--video">
        <iframe
          src="https://www.youtube.com/embed/otutSrxYpa4?controls=0"
          frameborder="0"
        ></iframe>
      </div>
      <div class="treiler--text">
        <h2>STRANGER THINGS VOL. 4</h2>
        <p>
          Mais experientes, os heróis de Stranger Things também precisam
          enfrentar desafios maiores do que nunca e fazer decisões que vão mudar
          suas vidas para sempre. Confira ao lado o trailer da quarta temporada.
        </p>
      </div>
    </div>
    <div class="imagens-serie">
      <h1>A SEGUNDA SÉRIE MAIS ASSISTIDA DA NETFLIX</h1>
      <div class="imagens">
        <img src="../assets/imagens/serie-image-02.png" alt="" />
        <img src="../assets/imagens/serie-image-01.png" alt="" />
        <img src="../assets/imagens/serie-image-03.png" alt="" />
      </div>
    </div>
    <div class="clube">
      <div class="clube--sobre">
        <h1>O CLUBE DUNGEONS & DRAGONS</h1>
        <p>
          Para deter Vecna, os heróis de Stranger Things também precisam de
          você. O Clube de D&D mais famoso de Hawkings está com vagas abertas
          para sua próxima aventura. Se você é destemido, gosta de desafios e
          não tem medo de rodar o D20, chegou a hora de se inscrever para fazer
          parte da nova campanha.
        </p>
      </div>
      <div class="clube--entrar">
        <div class="text">
          <h2>ENTRE PARA O CLUBE DE D&D E TENHA EXPERIÊNCIAS DE OUTRO MUNDO</h2>
        </div>
        <div class="inscrever">
          <h4>Nome</h4>
          <input type="text" />
          <h4>E-mail</h4>
          <input type="text" />
          <h4>Level</h4>
          <input type="text" />
          <h4>Personagem</h4>
          <input type="text" />
          <button>Me inscrever</button>
        </div>
      </div>
    </div>
    <div class="final">
        <logo />
    </div>
  </div>
</template>

<script>
import logo from "../assets/icons/logo.svg";
export default {
  components: {
    logo,
  },
};
</script>

<style></style>
