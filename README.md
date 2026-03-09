
# Introdução ao Ciclo de Vida de Modelos

## Versão do Python

Este projeto utiliza **Python 3.13.7**.

## Dependências

As dependências do projeto estão listadas em `requirements.txt`.

## Criando um Ambiente Virtual

Para criar um ambiente virtual, execute:

```bash
python -m venv venv
```

## Ativando o Ambiente Virtual

**Windows:**
```bash
venv\Scripts\activate
```

**macOS/Linux:**
```bash
source venv/bin/activate
```

## Desbloqueando execução do script activate
O Windows PowerShell às vezes bloqueia a execução de scripts por segurança. O script Activate.ps1 do Python venv é um script PowerShell, então ele é bloqueado pela política de execução. O erro vem da Execution Policy. Para corrigir, execute no PowerShell como administrador:

```bash
Set-ExecutionPolicy -ExecutionPolicy RemoteSigned -Scope CurrentUser
```

## Instalando as Dependências

Com o ambiente virtual ativado, instale as bibliotecas:

```bash
pip install -r requirements.txt
```
