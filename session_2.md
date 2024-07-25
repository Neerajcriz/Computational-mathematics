## Pseudocode_Solution of system of equation
```python
FUNCTION solution(A,B):
 Create augmented matrix:K=[A/B]
  Reduce in Row Reduced Echelon form
  Rank=no: of non zero rows of RREF
    IF Rank(K))!= Rank(A):
      print("System is inconsistent")
    ELSE IF:
      Solve using back substitution 
END FUNCTION
```
