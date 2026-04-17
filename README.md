# Medidor de Energy Harvesting Wireless

![Status do Projeto](https://img.shields.io/badge/Status-Desenvolvimento-yellow)
![PCB](https://img.shields.io/badge/PCB-KiCad-green)

## Descrição
O Medidor de Energy Harvesting Wireless é um circuito eletrônico dedicado a realizar a coleta de dados essenciais para aplicações técnico-científicas relacionadas a Energy Harveting via TEG, PVG, RFG, HEG, WIG, PZT e TC.

<p align="center">
  <img width="710" height="546" alt="Imagem1-1" src="https://github.com/user-attachments/assets/a5c3c2cb-6468-4d7f-957b-8b18b3eaf9d1" />
</p>

---

## Descrições técnicas

- Microcontrolador: MSP430FR5949;
- Armazenamento local via micro SD card;
- Envio de dados via UART ou via BLE 5.0;
- Medições de Geradores Termoelétricos (TEG):
  - Temperatura lado Quente;
  - Temperatura lado Frio;
  - Temperatura Ambiente;
- Medições de Geradores Fotovoltaicos (PVG):
  - Medidor de Tensão DC;
  - Medidor de Iluminação;
- Medições de Geradores via Transformadores de Corrente (TCG):
  - Medidor de Tensão AC;
- Medições de Geradores Piezoelétricos (PZT):
  - Medidor de Tensão AC;
  - Medidor de aceleração triaxial;
- Medidções de Geradores Hidroelétricos (HEG):
  - Medidor de Tensão;
  - Medidor de Corrente; 
- Medições de Geradores Eólicos (WIG):
  - Medidor de Tensão;
  - Medidor de Corrente; 
- Medições de Geradores via RF (RFG):
  - Medidor de Tensão;

---

## Estrutura do repositório
Os arquivos de hardware foram desenvolvidos utilizando o KiCad 9.0.
- **`.kicad_pcb`**: Layout da placa de circuito impresso (Board).
- **`.kicad_sch`**: Esquemático eletrônico do sistema (Schematic).
- **`.kicad_pro`**: Gerenciador de projeto do KiCad (Project).

---

## Autor
**Dr. Luiz Fernando Pinto de Oliveira**

*Engenheiro Eletrônico especializado em Sistemas Embarcados e Ultra-Low Power.*
- **Website:** [FAPLO](https://faplo.webnode.page/)
- **LinkedIn:** [lfpo](https://www.linkedin.com/in/lfpo/)

---

Shield: [![CC BY-NC-ND 4.0][cc-by-nc-nd-shield]][cc-by-nc-nd]

This work is licensed under a
[Creative Commons Attribution-NonCommercial-NoDerivs 4.0 International License][cc-by-nc-nd].

[![CC BY-NC-ND 4.0][cc-by-nc-nd-image]][cc-by-nc-nd]

[cc-by-nc-nd]: http://creativecommons.org/licenses/by-nc-nd/4.0/
[cc-by-nc-nd-image]: https://licensebuttons.net/l/by-nc-nd/4.0/88x31.png
[cc-by-nc-nd-shield]: https://img.shields.io/badge/License-CC%20BY--NC--ND%204.0-lightgrey.svg
