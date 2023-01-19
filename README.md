# Exercício App com Recursos Nativos

**Objetivo**: combinar diversos recursos nativos na construção de um app React Native

## Opção 1: App para registro de fotos de lugares visitados

O app deverá ter:
- Um botão para acionar a câmera para tirar uma foto do lugar
- Um botão que obtenha a localização atual do usuário (ou seja, do local onde ele está tirando a foto)
- Um campo de entrada de texto para digitar um nome/título para a foto/local

**Desafios:**
- Salvar o lugar visitado usando algum recurso de armazenamento local (async storage ou api-fake com json-server) ou remoto (firebase)
- Exibir em uma tela uma lista com as fotos/lugares

Este aplicativo deverá combinar os recursos nativos: `ImagePicker`, `MapView` e `Location`.

Qualquer outro recurso poderá ser utilizado se você achar necessário.


## Opção 2: App para simular um controle de ponto

O app deverá ter:
- Um botão para acionar a câmera para tirar um foto (selfie) do usuário
- Um botão que obtenha a localização atual do usuário (ou seja, do local onde ele está)
- Programação para obter a data/hora no momento em que o usuário estiver registrando o ponto

**Desafios:**
- Salvar o registro usando algum recurso de armazenamento local (async storage ou api-fake com json-server) ou remoto (firebase)
- Descobrir qual o nome da rua a partir da longitude e latitude (há APIs para isso, como por exemplo a: https://nominatim.openstreetmap.org/ui/reverse.html

Este aplicativo deverá combinar os recursos nativos: `ImagePicker`, `MapView` e `Location`.

Qualquer outro recurso poderá ser utilizado se você achar necessário.
