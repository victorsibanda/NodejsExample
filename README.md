# NodejsExample

TODO: Enter the cookbook description here.

## Chef Commands:

#### New Cookbook

```
  $ chef generate <name>

```

#### Kitchen

Run provision from Recipe
```
kitchen converge
```

create VM
```
$ kitchen create

```

prepare kitschen for testing

```
kitchen setup

```

run test /much like rake spec

```
kitchen verify

```

destroy machine

```
kitchen destroy
```

run all the above create --> destroy

```
kitchen test

```

Check if something exits within a recipe
unit test
```
chef exec rpsec

```

#### Unit Test (In Chef) and Recipe

A unit test in chef is similar to a unit test in python.
They Test single units of code.
In Chef, that refers to checking if something exists in the recipes.

#### Recipes

Are where you write your provision

#### Intergration tests with in spec
They are not like unit test they test to see the work machine after you run the recipes.
