# The-2nd-AI-New-Drug-Development-Competition-JUMP-AI-2024(Korea Pharmaceutical and Bio-Pharma Association & Ministry of Health and Welfare)
1. Data: Compiled a training dataset of 1,952 IRAK4 IC₅₀ measurements from the ChEMBL database.
2. Model: XGBoost and MPNN (Message Passing Neural Network).
3. Challenge: Prediction of IRAK4(Interleukin-1 Receptor-Associated Kinase 4) IC50 activity
4. Score: 0.64736(IC50(nM) Normalized RMSE(NRMSE)).
5. Leveraged SMILES (Simplified Molecular Input Line Entry System) ligand representations to extract molecular information, assess compound similarity from RDKit and PubChem databases, and computed docking scores.
6. Utilized a GNN-based approach by representing each molecule’s atoms as nodes and bonds as edges, implementing an MPNN model, and stacking its predictions with XGBoost outcomes.
7. Placed 7th of 900 teams, qualifying for the finals.
