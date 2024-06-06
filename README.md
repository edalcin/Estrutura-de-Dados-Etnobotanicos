# Estrutura de Dados Etnobotânicos

Este repositório visa elaborar um protocolo e orientar a coleta e organização de dados etnobotânicos a partir de consultas a publicações, incluindo obras antigas, pesquisas e artigos com dados sobre usos de plantas e seus respectivos nomes vernáculos. O objetivo principal é registrar e sistematizar informações sobre o uso de plantas no Brasil, especialmente de períodos históricos importantes, abrangendo todos os tipos de usos descritos, incluindo usos medicinais, nutricionais, ritualísticos e casos de toxicidade.

## Sistematização dos dados oriundos de referências bibliográficas

Consideramos, para efeito desta proposta de padrão, que dados etnobotânicos presentes em referências bibliográficas podem ser classificados em duas instâncias: a relação nome vernacular -> nome científico e a relação nome vernacular-> característica.

```mermaid
flowchart LR
    1[referência bibliográfica] --cita--> A
    1 --cita--> C
    A[nome vernacular] <-- cita --> B[nome científico(s)]
    C[nome vernacular] -- possui --> D[característica(s)]
```