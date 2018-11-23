Program Kalkulator Sederhana

1.) float tambah (float a, float b){
	- Inisialiasi fungsi tambah, tipe data menggunakan float
    return ( a + b );}
    - masukan rumus fungsi tambah (a + b)
-------------------------------------------------------------
    float kurang (float a, float b){
    - Inisialiasi fungsi kurang, tipe data menggunakan float
	return ( a - b );}
    - masukan rumus fungsi kurang (a - b)
-------------------------------------------------------------
    float kali (float a, float b){
    - Inisialiasi fungsi kali, tipe data menggunakan float
	return ( a * b );}
    - masukan rumus fungsi kali (a * b)
-------------------------------------------------------------
    float bagi (float a, float b){
    - Inisialiasi fungsi bagi, tipe data menggunakan float
	return (a / b );}
	- masukan rumus fungsi bagi (a / b)

2.) int main()
    {
    float bila, bilb;
    int pilihan;
    - Inisialisai main program
    - Tipe data bila, bilb : float |====| tipe data pilihan : integer

3.) cout<<"Masukan bilangan A : ";cin>>bila;
    cout<<"Masukan bilangan B : ";cin>>bilb;

    - Masukan bilangan a dan b

4.)

    do {
        cout<<endl;
        cout<<"Pilihlah operasinya :"<<endl;    |
        cout<<"1. Penjumlahan"<<endl;           |
        cout<<"2. Pengurangan"<<endl;           | Tampilah keterangan untuk
        cout<<"3. Perkalian"<<endl;             | memilih operasi hitung
        cout<<"4. Pembagian"<<endl;             |
        cout<<"0. Keluar dari aplikasi"<<endl;  |

        cout<<"Masukkan pilihan : ";            |Inputkan Pilihan
        cin>>pilihan;cout<<endl;                |

        switch(pilihan)                         | Pernyataan switch untuk pilihan
        {
        case 1 :
           cout<<"Hasil Penjumlahan dari "<<bila<<" + "<<bilb<<" adalah : "<<tambah(bila,bilb);
           break;
        - Jika diinputkan angka 1 maka yg dikerjakan operasi penjumlahan

        case 2 :
           cout<<"Hasil Pengurangan dari "<<bila<<" - "<<bilb<<" adalah : "<<kurang(bila,bilb);
           break;
        - Jika diinputkan angka 2 maka yg dikerjakan operasi pengurangan

        case 3 :
           cout<<"Hasil Perkalian dari "<<bila<<" x "<<bilb<<" adalah : "<<kali(bila,bilb);
           break;
        - Jika diinputkan angka 3 maka yg dikerjakan operasi perkalian

        case 4 :
           cout<<"Hasil Pembagian dari "<<bila<<" / "<<bilb<<" adalah : "<<bagi(bila,bilb);
           break;
        - Jika diinputkan angka 4 maka yg dikerjakan operasi pembagian

        case 0 :
            cout<<"Closing Program... ";
           break;
        - Jika diinputkan angka 0 maka print Closing Program...

        default :
            cout<<"Invalid Menu ";
        - Jika diinputkan angka selain di atas maka print Invalid Menu

        }cout<<endl;

    }
    while(pilihan!=0);

    - terdapat perulangan do while dengan penjelasan jika pilihan selain 0 maka akan
      tetap terus berulang sampai diinputkan 0

Berikut Flowchartnya : </br>
![alt text](https://raw.githubusercontent.com/arkyana/Praktikum6/master/img/flowchart.png)

Berikut Hasil Screenshotnya : </br>
![alt text](https://raw.githubusercontent.com/arkyana/Praktikum6/master/img/ss.png)
