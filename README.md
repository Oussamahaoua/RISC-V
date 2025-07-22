  Projet : Processeur RISC-V Multicycle en VHDL
Ce projet propose la conception, l’implémentation et la simulation d’un processeur RISC-V multicycle écrit en VHDL. L’objectif principal est de comprendre et de mettre en œuvre les principes fondamentaux d’un processeur RISC-V : séparation du datapath et de l’unité de contrôle, exécution par machine à états finis (FSM), et gestion des accès mémoire et registres.

   Structure du projet:
-Datapath : Composants VHDL du chemin de données (PC, ALU, Register File, MUX...).

-Control : Unité de contrôle FSM générant les signaux de contrôle.

-Mémoire unifiée : Bloc mémoire contenant les instructions et données.

-Top-Level : Intégration complète datapath + contrôle.

-Testbench : Simulation sous ModelSim pour validation.

-Simulation : Visualisation des résultats et comportement attendu.

   Fonctionnalités:
-Architecture multicycle (Fetch / Decode / Execute / Memory / Write-back)

-Instructions supportées : addi, add, sw, lw, beq

-Gestion du PC avec incrémentation et branchement conditionnel

-Simulation conforme sous ModelSim / GHDL

   Résultats:
-Simulation validée avec observation des cycles d’exécution, des registres et de la mémoire.

  Améliorations futures:
-Passage en pipeline pour de meilleures performances.

-xtension du jeu d’instruction RISC-V (ISA).

-Ajout de la gestion des exceptions et interruption
