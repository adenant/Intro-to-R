## Pengenalan Paket *tidyverse*

+++

### Learning Objectives
- Mengenal paket *tydiverse*
- Memahami apa dan kegunaan paket *dplyr* dan *tidyr* untuk kebutuhan manipulasi data
- Memahami sintaksis fungsi dalam paket *dplyr* dan *tidyr*

+++
### Mengenal paket *tydyverse*

- Paket *tydiverse* merupakan sebuah “umbrella-package” yang secara langsung meng-install beberapa paket yang bermanfaat untuk manipulasi data: *tidyr, dplyr, ggplot2, tibble*, dsb.
- Paket *tydiverse* bermaksud untuk mengatasi 3 permasalahan umum di R:
    - Hasil dari fungsi basis R biasanya tergantung pada tipe data
    - Penggunaan ekspresi R dengan cara yang tidak biasa yang depat membingungkan bagi pemula
    - Argumen-argumen tersembunyi
- Pada sesi ini, kita akan fokus pada 2 sub-paket dalam tydiverse: *tidyr* & *dplyr*
    
+++

### Apa itu *dplyr* and *tidyr*?
- Paket *dplyr* menyediakan *tools* yang umum digunakan dalam manipulasi data
- Paket ini dirancang khusus untuk bekerja dengan *data frame*, yang berbagai fungsi/kerja umumnya telah di optimasi dengan cara ditulis dalam sebuah *compiled language* (C++)
- Fitur tambahan meliputi kemampuan untuk bekerja secara langsung dengan data yang disimpan dalan database eksternal
- Keuntungannya, data dapat dikelola secara natif dalam framework relational database

+++

