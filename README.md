🚀 Projeto DevOps na AWS

🌍 Aplicação em Produção

🔗 https://devrhay.duckdns.org

Aplicação publicada em ambiente real na AWS com HTTPS configurado manualmente.

⸻

🏗 Arquitetura da Solução

EC2 (Linux Ubuntu)
⬇
Docker
⬇
Docker Compose
⬇
Nginx (Reverse Proxy)
⬇
Let’s Encrypt (SSL)
⬇
Domínio público via DuckDNS

⸻

⚙️ Tecnologias Utilizadas
	•	AWS EC2
	•	Linux (Ubuntu Server)
	•	Docker
	•	Docker Compose
	•	Nginx
	•	Certbot
	•	Let’s Encrypt
	•	DuckDNS

⸻

🔐 Segurança
	•	Configuração manual de HTTPS
	•	Geração de certificado SSL via Certbot
	•	Redirecionamento automático HTTP → HTTPS
	•	Porta 443 exposta via Docker Compose
	•	Configuração de Security Group na AWS

⸻

🚀 Processo de Deploy
	1.	Provisionamento manual da instância EC2
	2.	Configuração de regras de segurança (80, 443, 22)
	3.	Containerização da aplicação
	4.	Configuração do Nginx
	5.	Geração e instalação de certificado SSL
	6.	Deploy via Docker Compose

⸻

📌 Objetivo

Projeto prático para demonstrar conhecimentos em:
	•	Infraestrutura em Cloud
	•	Containerização
	•	Segurança de aplicações
	•	Deploy em produção
