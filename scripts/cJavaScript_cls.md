# VBA Project: **vbaJavaScript**
## VBA Module: **[cJavaScript](/scripts/cJavaScript.cls "source is here")**
### Type: ClassModule  

This procedure list for repo (vbaJavaScript) was automatically created on 6/25/2015 10:03:23 AM by VBAGit.
For more information see the [desktop liberation site](http://ramblings.mcpher.com/Home/excelquirks/drivesdk/gettinggithubready "desktop liberation")

Below is a section for each procedure in cJavaScript

---
VBA Procedure: **addFile**  
Type: **Function**  
Returns: **[cJavaScript](/scripts/cJavaScript_cls.md "cJavaScript")**  
Return description: **self**  
Scope: **Public**  
Description: **kind of like a script tag - adds a local script file to your code**  

*Public Function addFile(scriptFile As String) As cJavaScript*  

*name*|*type*|*optional*|*default*|*description*
---|---|---|---|---
scriptFile|String|False||file name


---
VBA Procedure: **addAppsScript**  
Type: **Function**  
Returns: **[cJavaScript](/scripts/cJavaScript_cls.md "cJavaScript")**  
Return description: **self**  
Scope: **Public**  
Description: **kind of like a script tag - adds a local apps script stuff**  

*Public Function addAppsScript(scriptUrl As String) As cJavaScript*  

*name*|*type*|*optional*|*default*|*description*
---|---|---|---|---
scriptUrl|String|False||the web app providing the code


---
VBA Procedure: **addUrl**  
Type: **Function**  
Returns: **[cJavaScript](/scripts/cJavaScript_cls.md "cJavaScript")**  
Return description: **self**  
Scope: **Public**  
Description: **kind of like a script tag - adds a hosted file to your code**  

*Public Function addUrl(scriptUrl As String) As cJavaScript*  

*name*|*type*|*optional*|*default*|*description*
---|---|---|---|---
scriptUrl|String|False||file link


---
VBA Procedure: **simpleUrlGet**  
Type: **Function**  
Returns: **String**  
Return description: **result**  
Scope: **Public**  
Description: **kind of like a script tag - adds a local script file to your code**  

*Public Function simpleUrlGet(fn As String, Optional complain As Boolean = True) As String*  

*name*|*type*|*optional*|*default*|*description*
---|---|---|---|---
fn|String|False||file link
complain|Boolean|True| True|optional complain if an error


---
VBA Procedure: **addCode**  
Type: **Function**  
Returns: **[cJavaScript](/scripts/cJavaScript_cls.md "cJavaScript")**  
Return description: **self**  
Scope: **Public**  
Description: **adds code to your script**  

*Public Function addCode(scriptCode As String) As cJavaScript*  

*name*|*type*|*optional*|*default*|*description*
---|---|---|---|---
scriptCode|String|False||some code


---
VBA Procedure: **code**  
Type: **Get**  
Returns: **String**  
Return description: **the code**  
Scope: **Public**  
Description: **returns the code**  

*Public Property Get code() As String*  

**no arguments required for this procedure**


---
VBA Procedure: **self**  
Type: **Get**  
Returns: **[cJavaScript](/scripts/cJavaScript_cls.md "cJavaScript")**  
Return description: **self**  
Scope: **Public**  
Description: **returns convenience self for with/chaining**  

*Public Property Get self() As cJavaScript*  

**no arguments required for this procedure**


---
VBA Procedure: **clear**  
Type: **Function**  
Returns: **[cJavaScript](/scripts/cJavaScript_cls.md "cJavaScript")**  
Return description: **self**  
Scope: **Public**  
Description: **clears the code**  

*Public Function clear() As cJavaScript*  

**no arguments required for this procedure**


---
VBA Procedure: **chunker**  
Type: **Get**  
Returns: **[cStringChunker](/libraries/cStringChunker_cls.md "cStringChunker")**  
Return description: **the code chunker**  
Scope: **Public**  
Description: **expose the stringchunker**  

*Public Property Get chunker() As cStringChunker*  

**no arguments required for this procedure**


---
VBA Procedure: **compile**  
Type: **Function**  
Returns: **Variant**  
Return description: **the script control to execute run against**  
Scope: **Public**  
Description: **execute code**  

*Public Function compile() As Variant*  

**no arguments required for this procedure**


---
VBA Procedure: **addArraySupport**  
Type: **Function**  
Returns: **[cJavaScript](/scripts/cJavaScript_cls.md "cJavaScript")**  
Return description: **self**  
Scope: **Public**  
Description: **if you need to deal with arrays, this will convert back and forwards from JS to vba**  

*Public Function addArraySupport() As cJavaScript*  

**no arguments required for this procedure**


---
VBA Procedure: **removeHtmlEscape**  
Type: **Function**  
Returns: **String**  
Return description: ****  
Scope: **Public**  
Description: ****  

*Public Function removeHtmlEscape(t As String) As String*  

*name*|*type*|*optional*|*default*|*description*
---|---|---|---|---
t|String|False||


---
VBA Procedure: **removeScriptTags**  
Type: **Function**  
Returns: **[cJavaScript](/scripts/cJavaScript_cls.md "cJavaScript")**  
Return description: **self**  
Scope: **Public**  
Description: **apps script sometimes have script tags**  

*Public Function removeScriptTags() As cJavaScript*  

**no arguments required for this procedure**


---
VBA Procedure: **Class_Initialize**  
Type: **Sub**  
Returns: **void**  
Return description: ****  
Scope: **Private**  
Description: ****  

*Private Sub Class_Initialize()*  

**no arguments required for this procedure**
