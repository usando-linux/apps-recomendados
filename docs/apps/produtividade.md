# 🖥️ Produtividade

Aplicativos essenciais para aumentar sua produtividade no Linux.

## 📝 Editores de Texto

### Visual Studio Code

**Descrição**: Editor de código leve e poderoso da Microsoft, com excelente suporte para desenvolvimento.

**Características**:
- ✅ Interface moderna e intuitiva
- ✅ Extensões abundantes
- ✅ Suporte nativo ao Git
- ✅ Terminal integrado
- ✅ Debugging avançado

**Instalação**:

```bash
# Ubuntu/Debian
wget -qO- https://packages.microsoft.com/keys/microsoft.asc | gpg --dearmor > packages.microsoft.gpg
sudo install -o root -g root -m 644 packages.microsoft.gpg /etc/apt/trusted.gpg.d/
sudo sh -c 'echo "deb [arch=amd64,arm64,armhf signed-by=/etc/apt/trusted.gpg.d/packages.microsoft.gpg] https://packages.microsoft.com/repos/code stable main" > /etc/apt/sources.list.d/vscode.list'
sudo apt update
sudo apt install code

# Fedora
sudo rpm --import https://packages.microsoft.com/keys/microsoft.asc
sudo sh -c 'echo -e "[code]\nname=Visual Studio Code\nbaseurl=https://packages.microsoft.com/yumrepos/code\nenabled=1\ngpgcheck=1\ngpgkey=https://packages.microsoft.com/keys/microsoft.asc" > /etc/yum.repos.d/vscode.repo'
sudo dnf install code

# Arch Linux
sudo pacman -S code
```

**Configuração recomendada**:
- Instale a extensão "Material Icon Theme"
- Configure o tema escuro
- Ative o autosave

---

### LibreOffice

**Descrição**: Suite de escritório completa e gratuita, alternativa ao Microsoft Office.

**Características**:
- ✅ Compatível com formatos do Microsoft Office
- ✅ Interface familiar
- ✅ Suporte a múltiplos idiomas
- ✅ Atualizações regulares

**Instalação**:

```bash
# Ubuntu/Debian
sudo apt install libreoffice

# Fedora
sudo dnf install libreoffice

# Arch Linux
sudo pacman -S libreoffice-fresh
```

---

## 📊 Gerenciadores de Tarefas

### Todoist

**Descrição**: Aplicativo de gerenciamento de tarefas com sincronização em nuvem.

**Instalação**:

```bash
# Snap (recomendado)
sudo snap install todoist

# Flatpak
flatpak install flathub com.todoist.Todoist
```

---

## 🎨 Design e Diagramação

### GIMP

**Descrição**: Editor de imagens profissional gratuito, alternativa ao Photoshop.

**Instalação**:

```bash
# Ubuntu/Debian
sudo apt install gimp

# Fedora
sudo dnf install gimp

# Arch Linux
sudo pacman -S gimp
```

---

## 💡 Dicas de Produtividade

1. **Use atalhos de teclado**: Aprenda os atalhos dos aplicativos que você usa mais
2. **Configure autosave**: Sempre ative o autosave nos editores
3. **Use múltiplos workspaces**: Organize suas tarefas em workspaces diferentes
4. **Backup regular**: Mantenha backups dos seus arquivos importantes

---

*Precisa de ajuda com algum aplicativo? Entre em contato com a comunidade!* 