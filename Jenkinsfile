// @yaml

pipeline:
  agent: any
  stages:
    - stage: Checkout
      steps:
        - checkout: scm
    - stage: Build
      steps:
        - bat: 'javac Main.java'
    - stage: Test
      steps:
        - bat: 'java Main'
    - stage: Deploy
      steps:
        - echo: "Déploiement sur le serveur de production en cours"
