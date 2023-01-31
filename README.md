# Librarian Trade Finder
A fabric mod that helps you find the enchantments you need from a Librarian Villager.

## Demo
![Demo](https://i.ibb.co/kgGT8YL/demo.gif)

## Installation
Download the jar from the [releases page](https://github.com/Greeenman999/LibrarianTradeFinder/releases/latest).

Or clone the repository and run `./gradlew build`.
The compiled jar should be under build/libs/.

## Usage

1. Encase the villager in a 1x1 area.
2. Place down a Lectern in front of the villager.
3. Look at the Lectern and execute `/tradefinder select`.
4. Put enough lecterns in your off-hand and an axe in your main-hand. The faster the axe can break the lectern, the faster the mod will be able to search.
5. Execute `/tradefinder search <enchantment> <maxPrice>` to start searching for you preferred enchantment. As soon as the mod found it, it will stop the search and message you.
6. If you want to stop the search before you found the enchantment, execute `/tradefinder stop`.

## Common Issues

 - The error: "You are not looking at a lectern."
   - Make sure you are looking at the lectern and not the villager.
 - The lectern doesn't get broken.
   - Some anti-cheats can prevent breaking the lectern or interacting with the villager if you are not looking at it.
 - My Lecterns are disappearing.
   - Sometimes the lecterns dropped, can get behind the lectern or somewhere else. Stop the mod, break the lectern, and try to find all the items. Then start the search again.