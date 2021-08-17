# BlazorWasmApp
Projeto de treinamento

# Primeiros passos para instalação do projeto G-SYS

Primeiramente devemos criar o ambiente de desenvimento instalando as seguintes aplicações:

- https://dotnet.microsoft.com/download
- https://code.visualstudio.com/download
- https://www.microsoft.com/pt-br/p/windows-terminal/9n0dx20hk701?activetab=pivot:overviewtab
- https://visualstudio.microsoft.com/pt-br/

Instalando CHOCOLATEY ( Windows Terminal como Administador)

```
Set-ExecutionPolicy Bypass -Scope Process -Force; [System.Net.ServicePointManager]::SecurityProtocol = [System.Net.ServicePointManager]::SecurityProtocol -bor 3072; iex ((New-Object System.Net.WebClient).DownloadString('https://chocolatey.org/install.ps1'))
```

Inicie o prompt de comando e execute: (Com Windows Terminal como Administador)

```
choco --version
choco install gh
choco install git
choco install dotnet
cd c:\
mkdir c:\Projetos
cd c:\Projetos
git clone https://github.com/alexkads/BlazorWasmApp.git
cd c:\Projetos\BlazorWasmApp
code .
```
