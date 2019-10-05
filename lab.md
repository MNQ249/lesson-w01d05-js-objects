const books = [
{
  title: 'Ford',
  author: 'Mustang',
  alreadyRead : false
},

{
  title: 'funny',
  author: 'jeje',
  alreadyRead : true
},

{
  title: 'red',
  author: 'jak',
  alreadyRead : true
}]

for(let i = 0; i< books.length; i++){
console.log(books[i].title +" BY "+ books[i].author);
}

let read = function(READ){
for(let i = 0; i<books.length; i++){
if (books[i].title === READ){
if(books[i].alreadyRead === true){
return "You already read ";
}
else{ return "You still need to read ";}
}
}
}
