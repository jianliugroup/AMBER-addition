# AMBER-addition
Updated files for the "middle" thermostat scheme for AmberTools18
Both serial and MPI versions are available.

~~~
cp ./2018bugfixfiles/AmberTools/src/sander/*.F90   $AMBERHOME/AmberTools/src/sander/
rm -rf  $AMBERHOME/test/*Middle*
cp -r ./2018bugfixfiles/test/*   $AMBERHOME/test/
~~~

Compile AMBER2018 again.

Follow the tutorial webpage
http://jianliugroup.pku.edu.cn/tutorials.html
to implement the efficient "middle" thermostat scheme
