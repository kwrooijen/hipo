## 0.5.2

* **[+]** Pass arguments to attribute handlers as strings

## 0.5.2

* **[+]** Attributes can have namespaces

## [0.5.0](https://github.com/jeluard/hipo/issues?q=is%3Aclosed+milestone%3A0.5.0)

* **[+]** Introduced `:create-element-fn` hook
* **[+]** Attributes handling can be customized via `:attribute-handlers`
* **[~]** Changed `hipo.create` semantic
* **[~]** Interceptors can be chained

## [0.4.0](https://github.com/jeluard/hipo/issues?q=is%3Aclosed+milestone%3A0.4.0)

* **[~]** Improved Interceptor semantic
* **[-]** Removed attribute handler extensibility

## [0.3.0](https://github.com/jeluard/hipo/issues?q=is%3Aclosed+milestone%3A0.3.0)

* **[+]** Elements can be reconciled via a function returned by `hipo.create-for-update`
* **[~]** Rename `hipo` to `hipo.core` (no more single segment namespace)
* **[-]** Custom Element **is** syntax (still discussed)

## [0.2.0](https://github.com/jeluard/hipo/issues?q=is%3Aclosed+milestone%3A0.2.0)

* **[+]** Custom Element support (type extension via **is** attribute)
* **[+]** Properties whose name starts with **on-** are handled as event listener
* **[+]** Specific form compilation (**for** / **if** / **when** / **list** )
* **[+]** Hint support via `^:text`
* **[+]** `hipo/partially-compiled?` allows to check for partial compilation
* **[~]** Stick to basic hiccup support (:classes and :style are no more handled specifically, only handle vectors, keyword namespace is ignored)
* **[~]** Renamed `hipo.macros.node` to `hipo.create`
* **[-]** PElement support
* **[-]** deftemplate
* And various performance improvements

## 0.1.0

* Initial import from dommy codebase
