# Trabajo-Final-CV

ITBA - DIPLOMATURA DEEP LEARNING - 2020/2Q

ALUMNO: Olivetti, Guillermo Alberto (Legajo 506511) - golivetti74@gmail.com


La notebook "Trabajo_Final_CNN_Style_Transfer.ipynb" es la original de referencia sin modificar.

La notebook "ITBA_DL2020-2Q_Olivetti_TP-Final-CV.ipynb" es la entrega del Trabajo Final de CV correspondiente a la diplomatura DL2020-2Q.
Esta notebook modificada incluye las respuestas a las preguntas del trabajo final junto con algunos comentarios e imágenes de referencia agregados durante el análisis del código.

En la carpeta "/content/output" están las imágenes originales del Trabajo Final (contenido y estilo) y la imagen final generada luego de 100 iteraciones (output_at_iteration_99.png).

En la carpeta "/content/Pregunta 8" están las imágenes finales generadas (resultado después de 100 iteraciones) a partir de las imágenes originales de la notebook para diferentes combinaciones de pesos de las losses.
En el nombre de archivo de cada imagen se indican los valores de los pesos de losses utilizados para generar dicha imagen. Por ejemplo, "pto8_alfa1_beta10000_TVL1e-1__xxxxxxx" significa que se usó un alfa (contenido) de 1, un beta (estilo) de 10000 y un peso para Total Variation Loss de 0.1

En la carpeta "/content/Pregunta 9" están las imágenes finales generadas (resultado después de 100 iteraciones) a partir de imágenes elegidas para algunas combinaciones de pesos de las losses.
Los archivos "Mama_Miro__output_at_iteration_99.png" y "Mama_Picasso__output_at_iteration_99.png" son las imágenes resultantes (luego de 100 iteraciones) utilizando como imagen de contenido "Mama.jpg" y como imagen de estilo "Miro_set-52.jpg" y "Pablo_Picasso_92.jpg".


## Referencias

[_[1] L. A. Gatys, A. S. Ecker, and M. Bethge. A neural algorithm of artistic style. arXiv preprint
arXiv:1508.06576, 2015._]

https://arxiv.org/abs/1508.06576
