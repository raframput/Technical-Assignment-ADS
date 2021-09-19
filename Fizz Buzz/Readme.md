//Inisialisasi Variabel
<br>
integer n;
<br>
string hasil;

//eksekusi input
<br>
input n;

//eksekusi input dan proses
<br>
for {int i=0; i < 10; i++}{
    <br>
    if(i % 3 == 0){
        <br>
        print hasil = "Fizz";
        <br>
    }else if (i % 5 == 0){
        <br>
        print hasil = "Buzz";
        <br>
    }else if( i % 3 == 0 && i % 5 == 0){
        <br>
        print hasil = "FizzBuzz";
        <br>
    }else{
        <br>
        print hasil = i
        <br>
    }