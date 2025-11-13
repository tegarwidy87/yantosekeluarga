import random
import time
import os

def clear_screen():
    """Membersihkan layar terminal (cross-platform)."""
    # Untuk Windows
    if os.name == 'nt':
        _ = os.system('cls')
    # Untuk MacOS dan Linux
    else:
        _ = os.system('clear')

def buat_baris_acak():
    """Menghasilkan satu baris berisi 3 angka acak (1-9)."""
    return [random.randint(1, 9) for _ in range(3)]

def cetak_grid(grid, highlight_row=-1):
    """
    Mencetak grid 3x3.
    Jika highlight_row (indeks 0, 1, atau 2) diset, baris itu akan ditandai.
    """
    print("\n" + "="*21)
    for i, row in enumerate(grid):
        # Format baris menjadi string
        row_str = f"| {row[0]} | {row[1]} | {row[2]} |"
        
        # Tambahkan penanda jika ini adalah baris yang di-highlight
        if i == highlight_row:
            print(f"> {row_str} <  <-- HASIL")
        else:
            print(f"  {row_str}  ")
    print("="*21 + "\n")

def putar_slot():
    """Fungsi utama untuk memutar slot dengan animasi."""
    
    print("Memutar...")
    
    # 1. Tentukan hasil AKHIR (baris tengah) terlebih dahulu
    # Ini adalah hasil yang akan kita gunakan
    final_row_mid = buat_baris_acak()
    
    # Pengaturan animasi
    spin_speed = 0.05  # Kecepatan ganti frame (detik)
    spin_duration = 5 # Total durasi putaran (detik)
    
    start_time = time.time()
    
    # 2. Animasi "Spin" (Flush)
    # Selama durasi spin, kita akan terus membersihkan layar
    # dan menampilkan grid yang acak.
    while time.time() - start_time < spin_duration:
        # Buat grid acak sementara untuk animasi
        temp_grid = [
            buat_baris_acak(),
            buat_baris_acak(), # Baris tengah juga acak selama spin
            buat_baris_acak()
        ]
        
        clear_screen()
        print("--- MEMUTAR ---")
        cetak_grid(temp_grid)
        time.sleep(spin_speed)

    # 3. Tampilkan Hasil Akhir
    clear_screen()
    print("--- HASIL AKHIR ---")
    
    # Buat grid final:
    # Baris atas dan bawah acak, tapi baris tengah adalah hasil final kita.
    final_grid = [
        buat_baris_acak(),  # Baris atas acak
        final_row_mid,      # Baris tengah adalah HASIL
        buat_baris_acak()   # Baris bawah acak
    ]
    
    # Cetak grid final dengan highlight baris tengah (indeks 1)
    cetak_grid(final_grid, highlight_row=1)
    
    # 4. Cek kondisi menang (jackpot)
    # Ambil angka dari baris tengah
    a1, a2, a3 = final_row_mid
    
    print(f"Hasil Anda (baris tengah): [ {a1} | {a2} | {a3} ]")
    
    if a1 == a2 == a3:
        print("\n" + "*"*25)
        print(">>> JACKPOT! ANDA MENANG! <<<")
        print("*"*25)
    else:
        print("\n--- Coba Lagi ---")

def main():
    """Fungsi utama untuk loop program."""
    clear_screen()
    print("===========================================")
    print(" Selamat Datang di Tegay87Slot ")
    print(" Hasil ditentukan oleh 3 angka di BARIS TENGAH ")
    print("===========================================")
    print("Ketik 'q' lalu Enter untuk keluar, atau tekan Enter untuk memutar.")

    while True:
        pilihan = input("\nTekan Enter untuk memutar...")
        
        if pilihan.lower() == 'q':
            clear_screen()
            print("Terima kasih telah bermain!")
            break
            
        putar_slot()

# Standar emas untuk menjalankan script Python
if __name__ == "__main__":
    main()