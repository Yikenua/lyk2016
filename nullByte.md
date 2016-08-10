
CSRF  (Cross_Site_Request_Forgery: Sitelerarası İstek Sahteciliği)


Yetkidişındaki alanlara erişmek amacıyla kullanılır.
Birini admin yapmak için:
            birini_admin_yap.php:?id=5
            
CSRF ikiye ayrılır:
1-GET
2-POST
Haberi olmadan sayfaya yönlendirmeli, 1x1 pxl resim gömerek farkında olmadan hacklenir.
<form post>
Select nem=id
Button
</form>

Css koduyla:
<style>
Form {display:none)}
</style>
<script>
Document.form[0].submit();
</script>

•	Browserlar aşağıdan yukarıya kodlar.

Eğer  data POST da oluşturulmuşsa:
If (isset ($_POST)){
Username=$_POST[“username”];
Md5($_POST[“password”]);
