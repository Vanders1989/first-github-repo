# Contábil360 — protótipo navegável

Protótipo demonstrativo de um sistema web contábil, fiscal e RH.

## Como testar

1. Abra o arquivo `index.html`.
2. Se preferir, baixe o arquivo e abra-o diretamente no navegador.
3. Use o menu lateral para navegar entre os módulos.

O protótipo funciona sem banco de dados e sem instalação. Os dados são fictícios e ficam apenas na sessão do navegador.

## Módulos

- Visão geral do escritório
- Cadastro e consulta de empresas
- Apuração demonstrativa do Simples Nacional
- Lançamentos fiscais
- Entradas e saídas
- Obrigações e prazos
- Documentos XML/PDF
- Lançamentos contábeis
- Plano de contas
- Balancete
- Conciliação bancária
- Fechamento e reabertura de competência
- Folha e RH
- Relatórios
- Configurações e permissões

## Campos de lançamentos

O protótipo demonstra os campos operacionais básicos:

- Empresa e filial
- Data e competência
- Documento e participante
- Histórico
- Tipo de operação
- CFOP/natureza
- CST/CSOSN
- NCM/código de serviço
- Retenções
- Valor
- Conta débito e conta crédito
- Centro de custo
- Forma de pagamento
- Status de conferência

## Observação

Os cálculos, fechamento, importação e transmissão são simulados. A versão de produção deverá usar API em C#/.NET, PostgreSQL, autenticação, permissões, auditoria, regras fiscais versionadas e validação contábil.

## Branch

`contabil360-prototipo`
