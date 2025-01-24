# Automacao_de_Processo
Projeto 1 – Automação de Processo – Aplicação de Mercado de Trabalho


Automação de Processo - Aplicação no Mercado de Trabalho

Este projeto contém um script Python que automatiza o processo de geração e envio de relatórios de vendas de várias lojas. O código realiza as seguintes tarefas:

Processa dados de vendas. Calcula indicadores como faturamento, diversidade de produtos, ticket médio, etc. Gera relatórios em formato Excel. Envia os relatórios por e-mail para os responsáveis de cada loja e para a diretoria.

Funcionalidades: Leitura e processamento de dados fictícios de vendas, lojas e emails. Geração de relatórios diários e anuais. Envio automático de e-mails com os relatórios em anexo.

Pré-requisitos: Antes de executar o código, você precisará instalar algumas dependências. Se você estiver usando o pip, pode instalar as bibliotecas necessárias com o seguinte comando:

pip instalar pandas openpyxl pywin32

Estrutura de Arquivos: Este projeto exige que você tenha os seguintes arquivos de dados para que o código funcione corretamente. Esses arquivos possuem dados fictícios, mas servem como exemplos para testar o script. seu_projeto/ │ ├── Bases de Dados/ │ Emails.xlsx # Dados fictícios de e-mails │ Lojas.csv # Dados fictícios das lojas │ Vendas.xlsx # Dados fictícios de vendas seu_script.py # O código principal README.md # Este arquivo

Como usar: Baixe ou clone este repositório.

Prepare os arquivos de dados.

Coloque seus arquivos de dados na pasta Bases de Dados: Emails.xlsx: Contém os e-mails dos gerentes de cada loja e da diretoria. Lojas.csv: Contém os dados das lojas, como nome e ID da loja. Vendas.xlsx: Contém os dados de vendas para cada loja, incluindo informações como produto, quantidade e valor final.

Execute o código. Após colocar os arquivos na pasta Bases de Dados, execute o script seu_script.py. O código irá gerar relatórios de vendas e enviá-los por e-mail para os responsáveis.

Verifique os resultados. O código irá salvar os relatórios gerados (em formato .xlsx) na pasta Backup Arquivos Lojas. Além disso, os e-mails serão enviados para os responsáveis das lojas e para a diretoria com os relatórios anexados.

Observações: Dados Fictícios: Os arquivos de dados utilizados (Emails.xlsx, Lojas.csv, Vendas.xlsx) são apenas exemplos e não representam dados reais. Se necessário, você pode ajustar os dados ou criar novos arquivos seguindo o formato especificado.

Como Personalizar: Caso queira usar seus próprios dados reais ou dados fictícios personalizados, basta ajustar o conteúdo dos arquivos Excel e CSV, respeitando a estrutura de colunas.

Personalização do Caminho: Os arquivos de dados devem estar na pasta Bases de Dados, que deve estar no mesmo diretório que o script seu_script.py. Caso deseje alterar o caminho para os arquivos, altere o código para refletir o novo caminho.

Contribuições: Sinta-se à vontade para contribuir com melhorias no código!

