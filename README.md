#GOpinionated

Simple & fast Go (Golang) IDE.
**Started 9.4.17**

##Motivation
Most availible IDEs are either incompatible with screen readers or take a while to start eating than lots of system resources.

##Goals
- [x] Be fast and memory-inexpensive. The IDE mustn't take more than 5 secs to start and load the example project plus shouldn't consume more than 128 MB of ram.
- [ ] Responsibility requirements such as max autocompletion time are yet to be defined.
- [x] The IDE should be screen reader-able (e.g. could be used with Jaws for windows and alike software), hence no GTK/QT or other technology may be considered. Not only should it be accessible in theory, it must be tested for being ergonomic with screen reading software (the list and testing process is to be defined).
- [ ] The IDE should provide syntax highlighting for built-in Go keywords as well as for functions, variables and types (both user-defined and built-in) in scope.
- [ ] Open definition should be availible by keystroke or control+left mouse click
- [ ] IDE must provide autocompletion. It is planned to use gocode tool but if it failes to provide needed  information, custom tools are to be written.
- [ ] A colored console that reflects build process and Go program output should be availible
- [ ] Go compiler messages must be delivered to the error list
- [ ] Some support for existing linters and running tests should be implemented
- [ ] Godoc invocation
- [ ] this list should be extended


###Goals for v0.1 beta
- [ ] Get something solid and working.


###Goals for 1.0 releace
- [ ] Fulfill above requirements and produce usable and tested product.
