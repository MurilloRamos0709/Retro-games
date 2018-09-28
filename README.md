 **Retropie**
 Instalacao do retropie no linux mint 19
 
**1Passo:** No terminal atualize o pacote APT usando o seguinte comando.
 sudo apt-get update && sudo apt-get upgrade (esse comando vai procurar por atualizacoes do sistema e em seguida ja fazer as atualizacoes do que foi encontrado).
 
**2Passo** Instale os pacotes nescessários com o comando.
 sudo apt-get install -y git dialog unzip xmlstarlet //( ainda no terminal).
 
**3Passo** Clone o projeto oficial do retropie
 git clone --depth=1 https://github.com/retropie/retropie-setup.git
 
**4Passo** Agora entre no setup do diretório do retropie com este comando.
 cd RetroPie-Setup
 
**5Passo** Execute o setup de instalacao do retropie com este comando.
 sudo ./retropie_setup.sh

**6Passo** vai aparecer algumas opcoes, selecione **basic install.** ( pelo teclado será feita as selecoes nas opcoes), (basic install = instalacao basica)

**7Passo** Após ter feito a instalacao do retropie, o aplicativo aparecerá no menu de aplicacoes

**8Passo** Feito tudo corretamente, agora, voce  só precisa copiar seus arquivos rom para os diretórios Rom associados corretamente. Se voce seguiu os passos acima, o diretório principal para todas as roms será ˜/retropie/roms ( ou home/ pi/retropie/roms, que é o mesmo aqui). Neste mesmo diretório existe um subdiretório para cada sistema emulado e suportado, por exemplo: NES, SNES, Sega megadrive, etc.

**OBS: Deve ser dada para as extensoes dos arquivos rom. Alguns emuladores usam .zip, enquanto outros usam uma extensao personalizada associada ao emulador em questao. Como por exemplo, o emulador Atari 2600 .a26, .bin e .rom.**
