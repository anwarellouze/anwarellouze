<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>l'avis de l'internaute concernant votre site web.</title>
</head>
<body>
    <h1>Votre avis</h1>
    <form action="/action_page.php">
        <p> Prénom <input name="nom" type="text"/> </p>
        <p> Nom <input name="nom" type="text"/> </p>
        <p> date naissance <input type="date"></p>
        <p> Genre:
       <br> <input type="radio" name="genre"/> Homme<br/>
<input type="radio" name="genre"/> Femme <br/>
<input type="radio" name="genre"/> Autre <br/></p>
<label for="email">Email:</label>
  <input type="email" id="email" name="email" pattern="[a-z0-9._%+\-]+@[a-z0-9.\-]+\.[a-z]{2,}$">
  <input type="submit"><br><br>
  <select name="pays" title="gouvernorat">
    <option value="Tunis">Tunis</option>
<option value="Ariana">Ariana</option>
<option value="Ben Arous">Ben Arous</option>
<option value="Manouba">Manouba</option>
<option value="Zaghouan">Zaghouan</option>
<option value="Nabeul">Nabeul</option>
<option value="Bizerte">Bizerte</option>
<option value="Béja">Béja</option>
<option value="Jendouba">Jendouba</option>
<option value="Kef">Kef</option>
<option value="Siliana">Siliana</option>
<option value="Sousse">Sousse</option>
<option value="Monastir">Monastir</option>
<option value="Mahdia">Mahdia</option>
<option value="Sfax">Sfax</option>
<option value="Kairouan">Kairouan</option>
<option value="Kasserine">Kasserine</option>
<option value="Sidi Bouzid">Sidi Bouzid</option>
<option value="Gabès">Gabès</option>
<option value="Mednine">Mednine</option>
<option value="Tataouine">Tataouine</option>
<option value="Gafsa">Gafsa</option>
<option value="Touzeur">Touzeur</option>
<option value="Kébili">Kébili</option>
<option value="Djerba">Djerba</option><br><br>
</select><br><br><br>
<p>Quelle est votre opinion sur système solaire ?</p>
<input type="radio" name="Quelle est votre opinion sur système solaire ?"/> bon<br/>
<input type="radio" name="Quelle est votre opinion sur système solaire ?"/> trés bon <br/>
<input type="radio" name="Quelle est votre opinion sur système solaire ?"/> moyenne <br/></p>

<textarea name="resume" rows="8" cols="40"></textarea><br><br>
<input type="submit" value="Envoyer" />
<input type="reset" value="Efacer" />
</form> 
</body>
</html>
