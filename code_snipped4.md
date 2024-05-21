<?php
$stringVariable = "строка";
$intVariable = 1;

eval($user_input);
eval('echo “done"');

eval($intVariable);
eval($stringVariable);

eval(f"some_func({user_input})");
eval("x = 1; x = x + 1");
eval(f"x = 1; x = x + 1");
