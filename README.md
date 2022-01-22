# bigfish_codes

The training script is in the root path, whose name is run_bc_chair/bucket/door/drawer.sh. 
Due to files storage limits, we put the trained models in the Google Drive(https://drive.google.com/file/d/1G9SGPXGF_KA3nISqVqG9ZOraobX9vWlj/view?usp=sharing). 
The evaluation script is the user_solution.py in the root path.

To make this repository clear, the differences with the official codebase are introduced. 
Compared with the official codebase, I only change two hyperparameters in the bc_mani_skill_pointnet_transformer.py. 
Namely, num_heads and num_blocks. Besides, I trained the models with 1024 batch size and 1.2 million iterations 
and submitted the models that obtained the highest success rate on training set.

More specially, 
1)	The best bucket model is 64head, 12 block, which was submitted in December 29 and achieved the success rate 37.2 on the leaderboard. 
2)	The best chair model is 64head, 12 block, which was submitted in December 29 and achieved the success rate 23.2 on the leaderboard. 
3)	The best drawer model is 64head, 12 block, which was submitted in January 4 and achieved the success rate 49.6 on the leaderboard. 
4)	The best door model is 16head, 16 block, which was submitted in January 14 and achieved the success rate 41.6 on the leaderboard.

We plan to write a technical report for improving the future research.

