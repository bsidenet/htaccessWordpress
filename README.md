.htaccess Seguro e Otimizado
Este ficheiro .htaccess foi criado para melhorar a segurança e o desempenho de um website, prevenindo ataques comuns, bloqueando tentativas de exploração e protegendo ficheiros sensíveis.

🔒 Funcionalidades de Segurança
Proteção do próprio ficheiro .htaccess: Evita o acesso direto a este ficheiro crítico.
Proteção do wp-config.php (se aplicável a WordPress): Impede o acesso a um dos ficheiros mais sensíveis do sistema.
Bloqueio da execução de scripts PHP em uploads (WordPress): Evita a execução de ficheiros maliciosos na pasta de uploads.
Prevenção contra injeção de código malicioso: Bloqueia caracteres perigosos e padrões comuns em ataques SQL Injection e XSS.
Bloqueio de redirecionamentos maliciosos: Impede que o site redirecione os utilizadores para domínios não autorizados.
Desativação da listagem de diretórios: Protege ficheiros sensíveis ao impedir a navegação direta entre diretórios.
Impedir Hotlinking: Evita que outros sites utilizem imagens hospedadas no servidor, economizando largura de banda.
Cabeçalhos de segurança HTTP: Adiciona proteções contra ataques XSS, Clickjacking e deteção incorreta de tipos MIME.
📂 Estrutura
Este ficheiro .htaccess pode ser colocado na raiz do servidor para proteger todo o website ou em diretórios específicos para aplicar regras restritivas em áreas sensíveis.

🛠 Como Utilizar
Faz o download do ficheiro ou copia o conteúdo para um novo ficheiro .htaccess no teu servidor.
Edita conforme necessário, ajustando regras específicas ao teu domínio e configuração.
Guarda e testa para garantir que tudo funciona corretamente sem interferir no funcionamento normal do site.
⚠️ Nota: Antes de aplicar as regras, testa o ficheiro num ambiente de desenvolvimento para evitar bloqueios indesejados.

📝 Licença
Este ficheiro é disponibilizado sob a licença MIT – podes utilizá-lo e modificá-lo livremente. 🚀
