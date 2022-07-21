# QiskitHackathonTW2022_Quantum_mapper
Qiskit Hackathon Taiwan 2022 - Group 4 - Quantum Mapper

## Where is the exportation script of our data?
  - Due to we have no enough time to make our code better and easily to use, so functions collect in following 2 `ipynb` files.
    - `hackthon.004.TSPtoIsing.ipynb` transpiles our map of cities of problem into Ising coefficient matrix.
    - `hackthon.003.IsingDataGen.ipynb` takes our Ising coefficient matrix, range of `catol` and `depth` on QAOA to execute our experiments and export the data.
    
  - Other files are used for reference, testing our codes, or making dummy data to make sure our experiment fine, so some files are the sample files from tutorial in Qiskit, some of them are our group members' previous works.
  
  - We used a submodule `mori` for data exportation and a python files `backend.py` to access importing backends, all  made by `@harui2019` (the actually owner of this repo), one of group member.
  
## Where is experiments data?
  The folloeing folders are our data.
  - test.3nodes.002
    !!! ATTENTION, the `catol` is not actually applied in this experiments, due to bugs when excute, all `catol` are actually `0.02` !!!
    
  - test.4nodes.001
    - 4 city by 16 qubits
    - penalty = 1000
    
  - test.p=100.3nodes.001
    - 3 city by 9 qubits
    - penalty = 100
    
  - test.p=1000.3nodes.001
    - 3 city by 9 qubits
    - penalty = 1000
    
  - test.p=10000.3nodes.001
    - 3 city by 9 qubits
    - penalty = 10000

  
