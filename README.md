# Case-Morada

Para a confecção desse projeto, decidi seguir pela primeira opção de implementação.
Para isso, segui as orientações para o case, disponíveis no github, utilizando a API do Google AI Studio e as bibliotecas python: Pandas, re, os, time e google.generativeai

# Configuração da Chave da API como Variável de Ambiente:

Como estou usando o Windows 11, a sequência de passos seguida foi a seguinte:

**1-** Abra o painel de controle do seu computador;<br>
**2-** Clique em Sistema, e novamente em sistema;<br>
**3-** Na janela aberta, vá até: Configurações avançadas de sistema;<br>
**4-** Clique em: Variáveis de Ambiente;<br>
**5-** Clique em Novo para criar uma nova variável;<br>
**6-** Chame-a de GEMINI_API_KEY;<br>
**7-** Cole no campo "Valor da Variável" a sua chave do Google AI Studio;

# Instruções de Execução:
**1-** Configure a chave da API como variável de ambiente, como descrito acima; <br>
**2-** Coloque os dados no mesmo diretório que o notebook "projeto"; <br>
**3-** Para instalar as bibliotecas usadas no desenvolvimento do case, abra o terminal e digite o comando: pip install -r requirements.txt; <br>
**4-** Clique em executar tudo no jupyter notebook;