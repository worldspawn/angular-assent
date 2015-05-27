# Angular Assent

Connects angular validation to assent.

## Install

`bower install angular-assent`

## Usage

``` html
<form name="form" novalidate>
  <input type="text" name="username" ng-model="user.username" validation-target />
  <input type="text" name="address.line1" ng-model="user.address.line1" validation-target />
</form>
```

Where user (is on the scope) is an instance of an object that has a validator set on it's prototype.

For more information please read the assent readme [Assent](https://github.com/worldspawn/assent)
