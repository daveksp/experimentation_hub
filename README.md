# Experimentation Hub

This project was designed in a way to be deployed into ec2 instances (or any other approach), but keeping in mind the 
need to provide a structure flexible enough and capable of being easily converted to serverless architecture. 

The flexibilization aspect lead to the adoption of a factory_app approach. It helps to keep things in a modularized 
way, makes it easier to setup, test and define different environments, and it's a good way to avoid circular imports.

<p align="center"><img src="http://dkspinheiro.com/glovo/component_diagram.png" /></p>