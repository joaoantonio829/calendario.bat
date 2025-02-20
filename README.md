# calendario.bat
![](https://us.123rf.com/450wm/bobrovee/bobrovee1707/bobrovee170700011/83099227-cone-realista-brilhante-do-calend%C3%A1rio-do-m%C3%AAs-com-datas-isolado-vector.jpg)

# Comandos ELSE, IF, ::, %TEXTO%, SET

Este documento explica os comandos `ELSE`, `IF`, `::`, `%TEXTO%` e `SET` utilizados em diversos contextos de programação e scripts.

## Explicação dos Comandos

- `IF`: Utilizado para executar um bloco de código caso uma condição seja verdadeira.
- `ELSE`: Define um bloco alternativo a ser executado caso a condição do `IF` seja falsa.
- `::`: Usado para adicionar comentários em scripts batch.
- `%TEXTO%`: Representa uma variável cujo valor pode ser substituído dinamicamente.
- `SET`: Define ou altera o valor de uma variável em um script.

## Exemplo de Uso - Calendário Simples

```
@echo off
:: Solicita ao usuário que digite um número correspondente ao mês
set /p mes=Digite o número do mês (1-12):

if %mes%==1 (
    echo Janeiro - Começo do ano!
) else if %mes%==12 (
    echo Dezembro - Fim do ano!
) else (
    echo Mês comum do ano.
)
pause
```




