# Angular-2-Testing

<blockquote><!--block-->Why do you need Unit testing in javascript?</blockquote><div><!--block-->Javascript is a dynamic language. Unit testing helps to control the code bases, when the complexity of applica</div>

<blockquote><!--block-->Introduction</blockquote><div><!--block--><em>What does testing an application yields ?</em>&nbsp; &nbsp; &nbsp;</div><ol><li><!--block-->Clarifies implementation requirement.</li><li><!--block-->Guards against changes.</li><li><!--block-->Reveals the implementation and design.</li></ol><div><!--block--><br><br></div>
<blockquote><!--block-->Tools and Technologies</blockquote><div><!--block--><em>There are four technologies</em></div><ol><li><!--block-->Jasmine</li><li><!--block-->Angular Testing Utilities</li><li><!--block-->Karma&nbsp; &nbsp;</li><li><!--block-->Protractor</li></ol><div><!--block--><br></div>

<blockquote><!--block-->Jasmine</blockquote><div><!--block-->Jasmine is a behaviour driven javascript framework which is developed for javascript unit testing.</div><blockquote><!--block-->Key Constructs in Jasmine</blockquote><ol><li><!--block--><strong><em>describe</em></strong><ol><li><!--block-->It is a block which is used to logically group unit tests by name.</li><li><!--block-->Syntax :</li></ol></li></ol><pre><!--block-->describe("name_of_block_",function(){
// your testing code goes here
})</pre><div><!--block--><br>name_of_block- usually will be a name of the script file which you will be testing</div>
<blockquote><!--block-->Setup</blockquote><div><!--block--><em>Two ways to achieve it&nbsp;</em></div><ol><li><!--block-->Creating a local development environment using&nbsp;<a href="https://github.com/aravindfz/firstAngular2App">this</a></li><li><!--block-->Start a new CLI project</li></ol><div><!--block--><br></div>
<blockquote><!--block-->Isolated unit tests</blockquote><ul><li><!--block-->Examines an instance of a class without any dependence or any injected values. &nbsp;</li><li><!--block-->Written for only pipes and services (singletons).</li><li><!--block-->Should create instance of class.</li></ul>
