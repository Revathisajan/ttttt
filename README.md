#!/bin/bash
echo "enter num"
read n
i=1
while [ $i -lt $n ]
do
echo $i
i=4(( $i+1 ))
done
