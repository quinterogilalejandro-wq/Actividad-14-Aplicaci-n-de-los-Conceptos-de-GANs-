# Actividad-14-Aplicaci-n-de-los-Conceptos-de-GANs-

# GAN desde Cero — Generación de Dígitos MNIST

> Implementación de una **Red Generativa Adversarial (GAN)** completamente conectada entrenada sobre el dataset MNIST, desarrollada en PyTorch .

## 📌 Descripción
Esta actividad implementa una GAN (Generative Adversarial Network) con arquitectura **totalmente densa (FC-GAN)** capaz de generar imágenes sintéticas de dígitos escritos a mano (0–9) a partir de vectores de ruido aleatorio.

El modelo sigue el esquema adversarial propuesto por Goodfellow et al. (2014):
- El **Generador** aprende a producir imágenes falsas que engañen al discriminador.
- El **Discriminador** aprende a distinguir imágenes reales de las generadas.
- Ambos se entrenan simultáneamente en un juego minimax de suma cero.
