# TicTacToe
This game is a simulation of Tic Tac Toe game. It is played on a 3X3 grid. It has 2 levels of web components. There is a board and the nine squares which are the buttons and children of the board. Board is the parent component and squares are the child components. To keep track of whose turn it is, a state is kept track of at board level. The child needs to know whose turn it is so there needs to be communication of the state between parent and child. Callbacks are used here. A callback is passed down from the parent to a child so the child can do what it needs to do and then transfer the information back to the parent. The nine children keep track of their own state, whether they are an X or an O. The first player to occupy 3 spaces in a row, column or diagonal wins. 

Roadmap of future improvements: I would like to add 2 new features: 
a) The already clicked buttons to be disabled
b) To keep track of the score of each player.

MIT License

Copyright (c) 2020 John Williams

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
