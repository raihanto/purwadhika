# Perpustakaan Adhi Raihanto

library = {
        'harrypotter1'  :   {'ID.':'0001',
                            'Judul Buku':'HP & The Goblet of Fire',
                            'Genre Buku':'Fiction',
                            'Nama Penulis':'J. K. Rowling',
                            'Status Peminjaman':'Sedang Dipinjam'},

        'harrypotter2'  :   {'ID.':'0002',
                            'Judul Buku':'HP & the Sorcerer Stone',
                            'Genre Buku':'Fiction',
                            'Nama Penulis':'J. K. Rowling',
                            'Status Peminjaman':'Tidak Sedang Dipinjam'},

        'richdadpoordad':   {'ID.':'0003',
                            'Judul Buku':'Rich Dad Poor Dad by RK',
                            'Genre Buku':'Finance',
                            'Nama Penulis':'R. Kiyosaki',
                            'Status Peminjaman':'Sedang Dipinjam'},

        'thealchemist'  :   {'ID.':'0004',
                            'Judul Buku':'The Alchemist - O Alquimista',
                            'Genre Buku':'Drama Fict',
                            'Nama Penulis':'Paulo Coelho',
                            'Status Peminjaman':'Sedang Dipinjam'},
}

def tampilseluruh():
    if len(library) == 0:
        print('Tidak ada data')
    else:
        print('')
        print('Berikut seluruh data Perpustakaan Adhi Raihanto:')
        print('ID. \t|Judul Buku \t\t\t|Genre Buku \t|Nama Penulis \t|Status Peminjaman')
        for key in library.keys():
            print('{} \t|{} \t|{} \t|{} \t|{}\t'.format(library[key]['ID.'], library[key]['Judul Buku'],library[key]['Genre Buku'],library[key]['Nama Penulis'],library[key]['Status Peminjaman']))

def lihatdata():
    while len(library) == 0:
        print('Tidak ada data')
        break
    else:
        while True:
            pilihFilter = int(input('\n- Perpustakaan Adhi Raihanto -\n\n[1] Filter berdasarkan genre buku\n[2] Filter berdasarkan status peminjaman\n[0] Kembali ke menu utama\n\nPilih menu yang anda inginkan:'))
            if pilihFilter == 1:
                pilihFilterGenre = int(input('\n- Perpustakaan Adhi Raihanto -\n\nSilahkan masukkan pilihan sesuai dengan genre yang anda inginkan: \n[1] Fiction\n[2] Drama Fiction\n[3] Finance\n[0] Kembali ke menu utama\n\nSilahkan masukkan pilihan anda: '))
                if pilihFilterGenre == 1:
                    print('Filter berdasarkan genre Fiction')
                    print('')
                    print('ID. \t|Judul Buku \t\t\t|Genre Buku \t|Nama Penulis \t|Status Peminjaman')
                    for key in library.keys():
                        if library[key]['Genre Buku'] == 'Fiction':
                            print('{} \t|{} \t|{} \t|{} \t|{}\t'.format(library[key]['ID.'], library[key]['Judul Buku'],library[key]['Genre Buku'],library[key]['Nama Penulis'],library[key]['Status Peminjaman']))
                        else:
                            continue
                elif pilihFilterGenre == 2:
                    print('Filter berdasarkan genre Drama Fiction')
                    print('')
                    print('ID. \t|Judul Buku \t\t\t|Genre Buku \t|Nama Penulis \t|Status Peminjaman')
                    for key in library.keys():
                        if library[key]['Genre Buku'] == 'Drama Fict':
                            print('{} \t|{} \t|{} \t|{} \t|{}\t'.format(library[key]['ID.'], library[key]['Judul Buku'],library[key]['Genre Buku'],library[key]['Nama Penulis'],library[key]['Status Peminjaman']))
                        else:
                            continue
                elif pilihFilterGenre == 3:
                    print('Filter berdasarkan genre Finance')
                    print('')
                    print('ID. \t|Judul Buku \t\t\t|Genre Buku \t|Nama Penulis \t|Status Peminjaman')
                    for key in library.keys():
                        if library[key]['Genre Buku'] == 'Finance':
                            print('{} \t|{} \t|{} \t|{} \t|{}\t'.format(library[key]['ID.'], library[key]['Judul Buku'],library[key]['Genre Buku'],library[key]['Nama Penulis'],library[key]['Status Peminjaman']))
                        else:
                            continue
                elif pilihFilterGenre == 0:
                    break
                else:
                    print('Data tidak ditemukan.')
            elif pilihFilter == 2:
                pilihFilterStatus = int(input('\n- Perpustakaan Adhi Raihanto -\n\nSilahkan masukkan pilihan sesuai dengan status yang anda inginkan: \n\n[1] Sedang dipinjam\n[2] Sedang tidak dipinjam\n[0] Kembali ke menu utama\n\nSilahkan masukkan pilihan anda: '))
                if pilihFilterStatus == 1:
                    print('Filter berdasarkan status sedang dipinjam')
                    print('')
                    print('ID. \t|Judul Buku \t\t\t|Genre Buku \t|Nama Penulis \t|Status Peminjaman')
                    for key in library.keys():
                        if library[key]['Status Peminjaman'] == 'Sedang Dipinjam':
                            print('{} \t|{} \t|{} \t|{} \t|{}\t'.format(library[key]['ID.'], library[key]['Judul Buku'],library[key]['Genre Buku'],library[key]['Nama Penulis'],library[key]['Status Peminjaman']))
                        else:
                            continue
                elif pilihFilterStatus == 2:
                    print('Filter berdasarkan status sedang tidak dipinjam')
                    print('')
                    print('ID. \t|Judul Buku \t\t\t|Genre Buku \t|Nama Penulis \t|Status Peminjaman')
                    for key in library.keys():
                        if library[key]['Status Peminjaman'] == 'Tidak Sedang Dipinjam':
                            print('{} \t|{} \t|{} \t|{} \t|{}\t'.format(library[key]['ID.'], library[key]['Judul Buku'],library[key]['Genre Buku'],library[key]['Nama Penulis'],library[key]['Status Peminjaman']))
                        else:
                            continue
                elif pilihFilterStatus == 0:
                    break
                else:
                    print('Data tidak ditemukan.')
            elif pilihFilter == 0:
                break
            else:
                print('Menu tidak ditemukan')  

def menambah():
    while True:
        tampilseluruh()
        inputKeyword = input('Masukkan keyword yang anda inginkan: ')
        inputFunction = inputKeyword.replace(' ','')
        if inputFunction.lower() not in library.keys():
            print('Silahkan masukkan data buku yang ingin anda tambahkan')
            inputID = input('Masukkan ID. buku: ')
            inputJudul = input('Masukkan judul buku: ')
            inputGenre = input('Masukkan genre buku: ')
            inputPenulis = input('Masukkan nama penulis: ')
            inputStatus = input('Masukkan status peminjaman: ')
            confirmInput = input(f'Silahkan mengkonfirmasi data yang anda masukkan = {inputID},{inputJudul},{inputGenre},{inputPenulis},{inputStatus} Y/N: ')
            if confirmInput != 'Y':
                print('Data tidak dimasukkan library')
                break
            else:
                library[inputFunction.lower()]={'ID.' : inputID, 'Judul Buku': inputJudul,'Genre Buku': inputGenre,'Nama Penulis': inputPenulis,'Status Peminjaman': inputStatus}
                tampilseluruh()
                print('Buku baru telah ditambahkan ke dalam library')
                break
        else:
            print('Keyword yang anda inginkan telah ada di daftar buku')
            break

def mengupdate():
    updateLib = int(input('\n- Perpustakaan Adhi Raihanto -\n\nSilahkan masukkan pilihan menu sesuai dengan yang anda inginkan: \n[1] Melakukan update berdasarkan keyword\n[0] Kembali ke menu utama\n\nSilahkan masukkan pilihan anda:'))
    if updateLib == 1: 
        tampilseluruh()
        updateLib = input('Masukkan keyword data yang akan diupdate: ')
        updateBaru = updateLib.replace(' ',' ')
        while updateBaru.lower() in library.keys():
            pilihUpdate = int(input('\n- Perpustakaan Adhi Raihanto -\n\nSilahkan pilih apa yang ingin anda update:\n[1] ID. \n[2] Judul Buku \n[3] Genre Buku \n[4] Nama Penulis \n[5] Status Peminjaman. \n[0] Kembali ke menu utama\nSilahkan masukkan pilihan anda:'))
            if pilihUpdate == 1:    
                inputUpdateID = input('Masukkan ID baru: ')
                updateIDBaru = inputUpdateID.replace(' ','')
                while updateIDBaru.lower() in library.keys():
                    print('ID telah ada di database!')
                    inputUpdateID = input('Masukkan ID baru: ')
                    updateIDBaru = inputUpdateID.replace(' ','')
                confirmUpdateID= input('Apakah anda yakin akan melakukan update data? Y/N: ')
                if confirmUpdateID != 'Y':
                    break
                else:
                    library[updateIDBaru] = library[updateBaru.lower()]
                    del library[updateBaru.lower()]
                    library[updateIDBaru]['ID.'] = inputUpdateID
                    tampilseluruh()
                    print('\nID. telah diupdate dalam database')
                    break
            elif pilihUpdate == 2:
                updateJudul = input('Masukkan judul baru: ')
                confirmUpdateJudul= input('Apakah anda yakin akan melakukan update data? Y/N: ')
                if confirmUpdateJudul != 'Y':
                    break
                else:
                    library[updateBaru.lower()]['Judul Buku'] = updateJudul
                    tampilseluruh()
                    print('\nJudul buku telah diupdate dalam database')
                    break
            elif pilihUpdate == 3:
                updateGenre = input('Masukkan genre baru: ')
                confirmUpdateGenre= input('Apakah anda yakin akan melakukan update data? Y/N: ')
                if confirmUpdateGenre != 'Y':
                    break
                else:
                    library[updateBaru.lower()]['Genre Buku'] = updateGenre
                    tampilseluruh()
                    print('\nGenre buku telah diupdate dalam database')
                    break
            elif pilihUpdate == 4:
                updatePenulis = input('Masukkan nama penulis baru: ')
                confirmUpdatePenulis= input('Apakah anda yakin akan melakukan update data? Y/N: ')
                if confirmUpdatePenulis != 'Y':
                    break
                else:
                    library[updateBaru.lower()]['Nama Penulis'] = updatePenulis
                    tampilseluruh()
                    print('\nNama penulis buku telah diupdate dalam database')
                    break   
            elif pilihUpdate == 5:
                updateStatus = input('Masukkan status peminjaman terkini: ')
                confirmUpdateStatus= input('Apakah anda yakin akan melakukan update data? Y/N: ')
                if confirmUpdateStatus != 'Y':
                    break
                else:
                    library[updateBaru.lower()]['Status Peminjaman'] = updateStatus
                    tampilseluruh()
                    print('\nStatus peminjaman telah diupdate dalam database')
                    break
            else:
                break
        else:
            print('Data tidak ada dalam daftar informasi')

def menghapus():
    tampilseluruh()
    inputMenghapus = input('Masukkan data yang akan anda hapus: ')
    menghapusData = inputMenghapus.replace(' ','')
    while menghapusData.lower() not in library.keys():
        print('Data tidak ditemukan')
        break
    else:
        checkHapus = input(f'Apakah anda yakin menghapus {inputMenghapus}? Y/N: ')
        while checkHapus != 'Y':
            print('')
            print('Informasi tidak dihapus dari database')
            break
        else:
            del library[menghapusData.lower()]
            tampilseluruh()
            print('')
            print('Informasi telah dihapus dari database')

def melihat():
    print('')
    print('- Perpustakaan Adhi Raihanto -')
    print('')
    print('Masukkan angka 1 untuk menampilkan seluruh data yang ada')
    print('Masukkan angka 2 untuk mencari data berdasarkan keyword')
    print('Masukkan selain angka 1 dan 2 untuk kembali ke menu utama')
    print('')

    kode=input('Masukkan kode sesuai dengan yang anda ingin lakukan: ')
    if kode =='1':
        print('Berikut seluruh data dan informasi yang tersimpan')
        tampilseluruh()
    elif kode =='2':
        lihatdata()
    else:
        print('Kembali ke menu utama')

def menu():
    print('')
    print('- Perpustakaan Adhi Raihanto -')
    print('')
    print('[1] Melihat informasi dan data buku')
    print('[2] Menambah informasi dan data buku')
    print('[3] Melakukan edit dan update informasi dan data buku')
    print('[4] Menghapus informasi dan data buku')
    print('[0] Menghentikan program')
    print('')
    
    kode=input('Masukkan kode sesuai dengan yang anda ingin lakukan: ')
    if kode =='1':
        melihat()
    elif kode =='2':
        menambah()
    elif kode =='3':
        mengupdate()
    elif kode =='4':
        menghapus()
    elif kode =='0':
        print("Terima kasih. Sampai jumpa kembali!")
        exit()
    else:
        print('Pilihan yang anda masukkan salah. Mohon masukkan kode yang sesuai.')

while(True):
    menu()
