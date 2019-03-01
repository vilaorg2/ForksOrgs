1. Create repository X in org A 
2. Fork X to create a copy in org B 
3. open an issue in org B for X. It will be assigned the number 1 
4. open a pull request in org A into A:master. It will also be assigned the number 1 
5. accept the PR 
6. Open and accept another PR that transports the new changes from A into X' master on B 
7. Issue 1 on B will now say that it was referenced by the PR merge commit on A

Merge to vilaorg first;
Now merge to vilaorg2
