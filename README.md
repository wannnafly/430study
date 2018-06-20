# 430study
when I study msp430, I meet some problem, and I solved it, than, this blog is my note.

0.befor coding
0.0 --WDT_A_hold(WDT_A_BASE); //close the watch dog
    --PMM_unlockLPM5();       //awake the chip,do not foget it!
1.  GPIO
  1.1 GPIO_OUTPUT
      --GPIO_setAsOutputPin(GPIO_PORT_P1,GPIO_PIN0); //set gpio as output
        for this function: --GPIO_PORT_P1   is   uint8_t
                           --GPIO_PIN0      is   uint16_t
      --GPIO_setOutputHighOnPin(GPIO_PORT_P1, GPIO_PIN0);  //set P1.1 as high
 
