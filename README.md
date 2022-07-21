# Qiskit Hackathon Taiwan 2022 - Group 4 - Quantum Mapper

## Where is the exportation script of our data?
  - Due to we have no enough time to make our code better and easily to use, so functions collect in following 2 `ipynb` files.
    - `hackthon.004.TSPtoIsing.ipynb` transpiles our map of cities of problem into Ising coefficient matrix.
    - `hackthon.003.IsingDataGen.ipynb` takes our Ising coefficient matrix, range of `catol` and `depth` on QAOA to execute our experiments and export the data.
    
  - Other files are used for reference, testing our codes, or making dummy data to make sure our experiment fine, so some files are the sample files from tutorial in Qiskit, some of them are our group members' previous works.
  
  - We used a submodule [`mori`](https://github.com/harui2019/mori/tree/4bc94be2d448f2145e66b583c808fbbde0876ff1) for data exportation and a python files `backend.py` to access importing backends, all  made by `@harui2019` (the actually owner of this repo), one of group member.
  
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
    
## Group Member
  - 何紹威, Shao-Wei Ho (coding)
  - 張淮竣, Huai-Chun Chang (coding) - `@harui2019` - james880818@gmail.com
  - 楊淯元, Yu-Yuan Yang (presenter, visualization) - `@yuyuan871111`
  - 李俊澤, Chun-Tse Li (presenter, coding)
  - 王勻遠, Yun-Yuan Wang (presenter, coding)
 

  
