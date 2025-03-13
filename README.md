# 🏬 Reconhecimento de Texto em Fachadas de Lojas com Azure AI Vision

Este projeto foi uma experiência prática utilizando o serviço **Azure AI Vision** para realizar o reconhecimento de texto (OCR) em imagens de fachadas de lojas.  

---

## 📸 **Imagens de Entrada**
Eu utilizei cinco imagens de fachadas de lojas, que estão na pasta `inputs`. Cada uma delas apresentava textos diferentes, desde nomes de lojas até promoções destacadas.

---

## 🚀 **Processo**
Para realizar o reconhecimento de texto, criei um recurso do tipo **Computer Vision** na Azure e acessei o **Vision Studio**. A interface foi bem intuitiva, e na aba **"Read"** consegui fazer o upload das imagens facilmente.  

Depois de enviar cada imagem, o serviço analisou rapidamente e exibiu o texto encontrado. Bastou clicar no botão **"Download results"** para salvar o arquivo gerado. Salvei esses resultados na pasta `output` e renomeei cada arquivo para algo como `resultado_loja1.txt`, facilitando a organização.

---

## 🏆 **Resultados**
Os textos extraídos ficaram bem precisos, mesmo com algumas variações de iluminação e ângulo.
