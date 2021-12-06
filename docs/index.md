# Posgrado en Ciencia e Ingeniería de la Computación 

###  Semestre: 2022-1

![alt text](https://github.com/ulises1229/DL_cuDNN_2022-1/raw/36b4a4732d1e8d4a813881c4f9dfde41e6ee11c4/figs/bg.png)


## Profesores
 Dr. Ulises Olivares Pinto
 
 Dr. David Oswaldo Pérez Martínez

## Objetivo del curso
Presentar al estudiante la librería cuDNN para la aceleración de operaciones elementales en arquitecturas de aprendizaje profundo en distintos tópicos de las ciencias de la computación. 


## Prerequisitos
#### Deseables
+ Dominio de los lenguajes de programación C y C++ 
+ Conicimiento básico de estructuras de datos y algoritmos
* Fundamentos de programación en GPUs

#### Hardware
Se deberá contar con una computadora con un GPU NVIDIA o en su defecto solicitar acceso a un servidor remoto


#### Software
Se deberá contar con el siguiente software instalado 

  + [CUDA Toolkit](https://developer.nvidia.com/cuda-toolkit)
  + Entonrno de desarrollo integrado(IDE)
    - [Eclipse](https://developer.nvidia.com/nsight-eclipse-edition)
    - [Clion](https://www.jetbrains.com/es-es/clion/)
  + [cuDNN](https://developer.nvidia.com/cudnn)
    

#### Cuentas
Se deberán crear cuentas en las siguientes plataformas:
  + Crear una cuenta en GitHub
  + Google Classroom
  
## Contenido del curso

<table>
<thead>
<tr>
<th style="text-align:center">No.</th>
<th style="text-align:left">Tema</th>
<th style="text-align:left">Conceptos</th>
<th style="text-align:center">Código</th>
<th style="text-align:left">Material complementario</th>
</tr>
</thead>
<tbody>
<tr>
<td style="text-align:center">1.</td>
<td style="text-align:left">Introducción a cuDNN</td>
<td style="text-align:left">Introducción a cuDNN, modelo de programación paralelo, arquitectura</td>
<td style="text-align:center"><ul> <li><a href="https://docs.nvidia.com/deeplearning/cudnn/developer-guide/index.html">cuDNN Developer Guide</a></li></ul></td>
<td style="text-align:left"><a href="https://arxiv.org/abs/1410.0759">Artículo seminal</a></td>
</tr>
<tr>
<td style="text-align:center">2.</td>
<td style="text-align:left">API C++ y modelo de programación</td>
<td style="text-align:left">Modelo de programación paralelo</td>
<td style="text-align:center"><ul> <li><a href="/code/cuda_samples_v11.4/Samples">CUDA Samples</a></li><li><a href="/code/cudnn_samples_v8">cuDNN Samples</a></li> <li><a href="code/simple_convolution/conv.cu">Convolución simple</a></li></ul></td>
<td style="text-align:left"><ul> <li> <a href="https://docs.nvidia.com/deeplearning/cudnn/index.html">Getting Started</a></li> <li><a href="https://docs.nvidia.com/deeplearning/cudnn/install-guide/index.html">Guía de instalación</a> </li> </ul></td>
</tr>
<tr>
<td style="text-align:center">3.</td>
<td style="text-align:left">Convoluciones con cuDNN</td>
<td style="text-align:left">convoluciones, representación de memoria</td>
<td style="text-align:center"><ul> <li><a href="code/simple_conv_cudnn_v8/conv.cu">Convolución simple cudnn V8</a></li> <li><a href="code/simple_conv_cudnn_v8/CMakeLists.txt">CmakeLists (Clion - cmake)</a></li> <li><a href="code/cudnn_samples_v8/mnistCUDNN">mnist</a></li> </ul></td>
<td style="text-align:left"><ul> <li><a href="https://docs.nvidia.com/deeplearning/cudnn/api/index.html">cuDNN API Reference</a> <li> <a href="https://docs.nvidia.com/deeplearning/cudnn/developer-guide/index.html">Developer Guide</a></li></ul></td>
</tr>
<tr>
<td style="text-align:center">4.</td>
<td style="text-align:left">Redes Neuronales Recurrentes</td>
<td style="text-align:left">Series, dependencias de corto y largo plazo</td>
<td style="text-align:center"><ul> <li><a href="code/cudnn_samples_v8/RNN/RNN_example.cu">RNN cuDNN</a> </ul></td>
<td style="text-align:left"><ul> <li> </li></ul></td>
</tr>
<tr>
<td style="text-align:center">5.</td>
<td style="text-align:left">cuDNN Frontend API</td>
<td style="text-align:left">Engines, Nknobs, Operation graphs,</td>
<td style="text-align:center"><ul> <li><a href="https://github.com/NVIDIA/cudnn-frontend">CUDNN Frontend API</a> </ul></td>
<td style="text-align:left"><ul> <li> </li></ul></td>




