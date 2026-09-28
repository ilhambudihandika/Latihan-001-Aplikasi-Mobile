# Latihan-001-Aplikasi-Mobile

````dart

void main() {
  String namaHewan = 'Kucing';
  int umurHewan = 3;
  double beratHewan = 4.5;
  bool sudahDivaksin = true;

  print(namaHewan);
  print(umurHewan);
  print(beratHewan);
  print(sudahDivaksin);

  //------------------------------------

  String? warnaHewan = 'Putih';

  print(warnaHewan);

  warnaHewan = null;

  print(warnaHewan);

  final String namaPemilik = 'Ilham';

  print(namaPemilik);

  const int jumlahHewan = 2;

  print(jumlahHewan);

  String jenisHewan = 'kucing';

  print(jenisHewan.toUpperCase());

  int jumlahKaki = 4;

  print(jumlahKaki);

  double tinggiHewan = 30.5;

  print(tinggiHewan);

  bool sudahMakan = true;

  print(sudahMakan);

  List<String> makananHewan = [
    'Ikan',
    'Ayam',
    'Whiskas'
  ];

  print(makananHewan);

  String namaSaya = 'Ilham';
  String namaPeliharaan = 'Milo';

  print('Nama saya $namaSaya, nama hewan saya $namaPeliharaan');
}
