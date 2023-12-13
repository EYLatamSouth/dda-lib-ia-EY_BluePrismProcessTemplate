# dda-lib-ia-EY_BluePrismProcessTemplate
Criado por: lucas.rodriguesoliveira@br.com.br
Data da última atualização: 13/12/2023

## 1-   Descrição
Este template de processo aborda todas as melhores práticas no desenvolvimento de soluções RPA em SAP Build Process Automation, combinando nossa vasta experiência na implementação de automações em diversas plataformas e ciclo de delivery EY. Oferece uma visão detalhada das práticas aplicadas nas diferentes camadas envolvidas, fornecendo insights à codificação, promovendo o sucesso tanto na automatização de processos de negócio, quanto em sua sustentação.

## 2-   Funcionalidades
- Main: Orquestra os componentes do Framework EY em SAP Build Process Automation, Execução das etapas dos requisitos funcionais, Compilação dos dados manipulados para disponibilização no relatório final;
  
- Init All Settings:  Inicialização (e concentração) de todas as variáveis globais, Criação das pastas de trabalho, Validação de arquivos e diretórios necessários para a execução;
  
- Init All Applications: Inicialização e login em todas as aplicações abrangidas pela solução, Validação de conexão à servidores e bancos de dados externos;

- Get Transactional Items: Extração/compilação de dados a serem processados, População da fila de processamento;

- Send E-mail: Envio do e-mail inicial/final da automação;
  
- Close All Applications: Log off e fechamento de aplicações;
  
- Send Report: Confeccionar HTMLs de comunicação via e-mail, Transpor arquivos trabalhados do diretório de trabalho ao diretório de devolutivas dos analistas, Gerar/disponibilizar/enviar o relatório final de execução da solução via e-mail

- Global Exception Handler: Sinalização por e-mail de falhas não recuperáveis da solução, com compartilhamento do relatório de execução.

## 3-   Pré Requisitos
- N/A.

## 4-   Procedimentos de Utilização
O detalhamento dos parâmetros de entrada/saídas, pré-Condição,	pós-Condição e comportamento nos cenários de falha de cada ativo, estão expostos na documentação fornecida neste repositório.

## 5-   Melhorias Futuras
- Inserção de Status de processamento e retentativas aos itens Transacionais;

- Inclusão de janela de processamento da solução, para melhor otimizar a carga de trabalho nos recursos;
  
- Atribuição do Status de “Não executado”, aos itens pendentes de execução, ao término da janela de processamento da solução;

- Inclusão de Arquivo de Configuração em formato de Dicionário de dados.


