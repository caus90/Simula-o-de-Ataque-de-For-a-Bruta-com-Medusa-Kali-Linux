Este repositório contém a implementação prática de ataques de força bruta utilizando **Kali Linux + Medusa** em um ambiente controlado com máquinas vulneráveis (*Metasploitable 2 / DVWA*).  
O objetivo foi compreender mecanismos de autenticação, explorar credenciais fracas e aplicar medidas de mitigação.

---

## 📌 Estrutura do Ambiente

| Máquina | Sistema | Função | IP |
|--------|---------|--------|----|
| Kali Linux | Kali Rolling |
| Metasploitable 2 | Ubuntu Vulnerável | Alvo FTP/SMB | 192.168.65.101 |
| DVWA | Web App vulnerável 

> Rede configurada como **Host-Only** no VirtualBox.

## 🧪 Testes Realizados

### 1️⃣ Brute Force FTP com Medusa
