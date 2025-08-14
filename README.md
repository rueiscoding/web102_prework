# WEB102 Prework - *WaveStarter*

Submitted by: **Rue Tripathy [rueiscoding]**

**WaveStarter** is a website for the company Sea Monster Crowdfunding that displays information about the games they have funded.

## Required Features

The following **required** functionality is completed:

* [ ] The introduction section explains the background of the company and how many games remain unfunded.
* [ ] The Stats section includes information about the total contributions and dollars raised as well as the top two most funded games.
* [ ] The Our Games section initially displays all games funded by Sea Monster Crowdfunding
* [ ] The Our Games section has three buttons that allow the user to display only unfunded games, only funded games, or all games.

The following **optional** features are implemented:

* [ ] Centered some headings
* [ ] The selected button's appearance changes to give user feedback on selection.
* [ ] Cleaned up the game cards.

## Video Walkthrough

Link to [Loom video](https://www.loom.com/share/14640d9bdd1c490e9fb3dfe8eeb721c1?sid=97854ae6-dce2-41de-8525-629253f7384f) for a walkthrough of implemented features.

## Notes

Styling outside of the css file got messy! 

I created a setActive() function that deselects all the buttons except the one passed as a parameter. I ran into some errors when I was directly invoking setActive on click instead of passing an anonymous function to wrap setActive.

## License

    Copyright [yyyy] [name of copyright owner]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
