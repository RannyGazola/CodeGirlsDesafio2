# AWS Step Functions
## O que é o AWS Step Functions
O AWS Step Functions é um serviço serverless que permite orquestrar serviços e aplicações na AWS por meio de workflows visuais e declarativos, podendo ser integrado a qualquer linguagem de programação. Ele facilita a criação e automação de fluxos entre microserviços, funções Lambda e outros recursos da AWS, sem a necessidade de configurar toda a infraestrutura previamente. Os workflows podem ser executados sob demanda ou de forma agendada, e aprimorados gradualmente conforme as necessidades do sistema.

## Benefícios de Utilizar o AWS Step Functions
✅ Por oferecer um modelo visual, permite controlar a execução de várias funções e serviços da AWS sem precisar escrever código;
✅ Totalmente serverless, sem a necessidade de gerenciar servidores, filas ou instâncias;
✅ Facilidade na integração com outros serviços da AWS;
✅ Possui controle de logs detalhados, facilitando o monitoramento e a manutenção;
✅ Pode ser modificado e aprimorado gradualmente, sem interromper os fluxos existentes;
✅ Suporta execuções agendadas, que podem ser configuradas em horários e dias específicos, facilitando a automação de rotinas como ETL de dados e backups.

## Como utilizar o AWS Step Functions
O AWS possui uma interface intuitiva, na lateral esquerda, é possível consultar e selecionar os serviços integrados, arrastando-os para o fluxo na tela e definindo as validações necessárias para a execução do workflow.
<img width="1873" height="846" alt="visualização lateral" src="https://github.com/user-attachments/assets/be1e7ab1-6405-4456-91b1-14554e95d314" />

Executei o seguinte fluxo de Hello World, um modelo disponível no AWS Step Functions:
<img width="975" height="758" alt="stepfunctions_graph" src="https://github.com/user-attachments/assets/e74f86d3-1023-424a-bc4d-e9620be231e2" />

É possível visualizar os detalhes de execução de cada etapa definida:
<img width="1830" height="746" alt="log" src="https://github.com/user-attachments/assets/c910270e-3b21-45d4-98c3-d7c157a5f046" />

## Conclusão
O AWS Step Functions é uma solução poderosa e escalável para orquestrar processos de forma visual e automatizada. Sua integração nativa com diversos serviços da AWS permite construir fluxos completos com baixo custo operacional. Além disso, a facilidade de monitoramento, a capacidade de evolução contínua dos workflows tornam o Step Functions uma ferramenta essencial para automação de processos, pipelines de dados e arquiteturas baseadas em microserviços que pode ser utilizado por diversas áreas de uma empresa, como a área de negócios.
