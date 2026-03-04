
<img width="1737" height="592" alt="Gemini_Generated_Image_2nxu092nxu092nxu" src="https://github.com/user-attachments/assets/f7854ca6-2dae-4123-900a-e2f408980c78" />




Sabor da Casa IA: Pipeline Marmitex com IA


Este projeto faz parte do desafio de código da DIO (Digital Innovation One). 
O objetivo é criar um pipeline de dados (Extract, Transform, Load) que utiliza Inteligência Artificial para gerar mensagens de marketing personalizadas para clientes de um restaurante.

 🚀 O Projeto
O sistema lê uma base de dados de clientes, processa seus gostos alimentares e 
utiliza o GPT-4 da OpenAI para criar ofertas exclusivas e 
recomendações personalizadas.

🛠️ Tecnologias Utilizadas
Python: Linguagem principal.
Pandas: Para manipulação e análise de dados.
OpenAI API: Para geração de conteúdo via IA (GPT-4).
Excel/CSV: Como fonte de dados inicial e final.

🔄 Fluxo do Pipeline (ETL)
1. Extração (Extract)
Leitura do arquivo `clientes_sabor_de_casa_ai.xlsx`. 
A base contém informações como nome, cidade, perfil alimentar e prato favorito de 10 clientes.

 2. Transformação (Transform)
Nesta etapa, o código percorre a lista de clientes e envia os dados para a IA.
Prompt Engineering: Criado para garantir que a IA responda no formato ideal para o negócio.
Tratamento de Dados: O código foi preparado para lidar com possíveis erros de conexão ou falta de créditos na API, garantindo a resiliência do pipeline.

3. Carregamento (Load)
Os dados transformados são salvos em um novo arquivo chamado `resultado_final_sabor_de_casa.xlsx`, pronto para ser utilizado pelo time de marketing.

 📊 Como Executar
1. Clone este repositório.
2. Certifique-se de ter o Python e o Pandas instalados.
3. Adicione sua `OPENAI_API_KEY` no script.
4. Execute o código no Google Colab ou VS Code.

 👤 Autora
Sabrina Fontes 

> *Nota: O projeto demonstra a integração prática de IA em fluxos de dados reais, focando em escalabilidade e personalização.
