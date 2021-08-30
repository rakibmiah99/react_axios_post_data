### react_axios_post_data
#### for file Access
header("Access-Control-Allow-Origin: *");
#### for get post data
$_POST['name'] --- <span style="color:red">Not Working 
  ---------------------------------
#### your nedd to this 
$_POST = json_decode(array_keys($_POST)[0],true);<br>
then <br>
$_POST['data-name']

  





