Objetivo do Projeto: (ETL para personalização de mensagens com IA Generativa).

Tecnologias Utilizadas: Python, requests, pandas, Google Gemini 2.5 Flash (destaque a mudança de API).

devido à indisponibilidade do endpoint de produção, a fase Extract (E) e a fase Load (L) foram adaptadas:

Extract: Dados extraídos de um Mock JSON local (all_users_mock.json) em vez da API.

Load: A função requests.put foi mantida para demonstrar a intenção, mas retorna False devido à falha de conexão do servidor externo.

Resultado Final: O resultado da Transformação (T) (as mensagens da IA) pode ser encontrado no arquivo relatorio_final_gemini.json.
