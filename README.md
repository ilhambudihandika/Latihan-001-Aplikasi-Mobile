# Latihan-001-Aplikasi-Mobile

void main() {
  String nama = 'Deny';
  int umur = 20;
  double tinggi = 170.5;
  bool mahasiswaAktif = true;

  print(nama);
  print(umur);
  print(tinggi);
  print(mahasiswaAktif);
  
  //------------------------------------
  
  String? namaTeman = 'Rapli';

  print(namaTeman);

  namaTeman = null;

  print(namaTeman);
  
  final String namaKampus = 'Institut Global';

  print(namaKampus);
  
  const int semester = 3;

  print(semester);
  
  String namamahasiswa = 'Deny';

  print(namamahasiswa.toUpperCase());
  
  int jumlahTeman = 5;

  print(jumlahTeman);
  
  double nilaiUjian = 85.5;

  print(nilaiUjian);
  
  bool sudahMengerjakanTugas = true;

  print(sudahMengerjakanTugas);
  
  List<String> mataKuliah = [
    'Matematika',
    'Pemrograman',
    'Aplikasi Mobile'
  ];

  print(mataKuliah);
  
  String namasaya = 'Deny';
  int semestersaya = 3;

  print('Nama saya $namasaya, semester $semestersaya');
}
