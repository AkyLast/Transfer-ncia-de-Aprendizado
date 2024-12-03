# Transfer Learning com TensorFlow/Keras

Este projeto demonstra como usar **Transfer Learning** para resolver problemas de classificação de imagens usando modelos pré-treinados, como o **MobileNetV2**, em conjunto com o framework **TensorFlow/Keras**.

---

## Bibliotecas Utilizadas

- **TensorFlow/Keras**: Framework para construção e treinamento de modelos de Deep Learning.
- **Matplotlib**: Para visualização de métricas como loss e accuracy ao longo do treinamento.
- **scikit-learn**: Auxilia na separação dos dados em conjuntos de treino e validação.
- **OpenCV**: Usado para verificar a integridade das imagens no dataset.
- **Google Colab**: Ambiente de execução ideal para projetos de aprendizado profundo com suporte a GPU.

---

## Por que Transfer Learning é Importante?

O **Transfer Learning** reaproveita o conhecimento de modelos pré-treinados em datasets grandes (como o ImageNet) para resolver problemas específicos com datasets menores. Isso é importante porque:

1. **Economiza Tempo e Recursos**: Modelos pré-treinados já aprenderam características úteis, como bordas e texturas, economizando esforço de treinamento.
2. **Performance Melhorada**: Oferece resultados superiores mesmo com um volume reduzido de dados.
3. **Facilidade de Uso**: Reduz a complexidade, tornando Deep Learning mais acessível.

---

## Aplicação Prática

Este projeto classifica imagens de gatos e cachorros usando Transfer Learning com o **MobileNetV2**, adaptando o modelo às necessidades do dataset. O código é modular e pode ser usado para outros problemas de classificação de imagens com ajustes mínimos.

---

Projeto para estudo e finalização de tarefa do bootcamp da dio.
