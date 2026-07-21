Dashboard de Folha & Impostos — Criado por Felipe Giunti (com IA) - TG Perícia

Dashboard interativo para conferência de folha de pagamento e guias de impostos (INSS, IRRF, FGTS), com leitura automática dos documentos em PDF, calculadora de fechamento de competência e histórico mensal por empresa.

Feito para uso da equipe de Departamento Pessoal da TG Perícia, Auditoria e Contabilidade.

O que ele faz
Lê os documentos automaticamente: você sobe os PDFs e o dashboard extrai os dados sozinho (nome da empresa, CNPJ, competência, proventos, descontos, bases de INSS/FGTS, valores das guias).
Confere as guias: compara o que a folha calculou com o valor real que saiu na guia de INSS/IRRF (DARF) e na guia FGTS Digital, sinalizando quando bate ou quando há diferença a investigar.
Mostra o impacto dos encargos sociais: quanto a empresa paga de encargos (INSS patronal, RAT, Terceiros, FGTS) em relação aos proventos — pronto para apresentar ao cliente.
Detalha por colaborador: tabela pesquisável e filtrável com todos os celetistas, aprendizes, autônomos e diretoria da competência.
Gera alertas automáticos: desligamentos no mês, bases de IRRF negativas, FGTS sobre 13º salário, etc.
Guarda o histórico mensal: cada competência processada pode ser salva, e o dashboard acumula a evolução mês a mês (gráfico de INSS × FGTS ao longo do tempo).
Documentos aceitos (todos em PDF)
#	Documento	Obrigatório?
1	Extrato Mensal (folha do Domínio)	Recomendado
2	Guia INSS/IRRF (DARF)	Opcional
3	Guia FGTS Digital (GFD)	Opcional
4	Relatório de Consignados	Opcional
5	Relatório FGTS Detalhado (por tipo de valor)	Opcional
6	Guia FGTS Rescisório	Opcional — só quando houver desligamento

Nenhum documento é obrigatório para usar o dashboard, mas quanto mais você subir, mais campos são preenchidos e conferidos automaticamente. O que não for lido automaticamente pode sempre ser digitado à mão na Calculadora de Fechamento.

Como usar
Abra o link do dashboard (ou o arquivo .html salvo no computador).
Na barra lateral esquerda, suba os PDFs da competência que está fechando.
Clique em Processar Documentos.
Confira os KPIs, a calculadora de fechamento, o impacto dos encargos sociais e os alertas.
Ajuste manualmente qualquer campo, se precisar.
Clique em Salvar Competência Atual para guardar o mês no histórico.
Clique em Salvar Dashboard Atualizado (.html) — no Chrome/Edge isso abre a janela "Salvar como", permitindo escolher direto a pasta do cliente/mês no computador. O arquivo salvo já leva o histórico completo embutido.
No mês seguinte, repita o processo abrindo o arquivo salvo (não o link original), para manter o histórico acumulado daquela empresa.
Requisitos
Navegador atualizado — Chrome ou Edge recomendados (o recurso de "Salvar como" direto na pasta só funciona neles; em outros navegadores o arquivo vai para a pasta de Downloads).
Conexão com a internet é necessária, pois o dashboard carrega bibliotecas externas (Chart.js e PDF.js) via CDN.
