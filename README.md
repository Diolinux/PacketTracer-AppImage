# AppImage for Cisco Packet Tracer 7.3

Fork de: https://github.com/konradmb/PacketTracer-AppImage

*🎶I'm already Tracer🎶*

### A configuration for [pkg2appimage](https://github.com/AppImage/pkg2appimage) to build Packet Tracer in AppImage form.

## Como usar?

*Tenha certeca de ter o pacote `git` instalado.

1. Clone este repositório e mude para dentro dele usando `cd`

    ```shell
    git clone https://github.com/konradmb/PacketTracer-AppImage.git
    cd PacketTracer-AppImage/
    ```
2. Download pkg2appimage tool e crie o executável
   ```shell
   wget https://github.com/AppImage/pkg2appimage/raw/master/pkg2appimage
   chmod +x pkg2appimage
   ```
3. Faça a build:

   ```shell
   ./pkg2appimage PacketTracer.yml
   ```

4. Depois do processo, o AppImage do Packet Tracer estará no diretório `out/`.


