📘 Gerador de Ficha Catalográfica Online
🧾 Descrição do Projeto

O Gerador de Ficha Catalográfica Online é uma aplicação web completa desenvolvida em HTML, CSS e JavaScript, que automatiza a criação da ficha catalográfica para trabalhos acadêmicos, como TCCs, monografias, dissertações e teses.

O sistema guia o usuário por etapas simples e visuais — começando pelos dados pessoais, depois dados da obra, e finalizando com a geração automática da ficha.

O design é institucional e responsivo, com interface limpa, campos arredondados, botão roxo moderno e fundo em degradê azul, garantindo uma experiência agradável em qualquer dispositivo.

⚙️ Como Funciona

O sistema é dividido em três etapas principais, cada uma representada por uma página HTML.

🧍‍♂️ 1️⃣ index.html — Dados Pessoais

Nesta primeira página, o usuário insere:

Nome completo do(s) autor(es) (separados por vírgula)

Orientador (com titulação opcional)

Coorientador (opcional, também com titulação)

E-mails dos autores

Após preencher todos os campos, o usuário clica em “Próximo” para seguir à segunda etapa.
Os dados são armazenados localmente via LocalStorage para uso posterior.

📚 2️⃣ obra.html — Dados da Obra

Na segunda página, o foco é o conteúdo do trabalho:

Título da Obra

Subtítulo (opcional)

Curso

Nível Acadêmico (Graduação, Especialização, Mestrado, Doutorado)

Ano de Publicação

Cidade

Quantidade de Páginas

Ilustrações (Coloridas ou P&B)

Palavras-chave

Resumo (opcional)

Ao clicar em “Gerar Ficha Catalográfica”, todos os dados (tanto pessoais quanto da obra) são salvos no navegador e o usuário é redirecionado automaticamente para a terceira página.

🧾 3️⃣ ficha_resultado.html — Ficha Catalográfica Gerada

Nesta página, a ficha catalográfica completa é gerada automaticamente com base nos dados armazenados.
A ficha segue o formato bibliográfico tradicional, incluindo:

Autor(es)

Título e subtítulo

Cidade e ano

Número de páginas e ilustrações

Orientador e coorientador

Curso e nível

Palavras-chave numeradas em números romanos

Indicação institucional (Universidade Santo Amaro)

O usuário pode:

Copiar a ficha com um clique (função integrada com o navigator.clipboard);

Voltar ao formulário para editar ou corrigir informações.

💻 Tecnologias Utilizadas
Tecnologia	Função
HTML5	Estrutura das páginas e formulários
CSS3	Estilo moderno com degradê azul, campos arredondados e design responsivo
JavaScript (ES6)	Armazenamento de dados, navegação entre páginas e geração dinâmica da ficha
LocalStorage API	Mantém os dados do usuário entre as páginas sem necessidade de backend
🧩 Arquivos do Projeto
Arquivo	Função
index.html	Coleta os dados pessoais dos autores, orientadores e e-mails.
obra.html	Reúne os dados da obra e gera a ficha a partir dos dados coletados.
ficha_resultado.html	Exibe a ficha catalográfica pronta, com opção de cópia e retorno ao formulário.
style.css (opcional)	Arquivo de estilo centralizado para manter consistência visual entre as páginas.
🚀 Como Executar

Baixe ou clone o repositório.

Abra o arquivo index.html em qualquer navegador moderno.

Preencha as informações pessoais e avance para “Dados da Obra”.

Complete os campos e clique em “Gerar Ficha Catalográfica”.

A ficha será exibida automaticamente na página de resultado, pronta para copiar e colar em seu trabalho acadêmico.

🧠 Principais Recursos

✅ Interface moderna e responsiva
✅ Armazenamento local sem necessidade de servidor
✅ Geração automática e padronizada da ficha catalográfica
✅ Função de cópia rápida
✅ Estrutura modular em três páginas

👨‍💻 Autor

Lucca Locoselli
Desenvolvido em 2025 como parte de um projeto de automação acadêmica e bibliográfica.

Contato: [LinkedIn](https://br.linkedin.com/in/lucca-fernandes-de-lima-locoselli-03b233214)
