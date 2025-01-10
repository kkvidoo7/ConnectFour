# ConnectFour

Run the playable but buggy game:

    $ dotnet run --project ConnectFour.Demo

Run the non-existant tests:

    $ dotnet test


# Testprotokoll

## Programmabsturz:
- Das Spiel stürzt ab, wenn in der Konsole nur „Spielzug“ eingegeben wird.
- Das Spiel stürzt ab, wenn versucht wird, einen Pin außerhalb des Spielfelds zu platzieren, horizontal wie auch vertikal.

## Spiellogik:
- Um diagonal von links nach rechts zu gewinnen, sind nur drei Pins erforderlich anstatt vier, die eigentlich notwendig sind.
