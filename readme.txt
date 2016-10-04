
function doIt(){
var count = 0
$('.dropQ').each(function(){
  var value = $(this).val()
  if(value.indexOf('@') > -1 ){
    count++
  }
})
console.log(count)
}
doIt()
// test
//testing