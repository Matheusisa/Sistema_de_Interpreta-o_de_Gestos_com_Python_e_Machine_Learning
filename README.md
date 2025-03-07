# Sistema de Interpretação de Gestos com Python e Machine Learning

Este projeto utiliza a biblioteca OpenCV para capturar vídeo da webcam e detectar gestos de mão em tempo real. O sistema pode reconhecer diferentes gestos e executar comandos específicos no sistema operacional.

## Requisitos

- Python 3.x
- OpenCV
- NumPy

## Instalação

1. Clone este repositório:
    ```bash
    git clone [<URL_DO_REPOSITORIO>](https://github.com/Matheusisa/Sistema_de_Interpreta-o_de_Gestos_com_Python_e_Machine_Learning.git)
    ```
2. Navegue até o diretório do projeto:
    ```bash
    cd Sistema-de-Interpretacao-de-Gestos
    ```
3. Instale as dependências:
    ```bash
    pip install opencv-python numpy
    ```

## Uso

1. Execute o script `detector_de_gestos.py`:
    ```bash
    python detector_de_gestos.py
    ```
2. Uma janela de vídeo será aberta mostrando a captura da webcam.
3. Coloque sua mão na região de interesse (ROI) definida pelo retângulo verde.
4. O sistema reconhecerá gestos e exibirá o gesto reconhecido na tela.

## Gestos Reconhecidos

- **0**: Navegador
- **1**: Word
- **2**: Excel
- **3**: PowerPoint
- **4**: Firefox
- **5**: Spyder
- **6**: Reposicionar

## Contribuição

Sinta-se à vontade para contribuir com este projeto. Envie pull requests ou abra issues para relatar problemas ou sugerir melhorias.

## Licença

Este projeto está licenciado sob a Licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.
