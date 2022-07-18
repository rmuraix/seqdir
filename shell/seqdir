# $1 is Number of folders to create.(require)
# $2 is folder name.
# $3 is division character.

if [ -z "$1" ]; then
    echo "The first argument is required!"
    exit
fi

PADDING_1=$(printf "%0${#1}d" 1)

for i in {${PADDING_1}..${1}}
do
    eval mkdir -p $i$3${2} 
done 
