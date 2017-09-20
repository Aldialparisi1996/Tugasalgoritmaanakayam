# Tugas_algoritma_anak_ayam
Aldi Alparisi Pratama Sistem Informasi Semester 1

program menghitung_lagu_anak_ayam;
uses crt;
var
x:integer;
Begin
clrscr;
write('masukkan anak ayam yang turun:');
readln(x);
while x >= 1 do
begin
writeln('anak ayam turun ',x,' mati 1 tinggal ',x-1,' ');
x:= x-1;
end;
writeln('anak ayam mati semua yang ada tinggal induknya');
readln;
end.
