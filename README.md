# ChessMates

## What is ChessMates?

ChessMates is a service designed to match chess players who want to play a specific opening with another player. For example, I just saw Daniel Naroditsky play the Colle system in a speedrun and want to learn it. Or maybe you're trying to crush people with the Stafford Gambit. Or, maybe you're tired of getting crushed by the Stafford gambit and want practice against it with the white pieces.

You want to do all of this, but you have no friends, because you are a chess player.

Fret not! ChessMates will match you with other lonely nerds who want to hone their skills with a particular opening, and let you quickly jump into a game with them on your favorite chess website!

## How it works

Simple! Just select the opening you want to play, and with which color, and you will placed in a queue until someone is found who wants to play that opening with the opposite color! Then, you'll be connected and begin playing games with each other. Alternatively, you can enter an exact move order to get to a desired starting position, and we will try to match you with someone who wants to play that line. There are additional options to match with players in a given ELO range.

## Openings

Our list of openings comes from https://www.chessgames.com/chessecohelp.html

# Development

Chessmates runs on neo4j, which requires libseabolt. To install it, see:
https://github.com/neo4j-drivers/seabolt

If you are on a newer mac, use this instead:
https://github.com/teomores/seabolt-M1
