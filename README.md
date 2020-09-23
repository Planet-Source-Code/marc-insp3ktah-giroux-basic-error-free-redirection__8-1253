<div align="center">

## Basic Error Free Redirection


</div>

### Description

You know how everyone tells you to use header to redirect, you probably know by now that this only works if headers haven't already been sent. Well this way it works everytime without any errors.
 
### More Info
 
You should put this in a seperate file (Eg: functions.php) and include it in your scripts or just simple put the print part in your script.


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[Marc 'InSp3KtaH' Giroux](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/marc-insp3ktah-giroux.md)
**Level**          |Beginner
**User Rating**    |4.5 (18 globes from 4 users)
**Compatibility**  |PHP 3\.0, PHP 4\.0
**Category**       |[Internet/ Browsers/ HTML](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/internet-browsers-html__8-9.md)
**World**          |[PHP](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/php.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/marc-insp3ktah-giroux-basic-error-free-redirection__8-1253/archive/master.zip)

### API Declarations

Use It Freely!


### Source Code

```
<?
  function redirect($url) {
   die('<meta http-equiv="refresh" content="0;URL='.$url.'">');
  }
?>
```

