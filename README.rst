.. -*- coding: utf-8 -*-

Introducción
============

Este es un ejemplo de la configuración avanzada usando `buildout`_ usada en el articulo 
`Buildout para instalar de todas las partes de un sitio`_, el cual explica como configurar 
una arquitectura de alta disponibilidad para sitios en `Plone`_.

Instalación
-----------

La instalación la realiza con los siguientes comandos: ::

  $ git clone https://github.com/plone-ve/buildout.plone.highavailability.git
  $ cd ./buildout.plone.highavailability
  $ python bootstrap.py
  $ ./bin/buildout -vN
  
  
.. _buildout: http://plone-spanish-docs.readthedocs.org/en/latest/buildout/replicacion_proyectos_python.html
.. _Buildout para instalar de todas las partes de un sitio: https://plone-spanish-docs.readthedocs.org/en/latest/buildout/plone_esquema_alta_disponibilidad.html
.. _Plone: http://es.wikipedia.org/wiki/Plone


.. image:: https://d2weczhvl823v0.cloudfront.net/plone-ve/buildout.plone.highavailability/trend.png
   :alt: Bitdeli badge
   :target: https://bitdeli.com/free

