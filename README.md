# Configuração para MKS Robin Nano V3.1
## O que foi feito até o momento
- Motor X funcionando com o Drive A4988
- Desativado a verificação de temperatura
- Habilitado o M42 para enviar sinal diretamente a um pino especifico
- Verificado que o Pino do Hotend 0 é o P69
- Verificado que o motor RS 550 só sai da Inércia em S40

## O que não esta funcionando
- Aquecedor da cama não funciona ( pode ter queimado)

## Comandos Úteis
- M115 traza versão do Firmware
- M42 I1 P69 S50 - Liga o Motor do Hotend 0 em S50 (S255 é o máximo)


https://github.com/makerbase-mks/MKS-WIFI
https://github.com/vincios/Mks-Wifi?tab=readme-ov-file
https://esp3d.io/ESP3D/Version_3.X/documentation/commands/