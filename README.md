# Travelgram

Projeto front-end estático de perfil de viagens, desenvolvido com HTML e CSS.

## Sobre

O Travelgram simula uma página de perfil de uma viajante, com:

- Navegação superior com logo, menu e avatar.
- Seção de perfil com foto, bio e informações de localização/estatísticas.
- Galeria de imagens de viagens.
- Rodapé com links institucionais.

## Tecnologias

- HTML5
- CSS3
- Google Fonts (Poppins e Alice)

## Estrutura do projeto

```text
projeto-travelgram/
├── index.html
├── README.md
├── assets/
│   ├── icons/
│   └── images/
└── styles/
    ├── global.css
    ├── nav.css
    ├── header.css
    ├── main.css
    ├── footer.css
    └── index.css
```

## Como executar

1. Clone este repositório:

   ```bash
   git clone <url-do-repositorio>
   ```

2. Acesse a pasta do projeto:

   ```bash
   cd projeto-travelgram
   ```

3. Abra o arquivo `index.html` no navegador.

Sugestão: se estiver usando VS Code, você pode usar a extensão Live Server para visualizar com atualização automática.

## Organização dos estilos

- `styles/index.css`: arquivo principal que importa os demais CSS.
- `styles/global.css`: reset, variáveis e estilos globais.
- `styles/nav.css`: barra de navegação.
- `styles/header.css`: seção de perfil.
- `styles/main.css`: grid/galeria de imagens.
- `styles/footer.css`: rodapé.

## Aprendizados praticados

- Estruturação semântica com HTML.
- Separação de responsabilidades no CSS por componentes/seções.
- Uso de variáveis CSS com `:root`.
- Layout com Flexbox.

## Melhorias futuras

- Ajustar responsividade para telas menores.
- Melhorar acessibilidade (textos alternativos mais descritivos nas imagens da galeria).
- Adicionar interações visuais (hover/transições) na galeria.

## Licença

Projeto para fins de estudo.
