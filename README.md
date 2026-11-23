<div align="center">

<img src="docs/banner.png" alt="Álbuns Oficina G3" width="100%">

<br><br>

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![Responsivo](https://img.shields.io/badge/Responsivo-e10600?style=for-the-badge)
![Licença MIT](https://img.shields.io/badge/Licença-MIT-black?style=for-the-badge)

**[🌐 Ver o site ao vivo](https://kaiquednzz.github.io/albuns-oficinag3/)**

</div>

---

## 🎸 Sobre o projeto

Mini site sobre a história e a discografia da banda **Oficina G3**. Ele reúne os álbuns de estúdio e ao vivo, cada um com uma página própria contendo a capa, o texto sobre o disco, a tracklist e os players do Spotify e do Apple Music para ouvir na hora.

Foi um dos meus primeiros projetos de estudo em desenvolvimento web, feito só com HTML e CSS para treinar estrutura de páginas, estilização, responsividade e organização de arquivos. Sem framework, sem build, sem dependência nenhuma.

## 📸 Preview

<div align="center">

<img src="docs/index-full.jpg" alt="Página inicial do site, com a apresentação da banda e a grade de álbuns" width="80%">

<sub>Página inicial: apresentação da banda e grade com todos os álbuns</sub>

<br><br>

<img src="docs/album-desktop.jpg" alt="Página de um álbum, com capa, título e descrição" width="80%">

<sub>Página de álbum: capa, texto sobre o disco, tracklist e players</sub>

<br><br>

<img src="docs/index-mobile.jpg" alt="Página inicial no celular" width="240">
&nbsp;&nbsp;&nbsp;
<img src="docs/album-mobile.jpg" alt="Página de álbum no celular" width="240">

<sub>Versão mobile</sub>

</div>

## 💿 Discografia no site

<div align="center">

<table>
  <tr>
    <td align="center"><a href="https://kaiquednzz.github.io/albuns-oficinag3/pages/ao-vivo.html"><img src="images/ao-vivo-image.jpg" width="150" alt="Capa de Ao Vivo"></a><br><sub><b>Ao Vivo</b><br>1990</sub></td>
    <td align="center"><a href="https://kaiquednzz.github.io/albuns-oficinag3/pages/nada-e-velho.html"><img src="images/nada-e-velho-image.jpg" width="150" alt="Capa de Nada é Tão Novo, Nada é Tão Velho"></a><br><sub><b>Nada é Tão Novo,<br>Nada é Tão Velho</b><br>1994</sub></td>
    <td align="center"><a href="https://kaiquednzz.github.io/albuns-oficinag3/pages/indiferenca.html"><img src="images/indifecenca-image.jpg" width="150" alt="Capa de Indiferença"></a><br><sub><b>Indiferença</b><br>1996</sub></td>
    <td align="center"><a href="https://kaiquednzz.github.io/albuns-oficinag3/pages/acustico.html"><img src="images/acustico-image.jpg" width="150" alt="Capa de Acústico"></a><br><sub><b>Acústico</b><br>1998</sub></td>
    <td align="center"><a href="https://kaiquednzz.github.io/albuns-oficinag3/pages/o-tempo.html"><img src="images/o-tempo-image.jpg" width="150" alt="Capa de O Tempo"></a><br><sub><b>O Tempo</b><br>2000</sub></td>
  </tr>
  <tr>
    <td align="center"><a href="https://kaiquednzz.github.io/albuns-oficinag3/pages/humanos.html"><img src="images/humanos-image.jpg" width="150" alt="Capa de Humanos"></a><br><sub><b>Humanos</b><br>2002</sub></td>
    <td align="center"><a href="https://kaiquednzz.github.io/albuns-oficinag3/pages/alem-do-que-os-olhos.html"><img src="images/alem-do-que-os-olhos-image.jpg" width="150" alt="Capa de Além do que os Olhos Podem Ver"></a><br><sub><b>Além do que os<br>Olhos Podem Ver</b><br>2005</sub></td>
    <td align="center"><a href="https://kaiquednzz.github.io/albuns-oficinag3/pages/elektracustica.html"><img src="images/elektracustica-image.jpg" width="150" alt="Capa de Elektracustika"></a><br><sub><b>Elektracustika</b><br>2007</sub></td>
    <td align="center"><a href="https://kaiquednzz.github.io/albuns-oficinag3/pages/depois-da-guerra.html"><img src="images/depois-da-guerra-image.jpg" width="150" alt="Capa de Depois da Guerra"></a><br><sub><b>Depois da Guerra</b><br>2008</sub></td>
    <td align="center"><a href="https://kaiquednzz.github.io/albuns-oficinag3/pages/h%26b.html"><img src="images/historias-e-bicicletas-image.jpg" width="150" alt="Capa de Histórias de Bicicletas"></a><br><sub><b>Histórias de Bicicletas</b><br>2013</sub></td>
  </tr>
</table>

</div>

## ✨ O que tem por dentro

- Página inicial com apresentação da banda, fatos rápidos e grade de álbuns
- Uma página para cada álbum, com capa, gêneros, descrição e tracklist numerada
- Players do Spotify e do Apple Music embutidos em cada disco
- Layout responsivo, com ajustes para tablet e celular
- Tema escuro com fundo de show e detalhes em vermelho, na identidade da banda
- Todo o conteúdo em português do Brasil

## 🛠️ Tecnologias

| Tecnologia | Uso |
| --- | --- |
| **HTML5** | Estrutura semântica das páginas (`header`, `main`, `section`, `footer`) |
| **CSS3** | Estilização, grid e flexbox, media queries para responsividade |
| **Google Fonts** | Fonte Raleway |
| **Spotify e Apple Music** | Players embutidos via `iframe` |

## 📁 Estrutura

```
albuns-oficinag3/
├── index.html          # Página inicial
├── pages/              # Uma página HTML por álbum
├── style/
│   └── style.css       # Estilo único compartilhado por todas as páginas
├── script/
│   └── script.js
├── images/             # Capas dos álbuns, logo e imagem de fundo
└── docs/               # Imagens usadas neste README
```

## 🚀 Como rodar localmente

Não precisa instalar nada. Clone o repositório e abra o `index.html` no navegador:

```bash
git clone https://github.com/kaiquednzz/albuns-oficinag3.git
cd albuns-oficinag3
```

Se preferir servir por um servidor local:

```bash
python3 -m http.server 8000
```

Depois é só acessar `http://localhost:8000`.

## 📚 O que aprendi

- Montar a estrutura de um site com várias páginas reaproveitando o mesmo padrão
- Organizar um CSS único para o projeto inteiro, separado por seções
- Deixar o layout responsivo com media queries
- Incorporar conteúdo externo com `iframe`
- Cuidar de caminhos relativos entre páginas e pastas

## 📄 Licença

Distribuído sob a licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.

## 👤 Autor

**Kaique Diniz**

[![GitHub](https://img.shields.io/badge/GitHub-kaiquednzz-181717?style=flat&logo=github&logoColor=white)](https://github.com/kaiquednzz)

---

<div align="center">
<sub>Projeto feito para estudo. Oficina G3 é uma banda brasileira, e as capas e os nomes pertencem aos seus respectivos donos. Site oficial: <a href="https://oficinag3.com.br">oficinag3.com.br</a></sub>
</div>
