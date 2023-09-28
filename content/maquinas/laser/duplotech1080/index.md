# Duplotech 1080

![alt text][img_1080]

## Especificações

- ^^Área útil:^^
    - 1000mm(x) 800mm(y)

- ^^Potência:^^
    - 100W

- ^^Materiais:^^
    - Corte:
        - Acrílico (até 6mm)
        - MDF (até 3mm)
        - Plásticos (que não tenham Cloro na composição)
        - Couro
    - Gravação:
        - Alumínio anodizado
        - Acrílico
        - MDF
        - Madeiras

[img_1080]:https://www.insper.edu.br/wp-content/uploads/2018/12/impressora-3d.png "Duplotech Laser 1080"

## Software

O software usado para configurar os arquivos para a laser e o [RDWorks 8.1][1]

## Arquivo de teste

![Arquivo de teste de gravação editavel](../files/TesteGravacao.svg)
![Arquivo de teste de gravação em DXF](../files/TesteGravacao.dxf)
![Arquivo de teste de gravação pronto para laser](../files/testGrav.rd)

## Parametros

- ^^Acrílico 3mm(CORTE):^^

    - **Speed**: 15 mm/s
    - **Power**: 70 - 75 %

 - ^^Acrílico 6mm(CORTE):^^

     - **Speed**: 8 mm/s
     - **Power**: 90 - 95 %

 - ^^MDF 3mm(CORTE):^^

     - **Speed**: 15 mm/s
     - **Power**: 70 - 75 %

 - ^^Compensado 10mm(CORTE):^^

     - **Speed**: 8 mm/s
     - **Power**: 90 - 95 %

## Gerar arquivos de corte

**Arquivo DXF**:

- Importar arquivos DXF para o [RDWorks][1].
- Setar parametros de velocídade e potencia para cada cor.
- Clicar em **"Salvar U file"** para exportar para o pendrive

[1]: https://www.duplotech.com.br/download.php?file=downloads/rdcam-8148.rar
