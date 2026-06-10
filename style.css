console.log("Agro Forte, Futuro Sustentável carregado com sucesso!");

const elementos = document.querySelectorAll("section");

function revelar() {
    elementos.forEach(secao => {
        const topo = secao.getBoundingClientRect().top;

        if (topo < window.innerHeight - 100) {
            secao.style.opacity = "1";
            secao.style.transform = "translateY(0)";
        }
    });
}

elementos.forEach(secao => {
    secao.style.opacity = "0";
    secao.style.transform = "translateY(50px)";
    secao.style.transition = "all 0.8s ease";
});

window.addEventListener("scroll", revelar);
window.addEventListener("load", revelar);

const ano = new Date().getFullYear();

const footer = document.querySelector("footer");

if (footer) {
    footer.innerHTML += `<p>© ${ano} - Agro Forte, Futuro Sustentável</p>`;
}
