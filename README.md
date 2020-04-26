

Reading from here:
https://learning.oreilly.com/library/view/embedded-programming-with/9780134030920/ch09.html#ch09

```
  make versatileqemu_config ARCH=arm CROSS_COMPILE=arm-none-eabi-

  # the OBJDUMP command isn't generating a good u-boot.lst file
  cp include/u-boot.lst.GOOD include/u-boot.lst

  make clean all ARCH=arm CROSS_COMPILE=arm-none-eabi-
```

