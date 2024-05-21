<?php
$_SESSION[$_POST['input']] = true;

$inputA = $_POST['input’];
$_SESSION[$inputA] = true;
$inputB = $_POST['input'];
$inputB = sha256($inputB);
$_SESSION[$inputB] = true;
