# formEmail

Como deixou o formulário funcional (envio de form para um E-mail)
Comandos Git que usou para criar e publicar seu repositótio no GitHub

 O formulário foi criado na aula de Linguagem de Marcação, utilizando linguagens como: HTML e CSS, foi utilizado:
 - Elementos: form, div, input.
 - Atributos: id, class, type.
 - Estilização com fontes, cores, borda, margem.

O envio tornou-se funcional por meio do action no html, com uma API própria que permite o envio, chamada formsubmit, então foi colocado o link e um email para fins de teste, e com o atributo method = "post", faz com que ele seja funcional. Ao final foi colocar um input do tipo hidden e nome _next para depois do captcha aparecer o meu site de formulário enviado com sucesso.

 Os comandos do Git utilizado para criar e publicar o repositório foram:
- git init
- git commit -m "first commit"
- git branch -M main
- git remote add origin https://github.com/meuPerfil/nomeProjeto.git
- git pull origin main --allow-unrelated-histories
- git push -u origin main
