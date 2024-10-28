 Start na Programação - OneBitCode

# PetLife - Um Lar Amoroso para Seu Pet

## Descrição
Este projeto foi desenvolvido durante o curso de Start na Programação da plataforma OneBitCode, criamos um site informativo e intuitivo para a clínica veterinária PetLife. O site oferece informações detalhadas sobre os serviços oferecidos, como consultas, vacinação, farmácia e muito mais, com o intuito de conectar os tutores com os cuidados essenciais para seus pets. 

## Tecnologias Utilizadas:
* **HTML5:** Estruturação da página, fornecendo a base semântica para o conteúdo.
* **CSS3:** Estilização visual, utilizando flexbox e grid para criar um layout responsivo e moderno, adaptando-se a diferentes dispositivos.
* **JavaScript:** Implementação de interações dinâmicas, como o efeito de mostrar e esconder as respostas das FAQs.

## Funcionalidades Principais
* **Página inicial:** Apresenta informações gerais sobre a clínica e os serviços prestados.
* **Página da clínica:** Detalhes sobre os serviços veterinários disponíveis.
* **Página da farmácia:** Informações sobre produtos para pets.
* **FAQs:** Seção com perguntas frequentes sobre os serviços da clínica.

## Estrutura do Projeto
* **index.html:** Arquivo principal que contém a estrutura HTML da página.
* **index.css:** Arquivo CSS responsável pelas estilizações da página.
* **script.js:** Arquivo JavaScript responsável pela interatividade das FAQs.
* **imagens:** Pasta contendo as imagens utilizadas no projeto.


## Código Exemplo (JavaScript)
```javascript
// Exemplo de como a interatividade das FAQs foi implementada:
const faqs = document.querySelectorAll('.duvida');

faqs.forEach(faq => {
  faq.addEventListener('click', () => {
    faq.classList.toggle('ativa');
  });
});
