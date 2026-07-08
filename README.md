# Redes-Generativas-Adversariales (GANs)

Implementación de una **Red Generativa Adversarial (GAN)**, arquitectura de aprendizaje no supervisado propuesta por Ian Goodfellow y su equipo en 2014, aplicada en este caso a la generación de imágenes.

## ¿Cómo funciona una GAN?

- **Generador** — crea datos sintéticos a partir de ruido aleatorio; mejora progresivamente su capacidad de generar datos realistas.
- **Discriminador** — evalúa si un dato es real o generado, y se vuelve más preciso a medida que se entrena.
- **Entrenamiento adversarial** — generador y discriminador se entrenan compitiendo entre sí hasta alcanzar un equilibrio donde el generador produce datos difíciles de distinguir de los reales.

## Contenido

- `RedesGenerativas.ipynb` — notebook con la definición, entrenamiento y evaluación de la GAN.
- `training_checkpoints/` — checkpoints guardados durante el entrenamiento.
- Imágenes `.png` generadas durante las distintas épocas de entrenamiento.

## Tecnologías

Python · TensorFlow / Keras · Redes Generativas Adversariales (GANs) · Jupyter Notebook

## Cómo ejecutar

```bash
pip install tensorflow numpy matplotlib jupyter
jupyter notebook RedesGenerativas.ipynb
```

## Autor

Horacio Laphitz — [GitHub](https://github.com/HoracioLaphitz) · [LinkedIn](https://www.linkedin.com/in/horacio-laphitz)
