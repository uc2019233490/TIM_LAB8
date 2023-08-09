
## TIM LAB8


Trabalho prático da disciplina Transmissão de Informação Multimédia da Universidade de Coimbra.

Objetivo: adquirir um conhecimento mais aprofundado sobre o protocolo de transporte em tempo real (RTP) e o protocolo de transmissãao em tempo real (RTSP). 

Baseado no código do autor do livro ”Computer Networking: A Top-Down Approach” de Jim Kurose.

Completou-se o código que implementa funcionalidades de streaming básicas usando python de modo a ver os protocolos a estudar a funcionar.


## Correr o código

Para usar o programa é ncessário correr os códigos Server e ClientLaucher de seguida.

O Server.py deve ser corrido da seguinte forma:

```bash
  python Server.py <porta>
```

No qual porta é o número da porta em que o socket RTSP fica à escuta. 

O ClientLauncher.py deve ser corrido da seguinte forma:

```bash
python ClientLauncher.py <endereco do host> <porta> <porta RTP> <nome ficheiro de video>
```

No qual endereço do host é o endereço onde está a correr o Server (usar localhost caso seja a mesma máquina), porta é a porta do Server definida, porta RTP é a porta a usar para receber o vídeo via RTP e nome ficheiro de vídeo é o nome do ficheiro que vai ser enviado via RTP (neste caso é movie.mjpeg)






## Autores

- [Matilde](https://www.github.com/uc2019233490) 
- [Catarina](https://www.github.com/YourSelft1013) 

