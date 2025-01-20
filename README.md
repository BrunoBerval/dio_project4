# dio_project4
Treinamento e detecção de objetos utilizando a rede YOLO  

# Criação de uma base de dados e treinamento da rede YOLO para detecção de objetos

## O Projeto

Este projeto tem como objetivo aplicar técnicas de visão computacional para a detecção de objetos em imagens urbanas, com foco específico em ciclistas, pedestres e carros. Utilizando o modelo YOLO (You Only Look Once), uma das soluções mais rápidas e precisas para detecção de objetos em tempo real, o projeto visa treinar e testar o modelo com um conjunto de dados de imagens de trânsito urbano. Embora o propósito principal seja acadêmico, este projeto exemplifica uma aplicação prática de aprendizado de máquina no mundo real, demonstrando como a tecnologia pode ser usada para analisar o tráfego urbano, com potencial para ser adaptado em contextos como monitoramento de tráfego ou sistemas de segurança por exemplo.

## A Base de dados

A base de dados city_dataset foi criada a partir de uma pesquisa detalhada e do download de imagens de trânsito urbano obtidas no Google Imagens. O objetivo foi compilar um conjunto de dados que representasse uma variedade de cenas urbanas, com foco em elementos de tráfego e transporte. Para a anotação dessas imagens, utilizei a ferramenta CVAT (Computer Vision Annotation Tool), que é amplamente reconhecida e utilizada em projetos de visão computacional para a criação de labels (rótulos) de forma precisa e eficiente.
Após concluir o processo de anotação das imagens, salvei a base de dados final no Google Drive para garantir um armazenamento seguro e acessível. A partir do Google Drive, a base de dados será disponibilizada para ser utilizada neste projeto de detecção de objetos

O CVAT facilita o processo de rotulagem manual ao permitir que o usuário desenhe caixas delimitadoras (bounding boxes) ao redor dos objetos de interesse em cada imagem. No meu caso, as classes definidas para o projeto foram ciclistas, pedestres e carros, ou seja, as caixas delimitadoras foram desenhadas para identificar e classificar essas três categorias de objetos através do link:  https://drive.google.com/drive/folders/1DXswiFetctlve3QblhDkAx6SXvSudaEj?usp=sharing

# Creation of a Database and Training the YOLO Network for Object Detection

## The Project

This project aims to apply computer vision techniques for object detection in urban images, with a specific focus on cyclists, pedestrians, and cars. Using the YOLO (You Only Look Once) model, one of the fastest and most accurate solutions for real-time object detection, the project seeks to train and test the model with a dataset of urban traffic images. Although the primary purpose is academic, this project exemplifies a practical application of machine learning in the real world, demonstrating how the technology can be used to analyze urban traffic, with potential for adaptation in contexts such as traffic monitoring or security systems, for example.

## The Dataset

The city_dataset was created from a detailed search and download of urban traffic images obtained from Google Images. The goal was to compile a dataset that represents a variety of urban scenes, with a focus on traffic and transportation elements. For annotating these images, I used the CVAT (Computer Vision Annotation Tool), which is widely recognized and used in computer vision projects for creating labels (annotations) in a precise and efficient manner. After completing the annotation process, I saved the final dataset on Google Drive to ensure secure and accessible storage. From Google Drive, the dataset will be made available for use in this object detection project.

CVAT facilitates the manual labeling process by allowing the user to draw bounding boxes around the objects of interest in each image. In my case, the classes defined for the project were cyclists, pedestrians, and cars. That is, the bounding boxes were drawn to identify and classify these three categories of objects through the following link: https://drive.google.com/drive/folders/1DXswiFetctlve3QblhDkAx6SXvSudaEj?usp=sharing 
