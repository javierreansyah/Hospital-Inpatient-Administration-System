import java.util.Scanner;

public class RawatInap {
    static int[] tanggal = {23, 11,2022};
    static int[] hargaKelas = {500000, 400000, 250000, 750000};
    static Object[][][][] dataPasien = new Object[][][][] {
            {
                    {
                            {"Nama panjang", "Intaha Irsani"},
                            {"Nama", "Irsa"},
                            {"Umur", "18"},
                            {"BPJS", "Tidak"},
                            {"Kelas", "1"},
                            {"Ruang", 4},
                            {"Kasur", 1},
                            {"Penyakit", "Demam Berdarah"},
                            {"Dokter", "dr. Robinson Pasaribu, Sp.BM"},
                            {"Tanggal Masuk", "20 November 2022"},
                            {"Obat", "Vitamin B12",1,7,500},
                            {"Obat", "Vitamin C",1,7,500},
                            {"Obat", "Paracetamol", 3,7,500}
                    }, {
                            {"Nama panjang", "Fatima Azzahra"},
                            {"Nama", "Azza"},
                            {"Umur", "17"},
                            {"BPJS", "Ya"},
                            {"Kelas", "1"},
                            {"Ruang", 1},
                            {"Kasur", 2},
                            {"Penyakit", "Asma"},
                            {"Dokter", "dr. M. Yusuf Wibisono"},
                            {"Tanggal Masuk", "21 November 2022"},
                            {"Obat", "Salbutamol", 3, 10, 500},
                            {"Obat", "Pulmicort", 2, 7, 500},
                            {"Obat", "Teosal", 2, 10, 500}
                    }, {
                            {"Nama panjang", "Haykal Dani Muhammad"},
                            {"Nama", "Dani"},
                            {"Umur", "17"},
                            {"BPJS", "Ya"},
                            {"Kelas", "1"},
                            {"Ruang", 2},
                            {"Kasur", 1},
                            {"Penyakit", "Leukimia"},
                            {"Dokter", "dr. M. Ary Firmanto, Sp.BM"},
                            {"Tanggal Masuk", "18 November 2022"},
                            {"Obat", " Gemtuzumab", 1, 10, 500},
                    }, {
                            {"Nama panjang", "Oyeng Mayong"},
                            {"Nama", "Oyeng"},
                            {"Umur", "30"},
                            {"BPJS", "Tidak"},
                            {"Kelas", "1"},
                            {"Ruang", 2},
                            {"Kasur", 2},
                            {"Penyakit", "Vertigo"},
                            {"{Dokter", "dr. Triastuti, Sp.A"},
                            {"Tanggal Masuk", "17 November 2022"},
                            {"Obat", "Entacavir", 2, 10, 500},
                            {"Obat", " Diphenhydramine",3, 10, 250},
                            {"Obat", "Benzodiazepine", 2, 10, 250},
                    }, {
                            {"Nama panjang", "Balqis Maul linda"},
                            {"Nama", "Linda"},
                            {"Umur", "22"},
                            {"BPJS", "Ya"},
                            {"Kelas", "1"},
                            {"Ruang", 3},
                            {"Kasur", 1},
                            {"Penyakit", "Tuberkulosis"},
                            {"Dokter", "dr. Hesti Puspasari, Sp.A,M.Kes"},
                            {"Tanggal Masuk", "17 November 2022"},
                            {"Obat", "Ethambutol", 1, 10, 500},
                            {"Obat", "Rifampicin", 3, 10, 215},
                            {"Obat", "Erabutol Plus", 3, 10, 215},
                    }
            }, {
                    {
                            {"Nama Panjang", "Shaggy Sulaiman"},
                            {"Nama", "Shaggy"},
                            {"Umur", 19},
                            {"BPJS", "Ya"},
                            {"Kelas", "2"},
                            {"Ruang", 1},
                            {"Kasur", 1},
                            {"Penyakit", "Pneumonia"},
                            {"Dokter", "dr. S Suwandi Sp.P"},
                            {"Tanggal Masuk", "16 November 2022"},
                            {"Obat", "Ibuprofen", 3, 5, 272},
                            {"Obat", "Antivirus", 3, 5, 720},
                    }, {
                            {"Nama Panjang", "Toby Tobuskus"},
                            {"Nama", "Toby"},
                            {"Umur", 22},
                            {"BPJS", "Ya"},
                            {"Kelas", "2"},
                            {"Ruang", 1},
                            {"Kasur", 2},
                            {"Penyakit", "Infeksi cacing usus"},
                            {"Dokter", "dr. Herry Purbayu, Sp.PD, K-GEH"},
                            {"Tanggal Masuk", "19 November 2022"},
                            {"Obat", "Mebendazoler", 3, 5, 20},
                            {"Obat", "Albendazole", 3, 5, 812},
                    }, {
                            {"Nama Panjang", "Jeffery Epsilon"},
                            {"Nama", "Jeff"},
                            {"Umur", 40},
                            {"BPJS", "Ya"},
                            {"Kelas", "2"},
                            {"Ruang", 1},
                            {"Kasur", 3},
                            {"Penyakit", "Patah Tulang"},
                            {"Dokter", "dr. Johan Bastian, Sp.OT"},
                            {"Tanggal Masuk", "18 November 2022"},
                            {"Tindakan", "Operasi patah tulang"},
                            {"Detail Tindakan",  "Pembedahan dan pengembalian posisi semula"},
                            {"Biaya Tindakan", 20000000},
                            {"Tanggal Tindakan", "19 November 2022"},
                            {"Obat", "Ketoprofen", 3, 3, 550},
                            {"Obat", "Gentamicin", 3, 4, 1000},
                    }
            }, {
                    {
                            {"Nama Panjang", "Jack Sparrow"},
                            {"Nama", "Sparrow"},
                            {"Umur", "27"},
                            {"BPJS", "Ya"},
                            {"Kelas", "3"},
                            {"Ruang", 1},
                            {"Kasur", 1},
                            {"Penyakit", "Ambeien"},
                            {"Dokter", "dr. Syifa Mustika, Sp.PD-KGEH"},
                            {"Tanggal Masuk", "20 November 2022"},
                            {"Obat", "Venomsil", 3, 5, 14500},
                            {"Obat", "Ardium" , 3, 5, 10500},
                    }, {
                            {"Nama Panjang", "Jennie Depp"},
                            {"Nama", "Jennie"},
                            {"Umur", "14"},
                            {"BPJS", "Ya"},
                            {"Kelas", "3"},
                            {"Ruang", 1},
                            {"Kasur", 2},
                            {"Penyakit", "Demam Berdarah"},
                            {"Dokter", "Dr. A. Heri Susanto, Sp.PD"},
                            {"Tanggal Masuk", "21 November 2022"},
                            {"Obat", "Paracetamol" , 3, 5, 1200},
                            {"Obat", "Domperidone" , 3, 5, 571},
                    }, {
                            {"Nama Panjang", "Forrest Gump"},
                            {"Nama", "Gump"},
                            {"Umur", "20"},
                            {"BPJS", "Ya"},
                            {"Kelas", "3"},
                            {"Ruang", 1},
                            {"Kasur", 3},
                            {"Penyakit", "Demam Tifoid"},
                            {"Dokter", "dr. Syifa Mustika, Sp.PD-KGEH"},
                            {"Tanggal Masuk", "10 November 2022"},
                            {"Obat", "Daiticin" , 3, 5, 1789},
                            {"Obat", "Interflox" , 3, 5, 23983},
                    }, {
                            {"Nama Panjang", "Muhammad Rafie"},
                            {"Nama", "Rafie"},
                            {"Umur", "18"},
                            {"BPJS", "Ya"},
                            {"Kelas", "3"},
                            {"Ruang", 1},
                            {"Kasur", 4},
                            {"Penyakit", "Muntaber"},
                            {"Dokter", "dr. Syifa Mustika, Sp.PD-KGEH"},
                            {"Tanggal Masuk", "17 November 2022"},
                            {"Obat", "Oralit" , 3, 5, 648},
                            {"Obat", "Loperamid" , 3, 5, 229},
                    }, {
                            {"Nama Panjang", "Derrick Rose"},
                            {"Nama", "Rose"},
                            {"Umur", "21"},
                            {"BPJS", "Tidak"},
                            {"Kelas", "3"},
                            {"Ruang", 1},
                            {"Kasur", 5},
                            {"Penyakit", "ACL"},
                            {"Dokter", "Prof.Dr.dr. Moch. Hidayat,Sp.B,Sp.OT"},
                            {"Tanggal Masuk", "18 November 2022"},
                            {"Tindakan", "Operasi Anterior Cruciate ligament"},
                            {"Detail Tindakan", "Robek Ligamen Lutut"},
                            {"Biaya Tindakan", 6000000},
                            {"Obat", "Paracetamol" , 3, 5,  1200},
                    } , {
                            {"Nama Panjang", "Kobi Mikail"},
                            {"Nama", "Kobi"},
                            {"Umur", "24"},
                            {"BPJS", "Ya"},
                            {"Kelas", "3"},
                            {"Ruang", 1},
                            {"Kasur", 6},
                            {"Penyakit", "Usus Buntu"},
                            {"Dokter", "dr. Syifa Mustika, Sp.PD-KGEH"},
                            {"Tanggal Masuk", "16 November 2022"},
                            {"Tindakan", "Operasi Usus Buntu"},
                            {"Detail Tindakan", "Pemotongan Usus Buntu"},
                            {"Biaya Tindakan", 5000000},
                            {"Obat", "Paracetamol" , 3, 5, 1200},
                            {"Obat", "Oralit" , 3, 5, 648},
                    }, {
                            {"Nama Panjang", "Malik Monk"},
                            {"Nama", "Malik"},
                            {"Umur", "27"},
                            {"BPJS", "Ya"},
                            {"Kelas", "3"},
                            {"Ruang", 1},
                            {"Kasur", 7},
                            {"Penyakit", "Auto Imune"},
                            {"Dokter", "Dr. A. Heri Susanto, Sp.PD"},
                            {"Tanggal Masuk", "11 November 2022"},
                            {"Tindakan", "Operasi Autoimun"},
                            {"Detail Tindakan", "Mengobati Penyumbatan Di Usus"},
                            {"Biaya Tindakan", 20000000},
                            {"Obat", "aspirin" , 3, 5, 500},
                            {"Obat", "Ibuprofen" , 3, 5, 545},
                            {"Obat", "Naproxen" , 3, 5, 22500},
                    }
            }, {
                    {
                            {"Nama Panjang", "Niki Minaj"},
                            {"Nama", "Niki"},
                            {"Umur", 19},
                            {"BPJS", "Ya"},
                            {"Kelas", "VIP"},
                            {"Ruang", 6},
                            {"Kasur", 1},
                            {"Penyakit", "Influenza tipe A"},
                            {"Dokter", "dr. Wilma Agustina, Sp.BPRE, Subsp. MO (K)"},
                            {"Tanggal Masuk", "20 November 2022"},
                            {"Obat", "Oseltamivir", 3, 5, 21},
                            {"Obat", "Antihistamin", 3, 5, 558},
                    }, {
                            {"Nama Panjang", "Lili Pichu"},
                            {"Nama", "Lili"},
                            {"Umur", 22},
                            {"BPJS", "Ya"},
                            {"Kelas", "VIP"},
                            {"Ruang", 2},
                            {"Kasur", 1},
                            {"Penyakit", "Infeksi cacing usus"},
                            {"Dokter", "dr. Ulfa Kholili, Sp.PD-KGEH"},
                            {"Tanggal Masuk", "17 November 2022"},
                            {"Obat", "Mebendazoler", 3, 5, 20},
                            {"Obat", "Albendazole", 3, 5, 812},
                    }, {
                            {"Nama Panjang", "Michael Tison"},
                            {"Nama", "Mike"},
                            {"Umur", "40"},
                            {"BPJS", "Ya"},
                            {"Kelas", "VIP"},
                            {"Ruang", 3},
                            {"Kasur", 1},
                            {"Penyakit", "Pergeseran Tulang"},
                            {"Dokter", "Dr. dr. Panji Sananta, Sp.OT, M.Ked"},
                            {"Tanggal Masuk", "21 November 2022"},
                            {"Tindakan", "Operasi patah tulang"},
                            {"Detail Tindakan",  "Pengembalian posisi tulang"},
                            {"Biaya Tindakan", 20000000},
                            {"Tanggal Tindakan", "22 November 2022"},
                            {"Obat", "Ketoprofen", 1, 3, 550},
                            {"Obat", "Gentamicin", 3, 4, 1000},
                            {"Obat", "Ibuprofen", 3, 5, 272},
                    }
            }
    };

    public static void login() {
        String[][] loginInfo = {
                {"owner", "owner123"},
                {"1", "1"},
                {"456112", "48001"},
                {"javier", "cerdas"},
        };
        Scanner inputData = new Scanner(System.in);
        String userIdLogin, passwordLogin, stringOutput = null;
        int opsiLogin, hitunganCobaLogin;
        boolean kondisiPilihanLoginUlang;
        boolean berhasilLogin = false;
        do {
            hitunganCobaLogin = 0;
            System.out.println("\nSilahlan login terlebih dahulu!");
            System.out.print("UserId: ");
            userIdLogin = inputData.next();
            System.out.print("Password: ");
            passwordLogin = inputData.next();

            for (int i = 0; i < loginInfo.length; i++) {
                if (userIdLogin.equals(loginInfo[i][0]) && (passwordLogin.equals(loginInfo[i][1]))) {
                    stringOutput ="Anda Berhasil Login";
                    berhasilLogin = true;
                    break;
                } else if (userIdLogin.equals(loginInfo[i][0])) {
                    hitunganCobaLogin++;
                    stringOutput = "Password Salah!";
                } else if (passwordLogin.equals(loginInfo[i][1])) {
                    hitunganCobaLogin++;
                    stringOutput = "UserID Salah!";
                } else if (!userIdLogin.equals(loginInfo[i][0]) && (!passwordLogin.equals(loginInfo[i][1])) && hitunganCobaLogin == 0) {
                    stringOutput = "UserID dan Password Salah!";
                }
            }
            if (hitunganCobaLogin <= 1) {
                System.out.println(stringOutput);
            } else {
                System.out.println("User ID atau Password Salah!");
            }

            if (!berhasilLogin) {
                System.out.println("[1] untuk mencoba lagi");
                System.out.println("[2] untuk keluar");

                kondisiPilihanLoginUlang = true;
                while (kondisiPilihanLoginUlang) {
                    System.out.print("Input: ");
                    opsiLogin = inputData.nextInt();
                    switch (opsiLogin) {
                        case 1:
                            kondisiPilihanLoginUlang = false;
                            break;
                        case 2:
                            System.out.println("Anda Telah Keluar dari Program");
                            System.exit(1);
                            break;
                        default:
                            System.out.println("Input Salah, coba lagi!");
                            break;
                    }
                }
            }
        } while (!berhasilLogin);
    }
    public static void printBiodataPasien(int kelas, int nomerPasien) {
        boolean sudahObat = false;
        if (kelas < dataPasien.length && nomerPasien < dataPasien[kelas].length) {
            System.out.println(" ");
            System.out.println("==================================================================");
            System.out.println("                          BIODATA PASIEN");
            System.out.println("==================================================================");
            for (int i = 0; i < dataPasien[kelas][nomerPasien].length; ++i) {
                if (dataPasien[kelas][nomerPasien][i][0].equals("Obat")) {
                    if (!sudahObat) {
                        System.out.println("==================================================================");
                        System.out.println("                       DAFTAR MEDIKASI PASIEN");
                        System.out.println("==================================================================");
                        sudahObat = true;
                    }
                    System.out.printf("%-20s : %dx untuk %d hari\n", dataPasien[kelas][nomerPasien][i][1], (int) dataPasien[kelas][nomerPasien][i][2], (int) dataPasien[kelas][nomerPasien][i][3]);
                } else {
                    System.out.printf("%-20s : ", dataPasien[kelas][nomerPasien][i][0]);
                    System.out.print(dataPasien[kelas][nomerPasien][i][1] + "\n");
                }
            }
            System.out.println("==================================================================");
        } else {
            System.out.println("\nData Pasien Tidak Ada\n");
        }
    }
    public static void printNotaPasien(int kelas, int nomorPasien) {
        int totalBiaya = 0;
        int totalHariOpname = lamaOpname((String) dataPasien[kelas][nomorPasien][9][1]);
        int totalBiayaOpname = totalHariOpname * hargaKelas[kelas];
        totalBiaya += totalBiayaOpname;
        System.out.println("\n======================================================");
        System.out.println("                     NOTA PASIEN");
        System.out.println("======================================================");
        System.out.printf("Nama Pasien   : %s\n", dataPasien[kelas][nomorPasien][0][1]);
        System.out.printf("Kelas         : %s\n", dataPasien[kelas][nomorPasien][5][1]);
        System.out.printf("BPJS          : %s\n", dataPasien[kelas][nomorPasien][3][1]);
        System.out.printf("Tanggal Masuk : %s\n", dataPasien[kelas][nomorPasien][9][1]);
        System.out.printf("Lama Opname   : %d hari\n", totalHariOpname);
        System.out.println("======================================================");
        System.out.printf("Opname                   : Rp%,d\n", totalBiayaOpname);
        int totalHargaObat;
        for(int i = 0; i < dataPasien[kelas][nomorPasien].length; i++) {
            if(dataPasien[kelas][nomorPasien][i][0].equals("Tindakan")) {
                System.out.printf("%-24s : Rp%,d\n", dataPasien[kelas][nomorPasien][i][1], (int) dataPasien[kelas][nomorPasien][i + 2][1]);
                totalBiaya += (int) dataPasien[kelas][nomorPasien][i + 2][1];
            } else if(dataPasien[kelas][nomorPasien][i][0].equals("Obat")) {
                totalHargaObat = (int) dataPasien[kelas][nomorPasien][i][2] * (int) dataPasien[kelas][nomorPasien][i][3] * (int) dataPasien[kelas][nomorPasien][i][4];
                System.out.printf("%-24s : Rp%,d\n", dataPasien[kelas][nomorPasien][i][1], totalHargaObat);
                totalBiaya += totalHargaObat;
            }
        }
        System.out.println("======================================================");
        String BPJS = (String) dataPasien[kelas][nomorPasien][3][1];
        if (BPJS.equals("Ya")) {
            System.out.printf("TOTAL BIAYA              : Rp%,d\n", totalBiaya);
            System.out.println("TOTAL YANG HARUS DIBAYAR : Rp0,00");
        } else {
            System.out.printf("TOTAL BIAYA              : Rp%,d\n", totalBiaya);
        }
        System.out.println("======================================================");
    }
    public static int[] translateTanggalMasuk(String tanggalString) {
        String[] tanggalPisah = tanggalString.split(" ");
        int bulanAngka = 0;
        switch (tanggalPisah[1]) {
            case "Januari": bulanAngka = 1; break;
            case "Februari": bulanAngka = 2; break;
            case "Maret": bulanAngka = 3; break;
            case "April": bulanAngka = 4; break;
            case "Mei": bulanAngka = 5; break;
            case "Juni": bulanAngka = 6; break;
            case "Juli": bulanAngka = 7; break;
            case "Agustus": bulanAngka = 8; break;
            case "September": bulanAngka = 9; break;
            case "Oktober": bulanAngka = 10; break;
            case "November": bulanAngka = 11; break;
            case "Desember": bulanAngka = 12; break;
        }
        int[] tanggalAngka = new int[3];
        tanggalAngka[0] = Integer.parseInt(tanggalPisah[0]);
        tanggalAngka[1] = bulanAngka;
        tanggalAngka[2] = Integer.parseInt(tanggalPisah[2]);
        return tanggalAngka;
    }
    public static int bulanHari(int bln, int thn) {
        int jumlahHari = 0;
        if (bln == 1) {
            jumlahHari = 31;
        } else if (bln == 2) {
            if (thn % 4 == 0) {
                jumlahHari = 29;
            } else {
                jumlahHari = 28;
            }
        } else if (bln == 3) {
            jumlahHari = 31;
        } else if (bln == 4) {
            jumlahHari = 30;
        } else if (bln == 5) {
            jumlahHari = 31;
        } else if (bln == 6) {
            jumlahHari = 30;
        } else if (bln == 7) {
            jumlahHari = 31;
        } else if (bln == 8) {
            jumlahHari = 31;
        } else if (bln == 9) {
            jumlahHari = 30;
        } else if (bln == 10) {
            jumlahHari = 31;
        } else if (bln == 11) {
            jumlahHari = 30;
        } else if (bln == 12) {
            jumlahHari = 31;
        }
        return jumlahHari;
    }
    public static int lamaOpname(String tanggalMasukString) {
        int[] tanggalMasuk = translateTanggalMasuk(tanggalMasukString);
        int hari = tanggalMasuk[0];
        int bulan = tanggalMasuk[1];
        int tahun = tanggalMasuk[2];
        int hariSekarang = tanggal[0];
        int bulanSekarang = tanggal[1];
        int tahunSekarang = tanggal[2];
        int jumlahHari = 0;
        while (tahun <= tahunSekarang) {
            while (bulan < bulanSekarang - 1 || tahun < tahunSekarang) {
                if (bulan == 13) {
                    bulan = 1;
                    tahun++;
                }
                jumlahHari += bulanHari(bulan, tahun);
                bulan++;
            }
            if (bulan == bulanSekarang && tahun == tahunSekarang) {
                while(hari < hariSekarang) {
                    hari++;
                    jumlahHari++;
                }
            }
            if (bulan == bulanSekarang - 1 && tahun == tahunSekarang) {
                while (hari <= bulanHari(bulan, tahun)) {
                    hari++;
                    jumlahHari++;
                }
                hari = 1;
                while (hari < hariSekarang) {
                    hari++;
                    jumlahHari++;
                }
            }
            tahun++;
        }
        return jumlahHari;
    }
    public static void layananDataPasien() {
        Scanner inputData = new Scanner(System.in);
        boolean kondisiLayananDataPasien = true;
        boolean kondisiPilihanLayananDataPasien;
        int pilihanKelas, nomerPasien, opsiLayananDataPasien;
        while (kondisiLayananDataPasien) {
            System.out.println("\nPilih Kelas!");
            System.out.println("[1] Kelas 1");
            System.out.println("[2] Kelas 2");
            System.out.println("[3] Kelas 3");
            System.out.println("[4] Kelas VIP");

            System.out.print("Input: ");
            pilihanKelas = inputData.nextInt();
            System.out.println("\n======\n");
            if (pilihanKelas <=4 && pilihanKelas >= 1) {
                switch (pilihanKelas) {
                    case 1:
                        System.out.println("Data Pasien Kelas 1:");
                        System.out.println("Jumlah Pasien: " + dataPasien[0].length);
                        for (int i = 0; i < dataPasien[0].length; ++i) {
                            System.out.printf("[%d] %s\n", (i + 1), dataPasien[0][i][0][1]);
                        }
                        break;
                    case 2:
                        System.out.println("Data Pasien Kelas 2:");
                        System.out.println("Jumlah Pasien: " + dataPasien[1].length);
                        for (int i = 0; i < dataPasien[1].length; ++i) {
                            System.out.printf("[%d] %s\n", (i + 1), dataPasien[1][i][0][1]);
                        }
                        break;
                    case 3:
                        System.out.println("Data Pasien Kelas 3:");
                        System.out.println("Jumlah Pasien: " + dataPasien[1].length);
                        for (int i = 0; i < dataPasien[2].length; ++i) {
                            System.out.printf("[%d] %s\n", (i + 1), dataPasien[2][i][0][1]);
                        }
                        break;
                    default:
                        System.out.println("Data Pasien Kelas VIP:");
                        System.out.println("Jumlah Pasien: " + dataPasien[1].length);
                        for (int i = 0; i < dataPasien[3].length; ++i) {
                            System.out.printf("[%d] %s\n", (i + 1), dataPasien[3][i][0][1]);
                        }
                        break;
                }
                kondisiPilihanLayananDataPasien = true;
                while (kondisiPilihanLayananDataPasien) {
                    System.out.println("\nOpsi");
                    System.out.println("[1] Buka Biodata Pasien");
                    System.out.println("[2] Cetak Nota Pembayaran");
                    System.out.println("[3] Buka Data Kelas Lain");
                    System.out.println("[4] Selesai");
                    System.out.print("Input: ");
                    opsiLayananDataPasien = inputData.nextInt();
                    switch (opsiLayananDataPasien) {
                        case 1:
                            System.out.print("Masukkan Nomer Pasien: ");
                            nomerPasien = inputData.nextInt();
                            printBiodataPasien((pilihanKelas - 1), (nomerPasien - 1));
                            break;
                        case 2:
                            System.out.print("Masukkan Nomer Pasien: ");
                            nomerPasien = inputData.nextInt();
                            printNotaPasien((pilihanKelas - 1), (nomerPasien - 1));
                            break;
                        case 3:
                            kondisiPilihanLayananDataPasien = false;
                            break;
                        case 4:
                            kondisiPilihanLayananDataPasien = false;
                            kondisiLayananDataPasien = false;
                            break;
                        default:
                            System.out.println("Input Salah");
                    }
                }
            } else {
                System.out.println("Input Salah");
            }
        }
    }
    public static void layananPencarianPasien() {
        Scanner inputData = new Scanner(System.in);
        String namaDicari;
        int opsiPencarianPasien;
        boolean kondisiLayananPencarianPasien = true;
        boolean kondisiOpsiPencarianPasien = true;
        while(kondisiLayananPencarianPasien) {
            boolean namaDitemukan = false;
            System.out.print("Masukan Nama: ");
            namaDicari = inputData.nextLine();
            for (int i = 0; i < dataPasien.length; ++i) {
                for (int j = 0; j < dataPasien[i].length; ++j) {
                    if (namaDicari.equals(dataPasien[i][j][0][1]) || namaDicari.equals(dataPasien[i][j][1][1])) {
                        namaDitemukan = true;
                        kondisiOpsiPencarianPasien = true;
                        System.out.println("\nData Pasien Ditemukan");
                        System.out.println("Nama Pasien: " + dataPasien[i][j][0][1]);
                        System.out.println("\nOpsi");
                        System.out.println("[1] Cetak Biodata");
                        System.out.println("[2] Cetak Nota Pembayaran");
                        while(kondisiOpsiPencarianPasien) {
                            System.out.print("Input: ");
                            opsiPencarianPasien = inputData.nextInt();
                            inputData.nextLine();
                            switch(opsiPencarianPasien) {
                                case 1:
                                    printBiodataPasien(i, j);
                                    kondisiOpsiPencarianPasien = false;
                                    break;
                                case 2:
                                    printNotaPasien(i, j);
                                    kondisiOpsiPencarianPasien = false;
                                    break;
                                default:
                                    System.out.println("Input Salah!");
                            }
                        }
                        System.out.println(" ");
                    }
                }
            }
            if (!namaDitemukan) {
                System.out.println("\nNama tidak ditemukan\n");
            }
            int pilihanOpsiPencarianPasien;
            boolean kondisiOpsiLayananPencarianPasien = true;
            while(kondisiOpsiLayananPencarianPasien) {
                System.out.println("Opsi");
                System.out.println("[1] Cari Pasien Lain");
                System.out.println("[2] Selesai");
                System.out.print("input: ");
                pilihanOpsiPencarianPasien = inputData.nextInt();
                inputData.nextLine();
                switch (pilihanOpsiPencarianPasien) {
                    case 1:
                        kondisiOpsiLayananPencarianPasien = false;
                        break;
                    case 2:
                        System.out.println("\nAnda Keluar dari Program Pencarian Pasien");
                        kondisiLayananPencarianPasien = false;
                        kondisiOpsiLayananPencarianPasien = false;
                        break;
                    default:
                        System.out.println("Input Salah\n");
                        break;
                }
            }
        }
    }
    public static void layananStatistik() {
        int jumlahPasienKelas1 = dataPasien[0].length;
        int jumlahPasienKelas2 = dataPasien[1].length;
        int jumlahPasienKelas3 = dataPasien[2].length;
        int jumlahPasienKelasVIP = dataPasien[3].length;
        int jumlahPasien = jumlahPasienKelas1 + jumlahPasienKelas2 + jumlahPasienKelas3 + jumlahPasienKelasVIP;
        int[][] dataRuangKelas1 = new int[dataPasien[0].length][2];
        int[][] dataRuangKelas2 = new int[dataPasien[1].length][2];
        int[][] dataRuangKelas3 = new int[dataPasien[2].length][2];
        int[] dataRuangKelasVIP = new int[dataPasien[3].length];
        for(int i = 0; i < dataPasien[0].length; i++) {
            dataRuangKelas1[i][0] = (int) dataPasien[0][i][5][1];
            dataRuangKelas1[i][1] = (int) dataPasien[0][i][6][1];
        }
        for(int i = 0; i < dataPasien[1].length; i++) {
            dataRuangKelas2[i][0] = (int) dataPasien[1][i][5][1];
            dataRuangKelas2[i][1] = (int) dataPasien[1][i][6][1];
        }
        for(int i = 0; i < dataPasien[2].length; i++) {
            dataRuangKelas3[i][0] = (int) dataPasien[2][i][5][1];
            dataRuangKelas3[i][1] = (int) dataPasien[2][i][6][1];
        }
        for(int i = 0; i < dataPasien[3].length; i++) {
            dataRuangKelasVIP[i] = (int) dataPasien[3][i][5][1];
        }
        String[][] ruang1 = new String[4][2];
        String[][] ruang2 = new String[1][6];
        String[][] ruang3 = new String[1][12];
        String[] ruangVIP = new String[6];
        for(int i = 0; i < ruang1.length; i++) {
            for(int j = 0; j < ruang1[i].length; j++) {
                ruang1[i][j] = "O";
            }
        }
        for(int i = 0; i < ruang2.length; i++) {
            for(int j = 0; j < ruang2[i].length; j++) {
                ruang2[i][j] = "O";
            }
        }
        for(int i = 0; i < ruang3.length; i++) {
            for(int j = 0; j < ruang3[i].length; j++) {
                ruang3[i][j] = "O";
            }
        }
        for(int i = 0; i < ruangVIP.length; i++) {
            ruangVIP[i] = "O";
        }
        //isi data

        for(int i = 0; i < dataRuangKelas1.length; i++) {
            ruang1[dataRuangKelas1[i][0] - 1][dataRuangKelas1[i][1] - 1] = "X";
        }
        for(int i = 0; i < dataRuangKelas2.length; i++) {
            ruang2[dataRuangKelas2[i][0] - 1][dataRuangKelas2[i][1] - 1] = "X";
        }
        for(int i = 0; i < dataRuangKelas3.length; i++) {
            ruang3[dataRuangKelas3[i][0] - 1][dataRuangKelas3[i][1] - 1] = "X";
        }
        for(int i = 0; i < dataRuangKelasVIP.length; i++) {
            ruangVIP[dataRuangKelasVIP[i] - 1] = "X";
        }
        System.out.println("======================================================");
        System.out.println("                  STATISTIK RAWAT INAP");
        System.out.println("======================================================");
        System.out.println("Jumlah Pasien Aktif     : " + jumlahPasien);
        System.out.println("Kelas 1                 : " + jumlahPasienKelas1);
        System.out.println("Kelas 2                 : " + jumlahPasienKelas2);
        System.out.println("Kelas 3                 : " + jumlahPasienKelas3);
        System.out.println("Kelas VIP               : " + jumlahPasienKelasVIP);
        System.out.println("======================================================");
        System.out.println("                       DATA RUANG");
        System.out.println("======================================================");
        System.out.println("KELAS 1");
        System.out.println("======================================================");
        System.out.printf("%-12s | %-12s | %-12s | %-12s\n", "RUANG 1", "RUANG 2", "RUANG 3", "RUANG 4");
        System.out.printf("[1] : %-6s | [1] : %-6s | [1] : %-6s | [1] : %-6s\n", ruang1[0][0], ruang1[1][0], ruang1[2][0], ruang1[3][0]);
        System.out.printf("[2] : %-6s | [2] : %-6s | [2] : %-6s | [2] : %-6s\n", ruang1[0][1], ruang1[1][1], ruang1[2][1], ruang1[3][1]);
        System.out.println("======================================================");
        System.out.println("KELAS 2");
        System.out.println("======================================================");
        System.out.printf("%-12s \n", "RUANG 1");
        System.out.printf("[1] : %-6s | [3] : %-6s | [5] : %-6s\n", ruang2[0][0], ruang2[0][2], ruang2[0][4]);
        System.out.printf("[2] : %-6s | [4] : %-6s | [6] : %-6s\n", ruang2[0][1], ruang2[0][3], ruang2[0][5]);
        System.out.println("======================================================");
        System.out.println("KELAS 3");
        System.out.println("======================================================");
        System.out.printf("%-12s \n", "RUANG 1");
        System.out.printf("[1] : %-6s | [4] : %-6s | [7] : %-6s | [10] : %-6s\n", ruang3[0][0], ruang3[0][3], ruang3[0][6], ruang3[0][9]);
        System.out.printf("[2] : %-6s | [5] : %-6s | [8] : %-6s | [11] : %-6s\n", ruang3[0][1], ruang3[0][4], ruang3[0][7], ruang3[0][10]);
        System.out.printf("[3] : %-6s | [6] : %-6s | [9] : %-6s | [12] : %-6s\n", ruang3[0][2], ruang3[0][5], ruang3[0][8], ruang3[0][11]);
        System.out.println("======================================================");
        System.out.println("KELAS VIP");
        System.out.println("======================================================");
        System.out.printf("[1] : %-6s | [3] : %-6s | [5] : %-6s\n", ruangVIP[0], ruangVIP[2], ruangVIP[4]);
        System.out.printf("[2] : %-6s | [4] : %-6s | [6] : %-6s\n", ruangVIP[1], ruangVIP[3], ruangVIP[5]);
        System.out.println("======================================================");
    }
    public static void layanan() {
        Scanner inputData = new Scanner(System.in);
        int opsiLayanan;
        boolean kondisiPilihanLayanan = true;
        while (kondisiPilihanLayanan) {
            System.out.println("\n======\n");
            System.out.println("Pilih Layanan");
            System.out.println("[1] Lihat Database Pasien");
            System.out.println("[2] Pencarian Pasien");
            System.out.println("[3] Statistik Rawat Inap");
            System.out.println("[4] Keluar dari Program");
            System.out.print("Input: ");

            opsiLayanan = inputData.nextInt();
            switch (opsiLayanan) {
                case 1:
                    System.out.println("\n======\n");
                    System.out.println("Anda memilih layanan Lihat Database Pasien");
                    layananDataPasien();
                    break;
                case 2:
                    System.out.println("\n======\n");
                    System.out.println("Anda memilih layanan Pencarian Pasien");
                    layananPencarianPasien();
                    break;
                case 3:
                    System.out.println("\n======\n");
                    layananStatistik();
                    break;
                case 4:
                    kondisiPilihanLayanan = false;
                    System.out.println("\n======\n");
                    System.out.println("Anda memilih Keluar dari Program");
                    break;
                default:
                    System.out.println("Input Salah Coba Lagi\n");
                    break;
            }
        }
    }
    public static void main(String[] args) {
        System.out.println("Selamat Datang di Sistem Layanan\nRawat Inap RS FILKOM");
        login();
        layanan();
        System.out.println("\nProgram Selesai");
    }
}
