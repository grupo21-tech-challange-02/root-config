O root-config é o projeto principal que orquestra os micro frontends da nossa aplicação. O site em produção pode ser acessado em: https://d1vqzf4765g06r.cloudfront.net/

### Passo a passo para executar localmente:

Instalar dependências:
- ```npm install```

Dentro do repositório root-config:
- ```npm run start --port 9000```

No navegador:
- ```http://localhost:9000/```

E deverá ser exibido a tela inicial:

<img width="1094" height="655" alt="Captura de Tela 2026-01-19 às 22 32 24" src="https://github.com/user-attachments/assets/d1946a6d-a3d9-45d9-8926-6f2c4b3880fe" />

### Instruções deploy

- Fazer o push de alguma alteração na branch main, diretamente ou via pull request;
- O workflow de deploy deve ser iniciado na aba actions;
- O workflow instala dependências, gera um novo arquivo .dist e faz upload no servidor;
- Após alguns segundos do término, o cache é invalidado e as alterações estão disponíveis;
