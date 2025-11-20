PARTE 1

Trabalho desenvolvido por Leonardo E. Mamede da Silva e Letícia Francisca de Moura e Silva.

A empresa Garage Detail é um lava jato que está no ramo há três anos implantando higienização e estética automotiva. Era de outro dono, que não quis mais continuar no ramo. Em 2025, Naldo, que era funcionário, decidiu assumir como novo gestor/dono.

O site foi desenvolvido com objetivo de divulgar os serviços do Garage Detail, facilitar o agendamento online de lavagens e fortalecer a imagem da marca como referência em cuidado automotivo. Além disso, busca atrair novos clientes, fidelizar os atuais e oferecer informações claras sobre os tipos de lavagem, valores e diferenciais do estabelecimento: higienizar com detalhes.

O público inicial da empresa eram moradores da região do Guará-Sof Sul, a partir dos 18 anos, abrangendo todos os perfis de clientes e empresas. Aproveitando o avanço do e-commerce, a empresa pretende fortalecer sua presença, conquistar novos clientes e expandir suas operações para áreas vizinhas.

A paleta de cores do site é composta por tons de preto, branco e cinza, sendo o preto e o branco as cores primárias, e o cinza utilizado como cor secundária e de fundo. Essa combinação representa a identidade visual da marca, transmitindo profissionalismo, elegância e confiança. O preto expressa força e sofisticação, o branco remete à limpeza e clareza, enquanto o cinza equilibra o contraste, reforçando modernidade e neutralidade.

O site apresenta uma barra de navegação no topo da página, com os botões Início, Sobre e Serviços, posicionados para que o usuário encontre rapidamente as principais seções. Essa disposição segue padrões comuns de navegação, facilita a exploração do conteúdo e proporciona uma experiência intuitiva, incentivando o visitante a conhecer a empresa e seus serviços.

As imagens das seções mostram os serviços de lavagem, polimento e higienização de forma atrativa, despertando o interesse do visitante e evidenciando o compromisso da Garage Detail com a excelência no cuidado automotivo.

A tipografia utilizada (fonte: “Mogra”) de traços simples e contemporâneos, proporciona boa leitura e harmonia com o estilo do site. O uso predominante do preto nas letras mantém a sobriedade e reforça a estética minimalista adotada.

As cores preto, branco e cinza foram selecionadas para transmitir profissionalismo, limpeza, sofisticação e modernidade, reforçando a identidade visual da Garage Detail. 

Os botões do menu posicionados no topo facilitam a navegação e tornam a experiência do usuário intuitiva, enquanto ícones próximos aos textos reforçam a compreensão visual dos serviços. 

O layout, com barra de navegação no topo, seções bem definidas e uso de imagens atrativas, permite que o visitante encontre informações rapidamente e navegue de forma agradável pelo site.

As etapas realizadas incluíram: 
Planejamento e definição do público-alvo e objetivos, realizados por ambos em 09/10/2025; 
Criação do design no Figma, realizada por ambos em 14/10/2025; 
Desenvolvimento do código do site, realizado por Leonardo em 15/10/2025; 
Elaboração do README, realizada por Letícia em 15/10/2025.

Segue link do protótipo do Figma:


https://www.figma.com/design/IEvhcYl8z9TRqXywaucs3Z/Projeto-Integrador?node-id=0-1&t=aa20TCKRnKUGdYJj-1 


* O que já está funcionando bem:
R. Interação, Inputs.
* Quais elementos HMTL se repetem em várias páginas?
R. Header, Nav, Footer, Aside.
* Onde o layout quebra ou fica estranho?
R. Na Página inicial, Menu de navegação, Footer, falta de elementos em Serviço e Sobre. 
* Quais melhorias fariam diferença real para o usuário do pequeno negócio?
R. Na parte de ofertas interativas.





PARTE 2

Garage Detail, lava jato com serviço apenas precencial e com o avanço do e-commerce, a empresa pretende fortalecer sua presença, conquistar novos clientes e expandir suas operações para áreas vizinhas com a ajuda do site
 desenvolvido por Leonardo E. Mamede da Silva e Letícia Francisca de Moura e Silva.

O site foi aberto no DevTools e está funcionando perfeitamente em todas as resoluções de tela
Não houve quebra no layout
Colocar um skiplink para melhoria do usuário 
As partes que se repetem e são idênticos: Header, nav, aside, footer
Os cards tem a mesma estrutura
Nossa seção de contato aparece em todas as páginas
Todas as páginas carregam corretamente, o código está funcionando bem
Interação, Inputs está funcionando bem
Usamos a tags (<header>, <nav>, <main>, <section>, <footer>)
Na pagina de início, temos 2 títulos principais e na página sobre temos um título principal. Os títulos seguem hierarquia lógica.
Todas as imagens têm atributo alt 
Todos os campos têm <label> associado via atributo for
Usamos <label> do lado de fora e não usamos placeholder
Não possui atributo required ou indicação visual
Todos os links e botões são acessíveis via Tab (por teclado)
Nosso projeto contém focus no CSS
O código não contém um skip link
Nosso site contém texto e fundo com contraste adequado (mínimo 4.5:1)
O tamanho da fonte é legível de tamanho 2 rem (32px)
No Lighthouse tivemos nota 50 de desempenho, 99 de acessibilidade, 96 de prática recomendas e 91 de CSO
O media queries está funcionando nas três
resoluções
As imagens estão fluidas e os grids se adaptam as resoluções
A estrutura de arquivos está organizada
Ajustamos a acessibilidade de todas as páginas
<header>, <nav>, <aside> 
Foram modularizados para facilitar qualquer futura mudança no projeto, usando apenas o recurso de componentes
O desafio que encontramos foi como colocar os componentes, consertar o erro das imagens já existetes da ultima entrega.

Futuras melhorias na parte de ofertas interativas fariam diferença real para o usuário do pequeno negócio, botão voltar ao topo pode ser acrescentado, efeitos hover mais elaorados.



Estrutura de pastas
.dist/
|-- index.html
|-- produtos.html
|-- serviços.html
|-- sobre.html
|-- componentes/
|   |-- header.html
|   |-- footer.html
|   |-- aside.html
|   |-- nav.html
|   |-- ofertas.html
|-- css/
|   |-- style.css
|   |-- responsive.css
|   |-- componentes.css
|-- js/
|   |-- components.js
|-- docs/
|   |-- rubricaDFE.pdf
|   |  |-- Protótipo Garage Deatail
|   |  |  |-- image 2
|   |  |  |-- image 3
|   |  |  |-- Protótipo Garage Detail
|-- img/
|   |-- carroRED.jpeg
|   |-- grand_b.jpeg
|   |-- grand_p.jpeg
|   |-- imagem_retan.jpeg
|   |-- lavagem.jpeg
|   |-- logo_b.jpeg
|   |-- logo_inst.jpeg
|   |-- logo_p.jpeg
|   |-- logo_whats.jpeg
|   |-- meninaLJ.jpeg
|   |-- polimento.jpeg
|-- README.md 

PARTE 3

Projeto: Garage Detail 

Trabalho desenvolvido por Leonardo E. Mamede da Silva e Letícia Francisca de Moura e Silva. 

Link do protótipo no Figma: 
https://www.figma.com/design/IEvhcYl8z9TRqXywaucs3Z/Projeto-Integrador?node-id=0-1&t=aa20TCKRnKUGdYJj-1 
 
Acesso ao site que foi publicado no Git Pages:  

https://leonardmamede.github.io/Projeto-final-Garage/ 

<img width="1564" height="876" alt="image" src="https://github.com/user-attachments/assets/187cf1a1-b550-45ce-9971-36df3f0013fd" />


Data de publicação: 12/11/2025 

A empresa Garage Detail é um lava jato que está no ramo há três anos implantando higienização e estética automotiva. Era de outro dono, que não quis mais continuar no ramo. Em 2025, Naldo, que era funcionário, decidiu assumir como novo gestor/dono. 

 

O site foi desenvolvido com objetivo de divulgar os serviços do Garage Detail, facilitar o agendamento online de lavagens e fortalecer a imagem da marca como referência em cuidado automotivo. Além disso, busca atrair novos clientes, fidelizar os atuais e oferecer informações claras sobre os tipos de lavagem, valores e diferenciais do estabelecimento: higienizar com detalhes. 

 

O público inicial da empresa eram moradores da região do Guará-Sof Sul, a partir dos 18 anos, abrangendo todos os perfis de clientes e empresas. Aproveitando o avanço do e-commerce, a empresa pretende fortalecer sua presença, conquistar novos clientes e expandir suas operações para áreas vizinhas. 

 

A paleta de cores do site é composta por tons de preto, branco e cinza, sendo o preto e o branco as cores primárias, e o cinza utilizado como cor secundária e de fundo. Essa combinação representa a identidade visual da marca, transmitindo profissionalismo, elegância e confiança. O preto expressa força e sofisticação, o branco remete à limpeza e clareza, enquanto o cinza equilibra o contraste, reforçando modernidade e neutralidade. 

 

O site apresenta uma barra de navegação no topo da página, com os botões Início, Sobre e Serviços, posicionados para que o usuário encontre rapidamente as principais seções. Essa disposição segue padrões comuns de navegação, facilita a exploração do conteúdo e proporciona uma experiência intuitiva, incentivando o visitante a conhecer a empresa e seus serviços. 

 

As imagens das seções mostram os serviços de lavagem, polimento e higienização de forma atrativa, despertando o interesse do visitante e evidenciando o compromisso da Garage Detail com a excelência no cuidado automotivo. 

Usamos uma logomarca feita pela própria empresa (Garage Detail) 

A tipografia utilizada (fonte: “Mogra”) de traços simples e contemporâneos, proporciona boa leitura e harmonia com o estilo do site. O uso predominante do preto nas letras mantém a sobriedade e reforça a estética minimalista adotada. 

 

As cores preto, branco e cinza foram selecionadas para transmitir profissionalismo, limpeza, sofisticação e modernidade, reforçando a identidade visual da Garage Detail.  

 

Os botões do menu posicionados no topo facilitam a navegação e tornam a experiência do usuário intuitiva, enquanto ícones próximos aos textos reforçam a compreensão visual dos serviços.  

 

O layout, com barra de navegação no topo, seções bem definidas e uso de imagens atrativas, permite que o visitante encontre informações rapidamente e navegue de forma agradável pelo site. 

 

As etapas realizadas incluíram:  

Planejamento e definição do público-alvo e objetivos, realizados por ambos em 09/10/2025;  

Criação do design no Figma, realizada por ambos em 14/10/2025;  

Desenvolvimento do código do site, realizado por Leonardo em 15/10/2025;  

Elaboração do README, realizada por Letícia em 15/10/2025. 

 

Garage Detail, lava jato com serviço apenas presencial e com o avanço do e-commerce, a empresa pretende fortalecer sua presença, conquistar novos clientes e expandir suas operações para áreas vizinhas com a ajuda do site 

 desenvolvido por Leonardo E. Mamede da Silva e Letícia Francisca de Moura e Silva. 

 

O site foi testado no DevTools e está funcionando corretamente em todas as resoluções de tela, sem apresentar quebras no layout. Mantivemos uma estrutura consistente em todas as páginas, incluindo elementos que se repetem de forma idêntica, como header, nav, aside e footer. Os cards também seguem a mesma estrutura, garantindo padrão visual e organização. 

Além disso, a seção de contato está presente em todas as páginas, facilitando o acesso do usuário às informações de comunicação. 

Todas as páginas do site estão carregando corretamente e o código está funcionando como esperado. As interações e os campos de input também estão operando sem problemas, garantindo que o usuário consiga navegar e utilizar as funcionalidades com fluidez, utilizamos corretamente as tags semânticas <header>, <nav>, <main>, <section> e <footer>, contribuindo para uma estrutura organizada, acessível e de fácil manutenção. 

Na página de início, utilizamos dois títulos principais, enquanto na página “Sobre” há apenas um título principal. Todos eles seguem uma hierarquia lógica, tendo boa organização e clareza na estrutura do conteúdo. 

Todas as imagens do site possuem atributo alt, contribuindo para acessibilidade e melhor interpretação por leitores de tela. Da mesma forma, todos os campos de formulário têm um <label> associado por meio do atributo for, assegurando boa usabilidade. Optamos por posicionar o <label> do lado de fora dos inputs e não utilizamos placeholders, garantindo maior acessibilidade e evitando ambiguidades no preenchimento. 

Todos os links e botões do site são acessíveis via Tab, garantindo navegação completa pelo teclado. Nosso projeto também conta com estilos de foco definidos no CSS, facilitando a identificação do elemento selecionado. 

Atualmente, o código não possui um skip link, o que pode ser considerado uma melhoria futura para acessibilidade. Ainda assim, o site apresenta contraste adequado entre texto e fundo, mantendo o mínimo recomendado de 4.5:1, e utiliza uma fonte legível em tamanho 2rem (32px), contribuindo para uma leitura confortável. 

Nos testes realizados no Lighthouse, obtivemos nota 50 em desempenho, 99 em acessibilidade, 96 em práticas recomendadas e 91 em SEO, demonstrando que o site atende bem aos critérios de qualidade, especialmente no que diz respeito à acessibilidade e boas práticas. 

O media queries está funcionando corretamente nas três resoluções previstas, garantindo que o layout se adapte de forma responsiva. As imagens são fluidas e os grids se ajustam às diferentes larguras de tela, mantendo um visual consistente em qualquer dispositivo. 

Nossa estrutura de arquivos está organizada, facilitando manutenção e leitura do código. realizamos ajustes de acessibilidade em todas as páginas. 

<header>, <nav>, <aside>  

Foram modularizados para facilitar qualquer futura mudança no projeto, usando apenas o recurso de componentes 

O desafio que encontramos foi como colocar os componentes, consertar o erro das imagens já existetes da última entrega. 

Futuras melhorias na parte de ofertas interativas fariam diferença real para o usuário do pequeno negócio, botão voltar ao topo pode ser acrescentado, efeitos hover mais elaborados. 

Estrutura de arquivos 
 

|-- index.html |-- serviços.html |-- sobre.html |-- componentes/ | |-- header.html | |-- aside.html | |-- footer.html | |--nav.html | |-- ofertas.html |-- css/ | |-- style.min.css | |-- responsivo.css | -- js/ | |-- componentes.js |-- docs/ | |-- rubricaDFE.pdf | | |-- Protótipo Garage Detalhe | | | |-- imagem 2 | | | |-- imagem 3 | | | |-- Detalhe Protótipo Garagem |-- img_web/ | |-- carroRED.webp | |-- grand_b.webp | |-- grand_p.webp | |-- imagem_retan.webp | |-- lavagem.webp | |-- logo_b.webp | |-- logo_inst.webp | |-- logo_p.webp | |-- logo_whats.webp | |-- meninaLJ.webp | |-- |-- README.md 

Utilizamos as tecnologias HTML5, CSS3 e Javascript no projeto 

Para executar o projeto no ambiente local, é preciso abrir o VSCode com um espaço de trabalho vazio. Depois de carregar a pasta no editor, abra o arquivo index.html e selecione Go Live para iniciar o Live Server e visualizar o site funcionando. Por conta da modularização, os componentes em Java Script não serão exibidos se o arquivo for aberto diretamente pelo navegador (ex.: C:\MeuPC\Documentos\index.html). 
 
Fizemos a minificação do CSS e do javascript para melhoria do carregamento do site. 

As imagens utilizadas no site passaram por otimização e foram convertidas para o formato .webp. 

O projeto foi desenvolvido em três etapas: na Parte 1, estruturamos o HTML básico; na Parte 2, aplicamos a estilização usando CSS3; e na Parte 3, realizamos os ajustes finais e adicionamos as funcionalidades em Java Script. 

Plano para melhorias: Colocar javascript com maior interação com usuário,  
 
Testes realizados: 

Microsoft edge, Chrome,  
Foram testadas em três resoluções: Desktop, tablet e mobile 
Além do computador, utilizamos nossos celulares para testar as páginas e garantir que tudo estivesse funcionando corretamente. 
 
Reflexão Individual (Letícia) 
Quando começamos o projeto eu entendi a importância de colocar cada passo antes de tudo e principalmente antes de começar o html, ajudou bastante em relação aos erros anteriores. Eu entendia bem pouco sobre html, após esse trabalho tenho mais uma noção. Continuo com dificuldades sobre o CSS, mas com o livro HTML e CSS3 percebo que estou evoluindo aos poucos.  
GitHub no geral foi o que mais achei desafiador, nunca tive contato, confesso que me assustou um pouco, mas com a paciência e ajuda da minha dupla ele super me explicou e conseguimos seguir bem. Precisamos de assistir vídeos no youtube, que foi de grande ajuda. Me desesperei em várias etapas, mas o Leonardo sempre paciente me dando suporte. A parte dos documentos também achei complicada. 

Nos reunimos online e em sala de aula para dividir as tarefas a cada etapa, um ajudando na dificuldade do outro, falando o que cada um já havia feito.  

Ainda preciso melhorar mais minha organização para estudar com mais eficiência e procurar cursos adicionais que reforcem minha formação na faculdade. 

 

Reflexão Individual (Leonardo) 

Trabalho digno do nome pela sua complexidade, trabalhamos de forma mais coerente e unidos, decidindo tudo entre nós mesmo para à realização. Durante o desenvolvimento do trabalho achei algumas partes mais fáceis e outras mais difíceis, e outras mais custosas para se fazer como o documents.  
O mais desesperador foi que quando enviei a pasta para o GitHub o site obteve um erro crítico onde nada concertava, mesmo que no Live Serve mostrando que estava funcionando perfeitamente. Nesse momento eu fiz tanta verificação de código depois de minificação que fiquei louco e quase desistir, mas depois de fazer um novo repositório foi! 
Na criação do CSS observei algumas dificuldades que tinha, mas fui em busca de informações e de ajuda quando ficava empacado. 

Gostei muito da forma que o site se estabeleceu, as criações e as dinâmicas para realizá-lo. 
 
 
Reflexão da dupla 

Acreditamos que evoluímos muito com o projeto, e que as expectativas do nosso trabalho foram alcançadas com sucesso, tivemos momentos que achamos que não daria certo, mas agora vendo o site pronto, estamos com o sentimento de dever cumprido. 

Com a aplicação de estratégias de SEO, o tráfego orgânico pode crescer de forma expressiva, estimulando os clientes a visitarem a loja presencialmente ou a se informarem sobre o serviço pelo o nosso site. A venda deste site ao proprietário seria totalmente viável, pois toda a estrutura — incluindo seções, layout, ícones e textos — foi planejada especificamente para atingir o público-alvo do negócio. 
