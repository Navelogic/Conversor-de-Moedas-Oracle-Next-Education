# 💱 Conversor de Moedas — Oracle Next Education

![Java](https://img.shields.io/badge/Java-21-blue?logo=java)
![Spring Boot](https://img.shields.io/badge/Spring%20Boot-3.5.3-brightgreen?logo=spring)
![License](https://img.shields.io/badge/Project-Navelogic-blueviolet)
## 📌 Descrição

Este é um **Conversor de Moedas** desenvolvido como desafio do **Oracle Next Education (ONE)**.  
Trata-se de uma aplicação **Java 21** com **Spring Boot**, executada totalmente no terminal, que permite converter valores entre moedas latino-americanas usando taxas **reais** via **ExchangeRate-API** — com fallback automático para taxas locais em caso de falha.

## ⚙️ Funcionalidades

✅ Conversão entre USD, BRL, ARS, BOB, CLP, COP  
✅ Consulta de taxas em tempo real (com cache inteligente)  
✅ Backup automático de taxas offline  
✅ Interface amigável e colorida no terminal  
✅ Suporte a `.env` para configuração de chave de API  
✅ Totalmente desenvolvido com **boas práticas Java** (Java 21, Lombok, Maven)

## 🚀 Como Executar

```bash
git clone https://github.com/seu-usuario/conversor_one.git
cd conversor_one
```

## 2️⃣ Configure sua chave da API:
Crie um arquivo .env na raiz do projeto:
```env
API_KEY=sua_chave_da_exchangerate_api
```

## 3️⃣ Compile e execute com Maven:
```bash
mvn clean install
mvn spring-boot:run
```

# 💡 Exemplo de Uso
```bash
=======================================
💱 CONVERSOR DE MOEDAS 💱
=======================================
Escolha uma opção:
1) Converter moeda
2) Ver taxas de câmbio
3) Sobre o sistema
4) Sair

> Digite sua opção: 1

Digite o valor: 100
De (BRL): 
Para (ARS): 
Resultado: R$ 100,00 BRL = $ 2.800,00 ARS
```

## 🧩 Desafios Enfrentados
* ✅ Gerenciar múltiplas moedas com taxas baseadas em dólar
* ✅ Implementar cache local para reduzir chamadas à API
* ✅ Manter a aplicação funcional offline, usando taxas de fallback
* ✅ Usar lombok para reduzir boilerplate
* ✅ Integrar JANSI e JLine para interface colorida e legível no terminal
* ✅ Criar uma experiência interativa amigável, mesmo em ambiente console

## 📚 Principais Bibliotecas
| Dependência         | Descrição                                    |
| ------------------- | -------------------------------------------- |
| Spring Boot Starter | Framework principal para configuração rápida |
| Lombok              | Anotações para reduzir boilerplate           |
| Gson                | Serialização e parsing JSON                  |
| JANSI               | Cores no terminal (ANSI escape)              |
| JLine               | Leitura avançada de terminal                 |

## 📌 Observação
Para usar a versão completa da ExchangeRate-API, registre uma conta gratuita em exchangerate-api.com e adicione sua chave no .env.

# 👨‍💻 Autor
Desenvolvido por Navelogic para o programa Oracle Next Education (ONE).

📲 Me siga no TikTok para mais projetos: [navelogic](https://www.tiktok.com/@navelogic)
