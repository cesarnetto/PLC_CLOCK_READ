# Leitura do Relógio com SFC1 em S7-300/400

## Funcionalidades Principais

- Módulo de Data/Hora
  - Leitura do Relógio Interno:
  - Acesso em tempo real ao relógio do CLP
  - Conversão para formatos legíveis (data completa, dia da semana, hora)

- Blocos de Conversão:
  -  DT_DATE: Converte formato DT para data (DD/MM/AAAA)
  -  DT_DAY: Extrai o dia da semana
  -  DT_TOD: Converte para horário (HH:MM:SS)

## Pré-requisitos
- CLP Siemens SIMATIC S7-300 (CPU 319-3 PN/DP)
- Software STEP 7 (versão 5.6)

## Estrutura do Código

/OB1 - Programa principal
/FC1 - DT_DATE (Conversão para data)
/FC2 - DT_DAY (Dia da semana)  
/FC3 - DT_TOD (Horário)
/DB1 - Armazenamento de valores temporais
/VAT1 - Tabela de monitoramento
