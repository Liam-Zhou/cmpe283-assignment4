# cmpe283-assignment4

 

1.For each member in your team, provide 1 paragraph detailing what parts of the lab that member implemented / researched. (You may skip this question if you are doing the lab by yourself). 

Only myself: Yilin Zhou (sjsuid:012571026)

2.Include a sample of your print of exit count output from dmesg from “with ept” and “without ept”. 

The sample of exit count output from dmesg from “with ept”:
![Image text](https://github.com/Liam-Zhou/cmpe283-assignment3/blob/main/pic/a3-3.png)
![Image text](https://github.com/Liam-Zhou/cmpe283-assignment3/blob/main/pic/a3-4.png)

The sample of exit count output from dmesg from “without ept”:

 ![Image text](https://github.com/Liam-Zhou/cmpe283-assignment4/blob/main/pic/a4-3.png)
 ![Image text](https://github.com/Liam-Zhou/cmpe283-assignment4/blob/main/pic/a4-4.png)
  
3.What did you learn from the count of exits? Was the count what you expected? If not, why not? 

 - As we can see in my output data, after setting the ept to 0 and running a sequence of queries of CPUID leaf function 0x4FFFFFFE. The number of exits increase obviously.
  It was within my expectation because disabling nested paging will force KVM to use shadow paging which means that there will be more exits enabled CR3 exit etc. Therefore, the count of exits will increase.

4.What changed between the two runs (ept vs no-ept)? 
  
  - By using no-ept, the VM will use shadow paging instead of nested paging which will be used under ept configuration. The exit counts of no-ept is larger than that in ept.


