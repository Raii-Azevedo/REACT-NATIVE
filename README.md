# REACT-NATIVE
<a href="url"><img src="https://github.com/Raii-Azevedo/REACT-NATIVE/blob/master/download.png" align="center" height="150" width="350" ></a>
 
## Descrição
- Curso e capacitação com React-Native e Projetos realizados.

## Projetos
- [Cookie da Sorte](https://github.com/Raii-Azevedo/biscoito-da-sorte/tree/master)
- [Calculadora IMC](https://github.com/Raii-Azevedo/IMC)
- [Cronômetro](https://github.com/Raii-Azevedo/Cronometro)


## Templates Básicos para React Native
<a href="url"><img src="https://github.com/Raii-Azevedo/Template-basico-react-native/blob/main/WhatsApp%20Image%202021-06-18%20at%2017.27.31.jpeg" align="left" height="480" width="300" ></a>
 
 - Templates básicos para o início de uma aplicação com React Native
 
 - Basic templates for starting an application with React Native
 
## Modelos:

- Modelo 1: [Template](https://github.com/Raii-Azevedo/Template-basico-react-native/blob/main/template.js)
- Modelo 2: [Template](https://github.com/Raii-Azevedo/Template-basico-react-native/blob/main/App.js)
 
## Tecnologia
 - React Native
 - JavaScript
 
### Emular App diretamente do celular via USB
#### Configurando o celular para emular o Aplicativo Native.
    
    Para habilitar a depuração USB no seu dispositivo, primeiro você precisa habilitar o menu "Opções do desenvolvedor" acessando Configurações → Sobre o
    telefone → Informações do software e, em seguida, tocando sete vezes na linha Número da compilação na parte inferior. Você pode então voltar para
    Configurações → Opções do desenvolvedor para ativar a "depuração USB"
 
#### Configurando LINUX para o celular emular o Aplicativo Native.
   - Instale o Node.js:
        ◦ Abra um terminal.
        ◦ Execute o seguinte comando para adicionar o repositório do Node.js:
          
          1  curl -sL https://deb.nodesource.com/setup_14.x | sudo -E bash -
          
        ◦ Em seguida, instale o Node.js com o comando:
          
          1  sudo apt-get install -y nodejs
          
          2. Instale o JDK (Java Development Kit):
            ◦ Execute o seguinte comando no terminal:
          
          1  sudo apt-get install -y openjdk-8-jdk
          
         3. Instale o Android SDK:
         ◦ Abra um terminal.
         ◦ Execute o seguinte comando para instalar o pacote SDK do Android:
          
          1  sudo apt-get install -y android-sdk
          
         ◦ Defina as variáveis de ambiente necessárias executando os seguintes comandos:
          
          
          1  echo 'export ANDROID_HOME=$HOME/Android/Sdk' >> ~/.bashrc
          2  echo 'export PATH=$PATH:$ANDROID_HOME/tools' >> ~/.bashrc
          3  echo 'export PATH=$PATH:$ANDROID_HOME/platform-tools' >> ~/.bashrc
          4  source ~/.bashrc
          
          4. Instale o React Native CLI:
            ◦ Execute o seguinte comando no terminal:
          
          
          1  sudo npm install -g react-native-cli
          2  sudo npm install -g react-native
          
          5. Configure as permissões USB:
           ◦ Conecte seu dispositivo Android ao computador via USB.
           ◦ No terminal, execute o seguinte comando:
          
          1  sudo usermod -aG plugdev $LOGNAME
          
          6. Configurar udev para dispositivos USB:
           ◦ Crie um novo arquivo de regra udev:
          
          1  sudo nano /etc/udev/rules.d/51-android.rules
          
           ◦ Adicione o seguinte conteúdo ao arquivo e salve:
          
          1  SUBSYSTEM=="usb", ATTR{idVendor}=="[ID_VENDOR]", MODE="0666", GROUP="plugdev"
          
          (Substitua [ID_VENDOR] pelo ID do fabricante do seu dispositivo Android. Você pode encontrar essa informação executando o comando lsusb no terminal.)
          
           ◦ Reinicie o serviço udev:
          
          1  sudo service udev restart
          
          7. Teste a conexão USB:
           ◦ No terminal, execute o seguinte comando:
          1  adb devices
          
           ◦ Seu dispositivo Android deve ser listado como um dispositivo conectado. Se ele não estiver aparecendo, verifique se as etapas anteriores foram
           seguidas corretamente.
          
          8. Crie um novo projeto React Native:
           ◦ No terminal, navegue para o diretório onde deseja criar seu projeto:
          
           ◦ Crie um novo projeto React Native com o seguinte comando:
          
          1  npx react-native init MeuApp
          
          9. Execute o aplicativo no dispositivo Android:
           ◦ Navegue para o diretório do projeto:
          
          1  cd MeuApp
          
           ◦ Inicie o servidor de desenvolvimento React Native:
          
          1  npx react-native start

## Links
 
  - [REACT-NATIVE](https://github.com/Raii-Azevedo/REACT-NATIVE)
 
 
## Authors
 
* **RAISSA AZEVEDO**: @Raii-Azevedo (https://github.com/Raii-Azevedo)om/Raii-Azevedo)
 
 

