# GrantCalc

## Sobre o Projeto
O **GrantCalc** é um sistema acadêmico para cálculo de bolsas estudantis. Permite cadastrar matrícula e valor base, aplicar auxílios (moradia, transporte, creche/alimentação) e penalidades (multa da biblioteca), exibindo um extrato detalhado com o valor final.

---

## Tecnologias
- Java + Spring Boot  
- Thymeleaf  
- Bootstrap 5  
- Padrão de Projeto **Decorator**

---

## Requisitos Funcionais
- **RF01**: Inserir matrícula e valor base da bolsa.  
- **RF02**: Selecionar auxílios extras (moradia, transporte, creche/alimentação).  
- **RF03**: Aplicar penalidades (ex.: multa da biblioteca).  
- **RF04**: Exibir extrato dinâmico com acréscimos/deduções e valor final.  

## Requisitos Não Funcionais
- **RNF01**: Extensibilidade garantida pelo uso do padrão Decorator (novos auxílios podem ser adicionados sem alterar o núcleo).  
- **RNF02**: Interface responsiva e clara, construída com Bootstrap.  
- **RNF03**: Validação de entradas em tempo real para integridade dos cálculos.  
- **RNF04**: Aderência aos princípios SOLID e Clean Code.  

---

