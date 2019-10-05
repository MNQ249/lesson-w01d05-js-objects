const pargraph = 'This is a test this';
const lestOfWorlds = pargraph.split(' ');
const wordFrequencies = {};
for(let i = 0; i < lestOfWorlds.length;i++){
const key = lestOfWorlds[i].towLowerCase();

if(wordFrequencies[key] === undefined){
wordFrequencies[key] =1;
}
else{wordFrequencies[key]++};
}

for(let i = 0; i < lestOfWorlds.length;i++){
const key = lestOfWorlds[i].toLowerCase();

if(wordFrequencies[key] === undefined){
wordFrequencies[key] =1;
}
else{wordFrequencies[key]++};
}
