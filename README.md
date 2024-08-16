# Portfólio Pessoal

Este é um portfólio pessoal, desenvolvido com HTML, CSS e SASS. O objetivo deste projeto é exibir meus trabalhos e habilidades em desenvolvimento web, incluindo projetos realizados e tecnologias que domino.

## 🚀 Tecnologias Utilizadas

- **HTML**: Estrutura básica das páginas.
- **CSS**: Estilização das páginas e layout responsivo.
- **SASS**: Pré-processador CSS para uma escrita mais eficiente e manutenção do estilo.

## 📂 Estrutura do Projeto

- `index.html`: Página principal do portfólio.
- `assets/`: Pasta contendo arquivos estáticos.
  - css/`: Pasta onde o CSS gerado pelo SASS é armazenado.
  - scss/`: Pasta para arquivos SASS, organizada da seguinte forma:
    - `base/`: Reset de estilos.
    - `global/`: Estilos genêricos, cores, mixins e tipografias.
    - `layouts/`: Estilos das sessões da página.
    - `util/`: Estilos utilitários e media queries.
    - `main.scss`: Arquivo principal que importa todos os outros arquivos SASS.

## 🛠️ Como Rodar o Projeto

1. **Clone o repositório:**

   ```bash
   git clone https://github.com/ifatinha/portfolio-website.git
   ```

2. **Navegue até o diretório do projeto:**
    ```bash
   cd portfolio-website
   ```

3. **Instale as dependências do SASS (se necessário):**
    ```
    npm install -g sass
    ```

3. **Compile o SASS para CSS:**
    ```
    sass scss/main.scss css/main.css
    ```

4. **Abra o arquivo index.html em um navegador para visualizar o portfólio.**
    ```
    open index.html
    ```

## 📖 Como Contribuir

Contribuições são bem-vindas! Sinta-se à vontade para abrir issues ou enviar pull requests para melhorar o projeto.

1. Fork o repositório.
2. Crie uma branch para sua feature:

    ```bash
    git checkout -b minha-feature
    ```

3. Faça commit das suas mudanças:

    ```bash
    git commit -am 'Adiciona nova feature'
    ```

4. Push para a branch:

    ```bash
    git push origin minha-feature
    ```

5. Crie uma Pull Request.

## Licença

Este projeto está licenciado sob a Licença MIT - veja o arquivo [LICENSE](LICENSE) para mais detalhes.

## 📧 Contato

Se você tiver alguma dúvida ou quiser entrar em contato, sinta-se à vontade para me enviar uma mensagem pelo [LinkedIn](https://www.linkedin.com/in/ifatima14/) ou por e-mail: [fferreira913@gmail.com](mailto:fferreira913@gmail.com).
