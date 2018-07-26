<a id="dictionary.md-define-bool" class="anch"></a>

##### Bool
Represents a value which can be either **true** or **false**.

<a id="dictionary.md-define-default-value" class="anch"></a>

##### Default values

Basic types have the following default values on static targets:

* `Int`: `0`
* `Float`: `NaN` on Flash, `0.0` on other static targets
* `Bool`: `false`



<a id="dictionary.md-define-dynamic-target" class="anch"></a>

##### Dynamic target
Dynamic targets are more lenient with their types and allow `null` values for basic types. This applies to the JavaScript, PHP, Neko and Flash 6-8 targets.

<a id="dictionary.md-define-nullable" class="anch"></a>

##### nullable
A type in Haxe is considered **nullable** if `null` is a valid value for it.

<a id="dictionary.md-define-static-target" class="anch"></a>

##### Static target
Static targets employ their own type system where `null` is not a valid value for basic types. This is true for the Flash, C++, Java and C# targets.

<a id="dictionary.md-define-void" class="anch"></a>

##### Void
Void denotes the absence of a type. It is used to express that something (usually a function) has no value.