🚀 NmapPilot - Portuguese BR
============================

Ferramenta Multiplataforma de Varredura de Rede e Reconhecimento
Desenvolvida para Estudantes, Entusiastas de Cibersegurança e Ambientes de Laboratório

📌 Visão Geral
--------------

**NmapPilot** é uma ferramenta leve, multiplataforma de varredura de rede inspirada em Nmap. Simplifica o reconhecimento de rede fornecendo uma interface de terminal limpa no estilo hacker, mantendo-se poderosa o suficiente para labs educacionais de teste de penetração.

A ferramenta está disponível para:

* 🐧 Linux
* 🪟 Windows  
* 🍎 macOS

Suporta varredura de IP, varredura de sub-rede, descoberta de serviços e exportação de resultados.

🖼 Visualização da Ferramenta
-----------------------------

[Captura de Tela do NmapPilot]

✨ Características
===================

* ✔ Varredura rápida de portas TCP
* ✔ Descoberta de hosts
* ✔ Detecção de serviços
* ✔ Varredura de sub-rede (suporte CIDR)
* ✔ Exportar resultados de varredura
* ✔ Interface de terminal estilo hacker limpa
* ✔ Binários pré-compilados para Linux, Windows e macOS
* ✔ Interface de comando fácil de usar

🧠 Como Funciona
=================

NmapPilot realiza reconhecimento por:

1. Enviando tentativas de conexão TCP para portas alvo
2. Identificando portas abertas, fechadas ou filtradas
3. Tentando detecção básica de serviço
4. Exibindo resultados formatados
5. Opcionalmente salvando os resultados em um arquivo

Para varreduras avançadas (varreduras privilegiadas), permissões de administrador/root podem ser necessárias.

💻 Plataformas Suportadas e Guia de Execução
==============================================

| Sistema Operacional | Arquivo a Usar | Como Executar | Requer Admin? |
|---|---|---|---|
| 🐧 Linux | `nmapilot` | `./nmapilot` | Sim (recomendado) |
| 🪟 Windows | `nmapilot.exe` | Duplo clique ou CMD | Sim (recomendado) |
| 🍎 macOS | `nmapilot_for_MAC` | `chmod +x` depois execute | Sim (recomendado) |

🐧 Instalação e Uso no Linux
=============================

### Passo 1: Navegue até a Pasta do Projeto

```
cd NmapPilot
```

### Passo 2: Dê Permissão de Execução

```
chmod +x nmapilot
```

### Passo 3: Execute a Ferramenta

```
./nmapilot
```

### Para Varredura Completa de Portas (Recomendado)

```
sudo ./nmapilot
```

### Comandos de Exemplo

```
./nmapilot 192.168.1.10
./nmapilot 192.168.1.0/24
./nmapilot 192.168.1.10 -o resultados.txt
```

🪟 Instalação e Uso no Windows
===============================

### Passo 1:

Baixe ou localize `nmapilot.exe`

### Passo 2:

Abra o Prompt de Comando dentro da pasta do projeto.

### Passo 3:

Execute:

```
nmapilot.exe 192.168.1.10
```

Ou simplesmente clique duas vezes em `nmapilot.exe`.

### Executar como Administrador (Importante)

Clique com botão direito → **Executar como Administrador** Isso permite recursos de varredura mais profundos.

🍎 Instalação e Uso no macOS
=============================

### Passo 1:

Abra o Terminal e navegue até o diretório do projeto.

```
cd NmapPilot
```

### Passo 2:

Torne executável:

```
chmod +x nmapilot_for_MAC
```

### Passo 3:

Execute a ferramenta:

```
./nmapilot_for_MAC 192.168.1.10
```

### Para Melhores Resultados:

```
sudo ./nmapilot_for_MAC
```

📦 Estrutura do Projeto
=======================

```
NmapPilot/
│
├── img/                  # Capturas de tela e ativos
├── nmapilot              # Executável Linux
├── nmapilot.exe          # Executável Windows
├── nmapilot_for_MAC      # Executável macOS
└── .git
```

🔧 Tecnologias Utilizadas
==========================

* Python 3
* Programação com Socket
* APIs de Rede do Sistema
* PyInstaller (para compilação executável)
* Interface ASCII Customizada

⚠ Aviso Legal
===============

Esta ferramenta é destinada para:

* Fins educacionais
* Simulações em laboratório
* Testes de penetração autorizados

NÃO faça varredura em redes sem autorização adequada. O desenvolvedor não se responsabiliza pelo uso indevido desta ferramenta.

👨‍💻 Autor
===========

**Ghaith Riabi** - Estudante de Cibersegurança | Engenheiro de Rede
Apaixonado por Hacking Ético & Implementação de SOC

📝 Documentação em Português
=============================

Esta é a versão traduzida para português brasileiro da ferramenta NmapPilot.
Projeto original: https://github.com/ghaithrb/NmapPilot

📄 Licença
==========

MIT License - Você é livre para modificar e distribuir este projeto para fins educacionais.

⭐ Suporte
==========

Se você gostou deste projeto:

* Dê uma ⭐ no GitHub
* Compartilhe com sua comunidade de cibersegurança
* Contribua com melhorias

Construído com paixão pela cibersegurança 🔥
