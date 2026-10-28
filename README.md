# PROJECT DESKTOP

Desktop virtual experimental feito com HTML, CSS e JavaScript, sem dependências ou etapa de build.

## Recursos atuais

- Área de trabalho responsiva com barra de tarefas e relógio.
- Janelas arrastáveis, minimizáveis, maximizáveis e redimensionáveis.
- Bloco de notas com salvamento local.
- Calculadora com operações básicas.
- Terminal simulado com comandos `help`, `date`, `clear`, `about` e `apps`.
- Configurações de cor e relógio salvas no navegador.

## Rodar localmente

Abra `index.html` em um navegador.

## Publicar no Cloudflare Pages

1. Entre no Cloudflare Dashboard e abra **Workers & Pages**.
2. Conecte o projeto Pages ao repositório `middes0/projectdesktop`.
3. Selecione a branch `main`.
4. Deixe **Build command** vazio.
5. Defina **Build output directory** como `/`.
6. Salve e aguarde a publicação automática após os commits.

Os aplicativos ainda são funções web de demonstração. O explorador não acessa automaticamente os arquivos privados do celular, e o terminal não executa comandos reais do sistema.