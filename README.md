# Bahuvachak

Bahuvachak is model based on [Parler-TTS](https://github.com/huggingface/parler-tts) a lightweight text-to-speech (TTS) model that can generate high-quality, natural sounding speech for 22 Indian languages.

To make parler-tts work for the Indic languages we use [IndicTrans2](https://github.com/ai4bharat/IndicTrans2) and [IndicTransToolkit](https://github.com/VarunGumma/IndicTransToolkit) to tokenize the prompt. 

We train it on the [IndicVoices-R]https://ai4bharat.iitm.ac.in/datasets/IndicVoices-R) which has high quality speech data for all 22 languages. 

This repository contains the inference and training code for Bahuvachak. 



