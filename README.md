# Como realizar o Download no Linux?

**1. Verifique se o Flatpak está instalado**

Abra o terminal e execute:

  - flatpak --version

Se aparecer uma versão, ele já está instalado.

**2. Instale o PCSX2**
   
Execute:

  - flatpak install flathub net.pcsx2.PCSX2

Confirme a instalação quando solicitado.

**3. Abra o PCSX2**
   
Depois de instalar, execute:

  - flatpak run net.pcsx2.PCSX2

Ou procure por PCSX2 no menu de aplicativos do Linux.

**4. Configure o emulador**
   
Na primeira inicialização, você precisará:

1. Escolher o idioma.
2. Configurar a BIOS do PlayStation 2.
3. Configurar seu controle ou teclado.
4. Selecionar a pasta onde estão seus jogos.


Atenção: você precisará de uma BIOS extraída do seu próprio PS2.



## Se o Flatpak não aparecer, provavelmente ele não está instalado no seu Linux. Você pode instalá-lo pelo terminal.

Primeiro, execute:

  - flatpak --version

Se aparecer command not found, instale conforme sua distribuição:

**Ubuntu / Debian / Linux Mint**

  - sudo apt update
    sudo apt install flatpak

**Fedora**

  - sudo dnf install flatpak

**Arch Linux / Manjaro**

  - sudo pacman -S flatpak

## Depois de instalar

Adicione o repositório Flathub:

  - flatpak remote-add --if-not-exists flathub https://flathub.org/repo/flathub.flatpakrepo

## Agora instale o PCSX2 e execute
