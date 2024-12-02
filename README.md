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
3. mengkonfigurasi GPIO untuk LED:
