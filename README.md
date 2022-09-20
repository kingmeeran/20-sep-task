# 20-sep-task

var temp=[]
function range(a,b){
  for(var i=a;i<=b;i++){
     temp.push(i)
  }
  return temp;
}
console.log(range(-4, 7))
console.log(range(3, 7))

function foo(arr){
  var r=arr.filter((e)=>e=='q');
  for(var i=0;i<=r.length;i++){
    if(r[i]=='q'){
      return `q(${r.length} times)`
      }
    }
  }
console.log(foo([3, 'q', 'q', 'q', 2, 3, 'q', 3, 'q', 'q',2, 4, 9, 3]));
