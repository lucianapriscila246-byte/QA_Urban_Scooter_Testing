# Urban Scooter: Testes de Web e API 

## Descrição
Projeto final do bootcamp de Analista de QA da TripleTen. O Urban Scooter é um aplicativo de aluguel de scooters. Neste projeto testei a interface web (formulário de pedido) e o backend (API de entregadores).

## Objetivo do projeto
- **Web:** validar os campos do formulário "Para quem é a scooter" (Nome, Sobrenome, Endereço, Estação de metrô e Telefone), com casos de teste positivos e negativos.
- **API:** validar as funcionalidades de adicionar (`POST /api/v1/courier`) e excluir (`DELETE /api/v1/courier/:id`) entregadores.

## Metodologia
1. Estudo dos requisitos e dos layouts do aplicativo.
2. Design dos casos de teste com **classes de equivalência** (todos os casos) e **análise de valores-limite** (nos campos com limite de tamanho).
3. Execução dos testes web no Google Chrome e no Opera, resolução 1280x720.
4. Design e execução de 9 casos de teste da API: 4 de criação de entregador (sucesso, login já existente, sem login, sem senha) e 5 de exclusão (id válido, exclusão repetida, id inexistente, id vazio, sem id).
5. Registro dos bugs no Jira, com o link na planilha.

## Resultado
- **Web:** 52 casos de teste. Em ambos os navegadores (Chrome e Opera) o resultado foi o mesmo: 44 aprovados e 8 reprovados.
- **API:** 9 casos de teste executados, com resultado real e status registrados.
- 11 relatórios de bug registrados no Jira (USQA-1 a USQA-11), com passos, resultado esperado, resultado real e prioridade.

## Ferramentas utilizadas
Google Sheets, Google Chrome, Opera, Postman, Jira.

## O que aprendi
- Aplicar classes de equivalência e valores-limite para montar casos de teste positivos e negativos.
- Escrever casos de teste claros, com pré-condição, etapas, resultado esperado e resultado real.
- Testar uma API usando o corpo da requisição e conferir o código de status e a mensagem de resposta.
- Registrar bugs no Jira de forma que outra pessoa consiga reproduzi-los.

## Melhorias possíveis
- A parte do aplicativo mobile (Tarefa 2 do projeto) não foi realizada nesta entrega. Seria o próximo passo.
- Automatizar os testes de API e ampliar a cobertura dos casos de teste.

## Como acessar os arquivos
- Planilha com casos de teste e resultados: https://docs.google.com/spreadsheets/d/14h6ZARitElKQ6Luo9n49ElGEFI2WPSVdqVkooGJtWrg/edit?usp=sharing
- Os bugs estão registrados no Jira e vinculados na planilha.
---
# Urban Scooter: Web- und API-Tests (Deutsche Version)

## Beschreibung
Abschlussprojekt des QA-Bootcamps von TripleTen. Urban Scooter ist eine App zum Mieten von Scootern. In diesem Projekt habe ich die Weboberfläche (Bestellformular) und das Backend (API für Kuriere) getestet.

## Projektziel
- **Web:** Validierung der Felder des Formulars „Für wen ist der Scooter" (Vorname, Nachname, Adresse, U-Bahn-Station und Telefonnummer) mit positiven und negativen Testfällen.
- **API:** Validierung der Funktionen zum Hinzufügen (`POST /api/v1/courier`) und Löschen (`DELETE /api/v1/courier/:id`) von Kurieren.

## Vorgehensweise
1. Analyse der Anforderungen und der Layouts der App.
2. Entwurf der Testfälle mit **Äquivalenzklassen** (alle Testfälle) und **Grenzwertanalyse** (bei Feldern mit Längenbegrenzung).
3. Durchführung der Web-Tests in Google Chrome und Opera, Auflösung 1280x720.
4. Entwurf und Durchführung von 9 API-Testfällen: 4 zum Anlegen eines Kuriers (Erfolg, Login bereits vorhanden, ohne Login, ohne Passwort) und 5 zum Löschen (gültige ID, doppeltes Löschen, nicht vorhandene ID, leere ID, ohne ID).
5. Dokumentation der Bugs in Jira mit Link in der Tabelle.

## Ergebnis
- **Web:** 52 Testfälle. In beiden Browsern (Chrome und Opera) war das Ergebnis gleich: 44 bestanden und 8 nicht bestanden.
- **API:** 9 Testfälle durchgeführt, mit tatsächlichem Ergebnis und Status dokumentiert.
- 11 Bug-Reports in Jira (USQA-1 bis USQA-11), mit Schritten, erwartetem Ergebnis, tatsächlichem Ergebnis und Priorität.

## Verwendete Werkzeuge
Google Sheets, Google Chrome, Opera, Postman, Jira.

## Was ich gelernt habe
- Äquivalenzklassen und Grenzwerte anwenden, um positive und negative Testfälle zu erstellen.
- Klare Testfälle schreiben, mit Vorbedingung, Schritten, erwartetem und tatsächlichem Ergebnis.
- Eine API mit dem Request-Body testen und Statuscode sowie Antwortnachricht prüfen.
- Bugs in Jira so dokumentieren, dass andere sie nachvollziehen können.

## Mögliche Verbesserungen
- Der Teil zur mobilen App (Aufgabe 2 des Projekts) wurde in dieser Abgabe nicht durchgeführt. Das wäre der nächste Schritt.
- API-Tests automatisieren und die Testabdeckung erweitern.
## Zugriff auf die Dateien
- Tabelle mit Testfällen und Ergebnissen: https://docs.google.com/spreadsheets/d/14h6ZARitElKQ6Luo9n49ElGEFI2WPSVdqVkooGJtWrg/edit?usp=sharing
- Die Bugs sind in Jira erfasst und in der Tabelle verlinkt.
