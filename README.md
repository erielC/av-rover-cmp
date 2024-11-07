# av-rover-cmp

<h3>GUIDELINES for Setting up platform.IO</h3>
<ul>
  <li>Make sure that there is only ONE .cpp file in your source file when you compile because if you have more .cpp and they contain the setup() & loop() functions then it will get confused and return an error.</li>
  <li>If files need to be stored and your intention is not to compile them place it in the archive folder as compiler only compiles src folder</li>
  <li>Unless your testing the code DO NOT place anything inside the test folder</li>
  <li>Any header files that you have written place them into the include folder as platformIO determines that's where the header files go</li>
</ul>
