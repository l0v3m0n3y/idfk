# idfk
JavaScript library for idfk.lol
# main
```js
async function main(){
    const {idfk} = require('./idfk');
    const url= new idfk();
    let req=await url.short_url("url")
    console.log(req)
}
main()
```
