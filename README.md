**Exercise 4 - Gain a good understanding of task behavior where a priority preeptive scheduling policy is used.**

Latihan ini bertujuan untuk memahami bagaimana cara Sistem Operasi Real-Time (RTOS) dapat menangani multitasking dengan diberikan kebijakan penjadwalan preeptive priority. pada bagian ini akan mengamati bagaiman tugas-tugas yang diberikan dengan prioritas berbeda memengaruhi urutan eksekusi dalam sistem berbasis STM32 dan FreeRTOS.

**Tujuan**

1. Memahami konsep preemptive scheduling pada FreeRTOS.
2. Memahami bagaimana task dapat berinteraksi di bawah sistem scheduling berbasis prioritas.

**Peralatan**
1. STM32F103C8T6
2. LED
3. KABEL JUMPER
4. Mini Debugger
   
**Langkah Implementasi**

1. Konfigurasi STM32CubeMX: Memilih board STM32F103C8T6.
2. Aktifkan FreeRTOS dari tab Middleware.
3. mengkonfigurasi GPIO untuk LED: GPIOA Pin 0: Green LED. GPIOA Pin 1: Red LED. GPIOA Pin 2: Blue LED (Task indikator). GPIOA Pin 3: Orange LED.
4. pengimplementasian kode: Task 1 (Green LED): dengan ospriorityLow. Berkedip selama 4 detik dengan frekuensi 20 Hz, lalu terdapat delay 6 detik. Task 2 (Red LED): ospriorityHigh. Berkedip selama 0,5 detik dengan frekuensi 20 Hz, lalu terdapat delay 1,5 detik.
5. Lakukan build dan debug kode menggunakan STM32CubeIDE ke board STM32 yang digunakan.
6. Lakukan pengamatan terhadap yang terjadi.

**Hasil Percobaan**



https://github.com/user-attachments/assets/a24249e3-547c-42fe-b2a0-65c13a5ac779


