<img width="1096" height="932" alt="Captura de tela 2025-10-17 033536" src="https://github.com/user-attachments/assets/4a346305-c001-4521-9faf-540042ca5d28" />
🐍 Medusa – Ferramenta de Teste de Força Bruta

Medusa é uma ferramenta de login brute-force amplamente utilizada em auditorias de segurança e pentests. Seu principal objetivo é testar a robustez de autenticações em diferentes protocolos e serviços, como HTTP, FTP, SSH, MySQL, SMB e outros.

⚙️ Principais características

Alta performance: permite execução em múltiplas threads, testando diversos logins simultaneamente.

Suporte a diversos serviços: compatível com protocolos como ftp, ssh, telnet, smb, http, rlogin, mysql, vnc, entre outros.

Customização: aceita listas de usuários (-U) e senhas (-P), possibilitando ataques direcionados.

Modularidade: cada protocolo é tratado como um módulo independente, facilitando atualizações e extensões.

🧠 Exemplo de uso
medusa -h 192.168.56.102 -u admin -P passwords.txt -M http


Esse comando tenta autenticar o usuário admin no host alvo (192.168.56.102) usando o módulo HTTP e a lista de senhas passwords.txt.
