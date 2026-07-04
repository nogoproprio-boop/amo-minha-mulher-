const nao = document.getElementById("nao");
const sim = document.getElementById("sim");

const telaPergunta = document.getElementById("tela-pergunta");
const telaVideo = document.getElementById("tela-video");
const video = document.getElementById("video");

// Faz o botão "Não" fugir
function fugir(){

    const x = Math.random() * (window.innerWidth - 120);
    const y = Math.random() * (window.innerHeight - 60);

    nao.style.position = "fixed";
    nao.style.left = x + "px";
    nao.style.top = y + "px";
}

// Desktop e celular
nao.addEventListener("mouseenter", fugir);
nao.addEventListener("touchstart", fugir);

// Quando clicar em SIM
sim.addEventListener("click", ()=>{

    telaPergunta.style.display = "none";
    telaVideo.style.display = "flex";

    video.play();
});