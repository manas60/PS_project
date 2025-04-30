# 16 byte CMOS SRAM

- Designed a 16-byte SRAM (Static Random Access Memory) using the 130nm technology node, employing a full custom approach.
- This SRAM design allows for reading or writing 8-bit data at a time.
- Throughout the project, various Cadence tools were employed to aid in the design and verification processes.

## Table of Contents

- [Introduction](#Introduction)
- [Architecture](#Architecture)
- [Components](#Components)
    - [8T_SRAM](#8T_SRAM)
    - [Precharge_circuit](#Precharge_circuit)
    - [Row_decoder](#Row_decoder)
    - [RAM/ICM logic block](#RAM/ICM_logic_block)
    - [Sense_Amplifier](#Sense_Amplifier)
    - [Write_driver](#Write_driver)
 
- [Design and testbench](#Design_and_testbench)
- [Layout](#Layout)
- [Conclusion](#Conclusion)

-  ### Layout  

  - In this section we will present the layouts of the entire design and the subcomponents of the design.
  - For the layout design we are using **cadence virtuoso** where as for verification like DRC and LVS we are using  **PVS**.

    ![SRAM](https://github.com/user-attachments/assets/0e30bd6b-d171-4b3d-9422-2f3bd35296e7)
    <p align="center">8T SRAM</p>

    ![Precharge_ckt](https://github.com/user-attachments/assets/9bb384d5-d662-4a19-8a6a-6229d8f07390)
    <p align="center">Precharge circuit</p>   
    
    ![Decoder](https://github.com/user-attachments/assets/d7213918-6ff7-490b-a815-385dd59c466f)
    <p align="center">Column Decoder</p>   
    
    ![Sense amplifier](https://github.com/user-attachments/assets/bf522ec0-207f-4b5d-8e39-4b99426f9898)
    <p align="center">Sense Amplifier</p>
    
    ![Write driver](https://github.com/user-attachments/assets/c19a8d4e-76f0-49a1-9217-46b4cade56db)
    <p align="center">Write driver</p>  
    
   
    **Project Final layout**
    _________________________
    
    ![Top_level](https://github.com/user-attachments/assets/aa56b891-cc2a-49a9-adf5-3fb450273ca5)


