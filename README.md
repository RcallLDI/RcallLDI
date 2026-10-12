# Let's Code! ⚡⚙建

```text
       +-----------------------+
   RST | 1                  28 | PC5 (SCL)
   RXD | 2                  27 | PC4 (SDA)
   TXD | 3    _  _   _      26 | PC3
  INT0 | 4   |  | \ | |     25 | PC2
  INT1 | 5   |--|  || |     24 | PC1
   T0  | 6   |  |_/ |_|     23 | PC0
   VCC | 7                  22 | GND
   GND | 8    RcallLDI      21 | AREF
  XTAL | 9   Let's Code!    20 | AVCC
  XTAL | 10                 19 | PB5 (SCK)
   T1  | 11                 18 | PB4 (MISO)
  AIN0 | 12                 19 | PB3 (MOSI)
  AIN1 | 13                 16 | PB2 (SS)
   PB0 | 14                 15 | PB1 
       +-----------------------+
```

> **rcall init_bigIdea**  ; 
> **ldi r31, 0xFF**       ;
