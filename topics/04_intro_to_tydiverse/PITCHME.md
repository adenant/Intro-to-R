## Pengenalan Paket *tidyverse*

+++

### Learning Objectives
- Mengenal paket *tydiverse*
- Memahami apa dan kegunaan paket *dplyr* dan *tidyr* untuk kebutuhan manipulasi data
- Memahami sintaksis fungsi dalam paket *dplyr* dan *tidyr*

+++

### Mengenal paket *tydyverse* (1)

- Paket *tydiverse* merupakan sebuah “umbrella-package” yang  berisikan beberapa paket yang bermanfaat untuk manipulasi data: *tidyr, dplyr, ggplot2, tibble*, dsb.
- Bermaksud mengatasi beberapa permasalahan umum dalam R, misal kerancuan penulisan perintah/ekspresi maupun argument fungsi yang tersembunyi
- Pada sesi ini, kita akan fokus pada 2 sub-paket dalam tydiverse: *tidyr* & *dplyr*
    
+++

### Mengenal paket *tydyverse* (2)

- Langkah pertama untuk menggunakan paket *tydiverse* adalah dengan menginstallnya dan memuat dalam workspace

    ```
    install.packages("tydyverse")
    library(tidyverse)
    ```

+++

### Apa itu *dplyr* and *tidyr*?
- Paket *dplyr* menyediakan *tools* yang umum digunakan dalam manipulasi data
- Paket ini dirancang khusus untuk bekerja dengan *data frame*, yang berbagai fungsi/kerja umumnya telah di optimasi dengan cara ditulis dalam sebuah *compiled language* (C++)
- Fitur tambahan meliputi kemampuan untuk bekerja secara langsung dengan data yang disimpan dalan database eksternal
- Keuntungannya, data dapat dikelola secara natif dalam framework relational database

+++

