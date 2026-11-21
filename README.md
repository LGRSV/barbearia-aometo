# Barbearia AOMETO

Site da barbearia do clube da AOMETO (Associação dos Oficiais Militares Estaduais do Tocantins), em Palmas.

Página única em HTML, sem dependências: abrir `index.html` no navegador.

## O que faz
- Tabela de preços com botão para marcar o serviço
- Reserva de horário: o cliente vê só os horários livres e a reserva entra na agenda na hora (Supabase)
- Painel dos funcionários (`painel.html`): login, agenda do dia, próximos 7 dias, situação de cada horário e total recebido
- Plano mensal
- Chat de dúvidas com respostas automáticas e passagem para o barbeiro

## Onde mudar os dados
A agenda fica no Supabase (tabelas `barbearia_*`, acessadas só por funções; sem login ninguém lê os dados).
Tudo do site fica no bloco `CONFIG`, no começo do `<script>` em `index.html`: WhatsApp, endereço, mapa, barbeiros,
serviços e preços (`null` mostra "consulte"), plano e horários.

## No ar
https://lgrsv.github.io/barbearia-aometo/

## Prévias
`previa-celular.png`, `previa-computador.png`, `previa-chat.png`
