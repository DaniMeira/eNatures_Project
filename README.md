# eNatures_Project
 In this repository you will find parts of my eNatures project, a greenhouse with autonomous control based on data collected by sensors with real-time data monitoring and control.

Portuguese(PT-BR)

Versões Comentadas

v1.0 - iniciei com visualização simples via cabo serial imprimindo os dados a cada segundo e registrando sempre os ultimos 12 totalizando a ultima hora completa permitindo ao usuário o acompanhamento detalhados das informações e identificar possíveis alterações ou falhas com precisão e dados concretos.

v1.1 - implantado a visualização web para visualização remota usando o mesmo wifi

v1.2 - feito ajustes devido aos travamentos e falhas no código: otimizado as strings, uso de wifi.reconect e delay(1) para suavizar quedas e travas comuns, reconexão automática com (wifi.satus() != WL_CONNECTED) Wifi.reconncect(); tá na loop() monitorando sempre, ajustes dos nomes e guardando histórico com 24 registros com indiceHistorico cíclico, 1 por hora, atualizando os dados a cada segundo via handleClient(), visualização mais amigável sem delays excessivos
