# Desafio_Eletronica_Tractian
Hardware challenge including block diagram design and PCB component placement for a 24V to 5V (20A) buck converter – TRACTIAN Tech Fast Track 2026.

Projeto desenvolvido para o desafio técnico do Tech Fast Track 2026 da TRACTIAN.

## Escopo

O desafio foi dividido em duas etapas:

### Task 1 — Pré-projeto (Diagrama de Blocos)
Elaboração de um sistema de aquisição multicanal com foco em:
- Definição da arquitetura do sistema
- Escolha de interfaces de comunicação
- Organização funcional dos blocos
- Considerações de robustez para ambiente industrial

### Task 2 — PCB Component Placement
Posicionamento dos componentes de um conversor DC/DC 24V → 5V (20A), priorizando:
- Minimização de loops de alta corrente
- Separação entre estágio de potência e controle
- Integridade de sinais sensíveis (feedback, compensação e sense)
- Redução de EMI e efeitos parasitas

## Principais Decisões de Projeto

- MOSFETs organizados de forma compacta para reduzir loop de comutação
- Indutor posicionado próximo ao nó SW
- Capacitores de entrada e saída agrupados para resposta a transientes
- Rede de feedback e compensação posicionadas próximas ao controlador
- Gate drive otimizado com trilhas curtas (R1 / R8)
- Bootstrap e redes auxiliares mantidas próximas ao U1

## Ferramentas
- KiCad 9.0.6

## Observações
O layout foi desenvolvido considerando restrições de área da placa e a necessidade de balancear proximidade elétrica, separação funcional e legibilidade.
