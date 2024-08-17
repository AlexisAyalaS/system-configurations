# **Configure Terminal on Mac**

### **1. Install Warp**
Download and install Warp from the official website:  
[**Warp Terminal**](https://www.warp.dev)

### **2. Install Oh My Zsh**

Run the following command to install **Oh My Zsh**:

[**Oh My ZSH!**](https://ohmyz.sh)

```shell
sh -c "$(curl -fsSL https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"
```
### **3. Ensure Homebrew is installed**
[**Homebrew**](https://brew.sh)

### **4. Install Fira Code Font**
Use Homebrew to install the Fira Code font:

```shell
brew install font-fira-code
```

### **5. Install Powerlevel10k**
Clone the Powerlevel10k theme repository:

```shell
git clone --depth=1 https://github.com/romkatv/powerlevel10k.git ${ZSH_CUSTOM:-$HOME/.oh-my-zsh/custom}/themes/powerlevel10k
```
Set the theme in your .zshrc file:

```shell
ZSH_THEME="powerlevel10k/powerlevel10k"
```
### **6. Configure Powerlevel10k**
Run the following command to configure Powerlevel10k and enable all styles:

```shell
p10k configure
```