# Download de imagens MODIS no Google Earth Engine e pré-processamento no RStudio
### Elaboração: Ana Larissa Ribeiro de Freitas

O objetivo deste código é possibilitar o download de produtos derivados de imagens MODIS para o período e área de interesse. As imagens são recortadas pela geometria da área de estudo e agrupadas em um único variável para possibilitar o download via drive ou url. 

É importante ressaltar, que dependendo da área de interesse a exportação de rasters pode ser prejudicada. Desta forma, indica-se que nestes casos sejam utilizados intervalos de tempo e/ou áreas menores para agrupar os mesmos. A url de acesso possui uma limitação de tamanho de arquivo menor do que o do drive. No entanto, é uma alternativa que funciona para compartilhamentos rápidos e evitar o uso do drive em casos onde o mesmo esteja cheio.

########## Console com os prints ##########

![image](https://user-images.githubusercontent.com/57720882/167972149-50bd5431-230c-436e-b40d-27c5bf648c3c.png)


obs.: o link para download é disponibilizado aqui.

########## Tasks para a exportação via drive ##########

![image](https://user-images.githubusercontent.com/57720882/167972337-9336c512-5211-4222-b645-b4fab6ff86af.png)


########## Exemplo de visualização do produto recortado para a área de interesse ##########
![image](https://user-images.githubusercontent.com/57720882/167971810-0e8437b5-cc05-45fa-acad-5c8a2a05c5e5.png)


#### Pré-processamento no RStudio #####
Aqui, o dado é pré-processado para obtermos os valores em ºC, e separarmos as bandas criadas no GEE, preservando a nomenclatura da imagem original. O código funciona com loops, de forma que possam ser tratadas todas as imagens produzidas no GEE. Na imagem, observa-se os arquivos "2020__1" e "2020__2", seguidas pela sequência de imagens extraídas das mesmas.

![image](https://user-images.githubusercontent.com/57720882/173126267-60382665-9d5a-49a4-95a9-5d94c690723e.png)

obs.: uma etapa de renomeação dos arquivos pode ser aplicada, a fim de conservar apenas as informações de data dos arquivos.

###### Propriedades do raster gerado no GEE via software SIG ##########
![image](https://user-images.githubusercontent.com/57720882/167973161-fb00b7ec-1115-4880-99ab-f8a750985270.png)

###### Propriedades do raster pós-processado via software SIG ##########
![image](https://user-images.githubusercontent.com/57720882/173127053-aef21eaa-49fd-40f1-b91e-22da018c3e77.png)

obs.: o arquivo agora possuim uma banda, passou para um tipo de dado que permite casas decimais, e recebe um novo nome.

### Contato: alarisig@gmail.com
