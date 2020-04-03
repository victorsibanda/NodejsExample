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
