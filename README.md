<h1>Javascript Best Practice Naming Conventions</h1>

<p>Always Iclude the Naming convention at the top of the DOcument to let people know which naming convention you are using
Any Variable which contains X_Varname means this variable is a blobal variable</p>

![GitHub Logo](/images/logo.png)
Format: ![Alt Text](url)

###Note: 
>This is a custom Naming convention which is used in my personal workflow and I incourage people to use a specific naming convention
>It is not necessory to use my naming convention, create your own naming convention and be consistent using it over your project.
>Alwasy mention your naming convention and link what naming convention measn what, create a wiki page like this and link it to the top of the project.
>Sometime you work in a team or an orgenisation which have their own special naming convention and you are forced to use it, remember be uniform on whatever naming convention you use.

###Important
>This Naming convention has been derived from Hungarian naming convention and mainly targeted to be followed in Javascript Application devlopment and might not be suitable for other oprgraming language.

>This Naming convention do include some naming convention which are not required in Javascript Application development and you will rearly use them.
[GitHub](http://github.com)

####` var _config = ''` 
Any configuration of Builtin variable which dont change and which user should not change during development.
####` var t_varName = ''`
`t_varName` `t_` means temporary variable which can be called inside a function to keeping count of some deta.
####` var g_varName = ''`
`g_varName` here `g_` means this is a global variabel ,
####` var f_varName = ''`
Here `f` means this variable contains a flag value.
####` var aVarName =[];` 
`aVarName` here `a` at he start means variable stores an Array
####` var nVarName = 3;`
`nVarName` here `n` at the start of variable name means it holds a cumber in Javascript specially n means coint variable to count something.
####` var iVarName = 3;`
`iVarName` here `i` at the start of the variable name means it stores an index/ in javascript in other language it means it stores and Integer.
####` var fVarname = 0.2`
fVarname here f stands for float Point variable, this is not common in javascript because it can be stored in.
####`var bVarname = true`
Here 'b' at the start of the variable measn it is a boolean variable
####` var fnFunctionName = function (){};`
Here `fn` at the start of the variable means it is a function.
####` var chVarName = 'c';`
Here `ch` means it is a caracter type variable
####` var cVarName = 2;` 
Here `c` means this variable stores count of something
####` var dwVarName = 0.0002 ` 
Here `dw` means this variable stores a bouble variable 
####`var fpVarname = 0` 
Here `fp` means this is a variable storing flaging point value.
####` var pVarName = 0x0000`
Here `p` means this variable is pointing to another memory location This variable is not used in Javascript it is only available in Language where there is option of memory manangement.
####` var rgVarName = []`
Here `rg` means this variable is storing range variable.
####` var dtVarName = '08-08-107Z-12-00-09T'`
here `dt` means date time value which means this variable stores a date time value.
####` var dsVarName = '08-08-2016'`
here `ds` means this variable stored a date string.
####` var doVarName = '08-08-2016'`
here `do` means this variable stored a date Object.
####` var tsVarName = '08-08-2016'`
here `ts` means this variable stored a time string.
####` var toVarName = '08-08-2016'`
here `to` means this variable stored a time string.
####` var ClassName = ''`
variable starts with a capital letter measns it is an class object.
####` var oVarName = ''`
`o` means this is an general object.
####`var $varName = $(document);`
Here `$` at he start of the variable means this cariable stores an unique type od deta, at this example it is storing a jQuery object
