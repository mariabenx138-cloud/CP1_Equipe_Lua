# CP1_Equipe_Lua

# Sistema de Controle Logístico Lunar (SCLL) 

Solução de apoio ao Centro de Controle para validar a viabilidade (combustível, bateria e risco) de missões logísticas lunares.

## Dados & Indicadores
* **Bases:** `veiculos_logisticos`, `cargas`, `janelas_operacao`, `telemetria_pouso` e `locais_pouso_apollo`.
* **Telemetria:** Classificação em *NORMAL / ALERTA / CRÍTICO* (via temperatura e vibração).
* **Risco da Missão:** Classificação final em *NORMAL / ALERTA / CRÍTICA / MISSÃO CONDENADA*.

## Módulos do Sistema

* **`programa_01_monitoramento.py`**: Monitora o estado geral da base lunar (frota, cargas pendentes, janelas e telemetria).
* **`programa_02_simulador.py`**: Simulador interativo. O usuário escolhe o veículo, carga e local para testar a viabilidade e receber a recomendação da missão.
