# LabIoT-FT | Site Oficial

Este é o repositório oficial do site do **Laboratório de Internet das Coisas e Telecomunicações (LabIoT-FT)** da Faculdade de Tecnologia (FT) - UNICAMP Limeira.

## Links

* **Site em Produção (Vercel):** <https://labiotsite.vercel.app/>
* **Repositório (GitHub):** <https://github.com/lgrando1/labiotsite>

## Sobre o Laboratório

O LabIoT-FT é um centro de pesquisa focado no desenvolvimento de soluções de ponta em Internet das Coisas (IoT) e Telecomunicações. O laboratório é coordenado pelo Prof. Dr. Edson Luiz Ursini e conta com uma equipe de pesquisadores de pós-doutorado, doutorandos e mestrandos.

## Sobre o Site

Este site é uma página estática desenvolvida para apresentar as linhas de pesquisa, a equipe e as publicações selecionadas do laboratório.

### Tecnologias Utilizadas

* **HTML5** (Estrutura)
* **Tailwind CSS** (Estilização via CDN)

O site foi construído intencionalmente em um único arquivo HTML (`labiot_unicamp.html`) para simplicidade, facilidade de manutenção e deploy rápido.

## Como Executar Localmente

Como este é um projeto HTML estático, não há necessidade de instalação de dependências ou de um servidor complexo.

1.  Clone este repositório:
    ```bash
    git clone [https://github.com/lgrando1/labiotsite.git](https://github.com/lgrando1/labiotsite.git)
    ```
2.  Navegue até o diretório do projeto:
    ```bash
    cd labiotsite
    ```
3.  Para o deploy na Vercel funcionar corretamente, o arquivo principal deve ser chamado `index.html`. Se você ainda não o fez, renomeie o arquivo:
    ```bash
    # No Windows (prompt)
    ren labiot_unicamp.html index.html
    
    # No macOS/Linux
    mv labiot_unicamp.html index.html
    ```
4.  Abra o arquivo `index.html` em seu navegador de preferência.

## Contribuições

Contribuições são bem-vindas! Se você encontrar algum erro, informação desatualizada ou tiver sugestões de melhoria, sinta-se à vontade para abrir uma *Issue* ou enviar um *Pull Request* neste repositório.

## Deploy

O site está configurado para deploy contínuo na [Vercel](https://vercel.com/) a partir da branch `main`, servindo o arquivo `index.html` como raiz.
