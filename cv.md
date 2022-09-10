# Pavel Kerus
### Front-end developer
***
### Contacts
* Email: kerus2014@gmail.com
* Phone: +375297444144
* GitHub: [pavel-kerus](https://github.com/kerus2014)
* LinkedIn: [Pavel Kerus](https://www.linkedin.com/in/pavel-kerus-397839161/)
### Experience
* __RS SCHOOL | Trainee Front-end developer__\
 _Sep 2022 - Feb 2023_\
Websites development
* __Construction company | Civil Engineer__\
 _Mar 2019 - Present_\
Performance of general contracting works for the construction of industrial and civil buildings
* __IT ACADEMY | Trainee UX/UI Design__\
_Jun 2021 - Dec 2021_\
Development of a website and a mobile application\
my works - [BEHANCE](https://www.behance.net/abef2689)

### Code example
``` <html>
<head>
  <title>Multiplication Table</title>
  <script type="text/javascript">
    var rows = prompt("How many rows for your multiplication table?");
    var cols = prompt("How many columns for your multiplication table?");
    if(rows == "" || rows == null)
        rows = 10;
    if(cols== "" || cols== null)
        cols = 10;
    createTable(rows, cols);
    function createTable(rows, cols)
    {
      var j=1;
      var output = "<table border='1' width='500' cellspacing='0'cellpadding='5'>";
      for(i=1;i<=rows;i++)
      {
      output = output + "<tr>";
        while(j<=cols)
        {
        output = output + "<td>" + i*j + "</td>";
         j = j+1;
       }
        output = output + "</tr>";
        j = 1;
    }
    output = output + "</table>";
    document.write(output);
    }
  </script>
</head>
<body>
</body>
```

### Skills & Tools
* HTMS
* CSS
* Javascript
* React Js
* Figma
* Git
* Adobe photoshop
* Adobe XD
* Sketch

