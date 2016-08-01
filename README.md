# Minesweeper
A Minesweeper game that has the option to load, save, and change difficulty.

The program is in Model View Controller(MVC) architecture, which is a way to organize code.
Bascally, the Controller sends informaton to the Model to handle. Then the Model updates the View.
The Model(MineModel.java) handles information from action events from the Controllers(MineButton.java, MineFrame.java).
Then it updates the Views(MineFrame.java, MinePanel.java), which is what the user sees.

The main class is in Minesweeper.java.

This program was made awhile ago, and in hindsight I should've been a little bit better with commenting in my code. Javadoc would've been a good option too.
