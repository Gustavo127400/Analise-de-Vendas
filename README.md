# **Automatização do Relatório Diário de Vendas**

## **Descrição do Projeto**

Este projeto tem como objetivo automatizar a geração e o envio diário de um relatório de vendas utilizando Python. A automatização garante que o time de vendas e a gestão recebam um relatório atualizado sem a necessidade de intervenção manual, otimizando o fluxo de trabalho e garantindo que as decisões sejam tomadas com base em dados atualizados.

## **Funcionalidades Implementadas**

1. **Conexão ao Banco de Dados:**
   - O script conecta-se automaticamente ao banco de dados SQL para extrair os dados de vendas do último dia.

2. **Processamento de Dados:**
   - Utiliza o `pandas` para processar e analisar os dados extraídos, calculando métricas como o total de vendas por produto, vendas por cliente, e produtos mais vendidos no dia.

3. **Geração do Relatório em Excel:**
   - O script gera um relatório em formato Excel (.xlsx) com múltiplas abas, cada uma contendo uma análise específica de vendas.

4. **Visualização de Dados:**
   - Cria gráficos utilizando `matplotlib` para visualizar as vendas por produto e por cliente, facilitando a interpretação dos dados.

5. **Envio de E-mail Automatizado:**
   - O relatório Excel é anexado a um e-mail que é enviado automaticamente para uma lista de destinatários pré-definida.
   - Utiliza a biblioteca `smtplib` para enviar o e-mail com o relatório anexo.

6. **Automatização Diária:**
   - Utiliza o `schedule` ou uma tarefa agendada (como cron no Linux ou Task Scheduler no Windows) para executar o script automaticamente todos os dias em um horário específico.

## **Tecnologias Utilizadas**

- **Python:** Linguagem principal para a automação e análise de dados.
- **Pandas:** Biblioteca para manipulação e análise de dados.
- **Matplotlib:** Biblioteca para criação de gráficos e visualizações.
- **OpenPyXL:** Biblioteca para gerar arquivos Excel.
- **Smtplib:** Biblioteca para envio de e-mails via SMTP.
- **Schedule (ou alternativa de sistema):** Para agendamento de tarefas diárias.

---

Este projeto é ideal para equipes que necessitam de atualizações constantes sobre as vendas e desejam otimizar processos através da automação.

---
