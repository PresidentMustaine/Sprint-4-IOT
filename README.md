# Sprint-4-IOT
Luigi - RM563096, Bruno - RM562863, Arthur - RM564958, Natalia - RM563072, Vitor - RM562208
# Projeto IoT - Sprint 4: Aplicação Prática da Arquitetura IoT

**Turma:** 1 ESPY-2025  
**Projeto Challenge:** Passa a Bola  
**Tema:** Comunicação IoT via HTTP (ESP32 + Flask)

 Objetivo
Demonstrar comunicação IoT entre um dispositivo ESP32 (simulado no Wokwi) e uma plataforma backend (Flask), publicando dados de sensor via HTTP POST e exibindo-os em tempo real no console do servidor.

 Estrutura
- `/device-esp32/`: Código do ESP32 no Wokwi  
- `/platform-server/`: Servidor Flask para receber e armazenar dados  
- `/docs/`: Relatórios, prints e diagramas  

## ⚙️ Como Executar
1. Suba o **servidor Flask**:
   ```bash
   cd platform-server
   pip install -r requirements.txt
   python server.py
