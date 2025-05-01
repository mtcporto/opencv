# FaceDetect AI - Detecção Facial com OpenCV.js

![FaceDetect AI](https://img.shields.io/badge/FaceDetect-AI-4e54c8?style=for-the-badge)
![OpenCV.js](https://img.shields.io/badge/OpenCV.js-4.8.0-green?style=for-the-badge)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

## Descrição

FaceDetect AI é uma aplicação web de código aberto que realiza detecção facial em tempo real diretamente no navegador, sem a necessidade de instalações ou plugins adicionais. Utilizando a biblioteca OpenCV.js, a aplicação é capaz de identificar e destacar rostos em um feed de vídeo da webcam do usuário instantaneamente.

## Tecnologias Utilizadas

- **OpenCV.js (v4.8.0)**: Versão JavaScript da biblioteca OpenCV (Open Source Computer Vision Library), que fornece algoritmos de processamento de imagem e visão computacional.
- **HTML5**: Estrutura da aplicação web, incluindo a API MediaDevices para acesso à webcam.
- **CSS3**: Estilização avançada com gradientes, animações e interface responsiva.
- **JavaScript**: Lógica da aplicação, manipulação do DOM e processamento de vídeo.
- **Haar Cascade Classifier**: Algoritmo de detecção de objetos/faces utilizado para a identificação facial.

## Recursos e Funcionalidades

- 🎥 **Detecção Facial em Tempo Real**: Identifica rostos instantaneamente através da webcam.
- 📊 **Estatísticas de Desempenho**: Exibe FPS (frames por segundo) e resolução do vídeo.
- 🖼️ **Visualização Aprimorada**: Interface moderna com destaque visual para os rostos detectados.
- 📱 **Design Responsivo**: Adapta-se a diferentes tamanhos de tela e dispositivos.
- 🛠️ **Controles Intuitivos**: Botões para iniciar e parar a detecção.
- 🔄 **Equalização de Histograma**: Melhora a detecção em diferentes condições de iluminação.
- ⚡ **Processamento Local**: Toda a detecção ocorre no navegador do cliente, sem envio de dados para servidores.

## Como Funciona

A aplicação utiliza o seguinte fluxo de processamento:

1. Carrega a biblioteca OpenCV.js a partir do CDN oficial.
2. Inicializa os recursos necessários e carrega o classificador Haar Cascade para detecção facial.
3. Captura o feed de vídeo da webcam do usuário.
4. Para cada frame do vídeo:
   - Converte a imagem para escala de cinza.
   - Aplica equalização de histograma para melhorar o contraste.
   - Detecta rostos utilizando o algoritmo Haar Cascade.
   - Desenha retângulos e elementos visuais ao redor dos rostos detectados.
5. Exibe estatísticas de desempenho e informações em tempo real.

## Requisitos

- Navegador moderno com suporte a HTML5, JavaScript e WebRTC (Chrome, Firefox, Edge, Safari).
- Webcam funcional.
- Conexão com a internet para carregar a biblioteca OpenCV.js.
- Permissão para acesso à câmera pelo navegador.

## Instalação e Uso

1. Clone o repositório:
   ```bash
   git clone https://github.com/seu-usuario/opencv.git
   cd opencv
   ```

2. Abra o arquivo index.html em um servidor web local ou hospede os arquivos em um servidor web.

3. Alternativamente, acesse a versão online em [https://seu-site.com/opencv](https://seu-site.com/opencv) (substitua pelo link real).

4. Permita o acesso à sua webcam quando solicitado pelo navegador.

5. Clique no botão "Iniciar Câmera" para começar a detecção facial.

## Privacidade e Segurança

- **Processamento Local**: Todos os dados de vídeo são processados localmente no navegador do usuário.
- **Sem Armazenamento**: Nenhuma imagem ou vídeo é armazenado ou enviado para servidores externos.
- **Sem Rastreamento**: A aplicação não utiliza cookies ou técnicas de rastreamento.

## Limitações

- A precisão da detecção facial pode variar com base nas condições de iluminação.
- O desempenho (FPS) depende da capacidade de processamento do dispositivo do usuário.
- O método Haar Cascade é menos preciso que algoritmos modernos de aprendizado profundo, mas é mais leve e adequado para processamento no navegador.

## Contribuição

Contribuições são bem-vindas! Se você deseja melhorar o FaceDetect AI, siga estes passos:

1. Faça um fork do projeto
2. Crie sua branch de recursos (`git checkout -b feature/recurso-incrivel`)
3. Faça commit das suas alterações (`git commit -m 'Adiciona recurso incrível'`)
4. Faça push para a branch (`git push origin feature/recurso-incrivel`)
5. Abra um Pull Request

## Licença

Este projeto está licenciado sob a MIT License - veja o arquivo LICENSE para detalhes.

## Agradecimentos

- Biblioteca [OpenCV](https://opencv.org/) e seus mantenedores
- Toda a comunidade de código aberto que contribui para bibliotecas de visão computacional
- Todos os desenvolvedores e colaboradores do projeto

---

Desenvolvido com ❤️ utilizando OpenCV.js & Tecnologias Web Modernas

Similar code found with 2 license types
