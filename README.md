# New-World-PRIMATES
A dataset containing multiple images of primates at various positions for the purpose of training computer vision algorithms.
OBS: the train file can be found at the link bellow 

Dataset para indentificação e detecção de primatas do novo mundo, aqueles endemicos da américa Latina.

o dataset está dividido em 3 pastas referentes ao teste, treino e validação
cada pasta contém duas subpastas contendo as imagens e os rótulos referentes as imagens

o padrão de anotação foi o YOLOV8

imagens estão no tamanho 640x640 pixels
e a auto-orientação foi aplicada


referente aos rótulos:
o primeiro valor é referente a classe, e os quatro seguintes referente as coordenadas da Bouding Box

cada linha no arquivo de anotação corresponde a um objeto detectado na imagem.
uma linha contém as seguintes informações, separadas por espaços:

    Class ID: O identificador da classe do objeto.
    x_center: A coordenada x do centro da caixa delimitadora, normalizada em relação à largura da imagem.
    y_center: A coordenada y do centro da caixa delimitadora, normalizada em relação à altura da imagem.
    width: A largura da caixa delimitadora, normalizada em relação à largura da imagem.
    height: A altura da caixa delimitadora, normalizada em relação à altura da imagem.

no caso do New World PRIMATES temos 6 classes. 

Disponível também em: https://drive.google.com/file/d/1Aq9q4ZAUKOHYQF1zuwCp4yGpYplZwGa3/view?usp=drive_link
OBS: O arquivo contendo as imagens para treino está no link disponível.
