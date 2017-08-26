$1-9
$10-${n}
#0-name of script
*-all the arguments as a single string
@-same as $.
$#total number of arguments
$$->PID of the script
$l->last return code
$?->return last return code
$*->all the  argument as single string
$0->represnetst name of the script



if  ["$#" == "0"]
then
  echo pass  at least one parameter.
  exit 1
fi

while(($#))
 do
   echo you gave me $1
   shift
 done


for loop:


for table in {2..-20..-2}
do 
echo $table;
done


for(( i=0;i<=10;i++))
do 
echo $i;
done

while loop:

i=10;
 while [ $i -ge 0 ];
do
echo "print age $i"
let i--;
done
