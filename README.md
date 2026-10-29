<p align="center">
  <img src="assets/banner.png" alt="FrontEnd TCC" width="100%">
</p>

<p align="center">
  Módulo de cabeçalho navegacional e folha de estilos globais em HTML5 e CSS3 desenvolvidos para a identidade visual do TCC.
</p>

<p align="center">
  <img alt="HTML5" src="https://img.shields.io/badge/HTML5-Sem%C3%A2ntico-C52E36?style=for-the-badge&logo=html5&logoColor=white">
  <img alt="CSS3" src="https://img.shields.io/badge/CSS3-Global_Styles-11120F?style=for-the-badge&logo=css3&logoColor=C52E36">
  <img alt="UI" src="https://img.shields.io/badge/M%C3%B3dulo-Header_Component-18181B?style=for-the-badge">
</p>

## Sobre o projeto

Durante a construção de uma aplicação web em equipe para o **Trabalho de Conclusão de Curso (TCC)**, padronizar o cabeçalho de navegação e o reset de estilos globais garante consistência visual entre todas as telas do sistema.

Este repositório preserva o componente base de interface (header.html), a folha de estilos global (globals.css) e o logotipo com fundo transparente (img/), estruturados para integração direta às páginas principais do projeto.

## Principais recursos

| Recurso | Como funciona |
|---|---|
| Cabeçalho reutilizável | header.html estrutura a barra superior com marca e links de navegação prontos para inclusão nas páginas. |
| Reset e estilos globais | globals.css padroniza margens, tipografia, cores e comportamento responsivo dos elementos base. |
| Ativo gráfico otimizado | Logotipo em PNG com fundo transparente na pasta img/ para sobreposição limpa em diferentes temas. |

## Tecnologias

<p>
  <img alt="HTML5" src="https://img.shields.io/badge/HTML5-C52E36?style=flat-square&logo=html5&logoColor=white">
  <img alt="CSS3" src="https://img.shields.io/badge/CSS3-11120F?style=flat-square&logo=css3&logoColor=C52E36">
  <img alt="VS Code" src="https://img.shields.io/badge/VS_Code-C52E36?style=flat-square&logo=visualstudiocode&logoColor=white">
</p>

- **HTML5 (header.html)** para marcação semântica do componente de topo;
- **CSS3 (globals.css)** para regras de layout, flexbox e variáveis visuais.

## Arquitetura

`mermaid
flowchart LR
    A[globals.css · Estilos Base] --> C[Componente header.html]
    B[img/ · Logotipo Transparente] --> C
    C --> D[Integração nas Telas do TCC]
`

## Estrutura do repositório

`	ext
frontEndTCC/
├── assets/
│   ├── banner.png                  Banner principal do repositório
│   └── project-animal.png          Símbolo da borboleta
├── img/                            Logotipo e recursos visuais da barra superior
├── globals.css                     Regras globais de estilização e layout
├── header.html                     Estrutura HTML do componente de cabeçalho
└── README.md
`

## Executando o código

1. Clone o repositório:
   `ash
   git clone https://github.com/arthurlynow098/frontEndTCC.git
   `
2. Abra o arquivo header.html no navegador ou com a extensão *Live Server* do VS Code para inspecionar o componente renderizado junto ao globals.css.

---

<p align="center"><sub>Estudo · construção · evolução</sub><br><a href="https://github.com/arthurlynow098">Perfil</a> · <a href="https://arthurentsev.vercel.app/">Portfólio</a> · <a href="https://www.linkedin.com/in/entsevarthur/">LinkedIn</a></p>
