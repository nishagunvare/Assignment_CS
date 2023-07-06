# Assignment_CS
1) <script>
var array1 = new Array("a","b","c","d","e","f");
var array2 = new Array("c","e");

for (var i = 0; i<array2.length; i++)
{
    var arrlen = array1.length;
    for (var j = 0; j<arrlen; j++)
{
        if (array2[i] == array1[j])
{
            array1=array1.slice(0,j).concat(array1.slice(j+1,arrlen));
        }
    }
}
alert(array1);

</script>


2)const word = 'aaadddAAAwwwweee'

let newWord = ' '

for (let i = 0; i < word.length; i++)
{

  if (word[i] === word[i + 1])
{

    newWord += word[i] + word[i + 1]

    i++

  }

}

console.log(newWord, newWord.lenght)

