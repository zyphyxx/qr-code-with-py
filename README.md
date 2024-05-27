
# QR Code Generator

![image](https://github.com/zyphyxx/qr-code-with-py/assets/127572883/4a27acb5-fc8e-4905-99f3-06d407ecbee5)


Este projeto é um gerador de QR Code simples desenvolvido em Python, utilizando bibliotecas como `tkinter` para a interface gráfica, `pyqrcode` para a geração dos QR Codes e `Pillow` para a manipulação de imagens. O aplicativo permite ao usuário inserir um nome e um link, e gera um QR Code correspondente, que é salvo em uma planilha do Excel.

## Funcionalidades

- Interface gráfica simples para entrada de dados
- Geração de QR Codes a partir de links fornecidos pelo usuário
- Exibição dos QR Codes gerados na interface
- Salvamento dos QR Codes gerados em arquivos PNG

## Requisitos

- Python 3.x
- Bibliotecas Python:
  - tkinter (incluída na biblioteca padrão do Python)
  - pyqrcode
  - pypng
  - Pillow

## Instalação

1. Clone este repositório:

   ```sh
   git@github.com:zyphyxx/qr-code-with-py.git
   cd qrcode-generator
   ```

2. Crie um ambiente virtual e ative-o:

   ```sh
   python -m venv venv
   # No Windows
   venv\Scripts\activate
   # No macOS/Linux
   source venv/bin/activate
   ```

3. Instale as dependências:

   ```sh
   pip install pyqrcode pypng Pillow
   ```

## Uso

1. Execute o script Python:

   ```sh
   python demo.py
   ```

2. Na janela do aplicativo, insira o nome do link e o URL que deseja converter em um QR Code.
3. Clique no botão "Generate QR code" para gerar e visualizar o QR Code.
4. O QR Code gerado será salvo como um arquivo PNG no diretório de trabalho atual.

## Estrutura do Projeto

```
qrcode-generator/
│
├── venv/                  # Ambiente virtual (não incluído no repositório)
├── demo.py                # Script principal do aplicativo
├── README.md              # Este arquivo
└── requirements.txt       # Lista de dependências do projeto
```
