<!DOCTYPE html>
<html>

<head>
<link rel="stylesheet" type="text/css" href="AHKETA_style.css" /> 
 <title>Zabelin KSP217</Title>
</head>

<body>
  <table> 
        <form> 
            <tr> 
                <td> 
                    <label for="name"> 
                        Имя:
                    </label> 
                </td> 
                <td><input type="text" id="name" /> 
                </td> 
            </tr> 
            <tr> 
                <td><label for="name2"> 
                        Фамилия:
                    </label> 
                </td> 
                <td><input type="text" id="name2" /> 
                </td> 
            </tr> 
            <tr> 
              <td><label for="countryselect">Страна:</label>

<select name="country" id="countryselect">
  <option value="">--Please choose an option--</option>
  <option value="russia">Россия</option>
  <option value="spain">Ирландия</option>
  <option value="usa">Бельгия</option>
  <option value="germany">Германия</option>
  <option value="france">Франция</option>
</select>
                </td> 
            </tr> 
            <tr> 
              <td><label for="sex">Пол:</label>

<select name="sex" id="sexselect">
  <option value="">--Please choose an option--</option>
  <option value="male">Мужской</option>
  <option value="female">Женский</option>
</select>
                </td> 
            </tr> 



   <tr> 
                <td> 
                    <label for="start"> Дата рождения:</label>
                  
                    </label> 
                </td> 
                <td><input type="date" id="start" name="trip-start" value="2000-01-00" min="1900-01-01" max="2023-10-17" />

                </td> 
            </tr> 

   <tr> 
                <td> 
<label for="story">Расскажите о себе:</label>
<textarea id="story" name="story" rows="5" cols="33">О себе</textarea>


                </td> 
            </tr> 

 <tr> 
                <td> 
                    <label for="EMail"> 
                        EMail:
                    </label> 
                </td> 
                <td><input type="text" id="email" /> 
                </td> 
            </tr> 
<tr> 
                <td> 
  <input type="checkbox" id="spam" name="spamonyouremail" checked />
    <label for="spam">Присылать спам на указанный EMail</label>
  
            
     </td> 
            </tr> 

  <tr> 
            <td> 
<input type="submit" value="Сохранить" />
     </td> 
            </tr> 
        </form> 
    </table> 
</body>

</html>
