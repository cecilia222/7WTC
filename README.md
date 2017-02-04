# 7WTC
class2


# genome_tools
My genomics scripts

Example usage:

...
echo "name, count" >my_file.csv
for fasta in *.fa; do
  count=$( bash count_seq.sh $fasta )
  echo "$fasta, $count" 
done >> my_file.csv
...
