# 🔓 Projeto de Quebra de Senhas com Medusa

## 📖 Sobre
Este projeto demonstra o uso da ferramenta Medusa para testes de penetração em serviços de autenticação, realizado em ambiente Kali Linux controlado para fins educacionais.

## ⚠️ Aviso Legal
- Use apenas em sistemas que você possui ou tem autorização explícita
- Este projeto é apenas para fins educacionais e de pesquisa
- O uso inadequado é de sua total responsabilidade

## 🚀 Como Usar

### 1. Configuração do Ambiente
```bash
chmod +x scripts/install_medusa.sh
./scripts/install_medusa.sh

medusa-password-cracking/
│
├── README.md
├── scripts/
│   ├── install_medusa.sh
│   ├── wordlist_generator.py
│   └── medusa_automation.sh
├── wordlists/
│   ├── common_passwords.txt
│   └── custom_wordlist.txt
├── results/
│   └── sample_results.txt
└── docs/
    └── methodology.md


### 6. Metodologia
**docs/methodology.md**
```markdown
# Metodologia de Teste

## 1. Reconhecimento
- Identificação de serviços ativos
- Enumeração de usuários
- Coleta de informações

## 2. Preparação
- Criação de wordlists
- Configuração de ferramentas
- Estabelecimento de ambiente de teste

## 3. Execução
- Ataques de força bruta
- Ataques de dicionário
- Análise de resultados

## 4. Análise
- Documentação de credenciais comprometidas
- Análise de padrões
- Recomendações de mitigação
