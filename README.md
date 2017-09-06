# 驼峰转换函数
function camelCase (str) {
  var arr = str.split('-');
  for(var i = 0; i<arr.length; i++){
    arr[i] = arr[i].charAt(0).toUpperCase()+arr[i].substr(1);
  }
  return arr.join('')
}
camelCase('stone-and-fex') 
