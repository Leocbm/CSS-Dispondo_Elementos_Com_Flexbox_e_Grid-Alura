<h1>CSS - Dispondo Elementos Com Flexbox e Grid - Alura</h1> 

> Status do Projeto: :warning: Em Construção

### Tópicos 

:small_blue_diamond: [Descrição do projeto](#descrição-do-projeto)

:small_blue_diamond: [Funcionalidades](#funcionalidades)

:small_blue_diamond: [Deploy da Aplicação](#deploy-da-aplicação)

:small_blue_diamond: [Objetivos](#objetivos)

:small_blue_diamond: [Pré-requisitos](#pré-requisitos)

:small_blue_diamond: [Como rodar a aplicação](#como-rodar-a-aplicação-arrow_forward)

:small_blue_diamond: [Guia de estilos](#guia-de-estilos)

:small_blue_diamond: [Desenvolvedores](#desenvolvedores)

:small_blue_diamond: [Instrutores](#instrutores)

## Descrição do projeto 

<p align="justify">
  Conhecendo e implementando o Flexbox e Grid para o desenvolvimento de uma página para Web através da formação Front-end da <a href="https://www.alura.com.br/">Alura</a>, desenvolvendo também do zero a página completa de uma comunidade de skate utilizando um layout dentro do Figma.
</p>

## Funcionalidades

:heavy_check_mark: Crie uma página Web utilizando mobile first.

:heavy_check_mark: Entenda o Flexbox e Grid.

:heavy_check_mark: Entenda o comportamento do layout em diferentes dispositivos.

:heavy_check_mark: Entenda unidades de medida, repetição de código e a manutenção do seu código.

## Deploy da Aplicação

> Link do deploy da aplicação com Vercel: https://hzc-page-leocbm.vercel.app/

> Imagem representativa da página
![image](https://user-images.githubusercontent.com/54343955/185694218-4209ee69-7437-4fbb-b784-f60a8a4e551c.png)

## Objetivos

:heavy_check_mark: Relacione o flexbox com maneiras já conhecidas de posicionamento de elementos.

:heavy_check_mark: Veja o flexbox e suas propriedades para o posicionamento de elementos.

:heavy_check_mark: Produza o cabeçalho utilizando as ferramentas do flexbox.

:heavy_check_mark: Identifique as limitações do flexbox.

:heavy_check_mark: Diferencie o flexbox do grid.

:heavy_check_mark: Prototipe o layout de um cartão utilizando propriedades básicas do grid.

:heavy_check_mark: Reconheça no layout do figma o que pode fazer parte de um grid.

:heavy_check_mark: Associe as propriedades novas com o que já existe de estrutura no projeto.

:heavy_check_mark: Veja como o layout atual se comporta em um dispositivo diferente.

:heavy_check_mark: Resolva os problemas com novas propriedades de grid.

:heavy_check_mark: Produza o restante do layout com novas propriedades de grid.

:heavy_check_mark: Identifique problemas como: repetição de código, manutenção e unidades de medida.

:heavy_check_mark: Entenda as vantagens de se utilizar a abordagem do grid.

:heavy_check_mark: Planeje como pode ser a construção das outras páginas do projeto utilizando as técnicas aprendidas.

## Pré-requisitos

- Editor de código-fonte qualquer, ex:
- :warning: [Visual Studio Code](https://code.visualstudio.com/)
- :warning: [Sublime Text](https://www.sublimetext.com/)
- :warning: Acesso a Internet.

## Como rodar a aplicação :arrow_forward:

No terminal, clone o projeto: 

```
git clone https://github.com/Leocbm/CSS-Dispondo_Elementos_Com_Flexbox_e_Grid-Alura.git
```
- Vá até o seu terminal, caso não saiba basta pesquisar por 'git CMD' na barra de pesquisa:
<img src="https://user-images.githubusercontent.com/54343955/182642752-1fd19d66-3b1c-46c5-9882-873eb1c3b8fc.png" width="480">

- Navegue até a pasta desejada com o comando 'cd', exemplo se sua pasta estiver no Desktop:

``` 
cd Desktop\Nova-pasta
```
- Na pasta, basta escrever o comando acima.
<img src="https://user-images.githubusercontent.com/54343955/184947487-9c1d476d-7b9f-4672-81e5-e54c37da99b5.png" width="580">

- Ou se preferir pode utilizar o terminal da própria IDE/Editor de códigos:
- Exemplo usando o terminal do Visual Studio Code:
<img src="https://user-images.githubusercontent.com/54343955/184947575-f415d62f-412e-458a-acac-2b874a43ab1e.png" width="880">

- Pronto! 😄
- Lembre-se de ter o <a href="https://git-scm.com/">git</a> instalado.

## Guia de estilos

Toda a estilização que será usada no projeto dentro do figma.

[Link do projeto no figma](https://www.figma.com/file/ibWktwVpnog76rMYOdVhks/Dispondo-elementos-com-flexbox-e-grid?node-id=54%3A2358)

## Fonte

```html
Open Sans:
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link rel="stylesheet" href="https://fonts.googleapis.com/css2?family=Open+Sans:wght@400;600;700&display=swap">
```

## Cores

corpo: `#1D232A`

cabeçalho: `#1D232A`

cabeçalho mobile: `#15191C`

menu lateral: `#15191C`

cartão: `#2C343A`

fonte: `#FFFFFF`

fonte alternativa: `#95999C`

links: `#0480DC`

botão: `#0480DC`

sombras: `0px 4px 4px rgba(0, 0, 0, 0.16)`

## Ícones

Estão dentro do arquivo de fonte `icones.ttf`. Para usar, primeiro importe a fonte no projeto usando `@font-face` e depois utilize os códigos abaixo para exibir o ícone.

```css
@font-face {
    font-family: 'icones';
    src: url(../font/icones.ttf);
}
```

> Cuidado com a localização do arquivo `icones.ttf`

Camisas = `\e900`

Carrinho = `\e901`

Inicio = `\e902`

Integrantes = `\e903`

Menu = `\e904`

Moeda = `\e905`

Notificação = `\e906`

Pico = `\e908`

Picos = `\e909`

Pinturas = `\e90a`

Play = `\e90b`

Relogio = `\e90c`

Seta-baixo = `\e90d`

Videos = `\e90e`

Visualizacao = `\e90f`

## Espaçamentos

Espaço interno botão: `8px`

Espaço entre elementos do botão: `8px`

Espaço entre elementos: `16px/8px`

Espaçamento interno do corpo: `16px`

Espaçamento entre o título do cartão de recentes e seus itens: `24px`

## Tamanhos

Tamanho do dispositivo mobile: `360px`

Tamanho do dispositivo desktop: `1440px`

Largura máxima do conteúdo principal: `1120px`

Largura máxima de um cartão desktop: `256px`

Altura mínima de um cartão: `320px`

## Desenvolvedores 
:octocat:

| [<img src="https://avatars.githubusercontent.com/u/54343955?v=4" width=250><br>](https://github.com/Leocbm)|
| :---: |
| [Leonardo Cunha](https://github.com/Leocbm) |
 [![Instagram](https://www.alura.com.br/assets/img/imersao-java/instagram.1655844054.svg)](https://www.instagram.com/leoleo_zen/) [![LinkedIn](https://www.alura.com.br/assets/img/imersao-java/linkedin.1655291590.svg)](https://www.linkedin.com/in/leonardo-cunha-317b67190/)   |

## Instrutores
:octocat:

 [<img src="https://media-exp1.licdn.com/dms/image/C4D03AQE809_noWJp0g/profile-displayphoto-shrink_200_200/0/1642888517367?e=1666224000&v=beta&t=a9rUlAIQkLfqJ-4bqCtCPOpLQrjZyYABmdu9z3Xja2I" width=250><br>](https://www.linkedin.com/in/matheus-alberto-marcus/) |[<img src="https://media-exp1.licdn.com/dms/image/C4D0BAQHnFDuaYnscdQ/company-logo_200_200/0/1658433175874?e=1668038400&v=beta&t=sI2VRJXheWgNJctiR_Ai11wSl32ooLZZD5HiIWDLkmY" width=250><br>](https://www.linkedin.com/school/aluracursos/)|
| :---: | :---: |
Matheus Alberto | Alura |
 [<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/github/github-original.svg" width="7%"/>](https://github.com/ikyrie) [![LinkedIn](https://www.alura.com.br/assets/img/imersao-java/linkedin.1655291590.svg)](https://www.linkedin.com/in/matheus-alberto-marcus/)   | [![Instagram](https://www.alura.com.br/assets/img/imersao-java/instagram.1655844054.svg)](https://www.instagram.com/aluraonline/)[![LinkedIn](https://www.alura.com.br/assets/img/imersao-java/linkedin.1655291590.svg)](https://www.linkedin.com/school/aluracursos/) |
