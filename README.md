### JavaScript Cookies

## Instalation:

```
<script src="/path/to/cookies.js"></script>
```

## Usage:
#Set cookies:
```
cookies.set('name','value','expire','path','domain');
```
-Only name and value are required.
-Expire is set on 30 days by default (or set your time).

#Get cookies:
```
cookies.get('name');
```
-Returns value of selected cookie.

#Remove cookie:

```
cookies.remove('name');
```
-Removes particular cookie.

#Remove all:
 
```
cookies.removeAll();
```
-Removes all your cookies.

#Get cookie array

```
cookies.getAll();
```
-Returns an array of all cookies in form:
	__name=value__

