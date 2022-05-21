#### :pencil:	<u>TÓPICOS REFERENTES AO CURSO INTRODUTÓRIO DE GIT/GITHUB</u> 		

-----------



**GIT** - VCS - Sistema de Controle de Versões; repositório local; CLI (Comand Line Interface):

- permite repositórios distribuídos e seguros (trabalho em equipe);

-  trabalhar off-line;

- no commit gera a SHA1 - HASH (Algoritmo de Hash Seguro - encriptação identificador de 40 dígitos) = assinatura;

- objetos responsáveis pelo versionamento do código: BLOB, TREE e COMMIT = confiabilidade/segurança do VCS;

- Working Tree: Working Directory - Staging Area - Local Repository;

- comandos:

  - git init (gera no diretório o repositório do .git; neste repositório (Working Directory) arquivos criados e não rastreados = Untracked);
  - git add (inicia versionamento e o arquivo começa a ser (em ciclos) rastreado = Tracked: Unmodified, Modified, Staged = Staging Area); 
  - git commit (gera objetos, HASH, salva a versão do novo código; armazena o histórico do snapshot (fluxo com todos os commits); commits integram o Local Repository);
  - git status (aponta o monitoramento dos estados do arquivo: Unmodified, Modified, Staged).

  

**GITHUB** - Remote Repository; guarda os versionamentos dos códigos do GIT:

- repositório on-line, armazenamento em nuvem;
- permite melhorar o código com contribuições de outros developers;
- permite reconhecimento;
- chave SSH - conexão segura e encriptada entre duas máquinas por chaves pública e privada;
- Token de acesso pessoal - assemelha-se ao acesso por usuário e senha, sendo a senha o token;
- Formatação Markdown.

