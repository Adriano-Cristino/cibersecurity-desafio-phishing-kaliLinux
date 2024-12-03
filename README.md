# 🎯 Phishing para captura de senhas do Google

## 📋 Descrição
Este projeto é uma demonstração educacional de como um ataque de phishing pode ser configurado usando o Kali Linux e a ferramenta SET (Social-Engineering Toolkit). O objetivo é aumentar a conscientização sobre segurança cibernética e demonstrar como ataques de phishing funcionam para que as pessoas possam se proteger melhor.

## ⚠️ Aviso Legal
**Este projeto deve ser usado apenas para fins educacionais em ambientes controlados e autorizados. O uso indevido de técnicas de phishing é ilegal e antiético.**

## 🛠️ Ferramentas Utilizadas
- Kali Linux
- setoolkit (Social Engineer Toolkit)

## 📝 Configurando o Phishing no Kali Linux

### Passo 1: Acesso Root
```bash
sudo su
```

### Passo 2: Iniciando o setoolkit
```bash
setoolkit
```

### Passo 3: Configuração do Ataque
1. Tipo de ataque:
   - Selecione: `Social-Engineering Attacks`
2. Vetor de ataque:
   - Selecione: `Web Site Attack Vectors`
3. Método de ataque:
   - Selecione: `Credential Harvester Attack Method`
4. Método de ataque:
   - Selecione: `Web Templates`
5. Obtendo o endereço da máquina:
   - Digite: `ifconfig`
6. Seleção do template:
   - Selecione: `Google`

## 📊 Resultados
- Os resultados e capturas de tela do ataque simulado podem ser encontrados no arquivo `desafio.jpg`

## 🔒 Recomendações de Segurança
Para se proteger contra ataques de phishing:
- Sempre verifique a URL do site
- Não clique em links suspeitos
- Use autenticação de dois fatores
- Mantenha seus sistemas atualizados
- Use um gerenciador de senhas confiável

## 🎓 Créditos
Desafio realizado como parte do Bootcamp Santander Cibersegurança pela [Digital Innovation One](https://www.dio.me/).

## 👨‍💻 Autor
Adriano Cristino

## 📄 Licença
Este projeto está sob a licença [MIT](https://choosealicense.com/licenses/mit/).
