CCB (Cédula de Crédito Bancário): O sistema opera com os tipos de financiamento Price e SAC, permitindo antecipação da próxima parcela a vencer ou da última parcela, com o devido desconto proporcional de juros, controle de inadimplência/atraso e gestão de seguros associados (seguro prestamista e seguro de crédito), cálculo da CET (Custo Efetivo Total) mensal e anual. A carteira de crédito é totalmente parametrizável de acordo com as necessidades operacionais da instituição.

CDB (Certificado de Depósito Bancário): O sistema calcula a rentabilidade de ativos pré-fixados ou pós-fixados indexados a indicadores de mercado (DI, SELIC, TR e IPCA). Os indexadores são atualizados automaticamente todos os dias via integração com as APIs do Banco Central. Permite a parametrização de curvas de taxas e percentuais de remuneração escalonados por volume aplicado e prazo de carência/resgate. Em cenários de resgate parcial, o sistema atualiza dinamicamente o fator da taxa e o percentual com base nas regras do plano de aplicação.

Contabilização e Regulatórios: Além da geração automática de lançamentos contábeis operacionais, o sistema calcula e provisiona diariamente a TJEO (Taxa de Juros Efetiva da Operação) sobre o rendimento acumulado, garantindo conformidade com os normativos de contabilidade regulatória do Banco Central.

3. Capital & Contábil
Contas e Capital: Explique o controle de saldos, fluxo de caixa e a parte de cotas-partes (capital integralizado).

Motor Contábil: Explique que o sistema possui um motor que gera lançamentos contábeis automáticos (débito/crédito) para cada evento financeiro (ex: quando um empréstimo é liquidado, o sistema já contabiliza a entrada no caixa e a baixa no direito a receber).

3. Reporte Regulatório (O que conversamos antes)
Destaque quais arquivos ou lógicas você simulou/implementou. Exemplos que chamam muita atenção:

SCR (Sistema de Informações de Créditos - ex: CADOC 3040): O motor que consolida a carteira de empréstimos para enviar ao BACEN.

Informações Contábeis (ex: COSIF): O plano de contas padrão que o BACEN exige das instituições financeiras.
