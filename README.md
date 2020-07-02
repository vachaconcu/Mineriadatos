# Mineriadatos

Este proyecto consiste en la identifiación de sexo y género a partir de imagenes, usando la base de datos UTKFace. 

Aquí se pueden encontrar: 

*CargaDatos.ipynb*, *Limpieza_Total.ipynb*,*One Hot Encoding.ipynb*; son los códigos necesarios para realizar la correcta carga de datos (Imagenes a tensores), limpieza de datos(Eliminación de imagenes mal etiquetadas) y codificación One-Hot, respectivamente.  

*Sexo_Primera_Final.ipynb* y *Sexo_Segunda_Final.ipynb* ; son los códigos necesarios para generar la arquitectura de un modelo ResNet v2 para identificación de sexo; aquí se encuentran consignadas las explicaciones de cada parte del código en español. 

*Raza_Primera_Final.ipynb* y *Raza_Segunda_Final.ipynb*; son los códigos necesarios para generar la arquitectura de un modelo ResNet v2 para identificación de raza; no se comentan estos códigos ya que su arquitectura es muy similar a la de sexo. 

*Modelos*; aquí se cargan los pesos finales obtenidos y se usan los modelos finales para mostrar con ejemplos como funciona el proyecto

# Bibliografía usada: 

*Conjunto de datos* 

Yang Song & Zhifei Zhang (2017). UTK FACE DATASET.

*Modelos* 

[1] Montenegro A & Montenegro D. 2020. Curso Minería de Datos, Universidad Nacional de Colombia. Recuperado en junio de 2020. Disponible en https://bit.ly/2V4eXoa 

[2] Andrew Ng,Kian Katanforoosh & Younes Bensouda Mourri. Convolutional Neural Networks. Plataforma coursera.

[3] Kaiming He, Xiangyu Zhang, Shaoqing Ren, & Jian Sun. 2016. Identity Mappings in Deep Residual Networks. Microsoft Research

 
 



