<?php
//Luas lingkaran
echo "<h1>". "Tugas Menghitung luas dan volume bangun menggunakan PHP" . "</h1>";
$panjang = 15 ;
$lebar = 10 ;
$luas = $panjang * $lebar ;
 
echo "1. " . " Luas persegi panjang dengan panjang " . $panjang ."cm". "<br>" . " dan lebar " . $lebar ."cm"." adalah ". "...cm". "<br>" . "Jawab = " . "<br>" . 
" Diketahui " . "<br>" . "a) Panjang= " . $panjang . "cm" . "<br>" .
"b) Lebar= " . $lebar . "cm". "<br>" . "#Luas persegi panjang = panjang x lebar " . "<br>" ."#" . $panjang . " x " . $lebar . "=" . "<br>" . 
"=" . $panjang * $lebar . "cm2" . "<br>" ;
$volume= $panjang * $lebar * $tinggi ;
$tinggi= 20 ;
echo "2. " . " Volume balok dengan panjang " . $panjang . "cm". "<br>" . " lebar " . $lebar . "cm". "<br>" . " tinggi " . $tinggi . "cm". "<br>" . "Jawab = " . "<br>" .
" Diketahui " . "<br>" . "a) Panjang= " . $panjang . "cm" . "<br>" .
"b) Lebar= " . $lebar . "cm". "<br>" . 
"c) Tinggi= " . $tinggi . "cm". "<br>" . "#Volume balok = panjang x lebar x tinggi " . "<br>" . "#" . $panjang . " x " . $lebar . " x " . $tinggi . "=" . "<br>" .
"=" . $panjang * $lebar * $tinggi . "cm3" . "<br>" ;
$keliling= (2*$panjang) + (2*$lebar) ;
echo "3. " . " Keliling persegi panjang dengan panjang " . $panjang . "cm". "<br>" . " lebar " . $lebar . "cm". "<br>" . "Jawab = " . "<br>" .
" Diketahui " . "<br>" . "a) Panjang= " . $panjang . "cm" . "<br>" .
"b) Lebar= " . $lebar . "cm". "<br>" . "#Keliling persegi panjang = (2xpanjang) + (2xlebar) " . "<br>" . "#" . "2x" . $panjang . " + " . "2x" . $lebar . "<br>" .
"=" . $keliling . "cm" . "<br>" ;
