# NUC029xEE_UART0_UART2
 NUC029xEE_UART0_UART2

update @ 2019/11/21

UART0 (PB1_UART0_TXD , PB0_UART0_RXD) and UART2 example (PB9_UART2_TXD , PB10_UART2_RXD) , 

Scenario : 

- UART0 always output 0x0 ~ 0xF , reapeatly per 250 ms (TIMER3)

- Enable UART0/UART2 RX interrupt 

- Test with tera term , broadcast 1 byte by press send (ex : 3)

- connect to PB0 (UART0 RX) and press send , log will display "UART0 : 0x33"

- connect to PB10 (UART2 RX) and press send , log will display "UART2 : 0x33"
