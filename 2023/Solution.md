//Task 1

#!/bin/bash
n=$3
for ((i=$2;i<=$n;i++));
do
mkdir $1${i}
done
