# DFA-to-Equivalent-Minimized-DFA
Here 7 file is attached.
1)File Maker.c is the file which can create the file of accepted format for Minimizing DFA.c
2).exe file is the application file created by the codes.
3).o files are object file here it is of no use.(It is attached because it is generated by the code also.)
4)Wanted_DFA is the file created by File Maker.c. It can also be used as an input to Minimizing DFA.c
5)Our Programme only accept .txt file with the format given below to accept the DFA from a file:-
  States:-{q1,q2,q3,q4,final}
  Alphabets:-{0,1,2,e0,sdf}
  Final States:-{final,q4}
  Starting State:-q1
  Transition Functions are:-
  del(q1,e0)=q2
  del(q3,sdf)=q2
  And so on...