# Portfólio de Estudos — ISO 27001 & GRC

Repositório com exercícios práticos desenvolvidos durante meu estudo autodidata da norma ISO/IEC 27001, com foco em GRC (Governance, Risk & Compliance) e Auditoria Interna de TI.

## Sobre este repositório

Não tenho certificação formal em ISO 27001 — este repositório documenta meu processo de aprendizado através da aplicação prática dos conceitos da norma em cenários simulados. Cada exercício segue a mesma lógica usada por profissionais de GRC no dia a dia: identificar ativos, avaliar riscos, mapear controles e definir como comprovar que esses controles funcionam.

## Estrutura do repositório

```
├── README.md
├── exercicios-risco/
│   ├── app-delivery.md
│   ├── sistema-rh.md
├── soa/
│   └── declaracao-aplicabilidade-empresa-ficticia.md
└── auditoria-simulada/
    ├── escopo-auditoria.md
    ├── relatorio-achados.md
    └── plano-acao-corretiva.md
```

## O que tem em cada pasta

### `exercicios-risco/`
Para cada sistema fictício analisado, uma tabela com 4 colunas: **Ativo | Risco | Controle (Anexo A) | Evidência**. O objetivo é praticar o raciocínio de risco antes de recorrer à lista de controles.

### `soa/`
Declaração de Aplicabilidade (SoA) preenchida para uma empresa fictícia, passando pelos 93 controles do Anexo A (versão 2022) e justificando aplicabilidade ou exclusão de cada um.

### `auditoria-simulada/`
Simulação completa de um ciclo de auditoria interna: definição de escopo, execução, achados (não-conformidades e observações fictícias), e plano de ação corretiva — seguindo a lógica da Cláusula 9.2 da norma.

## Metodologia de estudo

Baseado no princípio de aprender pela aplicação prática em vez de memorização:
1. Escolher um sistema/aplicação real ou fictício
2. Perguntar: o que estamos protegendo? O que pode dar errado? Quais controles existem? Como provamos que funcionam?
3. Documentar o raciocínio, não só a resposta final
4. Comparar com a lista oficial de controles para identificar lacunas

## Sobre mim

Em transição de carreira para GRC/Auditoria Interna de TI. Este repositório é meu caderno de estudos público em ISO 27001, feito de forma prática ao invés de memorização. Feedback é bem-vindo. https://br.linkedin.com/in/diegomathiasdafonseca

## Aviso

Todos os documentos aqui são exercícios de estudo com dados fictícios, sem relação com empresas reais. Feedback e correções são bem-vindos via issues.
