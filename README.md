# Kinetic binding coefficients

## Description
L'objectif de ce projet est de mettre en place un modèle mathématique qui va calculer les coefficients d'association et de dissociation d'un complexe anti-corps anti-gène.

Nous observons donc la quantité de lumière émise par le complexe formé par les deux molécules.

Le modèle mathématique est basé sur la résolution des équations différentielles caractérisant la cinétique de liaison des molécules à l'aide de méthodes numériques Python : solve_ivp et ode_int.
Des régressions linéaires et exponentielles ont également été testées pour la détermination des coefficients kon et koff.

Des installations de librairies sont potentiellement à prévoir : 

Des simulations par rapport aux comportements du complexe AC-AG en fonction des valeurs des coefficients kon et koff ont été réalisées : des courbes d'affinités sont observables. Cela est visible sur le notebook 

## Installation
Instructions pour installer le projet :
```sh
git clone https://example.com/mon-projet.git
cd mon-projet
npm install
