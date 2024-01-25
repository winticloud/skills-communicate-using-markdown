# This is an H1 markdown header

- [x] Turn on GitHub Pages
- [ ] Outline my portfolio
- [ ] Introduce myself to the world

``` javascript
var myVar = "Hello, world!";
```
![Image of Yaktocat](https://octodex.github.com/images/yaktocat.png)

``` bicep
param myVar = "Hello, world!"

resource resKeyvaultRg 'Microsoft.Resources/resourceGroups@2022-09-01' = {
  name: parKeyVaultRg
  location: parLocation
}

//Fortigate parameters
@description('allowed Fortigate firmware version')
@allowed([
  '7.0.13'
])
param parFortiImageVersion string
```
