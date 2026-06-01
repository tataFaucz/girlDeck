# 🌸 GirlDeck — Cyberdeck feito com um Samsung Galaxy A32

> *"I'm just a girl building a cyberdeck."* 💖💻

---

## 📖 Sobre o Projeto

O **GirlDeck** é um projeto pessoal de construção de um cyberdeck utilizando um **Samsung Galaxy A32** como núcleo principal do sistema.

Inspirado na cultura cyberpunk, no movimento maker e na estética *girly tech*, o projeto busca transformar um celular Android antigo em um computador portátil personalizado capaz de executar um ambiente Linux completo.

Mais do que um dispositivo, o GirlDeck é uma jornada de aprendizado envolvendo:

* Hardware;
* Linux;
* Programação;
* Cultura Maker;
* Produção de conteúdo;
* Desenvolvimento pessoal e profissional.

---

## 💻 O que é um Cyberdeck?

Cyberdecks são computadores portáteis personalizados inspirados em ficção científica, cultura hacker e estética cyberpunk.

Normalmente são construídos reaproveitando hardware antigo e adicionando:

* periféricos;
* modificações físicas;
* sistemas Linux;
* customizações visuais;
* componentes eletrônicos.

A proposta é transformar um dispositivo comum em algo único, funcional e cheio de personalidade.

O GirlDeck segue exatamente essa filosofia, utilizando um smartphone Android antigo como base principal.

---

## ✨ Conceito

O projeto mistura elementos de:

* Cyberpunk;
* Linux;
* Cultura Hacker;
* DIY (Do It Yourself);
* Tecnologia;
* Y2K;
* Soft Tech;
* Feminilidade;
* Cultura Maker.

A ideia é criar um cyberdeck funcional sem utilizar um Raspberry Pi inicialmente, aproveitando apenas o hardware já disponível.

---

# 🛠️ Hardware Utilizado

## Núcleo Principal

* Samsung Galaxy A32

## Periféricos Planejados

* Teclado Bluetooth compacto;
* Mouse Bluetooth;
* Hub USB-C OTG;
* Powerbank;
* Suporte articulado;
* Case artesanal personalizada.

---

# 🎀 Estética do Projeto

## Inspirações

* Cyberpunk;
* Y2K;
* Soft Tech;
* Magical Girl;
* Girl Hacker Aesthetic.

## Paleta de Cores

* Rosa;
* Branco;
* Lilás;
* Prata;
* Preto.

## Materiais Planejados

* EVA;
* MDF;
* Acrílico;
* Adesivos holográficos;
* Velcro;
* LEDs suaves.

---

# 🧃 O que Você Vai Precisar

Lembrando que este é apenas o setup utilizado neste projeto.

A melhor parte dos cyberdecks é que não existem regras. Você pode utilizar:

* Smartphones;
* Tablets;
* TV Box;
* Raspberry Pi;
* Mini PCs;
* Hardware reaproveitado.

### Materiais

* Android 5.0 ou superior 📱
* Aproximadamente 2 GB livres 💾
* Powerbank 🔋
* Teclado Bluetooth ⌨️
* Mouse Bluetooth 🖱️
* Hub USB 🌐
* Conexão com internet 🌎
* Criatividade 💖

---

# 🐧 Linux no Android com Termux

Para transformar o smartphone em um ambiente Linux completo será utilizado o projeto:

**Android Linux - Termux**

Recursos:

* Instalação automatizada;
* Detecção automática do dispositivo;
* Detecção de GPU;
* Compatibilidade com smartphones e tablets;
* Ambientes gráficos completos.

---

## Ambientes Desktop Disponíveis

| Ambiente   | Peso   | Recomendação          |
| ---------- | ------ | --------------------- |
| XFCE4      | Médio  | Recomendado           |
| LXQt       | Leve   | Dispositivos antigos  |
| MATE       | Médio  | Alternativa estável   |
| KDE Plasma | Pesado | Dispositivos potentes |

---

# ⚙️ Instalação

## 1. Instalar o F-Droid

Baixe e instale o F-Droid.

---

## 2. Instalar o Termux

Instale o Termux através do F-Droid.

---

## 3. Dar acesso ao armazenamento

```bash
termux-setup-storage
```

---

## 4. Habilitar opções do desenvolvedor

Ative o modo desenvolvedor no Android.

Nas Opções do Desenvolvedor:

* Desative:

  * "Desativar restrições de processos filhos"
  * ou "Disable Child Process Restrictions"

---

## 5. Atualizar pacotes

```bash
pkg update && pkg upgrade -y
```

---

## 6. Instalar Git

```bash
pkg install git -y
```

---

## 7. Clonar o projeto Linux Android

```bash
git clone https://github.com/lucasaguiar-la/linux-android.git
```

---

## 8. Executar o instalador

```bash
cd linux-android

chmod +x script-termux.sh

./script-termux.sh
```

---

## 9. Escolher ambiente desktop

Selecione:

* XFCE4 (recomendado)
* LXQt
* MATE
* KDE

Aguarde a instalação.

---

## 10. Inicializar Linux

```bash
cd

./start-linux.sh
```

---

## 11. Instalar Termux X11

Instale o Termux:X11.

Ao abrir o aplicativo, a interface gráfica do Linux estará disponível.

---

# 🔍 Detecção Automática de Hardware

O script detecta automaticamente:

* Marca do dispositivo;
* GPU;
* Drivers compatíveis;
* Configurações gráficas otimizadas.

Exemplos:

* Samsung;
* Xiaomi;
* Motorola;
* Qualcomm Adreno;
* Drivers Freedom;
* Drivers Zink.

---

# 💻 Stack de Software

## Sistema

* Android
* Linux via Termux
* Termux:X11

## Ferramentas

* Python
* Git
* Bash
* SSH
* Nano
* Vim
* Neofetch
* Htop

---

## Instalação das Ferramentas

```bash
pkg install python -y
pkg install nano -y
pkg install vim -y
pkg install openssh -y
pkg install wget -y
pkg install curl -y
pkg install neofetch -y
pkg install htop -y
```

---

# 🌸 Primeiro Teste Oficial

```python
print("GirlDeck online 🌸")
```

---

# 🧠 Objetivos de Aprendizado

## Hardware

* Montagem física;
* Alimentação elétrica;
* USB e OTG;
* Organização interna;
* Construção da case.

## Software

* Linux;
* Bash;
* Python;
* Git/GitHub;
* Redes;
* Automação.

## Conteúdo

* Produção de conteúdo tech;
* Storytelling;
* Branding pessoal;
* Documentação técnica.

---

# 📅 Roadmap

## Fase 1 — Setup Inicial

* [ ] Resetar o A32
* [ ] Instalar F-Droid
* [ ] Instalar Termux
* [ ] Configurar Linux
* [ ] Instalar ferramentas básicas

## Fase 2 — Estrutura Física

* [ ] Comprar teclado Bluetooth
* [ ] Comprar hub OTG
* [ ] Planejar case
* [ ] Construir estrutura artesanal

## Fase 3 — Customização

* [ ] Interface personalizada
* [ ] LEDs
* [ ] Adesivos
* [ ] Organização interna
* [ ] Estética cyberpunk girlie

## Fase 4 — Desenvolvimento

* [ ] Aprender Bash
* [ ] Aprender Python
* [ ] Criar scripts
* [ ] Automatizações
* [ ] Projetos de rede

---

# 📸 Conteúdo para Redes Sociais

Ideias de conteúdo:

* Timelapses;
* Linux no celular;
* Montagem da case;
* Setup tours;
* Evolução do projeto;
* Erros e acertos;
* Day in the Life Tech;
* Bastidores.

---

# 🚀 Futuras Expansões

* Raspberry Pi;
* Arduino;
* Monitor secundário;
* SDR;
* Bateria integrada;
* Servidor portátil;
* Automação física.

---

# 🌐 Referências

### Cyberdeck Café

https://cyberdeck.cafe

### Reddit Cyberdeck

https://www.reddit.com/r/cyberDeck/

### Hackaday

https://hackaday.com/blog/?s=cyberdeck

---

# 🩷 Filosofia do Projeto

O GirlDeck não busca perfeição.

O objetivo é:

* Aprender;
* Experimentar;
* Improvisar;
* Construir;
* Compartilhar;
* Evoluir publicamente.

Cada erro faz parte da jornada.

---

# 🚀 Status

```text
[ GirlDeck Boot Sequence Initialized... ]
```

🌸 Projeto em desenvolvimento.
