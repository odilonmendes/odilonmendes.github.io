---
layout: archive
title: "Ensino & Atuação Acadêmica"
permalink: /teaching/
author_profile: true
---

{% include base_path %}

### Filosofia e Atividades Didáticas

A integração entre rigor teórico e aplicação experimental prática orienta as atividades acadêmicas desenvolvidas junto aos cursos de graduação e pós-graduação em Engenharia na **Universidade Federal do Ceará (UFC)** e no **Instituto Federal do Ceará (IFCE)**.

A formação multidisciplinar — abrangendo Engenharia Mecatrônica, Engenharia de Telecomunicações, Engenharia Elétrica e Engenharia Aeronáutica (ITA) — permite proporcionar aos estudantes uma visão holística de problemas complexos de engenharia.

---

### Disciplinas e Tópicos de Interesse

* **Sistemas de Controle Clássico e Moderno:** Modelagem matemática no domínio do tempo e frequência, lugar das raízes, resposta em frequência, espaço de estados e controle robusto.
* **Visão Computacional & Processamento Digital de Imagens:** Filtragem, morfologia matemática, segmentação e aprendizagem de máquina para imagens médicas e industriais.
* **Automação & Robótica:** Cinemática direta e inversa de robôs manipuladores, acionamentos eletromecânicos e sistemas em tempo real.
* **Otimização Metaheurística:** Algoritmos bioinspirados (PSO, Algoritmos Genéticos) aplicados a problemas de engenharia.

---

### Cursos e Atividades Registradas

{% for post in site.teaching reversed %}
  {% include archive-single.html %}
{% endfor %}
