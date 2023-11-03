# Libft
[![fatkeski's 42 stats](https://badge.mediaplus.ma/darkgray/fatkeski?1337Badge=off&UM6P=off)](https://github.com/oakoudad/badge42)
# Libft Introduction

Libft (Library of Functions)

Bu proje kapsamında, bir fonksiyon kütüphanesi oluşturacaksınız.

### .c Files 
Tüm fonksiyonlarınızın yazılacağı yerdir.

### .h (Header)
Header dosyanız iki önemli amaç için kullanışlıdır:

İlk olarak, örneğin tüm .c dosyalarında `#include <unistd.h>` yazmak yerine, bu işlemi header dosyanızda sadece bir kez yazarsınız ve tüm .c dosyalarınız bu header dosyasından okur.
İkincisi, bir .c dosyasının diğer bir .c dosyasından başka bir fonksiyonu kullanması gerektiğinde, o fonksiyonu tekrar yazmak yerine sadece `#include "libft.h"` yazarsınız ve header dosyasında bulur.
Tüm .c dosyalarınızda `#include "libft.h"` eklediğinizden emin olun.

### Makefile 
Makefile, projelerinizi derlemek için bir dosya oluşturacağınız yerdir.

### Functions from `<ctype.h>`

- [`ft_isalpha`](ft_isalpha.c)	- Bir alfabedeki karakteri kontrol eder.
- [`ft_isdigit`](ft_isdigit.c)	- Bir rakamı (0 ile 9 arasında) kontrol eder.
- [`ft_isalnum`](ft_isalnum.c)	- Bir alfanumerik karakteri kontrol eder.
- [`ft_isascii`](ft_isascii.c)	- Bir karakterin ASCII karakter kümesine uyup uymadığını kontrol eder.
- [`ft_isprint`](ft_isprint.c)	- Herhangi bir yazdırılabilir karakteri kontrol eder.
- [`ft_toupper`](ft_toupper.c)	- Bir karakteri büyük harfe dönüştürür.
- [`ft_tolower`](ft_tolower.c)	- Bir karakteri küçük harfe dönüştürür.

### Functions from `<string.h>`

- [`ft_memset`](ft_memset.c)	- Belirtilen sabit bir bayt ile belleği doldurur.
- [`ft_strlen`](ft_strlen.c)	- Bir dizinin uzunluğunu hesaplar.
- [`ft_bzero`](ft_bzero.c)	- `s` ile gösterilen bellek alanının ilk `n` baytını sıfırlar.
- [`ft_memcpy`](ft_memcpy.c)	- src ile gösterilen bellek alanından bellek alanına n bayt kopyalar.
- [`ft_memmove`](ft_memmove.c)	- Bellek alanındaki src ile gösterilen n baytı bellek alanına kopyalar. Overlap durumunu doğru bir şekilde işler.
- [`ft_strlcpy`](ft_strlcpy.c)	- Bir diziyi belirli bir boyuta kopyalar ve belirtilen boyutu aşmayacağını garanti eder.
- [`ft_strlcat`](ft_strlcat.c)	- Bir diziyi diğer bir diziye ekler ve sonucu belirli bir boyutla sınırlar.
- [`ft_strchr`](ft_strchr.c)	- Bir dizide bir karakterin ilk bulunduğu adresi bulur.
- [`ft_strrchr`](ft_strrchr.c)	- Bir dizide bir karakterin son bulunduğu adresi bulur.
- [`ft_strncmp`](ft_strncmp.c)	- İlk n karaktere kadar karşılaştırır.
- [`ft_memchr`](ft_memchr.c)	- Belirli bir karakteri taramak için bir bellek bloğunu tarar ve bulunursa ilk bulunanın adresini döndürür.
- [`ft_memcmp`](ft_memcmp.c)	- İki bellek alanını, belirtilen boyuta kadar bayt bayt karşılaştırır.
- [`ft_strnstr`](ft_strnstr.c)	- Bir dizede, belirli bir boyuta kadar olan ilk alt dizi aranır.
- [`ft_strdup`](ft_strdup.c)	- Parametre olarak verilen dizinin bir kopyasını oluşturur ve yeni oluşturulan kopyaya işaret eden bir işaretçi döndürür.

### Functions from `<stdlib.h>`
- [`ft_atoi`](ft_atoi.c)	- Bir diziden tamsayıya dönüştürme yapar.
- [`ft_calloc`](ft_calloc.c)	- Bellek tahsis eder ve bu belleğin bayt değerlerini sıfırlar.

### Non-standard functions
- [`ft_substr`](ft_substr.c)	- Bir diziden bir alt dizi döndürür.
- [`ft_strjoin`](ft_strjoin.c)	- İki diziyi birleştirir.
- [`ft_strtrim`](ft_strtrim.c)	- Dizinin başını ve sonunu belirli bir karakter kümesiyle kırpar.
- [`ft_split`](ft_split.c)	- Bir diziyi, bir karakteri parametre olarak kullanarak böler.
- [`ft_itoa`](ft_itoa.c)	- Bir sayıyı bir diziye dönüştürür.
- [`ft_strmapi`](ft_strmapi.c)	- Bir dizinin her karakterine bir fonksiyon uygulayarak değişikliği dinamik olarak tahsis edilen diziye kopyalar.
- [`ft_striteri`](ft_striteri.c)	- Bir dizinin her karakterine bir fonksiyon uygular.
- [`ft_putchar_fd`](ft_putchar_fd.c)	- Bir karakteri bir dosya tanımlayıcısına output eder.
- [`ft_putstr_fd`](ft_putstr_fd.c)	- Bir diziyi bir dosya tanımlayıcısına output eder.
- [`ft_putendl_fd`](ft_putendl_fd.c)	- Bir diziyi bir dosya tanımlayıcısına output eder ve yeni bir satır ekler.
- [`ft_putnbr_fd`](ft_putnbr_fd.c)	- Bir sayıyı bir dosya tanımlayıcısına output eder.
