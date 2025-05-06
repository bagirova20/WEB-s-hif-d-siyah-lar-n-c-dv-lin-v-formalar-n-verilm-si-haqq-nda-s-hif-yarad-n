<!DOCTYPE html>
<html lang="az">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Siyahılar, Cədvəllər və Formalar</title>
</head>
<body>

  <h1>Siyahılar</h1>
  
  <!-- Sırasız Siyahı -->
  <h2>Sırasız Siyahı</h2>
  <ul>
    <li>Birinci maddə</li>
    <li>İkinci maddə</li>
    <li>Üçüncü maddə</li>
  </ul>
  
  <!-- Sıralanmış Siyahı -->
  <h2>Sıralanmış Siyahı</h2>
  <ol>
    <li>Birinci maddə</li>
    <li>İkinci maddə</li>
    <li>Üçüncü maddə</li>
  </ol>
  
  <!-- İç-içə Siyahı -->
  <h2>İç-içə Siyahı</h2>
  <ul>
    <li>Birinci maddə
      <ul>
        <li>Alt maddə 1</li>
        <li>Alt maddə 2</li>
      </ul>
    </li>
    <li>İkinci maddə</li>
  </ul>

  <h1>Cədvəl</h1>
  
  <!-- Cədvəl -->
  <table border="1">
    <tr>
      <th>Ad</th>
      <th>Yaş</th>
      <th>Şəhər</th>
    </tr>
    <tr>
      <td>Əli</td>
      <td>25</td>
      <td>Bakı</td>
    </tr>
    <tr>
      <td>Maria</td>
      <td>30</td>
      <td>Gəncə</td>
    </tr>
    <tr>
      <td>Ayşə</td>
      <td>28</td>
      <td>Sumqayit</td>
    </tr>
  </table>

  <h1>Forma</h1>
  
  <!-- Sadə Forma -->
  <form action="/submit" method="POST">
    <label for="name">Adınız:</label>
    <input type="text" id="name" name="name" required><br><br>

    <label for="email">Email:</label>
    <input type="email" id="email" name="email" required><br><br>

    <label for="message">Mesaj:</label><br>
    <textarea id="message" name="message" rows="4" cols="50"></textarea><br><br>

    <input type="submit" value="Göndər">
  </form>

  <h2>Seçimlər</h2>
  
  <!-- Seçimlər -->
  <form>
    <label for="gender">Cinsiyyət:</label><br>
    <input type="radio" id="male" name="gender" value="male">
    <label for="male">Kişi</label><br>
    <input type="radio" id="female" name="gender" value="female">
    <label for="female">Qadın</label><br><br>
    
    <label for="country">Ölkə:</label>
    <select id="country" name="country">
      <option value="azerbaijan">Azərbaycan</option>
      <option value="turkey">Türkiyə</option>
      <option value="usa">ABŞ</option>
    </select><br><br>
    
    <input type="submit" value="Göndər">
  </form>

</body>
</html>
