# Sudoku_Solver_in_C

Sudoku Solver implemented in C using the Backtracking Algorithm. This program takes a predefined 9×9 Sudoku puzzle, validates possible numbers according to Sudoku rules, and recursively fills the empty cells until a valid solution is found.

Features
<ul>
<li>Solves a 9×9 Sudoku puzzle automatically.</li>
<li>Uses recursive backtracking to explore possible solutions.</li>
<li>Validates each number based on:</li>
  <ul>
    <li>Row constraints</li>
    <li>Column constraints</li>
    <li>3×3 sub-grid constraints</li>
  </ul>
<li>Automatically backtracks when a selected number leads to an invalid solution.</li>
<li>Displays both the original puzzle and the solved puzzle in a formatted grid.</li>
<li>Handles unsolvable puzzles with an appropriate message.</li>
</ul>
