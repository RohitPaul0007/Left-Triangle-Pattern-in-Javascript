# Left-Triangle-Pattern-in-Javascript
//Left Triangle Pattern In JS
let n = 15;
let rp = "";
for (let i=1;i<n;i++){
  for( let j=0;j<i;j++){
    rp = rp + "*";
  }
  rp = rp +"\n";
}
alert(rp);
