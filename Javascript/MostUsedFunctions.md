## Frequently used code snippet

**1. Empty Object check**

```javascript
 function isEmptyObject(obj){
  if(Object.keys(obj).length === 0 && obj.constructor === Object)
  {
    return true;
  }
  return false;
}
```

```javascript
 function getISODateForToday(){
const date = new Date();
console.log('date= '+ date.toISOString().slice(0,10));
return date;
}
```
