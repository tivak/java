# 0.9.18
* fix of overflow detection for numeric primitive types
* fix of method prefix of error message
* issue #125 avoid nested JsonException
* fix #109 treat wildcard generics variable as Object

# 0.9.17
* fix leading zero
* fix #112 #119
* fix of parsing zero & min values
* issue #115 better leading zero detection
* fix #144, parse max int/long
* fix #110 if @JsonProperty is marked on field, ignore getter/setter

# 0.9.16

* issue #107 annotation should be marked on getter/setter if present
* fix ctor is null when encoding issue
* issue #104, JsonWrapper argument should not be mandatory
* issue #99 added mustBeValid method to Any class
* issue #97 demonstrate JsonProperty when both field and setter
* like "1.0e+10" should not fail
* issue #94 skip transient field
* issue #94 fix JsonProperty not changing fromNames and toNames
* issue #93 some control character should be esacped specially
* issue #93 fix control character serialization
* issue #92 fix generics support

# 0.9.15

breaking changes

* `null` is not omitted by default config

new features

* add `defaultValueToOmit` to @JsonProperty
* add `omitDefaultValue` to config
* encoder support indention in dynamic mode