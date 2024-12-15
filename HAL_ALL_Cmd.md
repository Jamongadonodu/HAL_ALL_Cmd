<font face=time>

[TOC]

---

# <font color=dust><center>HAL_All_Cmd</font></center>



---

## <font color=gree><center>GPIO</font></center>


### GPIO基础功能

<font size=5>

>HAL_GPIO_Init
HAL_GPIO_DeInit

>HAL_GPIO_ReadPin
HAL_GPIO_WritePin
HAL_GPIO_TogglePin

>HAL_GPIO_LockPin

>HAL_GPIO_EXTI_IRQHandler
HAL_GPIO_EXTI_Callback

</font>

---

## <font color=gree><center>UART</font></center>

### UART基础收发功能

<font size=5>

>HAL_UART_Init
HAL_UART_DeInit

>**HAL_UART_Transmit**
>HAL_UART_Transmit_IT
HAL_UART_Transmit_DMA

>**HAL_UART_Receive**
>HAL_UART_Receive_IT
HAL_UART_Receive_DMA

</font>

---

### UART_DMA功能

<font size=5>

>HAL_UART_DMAPause
HAL_UART_DMAResume
HAL_UART_DMAStop

</font>

---

### UART_Abort功能

<font size=5>

>HAL_UART_Abort
HAL_UART_AbortTransmit
HAL_UART_AbortReceive

>HAL_UART_Abort_IT
HAL_UART_AbortTransmit_IT
HAL_UART_AbortReceive_IT

</font>

---

### UART中断

<font size=5>

>void HAL_UART_IRQHandler

> __weak void HAL_UART_TxCpltCallback
 __weak void zdHAL_UART_RxCpltCallback

>HAL_UART_GetState

</font>

---

## <font color=gree><center>TIM</font></center> 

### 定时器基础功能

<font size=5>

>HAL_TIM_Base_Init
HAL_TIM_Base_DeInit
HAL_TIM_Base_MspInit
HAL_TIM_Base_MspDeInit

>**HAL_TIM_Base_Start**
>>HAL_TIM_Base_Start_IT
HAL_TIM_Base_Start_DMA

>**HAL_TIM_Base_Stop**
>>HAL_TIM_Base_Stop_IT
HAL_TIM_Base_Stop_DMA

</font>

---

### 输出比较功能

<font size=5>

>HAL_TIM_OC_Init
HAL_TIM_OC_DeInit
HAL_TIM_OC_MspInit
HAL_TIM_OC_MspDeInit

>**HAL_TIM_OC_Start**
>>HAL_TIM_OC_Start_IT
HAL_TIM_OC_Start_DMA

>**HAL_TIM_OC_Stop**
>>HAL_TIM_OC_Stop_IT
HAL_TIM_OC_Stop_DMA

</font>

---

### PWM功能

<font size=5>

>HAL_TIM_PWM_Init
HAL_TIM_PWM_DeInit
HAL_TIM_PWM_MspInit
HAL_TIM_PWM_MspDeInit

>**HAL_TIM_PWM_Start**
>>HAL_TIM_PWM_Start_IT
HAL_TIM_PWM_Start_DMA

>**HAL_TIM_PWM_Stop**
>>HAL_TIM_PWM_Stop_IT
HAL_TIM_PWM_Stop_DMA

</font>

---

### 输入捕获功能

<font size=5>

>HAL_TIM_IC_Init
HAL_TIM_IC_DeInit
HAL_TIM_IC_MspInit
HAL_TIM_IC_MspDeInit

>**HAL_TIM_IC_Start**
>>HAL_TIM_IC_Start_IT
HAL_TIM_IC_Start_DMA

>HAL_TIM_IC_Stop
HAL_TIM_IC_Stop_IT
HAL_TIM_IC_Stop_DMA

</font>

---

### 单脉冲模式

<font size=5>

>HAL_TIM_OnePulse_Init
HAL_TIM_OnePulse_DeInit
HAL_TIM_OnePulse_MspInit
HAL_TIM_OnePulse_MspDeInit

>HAL_TIM_OnePulse_Start
HAL_TIM_OnePulse_Start_IT

>HAL_TIM_OnePulse_Stop
HAL_TIM_OnePulse_Stop_IT

</font>

---

### 编码器功能

<font size=5>

>HAL_TIM_Encoder_Init
HAL_TIM_Encoder_DeInit
HAL_TIM_Encoder_MspInit
HAL_TIM_Encoder_MspDeInit

>**HAL_TIM_Encoder_Start**
>>HAL_TIM_Encoder_Start_IT
HAL_TIM_Encoder_Start_DMA

>**HAL_TIM_Encoder_Stop**
>>HAL_TIM_Encoder_Stop_IT
HAL_TIM_Encoder_Stop_DMA

</font>

---

### 回调函数

<font size=5>

>**HAL_TIM_PeriodElapsedCallback**
>>HAL_TIM_PeriodElapsedHalfCpltCallback

>HAL_TIM_OC_DelayElapsedCallback

>HAL_TIM_IC_CaptureCallback
HAL_TIM_IC_CaptureHalfCpltCallback

>HAL_TIM_PWM_PulseFinishedCallback
HAL_TIM_PWM_PulseFinishedHalfCpltCallback

>HAL_TIM_TriggerCallback
HAL_TIM_TriggerHalfCpltCallback

>HAL_TIM_ErrorCallback

</font>

---

## <font color=gree><center>ADC</font></center>

### ADC基础功能

<font size=5>

>ADC_Enable

>**HAL_ADC_Start**
>>HAL_ADC_Start_IT
HAL_ADC_Start_DMA

>**HAL_ADC_Stop**
>>HAL_ADC_Stop_IT
HAL_ADC_Stop_DMA

>**HAL_ADC_GetValue**

</font>

---

## <font color=gree><center>I2C</font></center>

### I2C基础模式

<font size=5>

>HAL_I2C_Init
HAL_I2C_DeInit

</font>

### I2C主模式功能

<font size=5>

>**HAL_I2C_Master_Transmit**
>>HAL_I2C_Master_Transmit_IT
HAL_I2C_Master_Transmit_DMA

>**HAL_I2C_Master_Receive**
>>HAL_I2C_Master_Receive_IT
HAL_I2C_Master_Receive_DMA

</font>

---

### I2C从模式功能

<font size=5>

>HAL_I2C_Slave_Transmit
>>HAL_I2C_Slave_Transmit_IT
HAL_I2C_Slave_Transmit_DMA

>HAL_I2C_Slave_Receive
>>HAL_I2C_Slave_Receive_IT
HAL_I2C_Slave_Receive_DMA

</font>

---

### I2C寄存器功能

<font size=5>

>HAL_I2C_Mem_Write
>>HAL_I2C_Mem_Write_IT
HAL_I2C_Mem_Write_DMA

>HAL_I2C_Mem_Read
>>HAL_I2C_Mem_Read_IT
HAL_I2C_Mem_Read_DMA

</font>

---

### I2C中断回调

<font size=5>

>void HAL_I2C_ER_IRQHandler

>__weak void HAL_I2C_MasterTxCpltCallback

>__weak void  HAL_I2C_MasterRxCpltCallback

>__weak void HAL_I2C_SlaveTxCpltCallback

>__weak void HAL_I2C_SlaveRxCpltCallback

</font>

---

### I2C其它功能

<font size=5>

>HAL_I2C_IsDeviceReady
HAL_I2C_EV_IRQHandler

>HAL_I2C_GetState
HAL_I2C_GetMode

>HAL_I2C_Master_Abort_IT

</font>

---

## <font color=gree><center>SPI</font></center>

### SPI基础功能

<font size=5>

>HAL_SPI_Init
HAL_SPI_DeInit

>**HAL_SPI_Transmit**
>>HAL_SPI_Transmit_IT
HAL_SPI_Transmit_DMA

>**HAL_SPI_Receive**
>>HAL_SPI_Receive_IT
HAL_SPI_Receive_DMA

>**HAL_SPI_TransmitReceive**
>>HAL_SPI_TransmitReceive_IT
HAL_SPI_TransmitReceive_DMA

</font>

### SPI中断回调

<font size=5>

>void HAL_SPI_IRQHandler

>__weak void HAL_SPI_TxCpltCallback

>__weak void HAL_SPI_RxCpltCallback

</font>

### SPI其他功能

<font size=5>

>HAL_SPI_Abort

>HAL_SPI_DMAPause
HAL_SPI_DMAResume
HAL_SPI_DMAStop

>HAL_SPI_GetState

</font>

---

## <font color=gree><center>Flash</font></center>

### Flash功能

<font size=5>

>HAL_FLASH_Lock
HAL_FLASH_Unlock

>HAL_FLASH_Program
HAL_FLASH_Program_IT

>HAL_FLASHEx_Erase

>void 
HAL_FLASH_IRQHandler

</font>

---

