# PhD

Doctoral dissertation repository of "Optimizing Performance and Energy Efficiency in Massively Parallel Systems".

The purpose of this repository is to serve as a hub for everything related to the thesis once it has been printed and bound.
The most recent information about this doctorate, the document, its errata, and the most important clarifications can be found here.

## Contents

- [Disclaimer](#disclaimer)
- [Defense](#defense)
- [Short Abstract](#short-abstract)
  - [Specialized keywords](#specialized-keywords)
- [Short Abstract in Spanish (Resumen Corto)](#short-abstract-in-spanish-resumen-corto)
  - [Palabras clave especializadas](#palabras-clave-especializadas)
- [Citing](#citing)

## Disclaimer

The PhD dissertation was authorized and deposited in the Registration Office of the University of Cantabria in November 2021, but the PhD was publicly defended before an international tribunal in January 2022, officially finishing the Doctoral Programme in Science and Technology and publishing the doctoral thesis world-wide.

This PDF document is the latest version of the thesis, but it is not exactly the official version, since it has had some slight modifications in style, for example in the cover page, the coloring of some source codes, some icons have been improved and a redesign of the style and presentation of chapter 4 has been made. That is, they are practically the same, but the author prefers this github version than the official one published in the university repositories.

The official publication is located in the University Repository (UCREA) at: [https://repositorio.unican.es/xmlui/](https://repositorio.unican.es/xmlui/) [to be published]

## Defense

The author, Raúl Nozal has been awarded for his PhD, his 5 years of work, the achieved publications and contributions, the presentation and public defense with an **excellent grade** (*Sobresaliente*).

Each member of the tribunal votes secretly and anonymously if the author receives the Cum Laude award, being necessary that all three members grant it. The result of the vote will be notified within 3 months.

## Short Abstract

**Optimizing Performance and Energy Efficiency in Massively Parallel Systems**

Heterogeneous systems are becoming increasingly relevant, due to their performance and energy efficiency capabilities, being present in all types of computing platforms, from embedded devices and servers to HPC nodes in large data centers. Their complexity implies that they are usually used under the task paradigm and the host-device programming model. This strongly penalizes accelerator utilization and system energy consumption, as well as making it difficult to adapt applications. 

Co-execution allows all devices to simultaneously compute the same problem, cooperating to consume less time and energy. However, programmers must handle all device management, workload distribution and code portability between systems, significantly complicating their programming. 

This thesis offers contributions to improve performance and energy efficiency in these massively parallel systems. The proposals address the following generally conflicting objectives: usability and programmability are improved, while ensuring enhanced system abstraction and extensibility, and at the same time performance, scalability and energy efficiency are increased. To achieve this, two runtime systems with completely different approaches are proposed. 

EngineCL, focused on OpenCL and with a high-level API, provides an extensible modular system and favors maximum compatibility between all types of devices. Its versatility allows it to be adapted to environments for which it was not originally designed, including applications with time-constrained executions or molecular dynamics HPC simulators, such as the one used in an international research center.

Considering industrial trends and emphasizing professional applicability, CoexecutorRuntime provides a flexible C++/SYCL-based system that provides co-execution support for oneAPI technology. This runtime brings programmers closer to the problem domain, enabling the exploitation of dynamic adaptive strategies that improve efficiency in all types of applications.

### Specialized Keywords

- Heterogeneous Computing
- Co-execution
- HPC
- Parallel Programming
- Performance Portability
- Accelerators
- Runtime Systems
- Load Balancing
- Usability
- Scheduling
- Maintainability
- C++
- OpenCL
- Intel oneAPI
- SYCL
- API Design
- Software Architecture
- Software Engineering
- Programming Languages

## Short Abstract in Spanish (Resumen Corto)

**Optimización del Rendimiento y la Eficiencia Energética en Sistemas Masivamente Paralelos**

Los sistemas heterogéneos son cada vez más relevantes, debido a sus capacidades de rendimiento y eficiencia energética, estando presentes en todo tipo de plataformas de cómputo, desde dispositivos embebidos y servidores, hasta nodos HPC de grandes centros de datos. Su complejidad hace que sean habitualmente usados bajo el paradigma de tareas y el modelo de programación host-device. Esto penaliza fuertemente el aprovechamiento de los aceleradores y el consumo energético del sistema, además de dificultar la adaptación de las aplicaciones. 

La co-ejecución permite que todos los dispositivos cooperen para computar el mismo problema, consumiendo menos tiempo y energía. No obstante, los programadores deben encargarse de toda la gestión de los dispositivos, la distribución de la carga y la portabilidad del código entre sistemas, complicando notablemente su programación. 

Esta tesis ofrece contribuciones para mejorar el rendimiento y la eficiencia energética en estos sistemas masivamente paralelos. Se realizan propuestas que abordan objetivos generalmente contrapuestos: se mejora la usabilidad y la programabilidad, a la vez que se garantiza una mayor abstracción y extensibilidad del sistema, y al mismo tiempo se aumenta el rendimiento, la escalabilidad y la eficiencia energética. Para ello, se proponen dos motores de ejecución con enfoques completamente distintos. 

EngineCL, centrado en OpenCL y con una API de alto nivel, favorece la máxima compatibilidad entre todo tipo de dispositivos y proporciona un sistema modular extensible. Su versatilidad permite adaptarlo a entornos para los que no fue concebido, como aplicaciones con ejecuciones restringidas por tiempo o simuladores HPC de dinámica molecular, como el utilizado en un centro de investigación internacional. 

Considerando las tendencias industriales y enfatizando la aplicabilidad profesional, CoexecutorRuntime proporciona un sistema flexible centrado en C++/SYCL que dota de soporte a la co-ejecución a la tecnología oneAPI. Este runtime acerca a los programadores al dominio del problema, posibilitando la explotación de estrategias dinámicas adaptativas que mejoran la eficiencia en todo tipo de aplicaciones.

### Palabras clave especializadas

- Computación heterogénea
- Co-ejecución
- HPC
- Programación paralela
- Portabilidad del rendimiento
- Aceleradores
- Runtime systems
- Balanceo de carga
- Usabilidad
- Planificación
- Mantenibilidad
- OpenCL
- Intel oneAPI
- SYCL
- C++
- Diseño API
- Arquitectura de Software
- Ingeniería de Software
- Lenguajes de programación

## Citing

Please, in case you cite this thesis, you may consider the PhD Thesis-specific bibtex format, an appropriate style for this publication and perfectly valid as long as it is supported by your bibtex processor:

```
@PhDThesis{nozal2022optimizing,
  title = {{Optimizing Performance and Energy Efficiency in Massively Parallel Systems}},
  author = {Ra{\'u}l Nozal},
  school = {{Universidad de Cantabria}},
  year = {2022}
}
```

Otherwise, you may use the Google Scholar bibtex format:

```
@Article{nozal2022optimizing,
  title = {{Optimizing Performance and Energy Efficiency in Massively Parallel Systems}},
  author = {Ra{\'u}l Nozal},
  journal = {Repositorio abierto de la Universidad de Cantabria},
  year = {2022}
}
```
