# AWS_CLF-02_Training
DIO bootcamp

### Guia Rápido de Comandos do Git
[Documentação Git](https://git-scm.com/docs)
- `git init`: Inicializa um repositório Git em um diretório local.
- `git add .`: Adiciona todas as mudanças ao próximo commit.
- `git commit -m "mensagem"`: Comita as alterações adicionadas com uma mensagem descritiva.
- `git push origin <branch>`: Envia uma ramificação específica para o repositório remoto.
- `git pull origin <branch>`: Atualiza a ramificação local com as alterações do repositório remoto.
- `git clone <URL>`: Clona um repositório remoto para o seu ambiente local.
- `git remote add origin <URL>`: Adiciona um repositório remoto como "origin".
- `git restore <file>`: Desfaz as alterações feitas em um arquivo específico, restaurando-o para a última versão comitada.
- `git status`: Exibe o status atual do repositório, incluindo arquivos modificados, adicionados ou removidos.
- `git log`: Exibe o histórico de commits do repositório.
- `git --amend -m "mensagem"`: Permite alterar a mensagem do commit mais recente.
- `git reset --soft <commit>`: Mantém as alterações no diretório de trabalho após o commit especificado.
- `git reset --mixed <commit>`: Mantém as alterações no stage após o commit especificado.
- `git reset --hard <commit>`: Desfaz todas as alterações após o commit especificado, tanto no diretório de trabalho quanto no stage.
- `git branch`: Lista todas as ramificações no repositório.
- `git checkout <branch>`: Muda para o branch especificado.
- `git merge <branch>`: Mescla uma ramificação específica na ramificação atual.
- `git diff`: Exibe as diferenças entre alterações no diretório de trabalho e o índice.
- `git fetch`: Obtém os commits e atualizações de um repositório remoto.
- `git stash`: Armazena temporariamente alterações locais de forma não comitada.

### Benefícios
- Alta disponibilidade: redundância, balanceamento de carga, backup e recuperação;
- Elasticidade: manual ou automática;
- Agilidade:  interface web, linha de comando ou API;

### AWS Well-Architected Framework
- Excelência operacional;
- Segurança: confidencialidade, integridade e disponibilidade de dados, gerenciamento de identidades e acessos, e detecção e resposta a eventos de segurança;
- Confiabilidade;
- Eficiência de performance: seleção, provisionamento, monitoramento e ajuste de recursos;
- Otimização de custos: melhor retorno sobre o investimento em recursos de TI e computação, incluindo análise, medição, previsão e controle de custos;
- Sustentabilidade: consumo de energia, emissão de carbono, uso de materiais e descarte de resíduos;

Escalabilidade vs Elasticidade;
Segurança vs Confiabilidade;
Otimização de Custos vs Sustentabilidade.

### AWS CAF (Cloud Adoption Framework)
7rs:
- Retire: transicao de aplicativo sem valor comercial,
- Retain: aplicativo com necessidade de adiar sua migracao para a nuvem,
- Rehost: mover aplicativos para a nuvem sem modifica-los, ou lift and shift,
- Relocate: transferir servidores ou instancias para outra plataforma na nuvem,
- Repurchase: substituir o aplicativo por uma versao ou produto diferente,
- Replatform: mover para a nuvem e introduzir otimizações, reduzir custos ou aproveitar recursos da nuvem,
- Refactor: modificar a arquitetura do aplicativo ou aproveitar os recursos nativos para melhorar agilidade.




