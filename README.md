# 🔐 bradesco-auth-strategy-showcase

> Showcase técnico da implementação do Strategy Pattern para autenticação em APIs

![Java](https://img.shields.io/badge/Java-17+-blue)
![Spring Boot](https://img.shields.io/badge/SpringBoot-Framework-brightgreen)
![REST API](https://img.shields.io/badge/API-REST-orange)
![Design Pattern](https://img.shields.io/badge/Pattern-Strategy-purple)
![Tests](https://img.shields.io/badge/Tests-Automated-success)
![Status](https://img.shields.io/badge/Status-Production--Ready-blue)

---

## 📌 Visão Geral

Este projeto demonstra a aplicação do **Strategy Pattern** para resolver problemas comuns de autenticação em múltiplos serviços.

A solução centraliza diferentes estratégias de autenticação em uma arquitetura limpa, escalável e desacoplada, permitindo maior controle, flexibilidade e qualidade nos testes.

---

##  Arquitetura da Solução

---

##  Objetivo

Demonstrar como centralizar e organizar múltiplas estratégias de autenticação em APIs, utilizando boas práticas de engenharia de software.

A proposta é:

- Criar uma arquitetura desacoplada  
- Permitir fácil extensão para novos tipos de autenticação  
- Melhorar a organização dos testes automatizados  
- Aumentar a confiabilidade e manutenção do código  

---

##  Problema

Em cenários reais, a autenticação costuma gerar diversos desafios:

- Lógica duplicada e espalhada  
- Baixa flexibilidade para novos fluxos  
- Steps de testes repetidos e conflitantes  
- Configurações inconsistentes (SSL, base URI, headers)  

Esses pontos tornam o sistema difícil de escalar e manter.

---

## 💡 Solução

A solução implementa o **Strategy Pattern**, onde cada tipo de autenticação é encapsulado como uma estratégia independente.

### ✔️ Benefícios da abordagem:

- Isolamento de cada tipo de autenticação  
- Seleção dinâmica de estratégias  
- Código extensível (Open/Closed Principle)  
- Redução de acoplamento  

###  Possibilidades avançadas:

- Simulação de tokens inválidos ou expirados  
- Testes com múltiplas permissões  
- Cenários avançados com variações de comportamento  
- Integração com IA generativa para testes dinâmicos  

---

## 📈 Resultados

A implementação trouxe ganhos claros:

- ✅ Centralização das autenticações  
- ✅ Facilidade de manutenção  
- ✅ Alta reusabilidade nos testes  
- ✅ Melhor organização dos fluxos  
- ✅ Suporte a testes avançados (incluindo segurança)  
- ✅ Aderência aos princípios **SRP** e **Open/Closed**  
- ✅ Alinhamento com boas práticas de qualidade  

---

##  Estrutura do Projeto


---

##  Tecnologias Utilizadas

- Java 17+
- Spring Boot  
- REST APIs  
- JUnit  
- Maven  

---

## 🚀 Como Executar

```bash
# Clonar repositório
git clone https://github.com/seu-user/bradesco-auth-strategy-showcase.git

# Entrar no projeto
cd bradesco-auth-strategy-showcase

# Rodar testes
mvn clean test
```

##  Aplicacoes Praticas

Testes automatizados de API
Validação de autenticação em múltiplos serviços
Simulação de cenários complexos
Estrutura base para frameworks de automação

---

##  Conceitos Aplicados

Strategy Pattern
Clean Architecture
SOLID (SRP, Open/Closed)
Test Automation Design
Engenharia de Qualidade

---

##  Próximos Passos


---

## Autor

Projeto desenvolvido como showcase técnico de arquitetura e qualidade de software, com foco em automação de testes e engenharia de qualidade por Rose Dias.


