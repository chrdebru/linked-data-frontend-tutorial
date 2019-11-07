# Serving Linked Data: A Step-by-Step Tutorial
Christophe Debruyne  
ADAPT, Trinity College Dublin  
WISE, Vrije Universiteit Brussel

## Introduction
The goal of this document is to provide you with step-by-step instructions for serving your data and ontology as Linked Data. This document by no means claims to provide the way for publishing those resources as such but may provide a basis.

This tutorial comes with two files; a file containing a cat ontology ([ontology.ttl](/files/ontology.ttl)) and a file containing instances ([data.ttl](/files/data.ttl)). You will notice that the domain of the ontology is ontology.example.org and the domain of the resources is data.example.org. This is a way of separating data and ontologies, but not the way. We will set up a Linked Data frontend that resembles http://dbpedia.org/. We will set up our local machine to listen to those domains step by step.

We will first set up the Linked Data frontend for the data. Then we will set up the frontend for the ontology. We finally make the necessary changes to serve both at the same time using one machine.

## License
This work is licensed under a [Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License](https://creativecommons.org/licenses/by-nc-sa/4.0/).
