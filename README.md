Redução de Dimensionalidade em Imagens para Redes Neurais
Este repositório contém um código em Python para realizar a redução de dimensionalidade em imagens coloridas para níveis de cinza e binarizadas (preto e branco) utilizando a biblioteca OpenCV. Além disso, o código também inclui a aplicação do algoritmo PCA (Principal Component Analysis) para reduzir a quantidade de informações das imagens.

Descrição
O código foi desenvolvido para realizar o seguinte processo:

Carregar uma imagem colorida em formato JPG ou PNG.
Converter a imagem para níveis de cinza (escala de cinza) utilizando a função cv2.cvtColor() da biblioteca OpenCV.
Binarizar a imagem resultante usando o algoritmo de limiarização (thresholding) da biblioteca OpenCV.
Aplicar o algoritmo PCA (Principal Component Analysis) para reduzir a dimensionalidade da imagem, preservando apenas as principais componentes.
Salvar as imagens resultantes em arquivos separados em formato JPG.
Como Usar
Certifique-se de ter o Python instalado em sua máquina.
Instale as bibliotecas necessárias (OpenCV e Matplotlib) executando o seguinte comando no terminal ou prompt de comando:
Copy code
pip install opencv-python matplotlib
Clone este repositório em sua máquina ou faça o download do arquivo ZIP.
Coloque a imagem que deseja processar na mesma pasta do arquivo main.py.
No código main.py, altere a variável caminho_imagem para o nome da sua imagem (por exemplo, 'minha_imagem.jpg') ou forneça o caminho absoluto da imagem (por exemplo, 'caminho/para/a/imagem/minha_imagem.jpg').
Execute o código main.py para realizar o processamento da imagem.
O código irá salvar as imagens resultantes em arquivos separados com os nomes 'imagem_cinza.jpg', 'imagem_binarizada.jpg' e 'imagem_reduzida.jpg'.
Dependências
O código utiliza as seguintes bibliotecas Python:

OpenCV: para carregar, converter e binarizar a imagem.
Matplotlib: para exibir as imagens resultantes.
Certifique-se de instalar essas bibliotecas antes de executar o código.

Observações
O valor do limiar utilizado para a binarização da imagem pode ser ajustado na variável limiar do código. Experimente diferentes valores para obter resultados mais adequados às suas necessidades.
A redução de dimensionalidade usando PCA é realizada definindo a variável num_componentes_desejados no código. Esse valor determina quantas componentes principais serão mantidas após a redução.
Contribuição
Sinta-se à vontade para contribuir com melhorias ou correções para este código. Basta enviar um pull request e ficarei feliz em avaliar suas sugestões.

Espero que este código seja útil para você. Se tiver alguma dúvida ou precisar de mais assistência, não hesite em entrar em contato.

Divirta-se processando imagens!
