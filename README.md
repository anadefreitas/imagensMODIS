# imagesMODIS
# Elaboração: Ana Larissa Ribeiro de Freitas

O objetivo deste código é possibilitar o download de produtos derivados de imagens MODIS para o período de tempo de interesse. As imagens são recortadas pela geometria da área de estudo e agrupadas em um único raster multibandas, quando exportado para o drive, ou podem ser obtidas separadamente via url. É importante ressaltar, que dependendo da área de interesse a exportação de rasters multibandas pode ser prejudicada. Desta forma, indica-se que nestes casos sejam utilizados intervalos de tempo menores para agrupar os mesmos.

Para realizar o download são disponibilizados dois procedimentos:
1 - para o drive
2 - gerar url para acesso

A url de acesso possui uma limitação de tamanho de arquivo menor do que o do drive. No entanto, é uma alternativa que funciona para compartilhamentos rápidos e
evitar o uso do drive em casos onde o mesmo esteja cheio. Assim, novamente, a delimitação da área e período de interesse é essencial para a criação do produto final.

########## Console com os prints ##########

![image](https://user-images.githubusercontent.com/57720882/167972149-50bd5431-230c-436e-b40d-27c5bf648c3c.png)


obs.: o link para download é disponibilizado aqui.

########## Tasks para a exportação via drive ##########

![image](https://user-images.githubusercontent.com/57720882/167972337-9336c512-5211-4222-b645-b4fab6ff86af.png)


########## Exemplo de visualização do produto recortado para a área de interesse ##########
![image](https://user-images.githubusercontent.com/57720882/167971810-0e8437b5-cc05-45fa-acad-5c8a2a05c5e5.png)


########## Propriedades do raster aberto via software SIG ##########
![image](https://user-images.githubusercontent.com/57720882/167973161-fb00b7ec-1115-4880-99ab-f8a750985270.png)


# Contato: alarisig@gmail.com
