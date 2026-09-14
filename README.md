# Contábil360 — protótipo navegável

Protótipo demonstrativo de um sistema web contábil, fiscal e RH.

## Como testar

1. Baixe o arquivo `index.html`.
2. Abra-o diretamente no navegador.
3. Use o menu lateral para navegar entre:
   - Visão geral
   - Empresas
   - Apuração fiscal
   - Obrigações
   - Documentos
   - Folha e RH
   - Relatórios
   - Configurações

O protótipo funciona sem banco de dados e sem instalação. Os dados são fictícios e ficam apenas na sessão do navegador.

## Fluxos disponíveis

- Filtrar empresas por nome, CNPJ, regime e status.
- Abrir o perfil de uma empresa.
- Cadastrar empresa demonstrativa.
- Percorrer o assistente de apuração do Simples Nacional.
- Importar arquivos XML/PDF de forma simulada.
- Consultar obrigações e alertas.
- Cadastrar colaborador demonstrativo.
- Simular geração de relatórios.

## Próxima etapa

Substituir os dados locais por uma API em C#/.NET, PostgreSQL, autenticação, permissões, auditoria e regras fiscais versionadas.
