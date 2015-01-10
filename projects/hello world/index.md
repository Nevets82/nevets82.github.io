---
layout: default
title: Hello, World!
---
# Hello, World! #

## Programming Languages ##

### ASP ###

```aspx-cs
<html>
	<head>
		<title>Hello, World!</title>
	</head>
	<body>
		<% Response.Write "<p>Hello World!</p>" %>
	</body>
</html>
```

### ASPX C# ###

```aspx-cs
<%@ Page Language="C#"%>
<html>
	<head>
		<title>Hello, World!</title>
	</head>
	<body>
	   <% Response.Write("<p>Hello, World!</p>"); %>
	</body>
</html>
```

### ASPX Visual Basic ###

```aspx-vb
<%@ Page Language="VB"%>
<html>
	<head>
		<title>Hello, World!</title>
	</head>
	<body>
	   <% Response.Write("<p>Hello, World!</p>") %>
	</body>
</html>
```

### C ###

```c
#include <stdio.h>

main()
{
	printf("Hello, World!");
}
```


### C++ ###

```c++
#include <iostream>

int main()
{
	std::cout << "Hello, World!";
}
```


### C# ###

```csharp
public class Program
{
	public static void Main()
	{
		System.Console.WriteLine("Hello, World!");
	}
}
```

### Java ###

```java
class Program {
	public static void main(String[] args) {
		System.out.println("Hello, World!");
	}
}
```

### JavaScript ###

```javascript
document.write("Hello, World!"); 
```

### PHP ###

```php
<?php
	Echo "Hello, World!";
?>
```

### Visual Basic ###

```vbnet
Module Program
	Sub Main()
		System.Console.WriteLine("Hello, World!")
	End Sub 
End Module
```

## Markup Languages ##

### HTML5 ###

```html
<!DOCTYPE html>
<html>
	<head>
		<meta charset="UTF-8">
		<title>Hello, World!</title>
	</head>
	<body>
		<p>Hello, World!</p>
	</body>
</html>
```

### Markdown ###

```
---
layout: default
title: Hello, World!
---
# Hello, World! #
```

### XHTML ###

```html
<!DOCTYPE html PUBLIC "-//W3C//DTD XHTML 1.0 Transitional//EN" "http://www.w3.org/TR/xhtml1/DTD/xhtml1-transitional.dtd">
<html xmlns="http://www.w3.org/1999/xhtml">
	<head>
		<title>Hello, World!</title>
	</head>
	<body>
		<p>Hello, World!</p>
	</body>
</html>
```

## Shell Languages ##

### Windows Batch ###

```bat
@ECHO off
ECHO Hello, World!
PAUSE
```

### PowerShell ###

```powershell
Write-Host Hello, World!
```

## Query Languages ##

### SQL ###

```sql
SELECT 'Hello, World!';
```