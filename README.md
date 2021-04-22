# RoleValidation &#x1F34E;

```diff
+ Short Documentation
```

:rice: Requirement :
- .env file (on localhost testing)


:eyes: Usage :
- Put this file to your helper directory folder. You can choose to make a new folder or not.
- import this component and put it to your if-else condition


:phone: Parameters :
- no need parameter


:paperclip: Example :
```js
if(RoleUser(process.env.REACT_APP_ROLE_ADMIN))
{
  this.executeDownload()
}
else // or you can skip this
{
  console.log("no action")
}
```

:camera: Preview :
- try it and you will know it :)
