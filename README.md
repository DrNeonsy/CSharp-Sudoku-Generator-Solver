# Sudoku Generator And Solver With Export Functionality
![CSharp](https://img.shields.io/badge/csharp-black?style=for-the-badge&logo=sharp)
![Console](https://img.shields.io/badge/console-black?style=for-the-badge&logo=windowsterminal)
![Dotnet](https://img.shields.io/badge/dotnet-black?style=for-the-badge&logo=dotnet)
![Windows](https://img.shields.io/badge/Windows-black?style=for-the-badge&logo=windows)

## Description
It started as an exercise in Java. Afterwards, I wanted to recreate it in C#, but more ideas kept coming up and this is the result. My teacher told me about the next topic being multi-dimensional arrays and that we would take a look at Sudoku. So, I was thinking about a generator, which was relatively easy except for the backtracking part of the algorithm because that was something new for me. After I wrote the program, I wanted to recreate it in C#, which led to this project.

## Idea
After recreating it, I wanted to make an usable app out of it:

1. Generate A Valid Sudoku
2. Allow For Input For The Sudoku To Solve
3. Check Whether The Input Is A Valid Board
4. Solve The Sudoku
5. Allow For Export To A TXT File

## How To Use
- You Start In A [Menu](#menu) Where You Can Press (G) To Generate A Sudoku Or (S) To Solve One.
- When You Decide For (S)olving One You Can Enter Each Row With Or Without WhiteSpaces Depending On What You Prefer.
- If You Enter An Empty Line It Will Reset To Row [1]
- If You Have Anything Other Than Numbers In Your Input The Row Will Reset To [current] So You Don't Have To Start From The Beginning.

## Note
I Do Not Check For Permissions So Make Sure The App Can Create The File If It Does Not Exist Or Open And Append To An Existing One.

## Images

### Menu
<img width="476" alt="Start" src="https://user-images.githubusercontent.com/65088572/190224339-688338c4-88c0-4d10-89f2-c139b98fea71.png">

### Generate
<img width="771" alt="Generate" src="https://user-images.githubusercontent.com/65088572/190224370-ba61d798-8308-4cd6-abf8-8a2f251eb298.png">

### Export
<img width="436" alt="Export" src="https://user-images.githubusercontent.com/65088572/190224391-19e3f5b3-dfcd-4860-a75c-878fee0af60c.png">

### Result
<img width="632" alt="Export_Result" src="https://user-images.githubusercontent.com/65088572/190224404-44eef4ee-7ece-49cb-820e-76830b3c80dd.png">

### Input
<img width="485" alt="Input" src="https://user-images.githubusercontent.com/65088572/190224431-67c54848-9780-4541-b0d4-a99dab12dd52.png">

### Example
![Input_Example](https://user-images.githubusercontent.com/65088572/190224450-e37d9be7-76c0-4b29-9011-647974eb29e6.png)

### Solved
<img width="371" alt="Solved" src="https://user-images.githubusercontent.com/65088572/190224463-68aff039-9c05-462d-a146-0f13f0debb20.png">

### Exit
<img width="268" alt="End" src="https://user-images.githubusercontent.com/65088572/190224479-a287c544-a8ad-4e2f-be67-2d25081a0472.png">
