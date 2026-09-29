Usage

1. Generate instances
Generate n aircraft maintenance scheduling instances:

python3 main.py --mode generate --size MEDIUM --n 5 --real

Available instance sizes include SMALL, MEDIUM, and LARGE.

2. Solve instances
Run the heuristic on the generated instances:

python3 main.py --mode solve --size MEDIUM --n 5 --real --solver HEURISTIC

3. Run the complete pipeline
To generate instances and run the full computational pipeline:

python3 run_pipeline.py

