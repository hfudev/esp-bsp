# API Reference

## Header files

- [components/bh1750/include/bh1750.h](#file-componentsbh1750includebh1750h)
- [components/ds18b20/include/ds18b20.h](#file-componentsds18b20includeds18b20h)
- [components/ds18b20/include/ds18b20_types.h](#file-componentsds18b20includeds18b20_typesh)
- [components/es7210/include/es7210.h](#file-componentses7210includees7210h)
- [components/es7210/priv_include/es7210_reg.h](#file-componentses7210priv_includees7210_regh)
- [components/es8311/include/es8311.h](#file-componentses8311includees8311h)
- [components/es8311/priv_include/es8311_reg.h](#file-componentses8311priv_includees8311_regh)
- [components/esp_lvgl_port/include/esp_lvgl_port.h](#file-componentsesp_lvgl_portincludeesp_lvgl_porth)
- [components/fbm320/include/fbm320.h](#file-componentsfbm320includefbm320h)
- [components/hts221/include/hts221.h](#file-componentshts221includehts221h)
- [components/hts221/include/hts221_reg.h](#file-componentshts221includehts221_regh)
- [components/io_expander/esp_io_expander/include/esp_io_expander.h](#file-componentsio_expanderesp_io_expanderincludeesp_io_expanderh)
- [components/io_expander/esp_io_expander_ht8574/include/esp_io_expander_ht8574.h](#file-componentsio_expanderesp_io_expander_ht8574includeesp_io_expander_ht8574h)
- [components/io_expander/esp_io_expander_tca9554/include/esp_io_expander_tca9554.h](#file-componentsio_expanderesp_io_expander_tca9554includeesp_io_expander_tca9554h)
- [components/io_expander/esp_io_expander_tca95xx_16bit/include/esp_io_expander_tca95xx_16bit.h](#file-componentsio_expanderesp_io_expander_tca95xx_16bitincludeesp_io_expander_tca95xx_16bith)
- [components/lcd/esp_lcd_gc9503/include/esp_lcd_gc9503.h](#file-componentslcdesp_lcd_gc9503includeesp_lcd_gc9503h)
- [components/lcd/esp_lcd_gc9a01/include/esp_lcd_gc9a01.h](#file-componentslcdesp_lcd_gc9a01includeesp_lcd_gc9a01h)
- [components/lcd/esp_lcd_ili9341/include/esp_lcd_ili9341.h](#file-componentslcdesp_lcd_ili9341includeesp_lcd_ili9341h)
- [components/lcd/esp_lcd_ra8875/include/esp_lcd_ra8875.h](#file-componentslcdesp_lcd_ra8875includeesp_lcd_ra8875h)
- [components/lcd/esp_lcd_sh1107/include/esp_lcd_sh1107.h](#file-componentslcdesp_lcd_sh1107includeesp_lcd_sh1107h)
- [components/lcd/esp_lcd_st7796/include/esp_lcd_st7796.h](#file-componentslcdesp_lcd_st7796includeesp_lcd_st7796h)
- [components/lcd_touch/esp_lcd_touch/include/esp_lcd_touch.h](#file-componentslcd_touchesp_lcd_touchincludeesp_lcd_touchh)
- [components/lcd_touch/esp_lcd_touch_cst816s/include/esp_lcd_touch_cst816s.h](#file-componentslcd_touchesp_lcd_touch_cst816sincludeesp_lcd_touch_cst816sh)
- [components/lcd_touch/esp_lcd_touch_ft5x06/include/esp_lcd_touch_ft5x06.h](#file-componentslcd_touchesp_lcd_touch_ft5x06includeesp_lcd_touch_ft5x06h)
- [components/lcd_touch/esp_lcd_touch_gt1151/include/esp_lcd_touch_gt1151.h](#file-componentslcd_touchesp_lcd_touch_gt1151includeesp_lcd_touch_gt1151h)
- [components/lcd_touch/esp_lcd_touch_gt911/include/esp_lcd_touch_gt911.h](#file-componentslcd_touchesp_lcd_touch_gt911includeesp_lcd_touch_gt911h)
- [components/lcd_touch/esp_lcd_touch_stmpe610/include/esp_lcd_touch_stmpe610.h](#file-componentslcd_touchesp_lcd_touch_stmpe610includeesp_lcd_touch_stmpe610h)
- [components/lcd_touch/esp_lcd_touch_tt21100/include/esp_lcd_touch_tt21100.h](#file-componentslcd_touchesp_lcd_touch_tt21100includeesp_lcd_touch_tt21100h)
- [components/mag3110/include/mag3110.h](#file-componentsmag3110includemag3110h)
- [components/mpu6050/include/mpu6050.h](#file-componentsmpu6050includempu6050h)
- [components/ssd1306/include/ssd1306.h](#file-componentsssd1306includessd1306h)
- [components/ssd1306/include/ssd1306_fonts.h](#file-componentsssd1306includessd1306_fontsh)
- [esp-box-lite/include/bsp/esp-box-lite.h](#file-esp-box-liteincludebspesp-box-liteh)
- [esp-box/include/bsp/esp-box.h](#file-esp-boxincludebspesp-boxh)
- [esp-box/include/bsp/touch.h](#file-esp-boxincludebsptouchh)
- [esp32_s3_korvo_2/include/bsp/touch.h](#file-esp32_s3_korvo_2includebsptouchh)
- [esp32_azure_iot_kit/include/bsp/esp32_azure_iot_kit.h](#file-esp32_azure_iot_kitincludebspesp32_azure_iot_kith)
- [esp32_c3_lcdkit/include/bsp/esp32_c3_lcdkit.h](#file-esp32_c3_lcdkitincludebspesp32_c3_lcdkith)
- [esp32_lyrat/include/bsp/esp32_lyrat.h](#file-esp32_lyratincludebspesp32_lyrath)
- [esp32_s2_kaluga_kit/include/bsp/esp32_s2_kaluga_kit.h](#file-esp32_s2_kaluga_kitincludebspesp32_s2_kaluga_kith)
- [esp-box-lite/include/bsp/display.h](#file-esp-box-liteincludebspdisplayh)
- [esp-box/include/bsp/display.h](#file-esp-boxincludebspdisplayh)
- [esp32_c3_lcdkit/include/bsp/display.h](#file-esp32_c3_lcdkitincludebspdisplayh)
- [esp32_s2_kaluga_kit/include/bsp/display.h](#file-esp32_s2_kaluga_kitincludebspdisplayh)
- [esp32_s3_eye/include/bsp/display.h](#file-esp32_s3_eyeincludebspdisplayh)
- [esp32_s3_korvo_2/include/bsp/display.h](#file-esp32_s3_korvo_2includebspdisplayh)
- [esp32_s3_usb_otg/include/bsp/display.h](#file-esp32_s3_usb_otgincludebspdisplayh)
- [esp_wrover_kit/include/bsp/display.h](#file-esp_wrover_kitincludebspdisplayh)
- [esp-box-lite/include/bsp/esp-bsp.h](#file-esp-box-liteincludebspesp-bsph)
- [esp-box/include/bsp/esp-bsp.h](#file-esp-boxincludebspesp-bsph)
- [esp32_azure_iot_kit/include/bsp/esp-bsp.h](#file-esp32_azure_iot_kitincludebspesp-bsph)
- [esp32_c3_lcdkit/include/bsp/esp-bsp.h](#file-esp32_c3_lcdkitincludebspesp-bsph)
- [esp32_lyrat/include/bsp/esp-bsp.h](#file-esp32_lyratincludebspesp-bsph)
- [esp32_s2_kaluga_kit/include/bsp/esp-bsp.h](#file-esp32_s2_kaluga_kitincludebspesp-bsph)
- [esp32_s3_eye/include/bsp/esp-bsp.h](#file-esp32_s3_eyeincludebspesp-bsph)
- [esp32_s3_korvo_2/include/bsp/esp-bsp.h](#file-esp32_s3_korvo_2includebspesp-bsph)
- [esp32_s3_lcd_ev_board/include/bsp/esp-bsp.h](#file-esp32_s3_lcd_ev_boardincludebspesp-bsph)
- [esp32_s3_usb_otg/include/bsp/esp-bsp.h](#file-esp32_s3_usb_otgincludebspesp-bsph)
- [esp_wrover_kit/include/bsp/esp-bsp.h](#file-esp_wrover_kitincludebspesp-bsph)
- [esp32_s3_eye/include/bsp/esp32_s3_eye.h](#file-esp32_s3_eyeincludebspesp32_s3_eyeh)
- [esp-box-lite/priv_include/bsp_err_check.h](#file-esp-box-litepriv_includebsp_err_checkh)
- [esp-box/priv_include/bsp_err_check.h](#file-esp-boxpriv_includebsp_err_checkh)
- [esp32_azure_iot_kit/priv_include/bsp_err_check.h](#file-esp32_azure_iot_kitpriv_includebsp_err_checkh)
- [esp32_c3_lcdkit/priv_include/bsp_err_check.h](#file-esp32_c3_lcdkitpriv_includebsp_err_checkh)
- [esp32_lyrat/priv_include/bsp_err_check.h](#file-esp32_lyratpriv_includebsp_err_checkh)
- [esp32_s2_kaluga_kit/priv_include/bsp_err_check.h](#file-esp32_s2_kaluga_kitpriv_includebsp_err_checkh)
- [esp32_s3_eye/priv_include/bsp_err_check.h](#file-esp32_s3_eyepriv_includebsp_err_checkh)
- [esp32_s3_korvo_2/priv_include/bsp_err_check.h](#file-esp32_s3_korvo_2priv_includebsp_err_checkh)
- [esp32_s3_lcd_ev_board/priv_include/bsp_err_check.h](#file-esp32_s3_lcd_ev_boardpriv_includebsp_err_checkh)
- [esp32_s3_usb_otg/priv_include/bsp_err_check.h](#file-esp32_s3_usb_otgpriv_includebsp_err_checkh)
- [esp_wrover_kit/priv_include/bsp_err_check.h](#file-esp_wrover_kitpriv_includebsp_err_checkh)
- [esp32_s3_korvo_2/include/bsp/esp32_s3_korvo_2.h](#file-esp32_s3_korvo_2includebspesp32_s3_korvo_2h)
- [esp32_s3_lcd_ev_board/include/bsp/esp32_s3_lcd_ev_board.h](#file-esp32_s3_lcd_ev_boardincludebspesp32_s3_lcd_ev_boardh)
- [esp32_s3_lcd_ev_board/priv_include/bsp_sub_board.h](#file-esp32_s3_lcd_ev_boardpriv_includebsp_sub_boardh)
- [esp32_s3_usb_otg/include/bsp/esp32_s3_usb_otg.h](#file-esp32_s3_usb_otgincludebspesp32_s3_usb_otgh)
- [esp_wrover_kit/include/bsp/esp_wrover_kit.h](#file-esp_wrover_kitincludebspesp_wrover_kith)

## File components/bh1750/include/bh1750.h


## Macros

| Type | Name |
| ---: | :--- |
| define  | [**BH1750\_I2C\_ADDRESS\_DEFAULT**](#define-bh1750_i2c_address_default)  (0x23)<br> |

## Types

| Type | Name |
| ---: | :--- |
| typedef void \* | [**bh1750\_handle\_t**](#typedef-bh1750_handle_t)  <br> |
| enum  | [**bh1750\_measure\_mode\_t**](#enum-bh1750_measure_mode_t)  <br> |

## Functions

| Type | Name |
| ---: | :--- |
|  bh1750\_handle\_t | [**bh1750\_create**](#function-bh1750_create) (i2c\_port\_t port, const uint16\_t dev\_addr) <br>_Create and init sensor object and return a sensor handle._ |
|  esp\_err\_t | [**bh1750\_delete**](#function-bh1750_delete) (bh1750\_handle\_t sensor) <br>_Delete and release a sensor object._ |
|  esp\_err\_t | [**bh1750\_get\_data**](#function-bh1750_get_data) (bh1750\_handle\_t sensor, float \*const data) <br>_Get light intensity from BH1750._ |
|  esp\_err\_t | [**bh1750\_power\_down**](#function-bh1750_power_down) (bh1750\_handle\_t sensor) <br>_Set bh1750 as power down mode (low current)_ |
|  esp\_err\_t | [**bh1750\_power\_on**](#function-bh1750_power_on) (bh1750\_handle\_t sensor) <br>_Set bh1750 as power on mode._ |
|  esp\_err\_t | [**bh1750\_set\_measure\_mode**](#function-bh1750_set_measure_mode)  <br>_Get light intensity from bh1750._ |
|  esp\_err\_t | [**bh1750\_set\_measure\_time**](#function-bh1750_set_measure_time) (bh1750\_handle\_t sensor, const uint8\_t measure\_time) <br>_Set measurement time._ |


## Macros Documentation

### define `BH1750_I2C_ADDRESS_DEFAULT`

```c
#define BH1750_I2C_ADDRESS_DEFAULT (0x23)
```


## Types Documentation

### typedef `bh1750_handle_t`

```c
typedef void* bh1750_handle_t;
```

### enum `bh1750_measure_mode_t`

```c
enum bh1750_measure_mode_t {
    BH1750_CONTINUE_1LX_RES = 0x10,
    BH1750_CONTINUE_HALFLX_RES = 0x11,
    BH1750_CONTINUE_4LX_RES = 0x13,
    BH1750_ONETIME_1LX_RES = 0x20,
    BH1750_ONETIME_HALFLX_RES = 0x21,
    BH1750_ONETIME_4LX_RES = 0x23
};
```


## Functions Documentation

### function `bh1750_create`

```c
bh1750_handle_t bh1750_create (
    i2c_port_t port,
    const uint16_t dev_addr
) 
```

### function `bh1750_delete`

```c
esp_err_t bh1750_delete (
    bh1750_handle_t sensor
) 
```

### function `bh1750_get_data`

```c
esp_err_t bh1750_get_data (
    bh1750_handle_t sensor,
    float *const data
) 
```

### function `bh1750_power_down`

```c
esp_err_t bh1750_power_down (
    bh1750_handle_t sensor
) 
```

### function `bh1750_power_on`

```c
esp_err_t bh1750_power_on (
    bh1750_handle_t sensor
) 
```

### function `bh1750_set_measure_mode`

```c
esp_err_t bh1750_set_measure_mode (
    bh1750_handle_t sensor,
    const bh1750_measure_mode_t cmd_measure
) 
```

### function `bh1750_set_measure_time`

```c
esp_err_t bh1750_set_measure_time (
    bh1750_handle_t sensor,
    const uint8_t measure_time
) 
```


## File components/ds18b20/include/ds18b20.h

## Classes

| Type | Name |
| ---: | :--- |
| struct | [**ds18b20\_config\_t**](#struct-ds18b20_config_t) <br>_DS18B20 configuration._ |


## Types

| Type | Name |
| ---: | :--- |
| typedef struct [**ds18b20\_device\_t**](#struct-ds18b20_device_t)\* | [**ds18b20\_device\_handle\_t**](#typedef-ds18b20_device_handle_t)  <br>_Type of DS18B20 device handle._ |

## Functions

| Type | Name |
| ---: | :--- |
|  esp\_err\_t | [**ds18b20\_del\_device**](#function-ds18b20_del_device)  <br>_Delete DS18B20 device._ |
|  esp\_err\_t | [**ds18b20\_get\_temperature**](#function-ds18b20_get_temperature)  <br>_Get temperature from DS18B20._ |
|  esp\_err\_t | [**ds18b20\_new\_device**](#function-ds18b20_new_device) (onewire\_device\_t \* device, const [**ds18b20\_config\_t**](#struct-ds18b20_config_t)\* config, [**ds18b20\_device\_handle\_t**](#struct-ds18b20_device_t)\* ret\_ds18b20) <br>_Create a new DS18B20 device based on the general 1-Wire device._ |
|  esp\_err\_t | [**ds18b20\_set\_resolution**](#function-ds18b20_set_resolution)  <br>_Set DS18B20's temperature conversion resolution._ |
|  esp\_err\_t | [**ds18b20\_trigger\_temperature\_conversion**](#function-ds18b20_trigger_temperature_conversion)  <br>_Trigger temperature conversion of DS18B20._ |

## Classes Documentation

### struct `ds18b20_config_t`



## Types Documentation

### typedef `ds18b20_device_handle_t`

```c
typedef struct ds18b20_device_t* ds18b20_device_handle_t;
```


## Functions Documentation

### function `ds18b20_del_device`

```c
esp_err_t ds18b20_del_device (
    ds18b20_device_handle_t ds18b20
) 
```

### function `ds18b20_get_temperature`

```c
esp_err_t ds18b20_get_temperature (
    ds18b20_device_handle_t ds18b20,
    float * temperature
) 
```

### function `ds18b20_new_device`

```c
esp_err_t ds18b20_new_device (
    onewire_device_t * device,
    const ds18b20_config_t * config,
    ds18b20_device_handle_t * ret_ds18b20
) 
```

### function `ds18b20_set_resolution`

```c
esp_err_t ds18b20_set_resolution (
    ds18b20_device_handle_t ds18b20,
    ds18b20_resolution_t resolution
) 
```

### function `ds18b20_trigger_temperature_conversion`

```c
esp_err_t ds18b20_trigger_temperature_conversion (
    ds18b20_device_handle_t ds18b20
) 
```


## File components/ds18b20/include/ds18b20_types.h



## Types

| Type | Name |
| ---: | :--- |
| enum  | [**ds18b20\_resolution\_t**](#enum-ds18b20_resolution_t)  <br>_DS18B20 supported resolutions._ |




## Types Documentation

### enum `ds18b20_resolution_t`

```c
enum ds18b20_resolution_t {
    DS18B20_RESOLUTION_9B,
    DS18B20_RESOLUTION_10B,
    DS18B20_RESOLUTION_11B,
    DS18B20_RESOLUTION_12B
};
```



## File components/es7210/include/es7210.h

## Classes

| Type | Name |
| ---: | :--- |
| struct | [**es7210\_codec\_config\_t**](#struct-es7210_codec_config_t) <br>_ES7210 codec config struct._ |
| struct | [**es7210\_i2c\_config\_t**](#struct-es7210_i2c_config_t) <br>_ES7210 I2C config struct._ |

## Macros

| Type | Name |
| ---: | :--- |
| define  | [**ES7210\_ADDRESS\_01**](#define-es7210_address_01)  (0x41)<br> |
| define  | [**ES7210\_ADDRESS\_10**](#define-es7210_address_10)  (0x42)<br> |
| define  | [**ES7210\_ADDRESS\_11**](#define-es7210_address_11)  (0x43)<br> |
| define  | [**ES7210\_ADDRRES\_00**](#define-es7210_addrres_00)  (0x40)<br>_I2C address of the ES7210._ |

## Types

| Type | Name |
| ---: | :--- |
| typedef struct [**es7210\_dev\_t**](#struct-es7210_dev_t)\* | [**es7210\_dev\_handle\_t**](#typedef-es7210_dev_handle_t)  <br>_Type of es7210 device handle._ |
| enum  | [**es7210\_i2s\_bits\_t**](#enum-es7210_i2s_bits_t)  <br>_Select I2S bit width for ES7210._ |
| enum  | [**es7210\_i2s\_fmt\_t**](#enum-es7210_i2s_fmt_t)  <br>_Select I2S interface format for ES7210._ |
| enum  | [**es7210\_mic\_bias\_t**](#enum-es7210_mic_bias_t)  <br>_Select MIC bias for ES7210._ |
| enum  | [**es7210\_mic\_gain\_t**](#enum-es7210_mic_gain_t)  <br>_Select MIC gain for ES7210._ |

## Functions

| Type | Name |
| ---: | :--- |
|  esp\_err\_t | [**es7210\_config\_codec**](#function-es7210_config_codec)  <br>_Configure codec-related parameters of ES7210._ |
|  esp\_err\_t | [**es7210\_config\_volume**](#function-es7210_config_volume)  <br>_Configure volume of ES7210._ |
|  esp\_err\_t | [**es7210\_del\_codec**](#function-es7210_del_codec)  <br>_Delete ES7210 device handle._ |
|  esp\_err\_t | [**es7210\_new\_codec**](#function-es7210_new_codec) (const [**es7210\_i2c\_config\_t**](#struct-es7210_i2c_config_t)\* i2c\_conf, [**es7210\_dev\_handle\_t**](#typedef-es7210_dev_handle_t)\* handle\_out) <br>_Create new ES7210 device handle._ |

## Classes Documentation

### struct `es7210_codec_config_t`

Variables:

-   bit_width  <br>
-   flags  <br>
-   i2s_format  <br>
-  uint32\_t mclk_ratio  <br>
-   mic_bias  <br>
-   mic_gain  <br>
-  uint32\_t sample_rate_hz  <br>
-  uint32\_t tdm_enable  <br>
### struct `es7210_i2c_config_t`

Variables:

-  uint8\_t i2c_addr  <br>
-  i2c\_port\_t i2c_port  <br>

## Macros Documentation

### define `ES7210_ADDRESS_01`

```c
#define ES7210_ADDRESS_01 (0x41)
```

### define `ES7210_ADDRESS_10`

```c
#define ES7210_ADDRESS_10 (0x42)
```

### define `ES7210_ADDRESS_11`

```c
#define ES7210_ADDRESS_11 (0x43)
```

### define `ES7210_ADDRRES_00`

```c
#define ES7210_ADDRRES_00 (0x40)
```


## Types Documentation

### typedef `es7210_dev_handle_t`

```c
typedef struct es7210_dev_t* es7210_dev_handle_t;
```

### enum `es7210_i2s_bits_t`

```c
enum es7210_i2s_bits_t {
    ES7210_I2S_BITS_16B = 16,
    ES7210_I2S_BITS_18B = 18,
    ES7210_I2S_BITS_20B = 20,
    ES7210_I2S_BITS_24B = 24,
    ES7210_I2S_BITS_32B = 32
};
```

### enum `es7210_i2s_fmt_t`

```c
enum es7210_i2s_fmt_t {
    ES7210_I2S_FMT_I2S = 0x00,
    ES7210_I2S_FMT_LJ = 0x01,
    ES7210_I2S_FMT_DSP_A = 0x03,
    ES7210_I2S_FMT_DSP_B = 0x13
};
```

### enum `es7210_mic_bias_t`

```c
enum es7210_mic_bias_t {
    ES7210_MIC_BIAS_2V18 = 0x00,
    ES7210_MIC_BIAS_2V26 = 0x10,
    ES7210_MIC_BIAS_2V36 = 0x20,
    ES7210_MIC_BIAS_2V45 = 0x30,
    ES7210_MIC_BIAS_2V55 = 0x40,
    ES7210_MIC_BIAS_2V66 = 0x50,
    ES7210_MIC_BIAS_2V78 = 0x60,
    ES7210_MIC_BIAS_2V87 = 0x70
};
```

### enum `es7210_mic_gain_t`

```c
enum es7210_mic_gain_t {
    ES7210_MIC_GAIN_0DB = 0,
    ES7210_MIC_GAIN_3DB = 1,
    ES7210_MIC_GAIN_6DB = 2,
    ES7210_MIC_GAIN_9DB = 3,
    ES7210_MIC_GAIN_12DB = 4,
    ES7210_MIC_GAIN_15DB = 5,
    ES7210_MIC_GAIN_18DB = 6,
    ES7210_MIC_GAIN_21DB = 7,
    ES7210_MIC_GAIN_24DB = 8,
    ES7210_MIC_GAIN_27DB = 9,
    ES7210_MIC_GAIN_30DB = 10,
    ES7210_MIC_GAIN_33DB = 11,
    ES7210_MIC_GAIN_34_5DB = 12,
    ES7210_MIC_GAIN_36DB = 13,
    ES7210_MIC_GAIN_37_5DB = 14
};
```


## Functions Documentation

### function `es7210_config_codec`

```c
esp_err_t es7210_config_codec (
    es7210_dev_handle_t handle,
    const es7210_codec_config_t * codec_conf
) 
```

### function `es7210_config_volume`

```c
esp_err_t es7210_config_volume (
    es7210_dev_handle_t handle,
    int8_t volume_db
) 
```

### function `es7210_del_codec`

```c
esp_err_t es7210_del_codec (
    es7210_dev_handle_t handle
) 
```

### function `es7210_new_codec`

```c
esp_err_t es7210_new_codec (
    const es7210_i2c_config_t * i2c_conf,
    es7210_dev_handle_t * handle_out
) 
```


## File components/es7210/priv_include/es7210_reg.h


## Macros

| Type | Name |
| ---: | :--- |
| define  | [**ES7210\_ADC12\_HPF1\_REG23**](#define-es7210_adc12_hpf1_reg23)  0x23<br> |
| define  | [**ES7210\_ADC12\_HPF2\_REG22**](#define-es7210_adc12_hpf2_reg22)  0x22<br> |
| define  | [**ES7210\_ADC1\_DIRECT\_DB\_REG1B**](#define-es7210_adc1_direct_db_reg1b)  0x1B<br> |
| define  | [**ES7210\_ADC2\_DIRECT\_DB\_REG1C**](#define-es7210_adc2_direct_db_reg1c)  0x1C<br> |
| define  | [**ES7210\_ADC34\_HPF1\_REG21**](#define-es7210_adc34_hpf1_reg21)  0x21<br> |
| define  | [**ES7210\_ADC34\_HPF2\_REG20**](#define-es7210_adc34_hpf2_reg20)  0x20        /\* HPF \*/<br> |
| define  | [**ES7210\_ADC34\_MUTERANGE\_REG14**](#define-es7210_adc34_muterange_reg14)  0x14        /\* Set mute range \*/<br> |
| define  | [**ES7210\_ADC3\_DIRECT\_DB\_REG1D**](#define-es7210_adc3_direct_db_reg1d)  0x1D<br> |
| define  | [**ES7210\_ADC4\_DIRECT\_DB\_REG1E**](#define-es7210_adc4_direct_db_reg1e)  0x1E        /\* ADC direct dB when ALC close, ALC max gain when ALC open \*/<br> |
| define  | [**ES7210\_ADC\_AUTOMUTE\_REG13**](#define-es7210_adc_automute_reg13)  0x13        /\* Set mute \*/<br> |
| define  | [**ES7210\_ALC\_SEL\_REG16**](#define-es7210_alc_sel_reg16)  0x16        /\* Set ALC mode \*/<br> |
| define  | [**ES7210\_ANALOG\_REG40**](#define-es7210_analog_reg40)  0x40        /\* ANALOG Power \*/<br> |
| define  | [**ES7210\_CLOCK\_OFF\_REG01**](#define-es7210_clock_off_reg01)  0x01        /\* Used to turn off the ADC clock \*/<br> |
| define  | [**ES7210\_LRCK\_DIVH\_REG04**](#define-es7210_lrck_divh_reg04)  0x04        /\* lrck\_divh \*/<br> |
| define  | [**ES7210\_LRCK\_DIVL\_REG05**](#define-es7210_lrck_divl_reg05)  0x05        /\* lrck\_divl \*/<br> |
| define  | [**ES7210\_MAINCLK\_REG02**](#define-es7210_mainclk_reg02)  0x02        /\* Set ADC clock frequency division \*/<br> |
| define  | [**ES7210\_MASTER\_CLK\_REG03**](#define-es7210_master_clk_reg03)  0x03        /\* MCLK source $ SCLK division \*/<br> |
| define  | [**ES7210\_MIC12\_BIAS\_REG41**](#define-es7210_mic12_bias_reg41)  0x41<br> |
| define  | [**ES7210\_MIC12\_POWER\_REG4B**](#define-es7210_mic12_power_reg4b)  0x4B        /\* MICBias & ADC & PGA Power \*/<br> |
| define  | [**ES7210\_MIC1\_GAIN\_REG43**](#define-es7210_mic1_gain_reg43)  0x43<br> |
| define  | [**ES7210\_MIC1\_POWER\_REG47**](#define-es7210_mic1_power_reg47)  0x47<br> |
| define  | [**ES7210\_MIC2\_GAIN\_REG44**](#define-es7210_mic2_gain_reg44)  0x44<br> |
| define  | [**ES7210\_MIC2\_POWER\_REG48**](#define-es7210_mic2_power_reg48)  0x48<br> |
| define  | [**ES7210\_MIC34\_BIAS\_REG42**](#define-es7210_mic34_bias_reg42)  0x42<br> |
| define  | [**ES7210\_MIC34\_POWER\_REG4C**](#define-es7210_mic34_power_reg4c)  0x4C<br> |
| define  | [**ES7210\_MIC3\_GAIN\_REG45**](#define-es7210_mic3_gain_reg45)  0x45<br> |
| define  | [**ES7210\_MIC3\_POWER\_REG49**](#define-es7210_mic3_power_reg49)  0x49<br> |
| define  | [**ES7210\_MIC4\_GAIN\_REG46**](#define-es7210_mic4_gain_reg46)  0x46<br> |
| define  | [**ES7210\_MIC4\_POWER\_REG4A**](#define-es7210_mic4_power_reg4a)  0x4A<br> |
| define  | [**ES7210\_MODE\_CONFIG\_REG08**](#define-es7210_mode_config_reg08)  0x08        /\* Set master/slave & channels \*/<br> |
| define  | [**ES7210\_OSR\_REG07**](#define-es7210_osr_reg07)  0x07<br> |
| define  | [**ES7210\_POWER\_DOWN\_REG06**](#define-es7210_power_down_reg06)  0x06        /\* power down \*/<br> |
| define  | [**ES7210\_RESET\_REG00**](#define-es7210_reset_reg00)  0x00        /\* Reset control \*/<br> |
| define  | [**ES7210\_SDP\_INTERFACE1\_REG11**](#define-es7210_sdp_interface1_reg11)  0x11        /\* Set sample & fmt \*/<br> |
| define  | [**ES7210\_SDP\_INTERFACE2\_REG12**](#define-es7210_sdp_interface2_reg12)  0x12        /\* Pins state \*/<br> |
| define  | [**ES7210\_TIME\_CONTROL0\_REG09**](#define-es7210_time_control0_reg09)  0x09        /\* Set Chip intial state period\*/<br> |
| define  | [**ES7210\_TIME\_CONTROL1\_REG0A**](#define-es7210_time_control1_reg0a)  0x0A        /\* Set Power up state period \*/<br> |




## Macros Documentation

### define `ES7210_ADC12_HPF1_REG23`

```c
#define ES7210_ADC12_HPF1_REG23 0x23
```

### define `ES7210_ADC12_HPF2_REG22`

```c
#define ES7210_ADC12_HPF2_REG22 0x22
```

### define `ES7210_ADC1_DIRECT_DB_REG1B`

```c
#define ES7210_ADC1_DIRECT_DB_REG1B 0x1B
```

### define `ES7210_ADC2_DIRECT_DB_REG1C`

```c
#define ES7210_ADC2_DIRECT_DB_REG1C 0x1C
```

### define `ES7210_ADC34_HPF1_REG21`

```c
#define ES7210_ADC34_HPF1_REG21 0x21
```

### define `ES7210_ADC34_HPF2_REG20`

```c
#define ES7210_ADC34_HPF2_REG20 0x20        /* HPF */
```

### define `ES7210_ADC34_MUTERANGE_REG14`

```c
#define ES7210_ADC34_MUTERANGE_REG14 0x14        /* Set mute range */
```

### define `ES7210_ADC3_DIRECT_DB_REG1D`

```c
#define ES7210_ADC3_DIRECT_DB_REG1D 0x1D
```

### define `ES7210_ADC4_DIRECT_DB_REG1E`

```c
#define ES7210_ADC4_DIRECT_DB_REG1E 0x1E        /* ADC direct dB when ALC close, ALC max gain when ALC open */
```

### define `ES7210_ADC_AUTOMUTE_REG13`

```c
#define ES7210_ADC_AUTOMUTE_REG13 0x13        /* Set mute */
```

### define `ES7210_ALC_SEL_REG16`

```c
#define ES7210_ALC_SEL_REG16 0x16        /* Set ALC mode */
```

### define `ES7210_ANALOG_REG40`

```c
#define ES7210_ANALOG_REG40 0x40        /* ANALOG Power */
```

### define `ES7210_CLOCK_OFF_REG01`

```c
#define ES7210_CLOCK_OFF_REG01 0x01        /* Used to turn off the ADC clock */
```

### define `ES7210_LRCK_DIVH_REG04`

```c
#define ES7210_LRCK_DIVH_REG04 0x04        /* lrck_divh */
```

### define `ES7210_LRCK_DIVL_REG05`

```c
#define ES7210_LRCK_DIVL_REG05 0x05        /* lrck_divl */
```

### define `ES7210_MAINCLK_REG02`

```c
#define ES7210_MAINCLK_REG02 0x02        /* Set ADC clock frequency division */
```

### define `ES7210_MASTER_CLK_REG03`

```c
#define ES7210_MASTER_CLK_REG03 0x03        /* MCLK source $ SCLK division */
```

### define `ES7210_MIC12_BIAS_REG41`

```c
#define ES7210_MIC12_BIAS_REG41 0x41
```

### define `ES7210_MIC12_POWER_REG4B`

```c
#define ES7210_MIC12_POWER_REG4B 0x4B        /* MICBias & ADC & PGA Power */
```

### define `ES7210_MIC1_GAIN_REG43`

```c
#define ES7210_MIC1_GAIN_REG43 0x43
```

### define `ES7210_MIC1_POWER_REG47`

```c
#define ES7210_MIC1_POWER_REG47 0x47
```

### define `ES7210_MIC2_GAIN_REG44`

```c
#define ES7210_MIC2_GAIN_REG44 0x44
```

### define `ES7210_MIC2_POWER_REG48`

```c
#define ES7210_MIC2_POWER_REG48 0x48
```

### define `ES7210_MIC34_BIAS_REG42`

```c
#define ES7210_MIC34_BIAS_REG42 0x42
```

### define `ES7210_MIC34_POWER_REG4C`

```c
#define ES7210_MIC34_POWER_REG4C 0x4C
```

### define `ES7210_MIC3_GAIN_REG45`

```c
#define ES7210_MIC3_GAIN_REG45 0x45
```

### define `ES7210_MIC3_POWER_REG49`

```c
#define ES7210_MIC3_POWER_REG49 0x49
```

### define `ES7210_MIC4_GAIN_REG46`

```c
#define ES7210_MIC4_GAIN_REG46 0x46
```

### define `ES7210_MIC4_POWER_REG4A`

```c
#define ES7210_MIC4_POWER_REG4A 0x4A
```

### define `ES7210_MODE_CONFIG_REG08`

```c
#define ES7210_MODE_CONFIG_REG08 0x08        /* Set master/slave & channels */
```

### define `ES7210_OSR_REG07`

```c
#define ES7210_OSR_REG07 0x07
```

### define `ES7210_POWER_DOWN_REG06`

```c
#define ES7210_POWER_DOWN_REG06 0x06        /* power down */
```

### define `ES7210_RESET_REG00`

```c
#define ES7210_RESET_REG00 0x00        /* Reset control */
```

### define `ES7210_SDP_INTERFACE1_REG11`

```c
#define ES7210_SDP_INTERFACE1_REG11 0x11        /* Set sample & fmt */
```

### define `ES7210_SDP_INTERFACE2_REG12`

```c
#define ES7210_SDP_INTERFACE2_REG12 0x12        /* Pins state */
```

### define `ES7210_TIME_CONTROL0_REG09`

```c
#define ES7210_TIME_CONTROL0_REG09 0x09        /* Set Chip intial state period*/
```

### define `ES7210_TIME_CONTROL1_REG0A`

```c
#define ES7210_TIME_CONTROL1_REG0A 0x0A        /* Set Power up state period */
```




## File components/es8311/include/es8311.h

## Classes

| Type | Name |
| ---: | :--- |
| struct | [**es8311\_clock\_config\_t**](#struct-es8311_clock_config_t) <br> |

## Macros

| Type | Name |
| ---: | :--- |
| define  | [**ES8311\_ADDRESS\_1**](#define-es8311_address_1)  0x19u<br> |
| define  | [**ES8311\_ADDRRES\_0**](#define-es8311_addrres_0)  0x18u<br> |

## Types

| Type | Name |
| ---: | :--- |
| typedef  | [**es8311\_clock\_config\_t**](#typedef-es8311_clock_config_t)  <br> |
| enum  | [**es8311\_fade\_t**](#enum-es8311_fade_t)  <br> |
| typedef void \* | [**es8311\_handle\_t**](#typedef-es8311_handle_t)  <br> |
| enum  | [**es8311\_mic\_gain\_t**](#enum-es8311_mic_gain_t)  <br> |
| enum  | [**es8311\_resolution\_t**](#enum-es8311_resolution_t)  <br> |
| typedef enum es8311\_resolution\_t | [**es8311\_resolution\_t**](#typedef-es8311_resolution_t)  <br> |

## Functions

| Type | Name |
| ---: | :--- |
|  es8311\_handle\_t | [**es8311\_create**](#function-es8311_create) (const i2c\_port\_t port, const uint16\_t dev\_addr) <br>_Create ES8311 object and return its handle._ |
|  void | [**es8311\_delete**](#function-es8311_delete) (es8311\_handle\_t dev) <br>_Delete ES8311 object._ |
|  esp\_err\_t | [**es8311\_init**](#function-es8311_init) (es8311\_handle\_t dev, const [**es8311\_clock\_config\_t**](#struct-es8311_clock_config_t)\*const clk\_cfg, const es8311\_resolution\_t res\_in, const es8311\_resolution\_t res\_out) <br>_Initialize ES8311._ |
|  esp\_err\_t | [**es8311\_microphone\_config**](#function-es8311_microphone_config) (es8311\_handle\_t dev, bool digital\_mic) <br>_Configure microphone._ |
|  esp\_err\_t | [**es8311\_microphone\_fade**](#function-es8311_microphone_fade) (es8311\_handle\_t dev, const es8311\_fade\_t fade) <br>_Configure fade in/out for DAC: microphone._ |
|  esp\_err\_t | [**es8311\_microphone\_gain\_set**](#function-es8311_microphone_gain_set) (es8311\_handle\_t dev, es8311\_mic\_gain\_t gain\_db) <br>_Set Microphone gain._ |
|  void | [**es8311\_register\_dump**](#function-es8311_register_dump) (es8311\_handle\_t dev) <br>_Print out ES8311 register content._ |
|  esp\_err\_t | [**es8311\_sample\_frequency\_config**](#function-es8311_sample_frequency_config) (es8311\_handle\_t dev, int mclk\_frequency, int sample\_frequency) <br>_Configure sampling frequency._ |
|  esp\_err\_t | [**es8311\_voice\_fade**](#function-es8311_voice_fade) (es8311\_handle\_t dev, const es8311\_fade\_t fade) <br>_Configure fade in/out for ADC: voice._ |
|  esp\_err\_t | [**es8311\_voice\_mute**](#function-es8311_voice_mute) (es8311\_handle\_t dev, bool enable) <br>_Mute ES8311 output._ |
|  esp\_err\_t | [**es8311\_voice\_volume\_get**](#function-es8311_voice_volume_get) (es8311\_handle\_t dev, int \* volume) <br>_Get output volume._ |
|  esp\_err\_t | [**es8311\_voice\_volume\_set**](#function-es8311_voice_volume_set) (es8311\_handle\_t dev, int volume, int \* volume\_set) <br>_Set output volume._ |

## Classes Documentation

### struct `es8311_clock_config_t`

Variables:

-  int mclk_frequency  <br>
-  bool mclk_from_mclk_pin  <br>
-  bool mclk_inverted  <br>
-  int sample_frequency  <br>
-  bool sclk_inverted  <br>

## Macros Documentation

### define `ES8311_ADDRESS_1`

```c
#define ES8311_ADDRESS_1 0x19u
```

### define `ES8311_ADDRRES_0`

```c
#define ES8311_ADDRRES_0 0x18u
```


## Types Documentation

### typedef `es8311_clock_config_t`

```c
typedef struct es8311_clock_config_t es8311_clock_config_t;
```

### enum `es8311_fade_t`

```c
enum es8311_fade_t {
    ES8311_FADE_OFF = 0,
    ES8311_FADE_4LRCK,
    ES8311_FADE_8LRCK,
    ES8311_FADE_16LRCK,
    ES8311_FADE_32LRCK,
    ES8311_FADE_64LRCK,
    ES8311_FADE_128LRCK,
    ES8311_FADE_256LRCK,
    ES8311_FADE_512LRCK,
    ES8311_FADE_1024LRCK,
    ES8311_FADE_2048LRCK,
    ES8311_FADE_4096LRCK,
    ES8311_FADE_8192LRCK,
    ES8311_FADE_16384LRCK,
    ES8311_FADE_32768LRCK,
    ES8311_FADE_65536LRCK
};
```

### typedef `es8311_handle_t`

```c
typedef void* es8311_handle_t;
```

### enum `es8311_mic_gain_t`

```c
enum es8311_mic_gain_t {
    ES8311_MIC_GAIN_MIN = -1,
    ES8311_MIC_GAIN_0DB,
    ES8311_MIC_GAIN_6DB,
    ES8311_MIC_GAIN_12DB,
    ES8311_MIC_GAIN_18DB,
    ES8311_MIC_GAIN_24DB,
    ES8311_MIC_GAIN_30DB,
    ES8311_MIC_GAIN_36DB,
    ES8311_MIC_GAIN_42DB,
    ES8311_MIC_GAIN_MAX
};
```

### enum `es8311_resolution_t`

```c
enum es8311_resolution_t {
    ES8311_RESOLUTION_16 = 16,
    ES8311_RESOLUTION_18 = 18,
    ES8311_RESOLUTION_20 = 20,
    ES8311_RESOLUTION_24 = 24,
    ES8311_RESOLUTION_32 = 32
};
```

### typedef `es8311_resolution_t`

```c
typedef enum es8311_resolution_t es8311_resolution_t;
```


## Functions Documentation

### function `es8311_create`

```c
es8311_handle_t es8311_create (
    const i2c_port_t port,
    const uint16_t dev_addr
) 
```

### function `es8311_delete`

```c
void es8311_delete (
    es8311_handle_t dev
) 
```

### function `es8311_init`

```c
esp_err_t es8311_init (
    es8311_handle_t dev,
    const es8311_clock_config_t *const clk_cfg,
    const es8311_resolution_t res_in,
    const es8311_resolution_t res_out
) 
```

### function `es8311_microphone_config`

```c
esp_err_t es8311_microphone_config (
    es8311_handle_t dev,
    bool digital_mic
) 
```

### function `es8311_microphone_fade`

```c
esp_err_t es8311_microphone_fade (
    es8311_handle_t dev,
    const es8311_fade_t fade
) 
```

### function `es8311_microphone_gain_set`

```c
esp_err_t es8311_microphone_gain_set (
    es8311_handle_t dev,
    es8311_mic_gain_t gain_db
) 
```

### function `es8311_register_dump`

```c
void es8311_register_dump (
    es8311_handle_t dev
) 
```

### function `es8311_sample_frequency_config`

```c
esp_err_t es8311_sample_frequency_config (
    es8311_handle_t dev,
    int mclk_frequency,
    int sample_frequency
) 
```

### function `es8311_voice_fade`

```c
esp_err_t es8311_voice_fade (
    es8311_handle_t dev,
    const es8311_fade_t fade
) 
```

### function `es8311_voice_mute`

```c
esp_err_t es8311_voice_mute (
    es8311_handle_t dev,
    bool enable
) 
```

### function `es8311_voice_volume_get`

```c
esp_err_t es8311_voice_volume_get (
    es8311_handle_t dev,
    int * volume
) 
```

### function `es8311_voice_volume_set`

```c
esp_err_t es8311_voice_volume_set (
    es8311_handle_t dev,
    int volume,
    int * volume_set
) 
```


## File components/es8311/priv_include/es8311_reg.h


## Macros

| Type | Name |
| ---: | :--- |
| define  | [**ES8311\_ADC\_REG15**](#define-es8311_adc_reg15)  0x15 /\* ADC, adc ramp rate, dmic sense \*/<br> |
| define  | [**ES8311\_ADC\_REG16**](#define-es8311_adc_reg16)  0x16 /\* ADC \*/<br> |
| define  | [**ES8311\_ADC\_REG17**](#define-es8311_adc_reg17)  0x17 /\* ADC, volume \*/<br> |
| define  | [**ES8311\_ADC\_REG18**](#define-es8311_adc_reg18)  0x18 /\* ADC, alc enable and winsize \*/<br> |
| define  | [**ES8311\_ADC\_REG19**](#define-es8311_adc_reg19)  0x19 /\* ADC, alc maxlevel \*/<br> |
| define  | [**ES8311\_ADC\_REG1A**](#define-es8311_adc_reg1a)  0x1A /\* ADC, alc automute \*/<br> |
| define  | [**ES8311\_ADC\_REG1B**](#define-es8311_adc_reg1b)  0x1B /\* ADC, alc automute, adc hpf s1 \*/<br> |
| define  | [**ES8311\_ADC\_REG1C**](#define-es8311_adc_reg1c)  0x1C /\* ADC, equalizer, hpf s2 \*/<br> |
| define  | [**ES8311\_CHD1\_REGFD**](#define-es8311_chd1_regfd)  0xFD /\* CHIP ID1 \*/<br> |
| define  | [**ES8311\_CHD1\_REGFD**](#define-es8311_chd1_regfd)  0xFD /\* CHIP ID1 \*/<br> |
| define  | [**ES8311\_CHD2\_REGFE**](#define-es8311_chd2_regfe)  0xFE /\* CHIP ID2 \*/<br> |
| define  | [**ES8311\_CHVER\_REGFF**](#define-es8311_chver_regff)  0xFF /\* VERSION \*/<br> |
| define  | [**ES8311\_CLK\_MANAGER\_REG01**](#define-es8311_clk_manager_reg01)  0x01 /\* select clk src for mclk, enable clock for codec \*/<br> |
| define  | [**ES8311\_CLK\_MANAGER\_REG02**](#define-es8311_clk_manager_reg02)  0x02 /\* clk divider and clk multiplier \*/<br> |
| define  | [**ES8311\_CLK\_MANAGER\_REG03**](#define-es8311_clk_manager_reg03)  0x03 /\* adc fsmode and osr  \*/<br> |
| define  | [**ES8311\_CLK\_MANAGER\_REG04**](#define-es8311_clk_manager_reg04)  0x04 /\* dac osr \*/<br> |
| define  | [**ES8311\_CLK\_MANAGER\_REG05**](#define-es8311_clk_manager_reg05)  0x05 /\* clk divier for adc and dac \*/<br> |
| define  | [**ES8311\_CLK\_MANAGER\_REG06**](#define-es8311_clk_manager_reg06)  0x06 /\* bclk inverter and divider \*/<br> |
| define  | [**ES8311\_CLK\_MANAGER\_REG07**](#define-es8311_clk_manager_reg07)  0x07 /\* tri-state, lrck divider \*/<br> |
| define  | [**ES8311\_CLK\_MANAGER\_REG08**](#define-es8311_clk_manager_reg08)  0x08 /\* lrck divider \*/<br> |
| define  | [**ES8311\_DAC\_REG31**](#define-es8311_dac_reg31)  0x31 /\* DAC, mute \*/<br> |
| define  | [**ES8311\_DAC\_REG32**](#define-es8311_dac_reg32)  0x32 /\* DAC, volume \*/<br> |
| define  | [**ES8311\_DAC\_REG33**](#define-es8311_dac_reg33)  0x33 /\* DAC, offset \*/<br> |
| define  | [**ES8311\_DAC\_REG34**](#define-es8311_dac_reg34)  0x34 /\* DAC, drc enable, drc winsize \*/<br> |
| define  | [**ES8311\_DAC\_REG35**](#define-es8311_dac_reg35)  0x35 /\* DAC, drc maxlevel, minilevel \*/<br> |
| define  | [**ES8311\_DAC\_REG37**](#define-es8311_dac_reg37)  0x37 /\* DAC, ramprate \*/<br> |
| define  | [**ES8311\_GPIO\_REG44**](#define-es8311_gpio_reg44)  0x44 /\* GPIO, dac2adc for test \*/<br> |
| define  | [**ES8311\_GP\_REG45**](#define-es8311_gp_reg45)  0x45 /\* GP CONTROL \*/<br> |
| define  | [**ES8311\_MAX\_REGISTER**](#define-es8311_max_register)  0xFF<br> |
| define  | [**ES8311\_RESET\_REG00**](#define-es8311_reset_reg00)  0x00  /\*reset digital,csm,clock manager etc.\*/<br> |
| define  | [**ES8311\_SDPIN\_REG09**](#define-es8311_sdpin_reg09)  0x09 /\* dac serial digital port \*/<br> |
| define  | [**ES8311\_SDPOUT\_REG0A**](#define-es8311_sdpout_reg0a)  0x0A /\* adc serial digital port \*/<br> |
| define  | [**ES8311\_SYSTEM\_REG0B**](#define-es8311_system_reg0b)  0x0B /\* system \*/<br> |
| define  | [**ES8311\_SYSTEM\_REG0C**](#define-es8311_system_reg0c)  0x0C /\* system \*/<br> |
| define  | [**ES8311\_SYSTEM\_REG0D**](#define-es8311_system_reg0d)  0x0D /\* system, power up/down \*/<br> |
| define  | [**ES8311\_SYSTEM\_REG0E**](#define-es8311_system_reg0e)  0x0E /\* system, power up/down \*/<br> |
| define  | [**ES8311\_SYSTEM\_REG0F**](#define-es8311_system_reg0f)  0x0F /\* system, low power \*/<br> |
| define  | [**ES8311\_SYSTEM\_REG10**](#define-es8311_system_reg10)  0x10 /\* system \*/<br> |
| define  | [**ES8311\_SYSTEM\_REG11**](#define-es8311_system_reg11)  0x11 /\* system \*/<br> |
| define  | [**ES8311\_SYSTEM\_REG12**](#define-es8311_system_reg12)  0x12 /\* system, Enable DAC \*/<br> |
| define  | [**ES8311\_SYSTEM\_REG13**](#define-es8311_system_reg13)  0x13 /\* system \*/<br> |
| define  | [**ES8311\_SYSTEM\_REG14**](#define-es8311_system_reg14)  0x14 /\* system, select DMIC, select analog pga gain \*/<br> |




## Macros Documentation

### define `ES8311_ADC_REG15`

```c
#define ES8311_ADC_REG15 0x15 /* ADC, adc ramp rate, dmic sense */
```

### define `ES8311_ADC_REG16`

```c
#define ES8311_ADC_REG16 0x16 /* ADC */
```

### define `ES8311_ADC_REG17`

```c
#define ES8311_ADC_REG17 0x17 /* ADC, volume */
```

### define `ES8311_ADC_REG18`

```c
#define ES8311_ADC_REG18 0x18 /* ADC, alc enable and winsize */
```

### define `ES8311_ADC_REG19`

```c
#define ES8311_ADC_REG19 0x19 /* ADC, alc maxlevel */
```

### define `ES8311_ADC_REG1A`

```c
#define ES8311_ADC_REG1A 0x1A /* ADC, alc automute */
```

### define `ES8311_ADC_REG1B`

```c
#define ES8311_ADC_REG1B 0x1B /* ADC, alc automute, adc hpf s1 */
```

### define `ES8311_ADC_REG1C`

```c
#define ES8311_ADC_REG1C 0x1C /* ADC, equalizer, hpf s2 */
```

### define `ES8311_CHD1_REGFD`

```c
#define ES8311_CHD1_REGFD 0xFD /* CHIP ID1 */
```

### define `ES8311_CHD1_REGFD`

```c
#define ES8311_CHD1_REGFD 0xFD /* CHIP ID1 */
```

### define `ES8311_CHD2_REGFE`

```c
#define ES8311_CHD2_REGFE 0xFE /* CHIP ID2 */
```

### define `ES8311_CHVER_REGFF`

```c
#define ES8311_CHVER_REGFF 0xFF /* VERSION */
```

### define `ES8311_CLK_MANAGER_REG01`

```c
#define ES8311_CLK_MANAGER_REG01 0x01 /* select clk src for mclk, enable clock for codec */
```

### define `ES8311_CLK_MANAGER_REG02`

```c
#define ES8311_CLK_MANAGER_REG02 0x02 /* clk divider and clk multiplier */
```

### define `ES8311_CLK_MANAGER_REG03`

```c
#define ES8311_CLK_MANAGER_REG03 0x03 /* adc fsmode and osr  */
```

### define `ES8311_CLK_MANAGER_REG04`

```c
#define ES8311_CLK_MANAGER_REG04 0x04 /* dac osr */
```

### define `ES8311_CLK_MANAGER_REG05`

```c
#define ES8311_CLK_MANAGER_REG05 0x05 /* clk divier for adc and dac */
```

### define `ES8311_CLK_MANAGER_REG06`

```c
#define ES8311_CLK_MANAGER_REG06 0x06 /* bclk inverter and divider */
```

### define `ES8311_CLK_MANAGER_REG07`

```c
#define ES8311_CLK_MANAGER_REG07 0x07 /* tri-state, lrck divider */
```

### define `ES8311_CLK_MANAGER_REG08`

```c
#define ES8311_CLK_MANAGER_REG08 0x08 /* lrck divider */
```

### define `ES8311_DAC_REG31`

```c
#define ES8311_DAC_REG31 0x31 /* DAC, mute */
```

### define `ES8311_DAC_REG32`

```c
#define ES8311_DAC_REG32 0x32 /* DAC, volume */
```

### define `ES8311_DAC_REG33`

```c
#define ES8311_DAC_REG33 0x33 /* DAC, offset */
```

### define `ES8311_DAC_REG34`

```c
#define ES8311_DAC_REG34 0x34 /* DAC, drc enable, drc winsize */
```

### define `ES8311_DAC_REG35`

```c
#define ES8311_DAC_REG35 0x35 /* DAC, drc maxlevel, minilevel */
```

### define `ES8311_DAC_REG37`

```c
#define ES8311_DAC_REG37 0x37 /* DAC, ramprate */
```

### define `ES8311_GPIO_REG44`

```c
#define ES8311_GPIO_REG44 0x44 /* GPIO, dac2adc for test */
```

### define `ES8311_GP_REG45`

```c
#define ES8311_GP_REG45 0x45 /* GP CONTROL */
```

### define `ES8311_MAX_REGISTER`

```c
#define ES8311_MAX_REGISTER 0xFF
```

### define `ES8311_RESET_REG00`

```c
#define ES8311_RESET_REG00 0x00  /*reset digital,csm,clock manager etc.*/
```

### define `ES8311_SDPIN_REG09`

```c
#define ES8311_SDPIN_REG09 0x09 /* dac serial digital port */
```

### define `ES8311_SDPOUT_REG0A`

```c
#define ES8311_SDPOUT_REG0A 0x0A /* adc serial digital port */
```

### define `ES8311_SYSTEM_REG0B`

```c
#define ES8311_SYSTEM_REG0B 0x0B /* system */
```

### define `ES8311_SYSTEM_REG0C`

```c
#define ES8311_SYSTEM_REG0C 0x0C /* system */
```

### define `ES8311_SYSTEM_REG0D`

```c
#define ES8311_SYSTEM_REG0D 0x0D /* system, power up/down */
```

### define `ES8311_SYSTEM_REG0E`

```c
#define ES8311_SYSTEM_REG0E 0x0E /* system, power up/down */
```

### define `ES8311_SYSTEM_REG0F`

```c
#define ES8311_SYSTEM_REG0F 0x0F /* system, low power */
```

### define `ES8311_SYSTEM_REG10`

```c
#define ES8311_SYSTEM_REG10 0x10 /* system */
```

### define `ES8311_SYSTEM_REG11`

```c
#define ES8311_SYSTEM_REG11 0x11 /* system */
```

### define `ES8311_SYSTEM_REG12`

```c
#define ES8311_SYSTEM_REG12 0x12 /* system, Enable DAC */
```

### define `ES8311_SYSTEM_REG13`

```c
#define ES8311_SYSTEM_REG13 0x13 /* system */
```

### define `ES8311_SYSTEM_REG14`

```c
#define ES8311_SYSTEM_REG14 0x14 /* system, select DMIC, select analog pga gain */
```




## File components/esp_lvgl_port/include/esp_lvgl_port.h

## Classes

| Type | Name |
| ---: | :--- |
| struct | [**lvgl\_port\_cfg\_t**](#struct-lvgl_port_cfg_t) <br>_Init configuration structure._ |
| struct | [**lvgl\_port\_display\_cfg\_t**](#struct-lvgl_port_display_cfg_t) <br>_Configuration display structure._ |
| struct | [**lvgl\_port\_rotation\_cfg\_t**](#struct-lvgl_port_rotation_cfg_t) <br>_Rotation configuration._ |

## Macros

| Type | Name |
| ---: | :--- |
| define  | [**ESP\_LVGL\_PORT\_INIT\_CONFIG**](#define-esp_lvgl_port_init_config) () <br>_LVGL port configuration structure._ |


## Functions

| Type | Name |
| ---: | :--- |
|  lv\_disp\_t \* | [**lvgl\_port\_add\_disp**](#function-lvgl_port_add_disp) (const [**lvgl\_port\_display\_cfg\_t**](#struct-lvgl_port_display_cfg_t)\* disp\_cfg) <br>_Add display handling to LVGL._ |
|  esp\_err\_t | [**lvgl\_port\_deinit**](#function-lvgl_port_deinit) (void) <br>_Deinitialize LVGL portation._ |
|  void | [**lvgl\_port\_flush\_ready**](#function-lvgl_port_flush_ready) (lv\_disp\_t \* disp) <br>_Notify LVGL, that data was flushed to LCD display._ |
|  esp\_err\_t | [**lvgl\_port\_init**](#function-lvgl_port_init) (const [**lvgl\_port\_cfg\_t**](#struct-lvgl_port_cfg_t)\* cfg) <br>_Initialize LVGL portation._ |
|  bool | [**lvgl\_port\_lock**](#function-lvgl_port_lock) (uint32\_t timeout\_ms) <br>_Take LVGL mutex._ |
|  esp\_err\_t | [**lvgl\_port\_remove\_disp**](#function-lvgl_port_remove_disp) (lv\_disp\_t \* disp) <br>_Remove display handling from LVGL._ |
|  void | [**lvgl\_port\_unlock**](#function-lvgl_port_unlock) (void) <br>_Give LVGL mutex._ |

## Classes Documentation

### struct `lvgl_port_cfg_t`

Variables:

-  int task_affinity  <br>
-  int task_max_sleep_ms  <br>
-  int task_priority  <br>
-  int task_stack  <br>
-  int timer_period_ms  <br>
### struct `lvgl_port_display_cfg_t`

Variables:

-  unsigned int buff_dma  <br>
-  unsigned int buff_spiram  <br>
-  uint32\_t buffer_size  <br>
-  bool double_buffer  <br>
-   flags  <br>
-  uint32\_t hres  <br>
-  esp\_lcd\_panel\_io\_handle\_t io_handle  <br>
-  bool monochrome  <br>
-  esp\_lcd\_panel\_handle\_t panel_handle  <br>
-   rotation  <br>
-  uint32\_t vres  <br>
### struct `lvgl_port_rotation_cfg_t`

Variables:

-  bool mirror_x  <br>
-  bool mirror_y  <br>
-  bool swap_xy  <br>

## Macros Documentation

### define `ESP_LVGL_PORT_INIT_CONFIG`

```c
#define ESP_LVGL_PORT_INIT_CONFIG (
    
) {                               \
        .task_priority = 4,       \
        .task_stack = 4096,       \
        .task_affinity = -1,      \
        .task_max_sleep_ms = 500, \
        .timer_period_ms = 5,     \
    }
```



## Functions Documentation

### function `lvgl_port_add_disp`

```c
lv_disp_t * lvgl_port_add_disp (
    const lvgl_port_display_cfg_t * disp_cfg
) 
```

### function `lvgl_port_deinit`

```c
esp_err_t lvgl_port_deinit (
    void
) 
```

### function `lvgl_port_flush_ready`

```c
void lvgl_port_flush_ready (
    lv_disp_t * disp
) 
```

### function `lvgl_port_init`

```c
esp_err_t lvgl_port_init (
    const lvgl_port_cfg_t * cfg
) 
```

### function `lvgl_port_lock`

```c
bool lvgl_port_lock (
    uint32_t timeout_ms
) 
```

### function `lvgl_port_remove_disp`

```c
esp_err_t lvgl_port_remove_disp (
    lv_disp_t * disp
) 
```

### function `lvgl_port_unlock`

```c
void lvgl_port_unlock (
    void
) 
```


## File components/fbm320/include/fbm320.h


## Macros

| Type | Name |
| ---: | :--- |
| define  | [**FBM320\_I2C\_ADDRESS\_0**](#define-fbm320_i2c_address_0)  0x6Cu<br>_FMB320 configurable I2C address._ |
| define  | [**FBM320\_I2C\_ADDRESS\_1**](#define-fbm320_i2c_address_1)  0x6Du<br> |
| define  | [**FBM320\_WHO\_AM\_I\_VAL**](#define-fbm320_who_am_i_val)  0x42u<br>_Device Identification value._ |

## Types

| Type | Name |
| ---: | :--- |
| typedef void \* | [**fbm320\_handle\_t**](#typedef-fbm320_handle_t)  <br> |
| enum  | [**fbm320\_measure\_mode\_t**](#enum-fbm320_measure_mode_t)  <br> |

## Functions

| Type | Name |
| ---: | :--- |
|  fbm320\_handle\_t | [**fbm320\_create**](#function-fbm320_create) (i2c\_port\_t port, const uint16\_t dev\_addr) <br>_Create sensor object and return a sensor handle._ |
|  void | [**fbm320\_delete**](#function-fbm320_delete) (fbm320\_handle\_t sensor) <br>_Delete and release a sensor object._ |
|  esp\_err\_t | [**fbm320\_get\_data**](#function-fbm320_get_data) (fbm320\_handle\_t sensor, const fbm320\_measure\_mode\_t meas\_mode, int32\_t \*const temperature, int32\_t \*const pressure) <br>_Get pressure and temperature from FBM320._ |
|  esp\_err\_t | [**fbm320\_get\_deviceid**](#function-fbm320_get_deviceid) (fbm320\_handle\_t sensor, uint8\_t \*const deviceid) <br>_Get device identification of FBM320._ |
|  esp\_err\_t | [**fbm320\_init**](#function-fbm320_init) (fbm320\_handle\_t sensor) <br>_Init barometer FBM320._ |


## Macros Documentation

### define `FBM320_I2C_ADDRESS_0`

```c
#define FBM320_I2C_ADDRESS_0 0x6Cu
```

### define `FBM320_I2C_ADDRESS_1`

```c
#define FBM320_I2C_ADDRESS_1 0x6Du
```

### define `FBM320_WHO_AM_I_VAL`

```c
#define FBM320_WHO_AM_I_VAL 0x42u
```


## Types Documentation

### typedef `fbm320_handle_t`

```c
typedef void* fbm320_handle_t;
```

### enum `fbm320_measure_mode_t`

```c
enum fbm320_measure_mode_t {
    FBM320_MEAS_PRESS_OSR_1024 = 0x34,
    FBM320_MEAS_PRESS_OSR_2048 = 0x74,
    FBM320_MEAS_PRESS_OSR_4096 = 0xB4,
    FBM320_MEAS_PRESS_OSR_8192 = 0xF4
};
```


## Functions Documentation

### function `fbm320_create`

```c
fbm320_handle_t fbm320_create (
    i2c_port_t port,
    const uint16_t dev_addr
) 
```

### function `fbm320_delete`

```c
void fbm320_delete (
    fbm320_handle_t sensor
) 
```

### function `fbm320_get_data`

```c
esp_err_t fbm320_get_data (
    fbm320_handle_t sensor,
    const fbm320_measure_mode_t meas_mode,
    int32_t *const temperature,
    int32_t *const pressure
) 
```

### function `fbm320_get_deviceid`

```c
esp_err_t fbm320_get_deviceid (
    fbm320_handle_t sensor,
    uint8_t *const deviceid
) 
```

### function `fbm320_init`

```c
esp_err_t fbm320_init (
    fbm320_handle_t sensor
) 
```


## File components/hts221/include/hts221.h

## Classes

| Type | Name |
| ---: | :--- |
| struct | [**hts221\_config\_t**](#struct-hts221_config_t) <br>_HTS221 Init structure definition._ |
| struct | [**hts221\_drdy\_config\_t**](#struct-hts221_drdy_config_t) <br>_Configuration structure for DRDY mode._ |

## Macros

| Type | Name |
| ---: | :--- |
| define  | [**HTS221\_WHO\_AM\_I\_VAL**](#define-hts221_who_am_i_val)  ((uint8\_t)0xBC)<br>_Device Identification value._ |

## Types

| Type | Name |
| ---: | :--- |
| enum  | [**hts221\_avgh\_t**](#enum-hts221_avgh_t)  <br>_Humidity average._ |
| enum  | [**hts221\_avgt\_t**](#enum-hts221_avgt_t)  <br>_Temperature average._ |
| typedef void(\* | [**hts221\_drdy\_callback\_t**](#typedef-hts221_drdy_callback_t)  <br>_Callback function type for DRDY mode._ |
| enum  | [**hts221\_drdylevel\_t**](#enum-hts221_drdylevel_t)  <br>_Active level of DRDY pin._ |
| typedef void \* | [**hts221\_handle\_t**](#typedef-hts221_handle_t)  <br> |
| enum  | [**hts221\_odr\_t**](#enum-hts221_odr_t)  <br>_Output data rate configuration._ |
| enum  | [**hts221\_outputtype\_t**](#enum-hts221_outputtype_t)  <br>_Push-pull/Open Drain selection on DRDY pin._ |

## Functions

| Type | Name |
| ---: | :--- |
|  hts221\_handle\_t | [**hts221\_create**](#function-hts221_create) (const i2c\_port\_t port) <br>_Create sensor object and return a sensor handle._ |
|  void | [**hts221\_delete**](#function-hts221_delete) (hts221\_handle\_t sensor) <br>_Delete and release a sensor object._ |
|  esp\_err\_t | [**hts221\_drdy\_disable**](#function-hts221_drdy_disable) (hts221\_handle\_t sensor) <br>_Disable DRDY mode._ |
|  esp\_err\_t | [**hts221\_drdy\_enable**](#function-hts221_drdy_enable) (hts221\_handle\_t sensor, const [**hts221\_drdy\_config\_t**](#struct-hts221_drdy_config_t)\*const config) <br>_Enable DRDY mode._ |
|  esp\_err\_t | [**hts221\_get\_config**](#function-hts221_get_config) (hts221\_handle\_t sensor, [**hts221\_config\_t**](#struct-hts221_config_t)\*const hts221\_config) <br>_Get configration of HTS221._ |
|  esp\_err\_t | [**hts221\_get\_deviceid**](#function-hts221_get_deviceid) (hts221\_handle\_t sensor, uint8\_t \*const deviceid) <br>_Get device identification of HTS221._ |
|  esp\_err\_t | [**hts221\_get\_humidity**](#function-hts221_get_humidity) (hts221\_handle\_t sensor, int16\_t \*const humidity) <br>_Read HTS221 Humidity output registers, and calculate humidity._ |
|  esp\_err\_t | [**hts221\_get\_temperature**](#function-hts221_get_temperature) (hts221\_handle\_t sensor, int16\_t \*const temperature) <br>_Read HTS221 temperature output registers, and calculate temperature._ |
|  esp\_err\_t | [**hts221\_init**](#function-hts221_init) (hts221\_handle\_t sensor, const [**hts221\_config\_t**](#struct-hts221_config_t)\*const hts221\_config) <br>_Init HTS221 sensor object._ |
|  esp\_err\_t | [**hts221\_set\_activate**](#function-hts221_set_activate) (hts221\_handle\_t sensor) <br>_Activate HTS221._ |
|  esp\_err\_t | [**hts221\_set\_avgh**](#function-hts221_set_avgh)  <br>_Set humidity average._ |
|  esp\_err\_t | [**hts221\_set\_avgt**](#function-hts221_set_avgt)  <br>_Set temperature average._ |
|  esp\_err\_t | [**hts221\_set\_bdumode**](#function-hts221_set_bdumode) (hts221\_handle\_t sensor, const bool status) <br>_Enable block data update._ |
|  esp\_err\_t | [**hts221\_set\_config**](#function-hts221_set_config) (hts221\_handle\_t sensor, const [**hts221\_config\_t**](#struct-hts221_config_t)\*const hts221\_config) <br>_Set configration of HTS221._ |
|  esp\_err\_t | [**hts221\_set\_heaterstate**](#function-hts221_set_heaterstate) (hts221\_handle\_t sensor, const bool status) <br>_Enable heater._ |
|  esp\_err\_t | [**hts221\_set\_odr**](#function-hts221_set_odr)  <br>_Set output data rate._ |
|  esp\_err\_t | [**hts221\_set\_powerdown**](#function-hts221_set_powerdown) (hts221\_handle\_t sensor) <br>_Set HTS221 as power down mode._ |
|  esp\_err\_t | [**hts221\_start\_oneshot**](#function-hts221_start_oneshot) (hts221\_handle\_t sensor) <br>_Enable one-shot mode._ |

## Classes Documentation

### struct `hts221_config_t`

Variables:

-   avg_h  <br>
-   avg_t  <br>
-  bool bdu_status  <br>
-   odr  <br>
### struct `hts221_drdy_config_t`

Variables:

-   drdy_callback  <br>
-  gpio\_num\_t drdy_pin  <br>
-  UBaseType\_t drdy_task_priority  <br>
-   irq_level  <br>
-   irq_output_type  <br>

## Macros Documentation

### define `HTS221_WHO_AM_I_VAL`

```c
#define HTS221_WHO_AM_I_VAL ((uint8_t)0xBC)
```


## Types Documentation

### enum `hts221_avgh_t`

```c
enum hts221_avgh_t {
    HTS221_AVGH_4 = 0x00,
    HTS221_AVGH_8 = 0x01,
    HTS221_AVGH_16 = 0x02,
    HTS221_AVGH_32 = 0x03,
    HTS221_AVGH_64 = 0x04,
    HTS221_AVGH_128 = 0x05,
    HTS221_AVGH_256 = 0x06,
    HTS221_AVGH_512 = 0x07
};
```

### enum `hts221_avgt_t`

```c
enum hts221_avgt_t {
    HTS221_AVGT_2 = 0x00,
    HTS221_AVGT_4 = 0x08,
    HTS221_AVGT_8 = 0x10,
    HTS221_AVGT_16 = 0x18,
    HTS221_AVGT_32 = 0x20,
    HTS221_AVGT_64 = 0x28,
    HTS221_AVGT_128 = 0x30,
    HTS221_AVGT_256 = 0x38
};
```

### typedef `hts221_drdy_callback_t`

```c
typedef void(* hts221_drdy_callback_t) (int16_t humidity, int16_t temperature);
```

### enum `hts221_drdylevel_t`

```c
enum hts221_drdylevel_t {
    HTS221_HIGH_LVL = 0x00,
    HTS221_LOW_LVL = 0x80
};
```

### typedef `hts221_handle_t`

```c
typedef void* hts221_handle_t;
```

### enum `hts221_odr_t`

```c
enum hts221_odr_t {
    HTS221_ODR_ONE_SHOT = 0x00,
    HTS221_ODR_1HZ = 0x01,
    HTS221_ODR_7HZ = 0x02,
    HTS221_ODR_12_5HZ = 0x03
};
```

### enum `hts221_outputtype_t`

```c
enum hts221_outputtype_t {
    HTS221_PUSHPULL = 0x00,
    HTS221_OPENDRAIN = 0x40
};
```


## Functions Documentation

### function `hts221_create`

```c
hts221_handle_t hts221_create (
    const i2c_port_t port
) 
```

### function `hts221_delete`

```c
void hts221_delete (
    hts221_handle_t sensor
) 
```

### function `hts221_drdy_disable`

```c
esp_err_t hts221_drdy_disable (
    hts221_handle_t sensor
) 
```

### function `hts221_drdy_enable`

```c
esp_err_t hts221_drdy_enable (
    hts221_handle_t sensor,
    const hts221_drdy_config_t *const config
) 
```

### function `hts221_get_config`

```c
esp_err_t hts221_get_config (
    hts221_handle_t sensor,
    hts221_config_t *const hts221_config
) 
```

### function `hts221_get_deviceid`

```c
esp_err_t hts221_get_deviceid (
    hts221_handle_t sensor,
    uint8_t *const deviceid
) 
```

### function `hts221_get_humidity`

```c
esp_err_t hts221_get_humidity (
    hts221_handle_t sensor,
    int16_t *const humidity
) 
```

### function `hts221_get_temperature`

```c
esp_err_t hts221_get_temperature (
    hts221_handle_t sensor,
    int16_t *const temperature
) 
```

### function `hts221_init`

```c
esp_err_t hts221_init (
    hts221_handle_t sensor,
    const hts221_config_t *const hts221_config
) 
```

### function `hts221_set_activate`

```c
esp_err_t hts221_set_activate (
    hts221_handle_t sensor
) 
```

### function `hts221_set_avgh`

```c
esp_err_t hts221_set_avgh (
    hts221_handle_t sensor,
    const hts221_avgh_t avgh
) 
```

### function `hts221_set_avgt`

```c
esp_err_t hts221_set_avgt (
    hts221_handle_t sensor,
    const hts221_avgt_t avgt
) 
```

### function `hts221_set_bdumode`

```c
esp_err_t hts221_set_bdumode (
    hts221_handle_t sensor,
    const bool status
) 
```

### function `hts221_set_config`

```c
esp_err_t hts221_set_config (
    hts221_handle_t sensor,
    const hts221_config_t *const hts221_config
) 
```

### function `hts221_set_heaterstate`

```c
esp_err_t hts221_set_heaterstate (
    hts221_handle_t sensor,
    const bool status
) 
```

### function `hts221_set_odr`

```c
esp_err_t hts221_set_odr (
    hts221_handle_t sensor,
    const hts221_odr_t odr
) 
```

### function `hts221_set_powerdown`

```c
esp_err_t hts221_set_powerdown (
    hts221_handle_t sensor
) 
```

### function `hts221_start_oneshot`

```c
esp_err_t hts221_start_oneshot (
    hts221_handle_t sensor
) 
```


## File components/hts221/include/hts221_reg.h


## Macros

| Type | Name |
| ---: | :--- |
| define  | [**HTS221\_AVGH\_MASK**](#define-hts221_avgh_mask)  ((uint8\_t)0x07)<br> |
| define  | [**HTS221\_AVGT\_MASK**](#define-hts221_avgt_mask)  ((uint8\_t)0x38)<br> |
| define  | [**HTS221\_AV\_CONF\_REG**](#define-hts221_av_conf_reg)  ((uint8\_t)0x10)<br>_Humidity and temperature average mode register._ |
| define  | [**HTS221\_BDU\_BIT**](#define-hts221_bdu_bit)  2u<br> |
| define  | [**HTS221\_BDU\_MASK**](#define-hts221_bdu_mask)  ((uint8\_t)0x04)<br> |
| define  | [**HTS221\_BOOT\_MASK**](#define-hts221_boot_mask)  ((uint8\_t)0x80)<br> |
| define  | [**HTS221\_CALIBRATION\_DATA\_SIZE**](#define-hts221_calibration_data_size)  16u<br> |
| define  | [**HTS221\_CALIBRATION\_DATA\_START**](#define-hts221_calibration_data_start)  ((uint8\_t)0x30)<br> |
| define  | [**HTS221\_CTRL\_REG1**](#define-hts221_ctrl_reg1)  ((uint8\_t)0x20)<br>_Control register 1._ |
| define  | [**HTS221\_CTRL\_REG2**](#define-hts221_ctrl_reg2)  ((uint8\_t)0x21)<br>_Control register 2._ |
| define  | [**HTS221\_CTRL\_REG3**](#define-hts221_ctrl_reg3)  ((uint8\_t)0x22)<br>_Control register 3._ |
| define  | [**HTS221\_DRDY\_BIT**](#define-hts221_drdy_bit)  2u<br> |
| define  | [**HTS221\_DRDY\_H\_L\_MASK**](#define-hts221_drdy_h_l_mask)  ((uint8\_t)0x80)<br> |
| define  | [**HTS221\_DRDY\_MASK**](#define-hts221_drdy_mask)  ((uint8\_t)0x04)<br> |
| define  | [**HTS221\_HEATER\_BIT**](#define-hts221_heater_bit)  1u<br> |
| define  | [**HTS221\_HEATER\_MASK**](#define-hts221_heater_mask)  ((uint8\_t)0x02)<br> |
| define  | [**HTS221\_HR\_OUT\_L\_REG**](#define-hts221_hr_out_l_reg)  ((uint8\_t)0x28)<br>_Humidity data (LSB)._ |
| define  | [**HTS221\_ODR\_MASK**](#define-hts221_odr_mask)  ((uint8\_t)0x03)<br> |
| define  | [**HTS221\_ONE\_SHOT\_MASK**](#define-hts221_one_shot_mask)  ((uint8\_t)0x01)<br> |
| define  | [**HTS221\_PD\_BIT**](#define-hts221_pd_bit)  7u<br> |
| define  | [**HTS221\_PD\_MASK**](#define-hts221_pd_mask)  ((uint8\_t)0x80)<br> |
| define  | [**HTS221\_PP\_OD\_MASK**](#define-hts221_pp_od_mask)  ((uint8\_t)0x40)<br> |
| define  | [**HTS221\_TEMP\_OUT\_L\_REG**](#define-hts221_temp_out_l_reg)  ((uint8\_t)0x2A)<br>_Temperature data (LSB)._ |
| define  | [**HTS221\_WHO\_AM\_I\_REG**](#define-hts221_who_am_i_reg)  ((uint8\_t)0x0F)<br>_Device Identification register._ |




## Macros Documentation

### define `HTS221_AVGH_MASK`

```c
#define HTS221_AVGH_MASK ((uint8_t)0x07)
```

### define `HTS221_AVGT_MASK`

```c
#define HTS221_AVGT_MASK ((uint8_t)0x38)
```

### define `HTS221_AV_CONF_REG`

```c
#define HTS221_AV_CONF_REG ((uint8_t)0x10)
```

### define `HTS221_BDU_BIT`

```c
#define HTS221_BDU_BIT 2u
```

### define `HTS221_BDU_MASK`

```c
#define HTS221_BDU_MASK ((uint8_t)0x04)
```

### define `HTS221_BOOT_MASK`

```c
#define HTS221_BOOT_MASK ((uint8_t)0x80)
```

### define `HTS221_CALIBRATION_DATA_SIZE`

```c
#define HTS221_CALIBRATION_DATA_SIZE 16u
```

### define `HTS221_CALIBRATION_DATA_START`

```c
#define HTS221_CALIBRATION_DATA_START ((uint8_t)0x30)
```

### define `HTS221_CTRL_REG1`

```c
#define HTS221_CTRL_REG1 ((uint8_t)0x20)
```

### define `HTS221_CTRL_REG2`

```c
#define HTS221_CTRL_REG2 ((uint8_t)0x21)
```

### define `HTS221_CTRL_REG3`

```c
#define HTS221_CTRL_REG3 ((uint8_t)0x22)
```

### define `HTS221_DRDY_BIT`

```c
#define HTS221_DRDY_BIT 2u
```

### define `HTS221_DRDY_H_L_MASK`

```c
#define HTS221_DRDY_H_L_MASK ((uint8_t)0x80)
```

### define `HTS221_DRDY_MASK`

```c
#define HTS221_DRDY_MASK ((uint8_t)0x04)
```

### define `HTS221_HEATER_BIT`

```c
#define HTS221_HEATER_BIT 1u
```

### define `HTS221_HEATER_MASK`

```c
#define HTS221_HEATER_MASK ((uint8_t)0x02)
```

### define `HTS221_HR_OUT_L_REG`

```c
#define HTS221_HR_OUT_L_REG ((uint8_t)0x28)
```

### define `HTS221_ODR_MASK`

```c
#define HTS221_ODR_MASK ((uint8_t)0x03)
```

### define `HTS221_ONE_SHOT_MASK`

```c
#define HTS221_ONE_SHOT_MASK ((uint8_t)0x01)
```

### define `HTS221_PD_BIT`

```c
#define HTS221_PD_BIT 7u
```

### define `HTS221_PD_MASK`

```c
#define HTS221_PD_MASK ((uint8_t)0x80)
```

### define `HTS221_PP_OD_MASK`

```c
#define HTS221_PP_OD_MASK ((uint8_t)0x40)
```

### define `HTS221_TEMP_OUT_L_REG`

```c
#define HTS221_TEMP_OUT_L_REG ((uint8_t)0x2A)
```

### define `HTS221_WHO_AM_I_REG`

```c
#define HTS221_WHO_AM_I_REG ((uint8_t)0x0F)
```




## File components/io_expander/esp_io_expander/include/esp_io_expander.h

## Classes

| Type | Name |
| ---: | :--- |
| struct | [**esp\_io\_expander\_config\_t**](#struct-esp_io_expander_config_t) <br>_IO Expander Configuration Type._ |
| struct | [**esp\_io\_expander\_s**](#struct-esp_io_expander_s) <br> |

## Macros

| Type | Name |
| ---: | :--- |
| define  | [**IO\_COUNT\_MAX**](#define-io_count_max)  (sizeof(uint32\_t) \* 8)<br> |

## Types

| Type | Name |
| ---: | :--- |
| enum  | [**esp\_io\_expander\_dir\_t**](#enum-esp_io_expander_dir_t)  <br>_IO Expander Pin direction._ |
| typedef [**esp\_io\_expander\_t**](#typedef-esp_io_expander_t)\* | [**esp\_io\_expander\_handle\_t**](#typedef-esp_io_expander_handle_t)  <br> |
| enum  | [**esp\_io\_expander\_pin\_num\_t**](#enum-esp_io_expander_pin_num_t)  <br>_IO Expander Pin Num._ |
| typedef  | [**esp\_io\_expander\_t**](#typedef-esp_io_expander_t)  <br>_IO Expander Device Type._ |

## Functions

| Type | Name |
| ---: | :--- |
|  esp\_err\_t | [**esp\_io\_expander\_del**](#function-esp_io_expander_del)  <br>_Delete device._ |
|  esp\_err\_t | [**esp\_io\_expander\_get\_level**](#function-esp_io_expander_get_level)  <br>_Get the intput level of a set of target IOs._ |
|  esp\_err\_t | [**esp\_io\_expander\_print\_state**](#function-esp_io_expander_print_state)  <br>_Print the current status of each IO of the device, including direction, input level and output level._ |
|  esp\_err\_t | [**esp\_io\_expander\_reset**](#function-esp_io_expander_reset)  <br>_Reset the device to its initial status._ |
|  esp\_err\_t | [**esp\_io\_expander\_set\_dir**](#function-esp_io_expander_set_dir)  <br>_Set the direction of a set of target IOs._ |
|  esp\_err\_t | [**esp\_io\_expander\_set\_level**](#function-esp_io_expander_set_level)  <br>_Set the output level of a set of target IOs._ |

## Classes Documentation

### struct `esp_io_expander_config_t`

Variables:

-  uint8\_t dir_out_bit_zero  <br>
-   flags  <br>
-  uint8\_t input_high_bit_zero  <br>
-  uint8\_t io_count  <br>
-  uint8\_t output_high_bit_zero  <br>
### struct `esp_io_expander_s`

Variables:

-   config  <br>_Configuration structure._
-  esp\_err\_t(\* del  <br>_Delete device (mandatory)_
-  esp\_err\_t(\* read_direction_reg  <br>_Read value from directioin register (mandatory)_
-  esp\_err\_t(\* read_input_reg  <br>_Read value from input register (mandatory)_
-  esp\_err\_t(\* read_output_reg  <br>_Read value from output register (mandatory)_
-  esp\_err\_t(\* reset  <br>_Reset the device to its initial state (mandatory)_
-  esp\_err\_t(\* write_direction_reg  <br>_Write value to direction register (mandatory)_
-  esp\_err\_t(\* write_output_reg  <br>_Write value to output register (mandatory)_

## Macros Documentation

### define `IO_COUNT_MAX`

```c
#define IO_COUNT_MAX (sizeof(uint32_t) * 8)
```


## Types Documentation

### enum `esp_io_expander_dir_t`

```c
enum esp_io_expander_dir_t {
    IO_EXPANDER_INPUT,
    IO_EXPANDER_OUTPUT
};
```

### typedef `esp_io_expander_handle_t`

```c
typedef esp_io_expander_t* esp_io_expander_handle_t;
```

### enum `esp_io_expander_pin_num_t`

```c
enum esp_io_expander_pin_num_t {
    IO_EXPANDER_PIN_NUM_0 = (1ULL << 0),
    IO_EXPANDER_PIN_NUM_1 = (1ULL << 1),
    IO_EXPANDER_PIN_NUM_2 = (1ULL << 2),
    IO_EXPANDER_PIN_NUM_3 = (1ULL << 3),
    IO_EXPANDER_PIN_NUM_4 = (1ULL << 4),
    IO_EXPANDER_PIN_NUM_5 = (1ULL << 5),
    IO_EXPANDER_PIN_NUM_6 = (1ULL << 6),
    IO_EXPANDER_PIN_NUM_7 = (1ULL << 7),
    IO_EXPANDER_PIN_NUM_8 = (1ULL << 8),
    IO_EXPANDER_PIN_NUM_9 = (1ULL << 9),
    IO_EXPANDER_PIN_NUM_10 = (1ULL << 10),
    IO_EXPANDER_PIN_NUM_11 = (1ULL << 11),
    IO_EXPANDER_PIN_NUM_12 = (1ULL << 12),
    IO_EXPANDER_PIN_NUM_13 = (1ULL << 13),
    IO_EXPANDER_PIN_NUM_14 = (1ULL << 14),
    IO_EXPANDER_PIN_NUM_15 = (1ULL << 15),
    IO_EXPANDER_PIN_NUM_16 = (1ULL << 16),
    IO_EXPANDER_PIN_NUM_17 = (1ULL << 17),
    IO_EXPANDER_PIN_NUM_18 = (1ULL << 18),
    IO_EXPANDER_PIN_NUM_19 = (1ULL << 19),
    IO_EXPANDER_PIN_NUM_20 = (1ULL << 20),
    IO_EXPANDER_PIN_NUM_21 = (1ULL << 21),
    IO_EXPANDER_PIN_NUM_22 = (1ULL << 22),
    IO_EXPANDER_PIN_NUM_23 = (1ULL << 23),
    IO_EXPANDER_PIN_NUM_24 = (1ULL << 24),
    IO_EXPANDER_PIN_NUM_25 = (1ULL << 25),
    IO_EXPANDER_PIN_NUM_26 = (1ULL << 26),
    IO_EXPANDER_PIN_NUM_27 = (1ULL << 27),
    IO_EXPANDER_PIN_NUM_28 = (1ULL << 28),
    IO_EXPANDER_PIN_NUM_29 = (1ULL << 29),
    IO_EXPANDER_PIN_NUM_30 = (1ULL << 30),
    IO_EXPANDER_PIN_NUM_31 = (1ULL << 31)
};
```

### typedef `esp_io_expander_t`

```c
typedef struct esp_io_expander_s esp_io_expander_t;
```


## Functions Documentation

### function `esp_io_expander_del`

```c
esp_err_t esp_io_expander_del (
    esp_io_expander_handle_t handle
) 
```

### function `esp_io_expander_get_level`

```c
esp_err_t esp_io_expander_get_level (
    esp_io_expander_handle_t handle,
    uint32_t pin_num_mask,
    uint32_t * level_mask
) 
```

### function `esp_io_expander_print_state`

```c
esp_err_t esp_io_expander_print_state (
    esp_io_expander_handle_t handle
) 
```

### function `esp_io_expander_reset`

```c
esp_err_t esp_io_expander_reset (
    esp_io_expander_handle_t handle
) 
```

### function `esp_io_expander_set_dir`

```c
esp_err_t esp_io_expander_set_dir (
    esp_io_expander_handle_t handle,
    uint32_t pin_num_mask,
    esp_io_expander_dir_t direction
) 
```

### function `esp_io_expander_set_level`

```c
esp_err_t esp_io_expander_set_level (
    esp_io_expander_handle_t handle,
    uint32_t pin_num_mask,
    uint8_t level
) 
```


## File components/io_expander/esp_io_expander_ht8574/include/esp_io_expander_ht8574.h


## Macros

| Type | Name |
| ---: | :--- |
| define  | [**ESP\_IO\_EXPANDER\_I2C\_HT8574\_ADDRESS\_000**](#define-esp_io_expander_i2c_ht8574_address_000)  (0x38)<br>_I2C address of the ht8574._ |
| define  | [**ESP\_IO\_EXPANDER\_I2C\_HT8574\_ADDRESS\_001**](#define-esp_io_expander_i2c_ht8574_address_001)  (0x29)<br> |
| define  | [**ESP\_IO\_EXPANDER\_I2C\_HT8574\_ADDRESS\_010**](#define-esp_io_expander_i2c_ht8574_address_010)  (0x2A)<br> |
| define  | [**ESP\_IO\_EXPANDER\_I2C\_HT8574\_ADDRESS\_011**](#define-esp_io_expander_i2c_ht8574_address_011)  (0x2B)<br> |
| define  | [**ESP\_IO\_EXPANDER\_I2C\_HT8574\_ADDRESS\_100**](#define-esp_io_expander_i2c_ht8574_address_100)  (0x2C)<br> |


## Functions

| Type | Name |
| ---: | :--- |
|  esp\_err\_t | [**esp\_io\_expander\_new\_i2c\_ht8574**](#function-esp_io_expander_new_i2c_ht8574) (i2c\_port\_t i2c\_num, uint32\_t i2c\_address, [**esp\_io\_expander\_handle\_t**](#struct-esp_io_expander_s)\* handle) <br>_Create a new ht8574 IO expander driver._ |


## Macros Documentation

### define `ESP_IO_EXPANDER_I2C_HT8574_ADDRESS_000`

```c
#define ESP_IO_EXPANDER_I2C_HT8574_ADDRESS_000 (0x38)
```

### define `ESP_IO_EXPANDER_I2C_HT8574_ADDRESS_001`

```c
#define ESP_IO_EXPANDER_I2C_HT8574_ADDRESS_001 (0x29)
```

### define `ESP_IO_EXPANDER_I2C_HT8574_ADDRESS_010`

```c
#define ESP_IO_EXPANDER_I2C_HT8574_ADDRESS_010 (0x2A)
```

### define `ESP_IO_EXPANDER_I2C_HT8574_ADDRESS_011`

```c
#define ESP_IO_EXPANDER_I2C_HT8574_ADDRESS_011 (0x2B)
```

### define `ESP_IO_EXPANDER_I2C_HT8574_ADDRESS_100`

```c
#define ESP_IO_EXPANDER_I2C_HT8574_ADDRESS_100 (0x2C)
```



## Functions Documentation

### function `esp_io_expander_new_i2c_ht8574`

```c
esp_err_t esp_io_expander_new_i2c_ht8574 (
    i2c_port_t i2c_num,
    uint32_t i2c_address,
    esp_io_expander_handle_t * handle
) 
```


## File components/io_expander/esp_io_expander_tca9554/include/esp_io_expander_tca9554.h


## Macros

| Type | Name |
| ---: | :--- |
| define  | [**ESP\_IO\_EXPANDER\_I2C\_TCA9554A\_ADDRESS\_000**](#define-esp_io_expander_i2c_tca9554a_address_000)  (0x38)<br>_I2C address of the TCA9554A._ |
| define  | [**ESP\_IO\_EXPANDER\_I2C\_TCA9554A\_ADDRESS\_001**](#define-esp_io_expander_i2c_tca9554a_address_001)  (0x39)<br> |
| define  | [**ESP\_IO\_EXPANDER\_I2C\_TCA9554A\_ADDRESS\_010**](#define-esp_io_expander_i2c_tca9554a_address_010)  (0x3A)<br> |
| define  | [**ESP\_IO\_EXPANDER\_I2C\_TCA9554A\_ADDRESS\_011**](#define-esp_io_expander_i2c_tca9554a_address_011)  (0x3B)<br> |
| define  | [**ESP\_IO\_EXPANDER\_I2C\_TCA9554A\_ADDRESS\_100**](#define-esp_io_expander_i2c_tca9554a_address_100)  (0x3C)<br> |
| define  | [**ESP\_IO\_EXPANDER\_I2C\_TCA9554A\_ADDRESS\_101**](#define-esp_io_expander_i2c_tca9554a_address_101)  (0x3D)<br> |
| define  | [**ESP\_IO\_EXPANDER\_I2C\_TCA9554A\_ADDRESS\_110**](#define-esp_io_expander_i2c_tca9554a_address_110)  (0x3E)<br> |
| define  | [**ESP\_IO\_EXPANDER\_I2C\_TCA9554A\_ADDRESS\_111**](#define-esp_io_expander_i2c_tca9554a_address_111)  (0x3F)<br> |
| define  | [**ESP\_IO\_EXPANDER\_I2C\_TCA9554\_ADDRESS\_000**](#define-esp_io_expander_i2c_tca9554_address_000)  (0x20)<br>_I2C address of the TCA9554._ |
| define  | [**ESP\_IO\_EXPANDER\_I2C\_TCA9554\_ADDRESS\_001**](#define-esp_io_expander_i2c_tca9554_address_001)  (0x21)<br> |
| define  | [**ESP\_IO\_EXPANDER\_I2C\_TCA9554\_ADDRESS\_010**](#define-esp_io_expander_i2c_tca9554_address_010)  (0x22)<br> |
| define  | [**ESP\_IO\_EXPANDER\_I2C\_TCA9554\_ADDRESS\_011**](#define-esp_io_expander_i2c_tca9554_address_011)  (0x23)<br> |
| define  | [**ESP\_IO\_EXPANDER\_I2C\_TCA9554\_ADDRESS\_100**](#define-esp_io_expander_i2c_tca9554_address_100)  (0x24)<br> |
| define  | [**ESP\_IO\_EXPANDER\_I2C\_TCA9554\_ADDRESS\_101**](#define-esp_io_expander_i2c_tca9554_address_101)  (0x25)<br> |
| define  | [**ESP\_IO\_EXPANDER\_I2C\_TCA9554\_ADDRESS\_110**](#define-esp_io_expander_i2c_tca9554_address_110)  (0x26)<br> |
| define  | [**ESP\_IO\_EXPANDER\_I2C\_TCA9554\_ADDRESS\_111**](#define-esp_io_expander_i2c_tca9554_address_111)  (0x27)<br> |


## Functions

| Type | Name |
| ---: | :--- |
|  esp\_err\_t | [**esp\_io\_expander\_new\_i2c\_tca9554**](#function-esp_io_expander_new_i2c_tca9554) (i2c\_port\_t i2c\_num, uint32\_t i2c\_address, [**esp\_io\_expander\_handle\_t**](#struct-esp_io_expander_s)\* handle) <br>_Create a new TCA9554 IO expander driver._ |


## Macros Documentation

### define `ESP_IO_EXPANDER_I2C_TCA9554A_ADDRESS_000`

```c
#define ESP_IO_EXPANDER_I2C_TCA9554A_ADDRESS_000 (0x38)
```

### define `ESP_IO_EXPANDER_I2C_TCA9554A_ADDRESS_001`

```c
#define ESP_IO_EXPANDER_I2C_TCA9554A_ADDRESS_001 (0x39)
```

### define `ESP_IO_EXPANDER_I2C_TCA9554A_ADDRESS_010`

```c
#define ESP_IO_EXPANDER_I2C_TCA9554A_ADDRESS_010 (0x3A)
```

### define `ESP_IO_EXPANDER_I2C_TCA9554A_ADDRESS_011`

```c
#define ESP_IO_EXPANDER_I2C_TCA9554A_ADDRESS_011 (0x3B)
```

### define `ESP_IO_EXPANDER_I2C_TCA9554A_ADDRESS_100`

```c
#define ESP_IO_EXPANDER_I2C_TCA9554A_ADDRESS_100 (0x3C)
```

### define `ESP_IO_EXPANDER_I2C_TCA9554A_ADDRESS_101`

```c
#define ESP_IO_EXPANDER_I2C_TCA9554A_ADDRESS_101 (0x3D)
```

### define `ESP_IO_EXPANDER_I2C_TCA9554A_ADDRESS_110`

```c
#define ESP_IO_EXPANDER_I2C_TCA9554A_ADDRESS_110 (0x3E)
```

### define `ESP_IO_EXPANDER_I2C_TCA9554A_ADDRESS_111`

```c
#define ESP_IO_EXPANDER_I2C_TCA9554A_ADDRESS_111 (0x3F)
```

### define `ESP_IO_EXPANDER_I2C_TCA9554_ADDRESS_000`

```c
#define ESP_IO_EXPANDER_I2C_TCA9554_ADDRESS_000 (0x20)
```

### define `ESP_IO_EXPANDER_I2C_TCA9554_ADDRESS_001`

```c
#define ESP_IO_EXPANDER_I2C_TCA9554_ADDRESS_001 (0x21)
```

### define `ESP_IO_EXPANDER_I2C_TCA9554_ADDRESS_010`

```c
#define ESP_IO_EXPANDER_I2C_TCA9554_ADDRESS_010 (0x22)
```

### define `ESP_IO_EXPANDER_I2C_TCA9554_ADDRESS_011`

```c
#define ESP_IO_EXPANDER_I2C_TCA9554_ADDRESS_011 (0x23)
```

### define `ESP_IO_EXPANDER_I2C_TCA9554_ADDRESS_100`

```c
#define ESP_IO_EXPANDER_I2C_TCA9554_ADDRESS_100 (0x24)
```

### define `ESP_IO_EXPANDER_I2C_TCA9554_ADDRESS_101`

```c
#define ESP_IO_EXPANDER_I2C_TCA9554_ADDRESS_101 (0x25)
```

### define `ESP_IO_EXPANDER_I2C_TCA9554_ADDRESS_110`

```c
#define ESP_IO_EXPANDER_I2C_TCA9554_ADDRESS_110 (0x26)
```

### define `ESP_IO_EXPANDER_I2C_TCA9554_ADDRESS_111`

```c
#define ESP_IO_EXPANDER_I2C_TCA9554_ADDRESS_111 (0x27)
```



## Functions Documentation

### function `esp_io_expander_new_i2c_tca9554`

```c
esp_err_t esp_io_expander_new_i2c_tca9554 (
    i2c_port_t i2c_num,
    uint32_t i2c_address,
    esp_io_expander_handle_t * handle
) 
```


## File components/io_expander/esp_io_expander_tca95xx_16bit/include/esp_io_expander_tca95xx_16bit.h



## Types

| Type | Name |
| ---: | :--- |
| enum  | [**esp\_io\_expander\_tca\_95xx\_16bit\_address**](#enum-esp_io_expander_tca_95xx_16bit_address)  <br>_I2C address of the TCA9539 or TCA9555._ |

## Functions

| Type | Name |
| ---: | :--- |
|  esp\_err\_t | [**esp\_io\_expander\_new\_i2c\_tca95xx\_16bit**](#function-esp_io_expander_new_i2c_tca95xx_16bit) (i2c\_port\_t i2c\_num, uint32\_t i2c\_address, [**esp\_io\_expander\_handle\_t**](#struct-esp_io_expander_s)\* handle) <br>_Create a new TCA95xx\_16bit IO expander driver._ |



## Types Documentation

### enum `esp_io_expander_tca_95xx_16bit_address`

```c
enum esp_io_expander_tca_95xx_16bit_address {
    ESP_IO_EXPANDER_I2C_TCA9539_ADDRESS_00 = 0b1110100,
    ESP_IO_EXPANDER_I2C_TCA9539_ADDRESS_01 = 0b1110101,
    ESP_IO_EXPANDER_I2C_TCA9539_ADDRESS_10 = 0b1110110,
    ESP_IO_EXPANDER_I2C_TCA9539_ADDRESS_11 = 0b1110111,
    ESP_IO_EXPANDER_I2C_TCA9555_ADDRESS_000 = 0b0100000,
    ESP_IO_EXPANDER_I2C_TCA9555_ADDRESS_001 = 0b0100001,
    ESP_IO_EXPANDER_I2C_TCA9555_ADDRESS_010 = 0b0100010,
    ESP_IO_EXPANDER_I2C_TCA9555_ADDRESS_011 = 0b0100011,
    ESP_IO_EXPANDER_I2C_TCA9555_ADDRESS_100 = 0b0100000,
    ESP_IO_EXPANDER_I2C_TCA9555_ADDRESS_101 = 0b0100101,
    ESP_IO_EXPANDER_I2C_TCA9555_ADDRESS_110 = 0b0100110,
    ESP_IO_EXPANDER_I2C_TCA9555_ADDRESS_111 = 0b0100111
};
```


## Functions Documentation

### function `esp_io_expander_new_i2c_tca95xx_16bit`

```c
esp_err_t esp_io_expander_new_i2c_tca95xx_16bit (
    i2c_port_t i2c_num,
    uint32_t i2c_address,
    esp_io_expander_handle_t * handle
) 
```


## File components/lcd/esp_lcd_gc9503/include/esp_lcd_gc9503.h


## Macros

| Type | Name |
| ---: | :--- |
| define  | [**GC9503\_480\_480\_PANEL\_60HZ\_RGB\_TIMING**](#define-gc9503_480_480_panel_60hz_rgb_timing) () <br>_RGB timing structure._ |
| define  | [**GC9503\_PANEL\_IO\_3WIRE\_SPI\_CONFIG**](#define-gc9503_panel_io_3wire_spi_config) (line\_cfg) <br>_3-wire SPI panel IO configuration structure_ |


## Functions

| Type | Name |
| ---: | :--- |
|  esp\_err\_t | [**esp\_lcd\_new\_panel\_gc9503**](#function-esp_lcd_new_panel_gc9503) (esp\_lcd\_panel\_io\_handle\_t io\_handle, const esp\_lcd\_rgb\_panel\_config\_t \* rgb\_config, esp\_lcd\_panel\_handle\_t \* ret\_panel) <br>_Create LCD panel for GC9503._ |


## Macros Documentation

### define `GC9503_480_480_PANEL_60HZ_RGB_TIMING`

```c
#define GC9503_480_480_PANEL_60HZ_RGB_TIMING (
    
) {                                               \
        .pclk_hz = 16 * 1000 * 1000,                \
        .h_res = 480,                               \
        .v_res = 480,                               \
        .hsync_pulse_width = 10,                    \
        .hsync_back_porch = 10,                     \
        .hsync_front_porch = 20,                    \
        .vsync_pulse_width = 10,                    \
        .vsync_back_porch = 10,                     \
        .vsync_front_porch = 10,                    \
        .flags.pclk_active_neg = false,             \
    }
```

### define `GC9503_PANEL_IO_3WIRE_SPI_CONFIG`

```c
#define GC9503_PANEL_IO_3WIRE_SPI_CONFIG (
    line_cfg
) {                                                       \
        .line_config = line_cfg,                            \
        .expect_clk_speed = PANEL_IO_3WIRE_SPI_CLK_MAX,     \
        .spi_mode = 0,                                      \
        .lcd_cmd_bytes = 1,                                 \
        .lcd_param_bytes = 1,                               \
        .flags = {                                          \
            .use_dc_bit = true,                             \
            .dc_zero_on_data = false,                       \
            .lsb_first = false,                             \
            .cs_high_active = false,                        \
            .del_keep_cs_inactive = true,                   \
        },                                                  \
    }
```



## Functions Documentation

### function `esp_lcd_new_panel_gc9503`

```c
esp_err_t esp_lcd_new_panel_gc9503 (
    esp_lcd_panel_io_handle_t io_handle,
    const esp_lcd_rgb_panel_config_t * rgb_config,
    esp_lcd_panel_handle_t * ret_panel
) 
```


## File components/lcd/esp_lcd_gc9a01/include/esp_lcd_gc9a01.h




## Functions

| Type | Name |
| ---: | :--- |
|  esp\_err\_t | [**esp\_lcd\_new\_panel\_gc9a01**](#function-esp_lcd_new_panel_gc9a01) (const esp\_lcd\_panel\_io\_handle\_t io, const esp\_lcd\_panel\_dev\_config\_t \* panel\_dev\_config, esp\_lcd\_panel\_handle\_t \* ret\_panel) <br>_Create LCD panel for model GC9A01._ |




## Functions Documentation

### function `esp_lcd_new_panel_gc9a01`

```c
esp_err_t esp_lcd_new_panel_gc9a01 (
    const esp_lcd_panel_io_handle_t io,
    const esp_lcd_panel_dev_config_t * panel_dev_config,
    esp_lcd_panel_handle_t * ret_panel
) 
```


## File components/lcd/esp_lcd_ili9341/include/esp_lcd_ili9341.h




## Functions

| Type | Name |
| ---: | :--- |
|  esp\_err\_t | [**esp\_lcd\_new\_panel\_ili9341**](#function-esp_lcd_new_panel_ili9341) (const esp\_lcd\_panel\_io\_handle\_t io, const esp\_lcd\_panel\_dev\_config\_t \* panel\_dev\_config, esp\_lcd\_panel\_handle\_t \* ret\_panel) <br>_Create LCD panel for model ILI9341._ |




## Functions Documentation

### function `esp_lcd_new_panel_ili9341`

```c
esp_err_t esp_lcd_new_panel_ili9341 (
    const esp_lcd_panel_io_handle_t io,
    const esp_lcd_panel_dev_config_t * panel_dev_config,
    esp_lcd_panel_handle_t * ret_panel
) 
```


## File components/lcd/esp_lcd_ra8875/include/esp_lcd_ra8875.h

## Classes

| Type | Name |
| ---: | :--- |
| struct | [**esp\_lcd\_panel\_ra8875\_config\_t**](#struct-esp_lcd_panel_ra8875_config_t) <br>_Vendor specific configuration structure for panel device._ |



## Functions

| Type | Name |
| ---: | :--- |
|  esp\_err\_t | [**esp\_lcd\_new\_panel\_ra8875**](#function-esp_lcd_new_panel_ra8875) (const esp\_lcd\_panel\_io\_handle\_t io, const esp\_lcd\_panel\_dev\_config\_t \* panel\_dev\_config, esp\_lcd\_panel\_handle\_t \* ret\_panel) <br>_Create LCD panel for model RA8875._ |

## Classes Documentation

### struct `esp_lcd_panel_ra8875_config_t`

Variables:

-  uint16\_t lcd_height  <br>
-  uint16\_t lcd_width  <br>
-  int mcu_bit_interface  <br>
-  int wait_gpio_num  <br>



## Functions Documentation

### function `esp_lcd_new_panel_ra8875`

```c
esp_err_t esp_lcd_new_panel_ra8875 (
    const esp_lcd_panel_io_handle_t io,
    const esp_lcd_panel_dev_config_t * panel_dev_config,
    esp_lcd_panel_handle_t * ret_panel
) 
```


## File components/lcd/esp_lcd_sh1107/include/esp_lcd_sh1107.h


## Macros

| Type | Name |
| ---: | :--- |
| define  | [**ESP\_LCD\_IO\_I2C\_SH1107\_ADDRESS**](#define-esp_lcd_io_i2c_sh1107_address)  (0x3C)<br>_I2C address of the SH1107 controller._ |
| define  | [**ESP\_LCD\_IO\_I2C\_SH1107\_ADDRESS1**](#define-esp_lcd_io_i2c_sh1107_address1)  (0x3D)<br> |
| define  | [**ESP\_LCD\_IO\_I2C\_SH1107\_CONFIG**](#define-esp_lcd_io_i2c_sh1107_config) () <br>_Touch IO configuration structure._ |


## Functions

| Type | Name |
| ---: | :--- |
|  esp\_err\_t | [**esp\_lcd\_new\_panel\_sh1107**](#function-esp_lcd_new_panel_sh1107) (const esp\_lcd\_panel\_io\_handle\_t io, const esp\_lcd\_panel\_dev\_config\_t \* panel\_dev\_config, esp\_lcd\_panel\_handle\_t \* ret\_panel) <br>_Create LCD panel for model SH1107._ |


## Macros Documentation

### define `ESP_LCD_IO_I2C_SH1107_ADDRESS`

```c
#define ESP_LCD_IO_I2C_SH1107_ADDRESS (0x3C)
```

### define `ESP_LCD_IO_I2C_SH1107_ADDRESS1`

```c
#define ESP_LCD_IO_I2C_SH1107_ADDRESS1 (0x3D)
```

### define `ESP_LCD_IO_I2C_SH1107_CONFIG`

```c
#define ESP_LCD_IO_I2C_SH1107_CONFIG (
    
) {                                              \
        .dev_addr = ESP_LCD_IO_I2C_SH1107_ADDRESS , \
        .control_phase_bytes = 1,           \
        .dc_bit_offset = 0,                 \
        .lcd_cmd_bits = 8,                  \
        .lcd_param_bits = 8,                \
        .flags =                            \
        {                                   \
            .disable_control_phase = 1,     \
        }                                   \
    }
```



## Functions Documentation

### function `esp_lcd_new_panel_sh1107`

```c
esp_err_t esp_lcd_new_panel_sh1107 (
    const esp_lcd_panel_io_handle_t io,
    const esp_lcd_panel_dev_config_t * panel_dev_config,
    esp_lcd_panel_handle_t * ret_panel
) 
```


## File components/lcd/esp_lcd_st7796/include/esp_lcd_st7796.h




## Functions

| Type | Name |
| ---: | :--- |
|  esp\_err\_t | [**esp\_lcd\_new\_panel\_st7796**](#function-esp_lcd_new_panel_st7796) (const esp\_lcd\_panel\_io\_handle\_t io, const esp\_lcd\_panel\_dev\_config\_t \* panel\_dev\_config, esp\_lcd\_panel\_handle\_t \* ret\_panel) <br>_Create LCD panel for model ST7796._ |




## Functions Documentation

### function `esp_lcd_new_panel_st7796`

```c
esp_err_t esp_lcd_new_panel_st7796 (
    const esp_lcd_panel_io_handle_t io,
    const esp_lcd_panel_dev_config_t * panel_dev_config,
    esp_lcd_panel_handle_t * ret_panel
) 
```


## File components/lcd_touch/esp_lcd_touch/include/esp_lcd_touch.h

## Classes

| Type | Name |
| ---: | :--- |
| struct | [**esp\_lcd\_touch\_config\_t**](#struct-esp_lcd_touch_config_t) <br>_Touch Configuration Type._ |
| struct | [**esp\_lcd\_touch\_data\_t**](#struct-esp_lcd_touch_data_t) <br> |
| struct | [**esp\_lcd\_touch\_s**](#struct-esp_lcd_touch_s) <br>_Declare of Touch Type._ |


## Types

| Type | Name |
| ---: | :--- |
| typedef [**esp\_lcd\_touch\_t**](#typedef-esp_lcd_touch_t)\* | [**esp\_lcd\_touch\_handle\_t**](#typedef-esp_lcd_touch_handle_t)  <br> |
| typedef void(\* | [**esp\_lcd\_touch\_interrupt\_callback\_t**](#typedef-esp_lcd_touch_interrupt_callback_t)  <br>_Touch controller interrupt callback type._ |
| typedef  | [**esp\_lcd\_touch\_t**](#typedef-esp_lcd_touch_t)  <br>_Touch controller type._ |

## Functions

| Type | Name |
| ---: | :--- |
|  esp\_err\_t | [**esp\_lcd\_touch\_del**](#function-esp_lcd_touch_del)  <br>_Delete touch (free all allocated memory and restart HW)_ |
|  bool | [**esp\_lcd\_touch\_get\_coordinates**](#function-esp_lcd_touch_get_coordinates)  <br>_Read coordinates from touch controller._ |
|  esp\_err\_t | [**esp\_lcd\_touch\_get\_mirror\_x**](#function-esp_lcd_touch_get_mirror_x)  <br>_Is mirrored X._ |
|  esp\_err\_t | [**esp\_lcd\_touch\_get\_mirror\_y**](#function-esp_lcd_touch_get_mirror_y)  <br>_Is mirrored Y._ |
|  esp\_err\_t | [**esp\_lcd\_touch\_get\_swap\_xy**](#function-esp_lcd_touch_get_swap_xy)  <br>_Are X and Y coordinates swapped._ |
|  esp\_err\_t | [**esp\_lcd\_touch\_read\_data**](#function-esp_lcd_touch_read_data)  <br>_Read data from touch controller._ |
|  esp\_err\_t | [**esp\_lcd\_touch\_register\_interrupt\_callback**](#function-esp_lcd_touch_register_interrupt_callback)  <br>_Register user callback called after the touch interrupt occured._ |
|  esp\_err\_t | [**esp\_lcd\_touch\_set\_mirror\_x**](#function-esp_lcd_touch_set_mirror_x)  <br>_Mirror X after read coordinates._ |
|  esp\_err\_t | [**esp\_lcd\_touch\_set\_mirror\_y**](#function-esp_lcd_touch_set_mirror_y)  <br>_Mirror Y after read coordinates._ |
|  esp\_err\_t | [**esp\_lcd\_touch\_set\_swap\_xy**](#function-esp_lcd_touch_set_swap_xy)  <br>_Swap X and Y after read coordinates._ |

## Classes Documentation

### struct `esp_lcd_touch_config_t`

Variables:

-   flags  <br>
-  gpio\_num\_t int_gpio_num  <br>
-  unsigned int interrupt  <br>
-   interrupt_callback  <br>
-   levels  <br>
-  unsigned int mirror_x  <br>
-  unsigned int mirror_y  <br>
-  void(\* process_coordinates  <br>
-  unsigned int reset  <br>
-  gpio\_num\_t rst_gpio_num  <br>
-  unsigned int swap_xy  <br>
-  uint16\_t x_max  <br>
-  uint16\_t y_max  <br>
### struct `esp_lcd_touch_data_t`

Variables:

-   coords  <br>
-  portMUX\_TYPE lock  <br>
-  uint8\_t points  <br>
-  uint16\_t strength  <br>
-  uint16\_t x  <br>
-  uint16\_t y  <br>
### struct `esp_lcd_touch_s`

Variables:

-   config  <br>_Configuration structure._
-   data  <br>_Data structure._
-  esp\_err\_t(\* del  <br>_Delete Touch._
-  esp\_err\_t(\* get_mirror_x  <br>_Is mirrored X (optional)_
-  esp\_err\_t(\* get_mirror_y  <br>_Is mirrored Y (optional)_
-  esp\_err\_t(\* get_swap_xy  <br>_Are X and Y coordinates swapped (optional)_
-  bool(\* get_xy  <br>_Get coordinates from touch controller (mandatory)_
-  esp\_lcd\_panel\_io\_handle\_t io  <br>_Communication interface._
-  esp\_err\_t(\* read_data  <br>_Read data from touch controller (mandatory)_
-  esp\_err\_t(\* set_mirror_x  <br>_Mirror X after read coordinates If set, then not used SW mirroring._
-  esp\_err\_t(\* set_mirror_y  <br>_Mirror Y after read coordinates If set, then not used SW mirroring._
-  esp\_err\_t(\* set_swap_xy  <br>_Swap X and Y after read coordinates (optional) If set, then not used SW swapping._


## Types Documentation

### typedef `esp_lcd_touch_handle_t`

```c
typedef esp_lcd_touch_t* esp_lcd_touch_handle_t;
```

### typedef `esp_lcd_touch_interrupt_callback_t`

```c
typedef void(* esp_lcd_touch_interrupt_callback_t) (esp_lcd_touch_handle_t tp);
```

### typedef `esp_lcd_touch_t`

```c
typedef struct esp_lcd_touch_s esp_lcd_touch_t;
```


## Functions Documentation

### function `esp_lcd_touch_del`

```c
esp_err_t esp_lcd_touch_del (
    esp_lcd_touch_handle_t tp
) 
```

### function `esp_lcd_touch_get_coordinates`

```c
bool esp_lcd_touch_get_coordinates (
    esp_lcd_touch_handle_t tp,
    uint16_t * x,
    uint16_t * y,
    uint16_t * strength,
    uint8_t * point_num,
    uint8_t max_point_num
) 
```

### function `esp_lcd_touch_get_mirror_x`

```c
esp_err_t esp_lcd_touch_get_mirror_x (
    esp_lcd_touch_handle_t tp,
    bool * mirror
) 
```

### function `esp_lcd_touch_get_mirror_y`

```c
esp_err_t esp_lcd_touch_get_mirror_y (
    esp_lcd_touch_handle_t tp,
    bool * mirror
) 
```

### function `esp_lcd_touch_get_swap_xy`

```c
esp_err_t esp_lcd_touch_get_swap_xy (
    esp_lcd_touch_handle_t tp,
    bool * swap
) 
```

### function `esp_lcd_touch_read_data`

```c
esp_err_t esp_lcd_touch_read_data (
    esp_lcd_touch_handle_t tp
) 
```

### function `esp_lcd_touch_register_interrupt_callback`

```c
esp_err_t esp_lcd_touch_register_interrupt_callback (
    esp_lcd_touch_handle_t tp,
    esp_lcd_touch_interrupt_callback_t callback
) 
```

### function `esp_lcd_touch_set_mirror_x`

```c
esp_err_t esp_lcd_touch_set_mirror_x (
    esp_lcd_touch_handle_t tp,
    bool mirror
) 
```

### function `esp_lcd_touch_set_mirror_y`

```c
esp_err_t esp_lcd_touch_set_mirror_y (
    esp_lcd_touch_handle_t tp,
    bool mirror
) 
```

### function `esp_lcd_touch_set_swap_xy`

```c
esp_err_t esp_lcd_touch_set_swap_xy (
    esp_lcd_touch_handle_t tp,
    bool swap
) 
```


## File components/lcd_touch/esp_lcd_touch_cst816s/include/esp_lcd_touch_cst816s.h


## Macros

| Type | Name |
| ---: | :--- |
| define  | [**ESP\_LCD\_TOUCH\_IO\_I2C\_CST816S\_ADDRESS**](#define-esp_lcd_touch_io_i2c_cst816s_address)  (0x15)<br>_I2C address of the CST816S controller._ |
| define  | [**ESP\_LCD\_TOUCH\_IO\_I2C\_CST816S\_CONFIG**](#define-esp_lcd_touch_io_i2c_cst816s_config) () <br>_Touch IO configuration structure._ |


## Functions

| Type | Name |
| ---: | :--- |
|  esp\_err\_t | [**esp\_lcd\_touch\_new\_i2c\_cst816s**](#function-esp_lcd_touch_new_i2c_cst816s) (const esp\_lcd\_panel\_io\_handle\_t io, const [**esp\_lcd\_touch\_config\_t**](#struct-esp_lcd_touch_config_t)\* config, [**esp\_lcd\_touch\_handle\_t**](#struct-esp_lcd_touch_s)\* tp) <br>_Create a new CST816S touch driver._ |


## Macros Documentation

### define `ESP_LCD_TOUCH_IO_I2C_CST816S_ADDRESS`

```c
#define ESP_LCD_TOUCH_IO_I2C_CST816S_ADDRESS (0x15)
```

### define `ESP_LCD_TOUCH_IO_I2C_CST816S_CONFIG`

```c
#define ESP_LCD_TOUCH_IO_I2C_CST816S_CONFIG (
    
) {                                                    \
        .dev_addr = ESP_LCD_TOUCH_IO_I2C_CST816S_ADDRESS , \
        .control_phase_bytes = 1,                        \
        .dc_bit_offset = 0,                              \
        .lcd_cmd_bits = 8,                              \
        .flags =                                         \
        {                                                \
            .disable_control_phase = 1,                  \
        }                                                \
    }
```



## Functions Documentation

### function `esp_lcd_touch_new_i2c_cst816s`

```c
esp_err_t esp_lcd_touch_new_i2c_cst816s (
    const esp_lcd_panel_io_handle_t io,
    const esp_lcd_touch_config_t * config,
    esp_lcd_touch_handle_t * tp
) 
```


## File components/lcd_touch/esp_lcd_touch_ft5x06/include/esp_lcd_touch_ft5x06.h


## Macros

| Type | Name |
| ---: | :--- |
| define  | [**ESP\_LCD\_TOUCH\_IO\_I2C\_FT5x06\_ADDRESS**](#define-esp_lcd_touch_io_i2c_ft5x06_address)  (0x38)<br>_I2C address of the FT5x06 controller._ |
| define  | [**ESP\_LCD\_TOUCH\_IO\_I2C\_FT5x06\_CONFIG**](#define-esp_lcd_touch_io_i2c_ft5x06_config) () <br>_Touch IO configuration structure._ |


## Functions

| Type | Name |
| ---: | :--- |
|  esp\_err\_t | [**esp\_lcd\_touch\_new\_i2c\_ft5x06**](#function-esp_lcd_touch_new_i2c_ft5x06) (const esp\_lcd\_panel\_io\_handle\_t io, const [**esp\_lcd\_touch\_config\_t**](#struct-esp_lcd_touch_config_t)\* config, [**esp\_lcd\_touch\_handle\_t**](#struct-esp_lcd_touch_s)\* out\_touch) <br>_Create a new FT5x06 touch driver._ |


## Macros Documentation

### define `ESP_LCD_TOUCH_IO_I2C_FT5x06_ADDRESS`

```c
#define ESP_LCD_TOUCH_IO_I2C_FT5x06_ADDRESS (0x38)
```

### define `ESP_LCD_TOUCH_IO_I2C_FT5x06_CONFIG`

```c
#define ESP_LCD_TOUCH_IO_I2C_FT5x06_CONFIG (
    
) {                                       \
        .dev_addr = ESP_LCD_TOUCH_IO_I2C_FT5x06_ADDRESS , \
        .control_phase_bytes = 1,           \
        .dc_bit_offset = 0,                 \
        .lcd_cmd_bits = 8,                  \
        .flags =                            \
        {                                   \
            .disable_control_phase = 1,     \
        }                                   \
    }
```



## Functions Documentation

### function `esp_lcd_touch_new_i2c_ft5x06`

```c
esp_err_t esp_lcd_touch_new_i2c_ft5x06 (
    const esp_lcd_panel_io_handle_t io,
    const esp_lcd_touch_config_t * config,
    esp_lcd_touch_handle_t * out_touch
) 
```


## File components/lcd_touch/esp_lcd_touch_gt1151/include/esp_lcd_touch_gt1151.h


## Macros

| Type | Name |
| ---: | :--- |
| define  | [**ESP\_LCD\_TOUCH\_IO\_I2C\_GT1151\_ADDRESS**](#define-esp_lcd_touch_io_i2c_gt1151_address)  (0x14)<br>_I2C address of the GT1151 controller._ |
| define  | [**ESP\_LCD\_TOUCH\_IO\_I2C\_GT1151\_CONFIG**](#define-esp_lcd_touch_io_i2c_gt1151_config) () <br>_Touch IO configuration structure._ |


## Functions

| Type | Name |
| ---: | :--- |
|  esp\_err\_t | [**esp\_lcd\_touch\_new\_i2c\_gt1151**](#function-esp_lcd_touch_new_i2c_gt1151) (const esp\_lcd\_panel\_io\_handle\_t io, const [**esp\_lcd\_touch\_config\_t**](#struct-esp_lcd_touch_config_t)\* config, [**esp\_lcd\_touch\_handle\_t**](#struct-esp_lcd_touch_s)\* tp) <br>_Create a new GT1151 touch driver._ |


## Macros Documentation

### define `ESP_LCD_TOUCH_IO_I2C_GT1151_ADDRESS`

```c
#define ESP_LCD_TOUCH_IO_I2C_GT1151_ADDRESS (0x14)
```

### define `ESP_LCD_TOUCH_IO_I2C_GT1151_CONFIG`

```c
#define ESP_LCD_TOUCH_IO_I2C_GT1151_CONFIG (
    
) {                                                    \
        .dev_addr = ESP_LCD_TOUCH_IO_I2C_GT1151_ADDRESS , \
        .control_phase_bytes = 1,                        \
        .dc_bit_offset = 0,                              \
        .lcd_cmd_bits = 16,                              \
        .flags =                                         \
        {                                                \
            .disable_control_phase = 1,                  \
        }                                                \
    }
```



## Functions Documentation

### function `esp_lcd_touch_new_i2c_gt1151`

```c
esp_err_t esp_lcd_touch_new_i2c_gt1151 (
    const esp_lcd_panel_io_handle_t io,
    const esp_lcd_touch_config_t * config,
    esp_lcd_touch_handle_t * tp
) 
```


## File components/lcd_touch/esp_lcd_touch_gt911/include/esp_lcd_touch_gt911.h


## Macros

| Type | Name |
| ---: | :--- |
| define  | [**ESP\_LCD\_TOUCH\_IO\_I2C\_GT911\_ADDRESS**](#define-esp_lcd_touch_io_i2c_gt911_address)  (0x5D)<br>_I2C address of the GT911 controller._ |
| define  | [**ESP\_LCD\_TOUCH\_IO\_I2C\_GT911\_CONFIG**](#define-esp_lcd_touch_io_i2c_gt911_config) () <br>_Touch IO configuration structure._ |


## Functions

| Type | Name |
| ---: | :--- |
|  esp\_err\_t | [**esp\_lcd\_touch\_new\_i2c\_gt911**](#function-esp_lcd_touch_new_i2c_gt911) (const esp\_lcd\_panel\_io\_handle\_t io, const [**esp\_lcd\_touch\_config\_t**](#struct-esp_lcd_touch_config_t)\* config, [**esp\_lcd\_touch\_handle\_t**](#struct-esp_lcd_touch_s)\* out\_touch) <br>_Create a new GT911 touch driver._ |


## Macros Documentation

### define `ESP_LCD_TOUCH_IO_I2C_GT911_ADDRESS`

```c
#define ESP_LCD_TOUCH_IO_I2C_GT911_ADDRESS (0x5D)
```

### define `ESP_LCD_TOUCH_IO_I2C_GT911_CONFIG`

```c
#define ESP_LCD_TOUCH_IO_I2C_GT911_CONFIG (
    
) {                                       \
        .dev_addr = ESP_LCD_TOUCH_IO_I2C_GT911_ADDRESS , \
        .control_phase_bytes = 1,           \
        .dc_bit_offset = 0,                 \
        .lcd_cmd_bits = 16,                 \
        .flags =                            \
        {                                   \
            .disable_control_phase = 1,     \
        }                                   \
    }
```



## Functions Documentation

### function `esp_lcd_touch_new_i2c_gt911`

```c
esp_err_t esp_lcd_touch_new_i2c_gt911 (
    const esp_lcd_panel_io_handle_t io,
    const esp_lcd_touch_config_t * config,
    esp_lcd_touch_handle_t * out_touch
) 
```


## File components/lcd_touch/esp_lcd_touch_stmpe610/include/esp_lcd_touch_stmpe610.h


## Macros

| Type | Name |
| ---: | :--- |
| define  | [**ESP\_LCD\_TOUCH\_IO\_SPI\_STMPE610\_CONFIG**](#define-esp_lcd_touch_io_spi_stmpe610_config) (touch\_cs) <br>_Communication SPI device IO structure._ |
| define  | [**ESP\_LCD\_TOUCH\_SPI\_CLOCK\_HZ**](#define-esp_lcd_touch_spi_clock_hz)  (1 \* 1000 \* 1000)<br>_Recommended clock for SPI read of the STMPE610._ |


## Functions

| Type | Name |
| ---: | :--- |
|  esp\_err\_t | [**esp\_lcd\_touch\_new\_spi\_stmpe610**](#function-esp_lcd_touch_new_spi_stmpe610) (const esp\_lcd\_panel\_io\_handle\_t io, const [**esp\_lcd\_touch\_config\_t**](#struct-esp_lcd_touch_config_t)\* config, [**esp\_lcd\_touch\_handle\_t**](#struct-esp_lcd_touch_s)\* out\_touch) <br>_Create a new STMPE610 touch driver._ |


## Macros Documentation

### define `ESP_LCD_TOUCH_IO_SPI_STMPE610_CONFIG`

```c
#define ESP_LCD_TOUCH_IO_SPI_STMPE610_CONFIG (
    touch_cs
) {                                               \
        .cs_gpio_num = touch_cs,                    \
        .pclk_hz = ESP_LCD_TOUCH_SPI_CLOCK_HZ ,      \
        .lcd_cmd_bits = 8,                          \
        .lcd_param_bits = 8,                        \
        .spi_mode = 1,                              \
        .trans_queue_depth = 1,                    \
    }
```

### define `ESP_LCD_TOUCH_SPI_CLOCK_HZ`

```c
#define ESP_LCD_TOUCH_SPI_CLOCK_HZ (1 * 1000 * 1000)
```



## Functions Documentation

### function `esp_lcd_touch_new_spi_stmpe610`

```c
esp_err_t esp_lcd_touch_new_spi_stmpe610 (
    const esp_lcd_panel_io_handle_t io,
    const esp_lcd_touch_config_t * config,
    esp_lcd_touch_handle_t * out_touch
) 
```


## File components/lcd_touch/esp_lcd_touch_tt21100/include/esp_lcd_touch_tt21100.h


## Macros

| Type | Name |
| ---: | :--- |
| define  | [**ESP\_LCD\_TOUCH\_IO\_I2C\_TT21100\_ADDRESS**](#define-esp_lcd_touch_io_i2c_tt21100_address)  (0x24)<br>_I2C address of the TT21100 controller._ |
| define  | [**ESP\_LCD\_TOUCH\_IO\_I2C\_TT21100\_CONFIG**](#define-esp_lcd_touch_io_i2c_tt21100_config) () <br>_Touch IO configuration structure._ |


## Functions

| Type | Name |
| ---: | :--- |
|  esp\_err\_t | [**esp\_lcd\_touch\_new\_i2c\_tt21100**](#function-esp_lcd_touch_new_i2c_tt21100) (const esp\_lcd\_panel\_io\_handle\_t io, const [**esp\_lcd\_touch\_config\_t**](#struct-esp_lcd_touch_config_t)\* config, [**esp\_lcd\_touch\_handle\_t**](#struct-esp_lcd_touch_s)\* out\_touch) <br>_Create a new TT21100 touch driver._ |


## Macros Documentation

### define `ESP_LCD_TOUCH_IO_I2C_TT21100_ADDRESS`

```c
#define ESP_LCD_TOUCH_IO_I2C_TT21100_ADDRESS (0x24)
```

### define `ESP_LCD_TOUCH_IO_I2C_TT21100_CONFIG`

```c
#define ESP_LCD_TOUCH_IO_I2C_TT21100_CONFIG (
    
) {                                       \
        .dev_addr = ESP_LCD_TOUCH_IO_I2C_TT21100_ADDRESS , \
        .control_phase_bytes = 1,           \
        .dc_bit_offset = 0,                 \
        .lcd_cmd_bits = 0,                  \
        .flags =                            \
        {                                   \
            .disable_control_phase = 1,     \
        }                                   \
    }
```



## Functions Documentation

### function `esp_lcd_touch_new_i2c_tt21100`

```c
esp_err_t esp_lcd_touch_new_i2c_tt21100 (
    const esp_lcd_panel_io_handle_t io,
    const esp_lcd_touch_config_t * config,
    esp_lcd_touch_handle_t * out_touch
) 
```


## File components/mag3110/include/mag3110.h

## Classes

| Type | Name |
| ---: | :--- |
| struct | [**mag3110\_result\_t**](#struct-mag3110_result_t) <br> |

## Macros

| Type | Name |
| ---: | :--- |
| define  | [**MAG3110\_WHO\_AM\_I\_VAL**](#define-mag3110_who_am_i_val)  0xC4u<br>_Device Identification value._ |

## Types

| Type | Name |
| ---: | :--- |
| enum  | [**mag3110\_data\_rate\_t**](#enum-mag3110_data_rate_t)  <br>_Data rate and oversampling settings._ |
| typedef void \* | [**mag3110\_handle\_t**](#typedef-mag3110_handle_t)  <br> |

## Functions

| Type | Name |
| ---: | :--- |
|  esp\_err\_t | [**mag3110\_calibrate**](#function-mag3110_calibrate) (mag3110\_handle\_t sensor, const uint32\_t cal\_duration\_ms) <br>_Calibrate MAG3110 for a hard-iron offset._ |
|  mag3110\_handle\_t | [**mag3110\_create**](#function-mag3110_create) (const i2c\_port\_t port) <br>_Create and init sensor object and return a sensor handle._ |
|  void | [**mag3110\_delete**](#function-mag3110_delete) (mag3110\_handle\_t sensor) <br>_Delete and release a sensor object._ |
|  esp\_err\_t | [**mag3110\_get\_deviceid**](#function-mag3110_get_deviceid) (mag3110\_handle\_t sensor, uint8\_t \*const deviceid) <br>_Get device identification of MAG3110._ |
|  esp\_err\_t | [**mag3110\_get\_magnetic\_induction**](#function-mag3110_get_magnetic_induction) (mag3110\_handle\_t sensor, [**mag3110\_result\_t**](#struct-mag3110_result_t)\*const mag\_induction) <br>_Read MAG3110 output register and return them in [0.1uT]._ |
|  esp\_err\_t | [**mag3110\_start**](#function-mag3110_start)  <br>_Start mag3110 sensor to measure._ |
|  esp\_err\_t | [**mag3110\_start\_raw**](#function-mag3110_start_raw)  <br>_Start mag3110 sensor in raw mode._ |
|  esp\_err\_t | [**mag3110\_stop**](#function-mag3110_stop) (mag3110\_handle\_t sensor) <br>_Stop MAG3110 measurement._ |

## Classes Documentation

### struct `mag3110_result_t`

Variables:

-  int16\_t x  <br>
-  int16\_t y  <br>
-  int16\_t z  <br>

## Macros Documentation

### define `MAG3110_WHO_AM_I_VAL`

```c
#define MAG3110_WHO_AM_I_VAL 0xC4u
```


## Types Documentation

### enum `mag3110_data_rate_t`

```c
enum mag3110_data_rate_t {
    MAG3110_DR_OS_80_16 = 0x00,
    MAG3110_DR_OS_40_32 = 0x08,
    MAG3110_DR_OS_20_64 = 0x10,
    MAG3110_DR_OS_10_128 = 0x18,
    MAG3110_DR_OS_40_16 = 0x20,
    MAG3110_DR_OS_20_32 = 0x28,
    MAG3110_DR_OS_10_64 = 0x30,
    MAG3110_DR_OS_5_128 = 0x38,
    MAG3110_DR_OS_20_16 = 0x40,
    MAG3110_DR_OS_10_32 = 0x48,
    MAG3110_DR_OS_5_64 = 0x50,
    MAG3110_DR_OS_2_5_128 = 0x58,
    MAG3110_DR_OS_10_16 = 0x60,
    MAG3110_DR_OS_5_32 = 0x68,
    MAG3110_DR_OS_2_5_64 = 0x70,
    MAG3110_DR_OS_1_25_128 = 0x78,
    MAG3110_DR_OS_5_16 = 0x80,
    MAG3110_DR_OS_2_5_32 = 0x88,
    MAG3110_DR_OS_1_25_64 = 0x90,
    MAG3110_DR_OS_0_63_128 = 0x98,
    MAG3110_DR_OS_2_5_16 = 0xA0,
    MAG3110_DR_OS_1_25_32 = 0xA8,
    MAG3110_DR_OS_0_63_64 = 0xB0,
    MAG3110_DR_OS_0_31_128 = 0xB8,
    MAG3110_DR_OS_1_25_16 = 0xC0,
    MAG3110_DR_OS_0_63_32 = 0xC8,
    MAG3110_DR_OS_0_31_64 = 0xD0,
    MAG3110_DR_OS_0_16_128 = 0xD8,
    MAG3110_DR_OS_0_63_16 = 0xE0,
    MAG3110_DR_OS_0_31_32 = 0xE8,
    MAG3110_DR_OS_0_16_64 = 0xF0,
    MAG3110_DR_OS_0_08_128 = 0xF8
};
```

### typedef `mag3110_handle_t`

```c
typedef void* mag3110_handle_t;
```


## Functions Documentation

### function `mag3110_calibrate`

```c
esp_err_t mag3110_calibrate (
    mag3110_handle_t sensor,
    const uint32_t cal_duration_ms
) 
```

### function `mag3110_create`

```c
mag3110_handle_t mag3110_create (
    const i2c_port_t port
) 
```

### function `mag3110_delete`

```c
void mag3110_delete (
    mag3110_handle_t sensor
) 
```

### function `mag3110_get_deviceid`

```c
esp_err_t mag3110_get_deviceid (
    mag3110_handle_t sensor,
    uint8_t *const deviceid
) 
```

### function `mag3110_get_magnetic_induction`

```c
esp_err_t mag3110_get_magnetic_induction (
    mag3110_handle_t sensor,
    mag3110_result_t *const mag_induction
) 
```

### function `mag3110_start`

```c
esp_err_t mag3110_start (
    mag3110_handle_t sensor,
    const mag3110_data_rate_t data_rate
) 
```

### function `mag3110_start_raw`

```c
esp_err_t mag3110_start_raw (
    mag3110_handle_t sensor,
    const mag3110_data_rate_t data_rate
) 
```

### function `mag3110_stop`

```c
esp_err_t mag3110_stop (
    mag3110_handle_t sensor
) 
```


## File components/mpu6050/include/mpu6050.h

## Classes

| Type | Name |
| ---: | :--- |
| struct | [**complimentary\_angle\_t**](#struct-complimentary_angle_t) <br> |
| struct | [**mpu6050\_acce\_value\_t**](#struct-mpu6050_acce_value_t) <br> |
| struct | [**mpu6050\_gyro\_value\_t**](#struct-mpu6050_gyro_value_t) <br> |
| struct | [**mpu6050\_int\_config\_t**](#struct-mpu6050_int_config_t) <br> |
| struct | [**mpu6050\_raw\_acce\_value\_t**](#struct-mpu6050_raw_acce_value_t) <br> |
| struct | [**mpu6050\_raw\_gyro\_value\_t**](#struct-mpu6050_raw_gyro_value_t) <br> |
| struct | [**mpu6050\_temp\_value\_t**](#struct-mpu6050_temp_value_t) <br> |

## Macros

| Type | Name |
| ---: | :--- |
| define  | [**MPU6050\_I2C\_ADDRESS**](#define-mpu6050_i2c_address)  0x68u<br> |
| define  | [**MPU6050\_I2C\_ADDRESS\_1**](#define-mpu6050_i2c_address_1)  0x69u<br> |
| define  | [**MPU6050\_WHO\_AM\_I\_VAL**](#define-mpu6050_who_am_i_val)  0x68u<br> |

## Types

| Type | Name |
| ---: | :--- |
| enum  | [**mpu6050\_acce\_fs\_t**](#enum-mpu6050_acce_fs_t)  <br> |
| enum  | [**mpu6050\_gyro\_fs\_t**](#enum-mpu6050_gyro_fs_t)  <br> |
| typedef void \* | [**mpu6050\_handle\_t**](#typedef-mpu6050_handle_t)  <br> |
| enum  | [**mpu6050\_int\_clear\_t**](#enum-mpu6050_int_clear_t)  <br> |
| enum  | [**mpu6050\_int\_latch\_t**](#enum-mpu6050_int_latch_t)  <br> |
| enum  | [**mpu6050\_int\_pin\_active\_level\_t**](#enum-mpu6050_int_pin_active_level_t)  <br> |
| enum  | [**mpu6050\_int\_pin\_mode\_t**](#enum-mpu6050_int_pin_mode_t)  <br> |
| typedef gpio\_isr\_t | [**mpu6050\_isr\_t**](#typedef-mpu6050_isr_t)  <br> |

## Functions

| Type | Name |
| ---: | :--- |
|  esp\_err\_t | [**mpu6050\_complimentory\_filter**](#function-mpu6050_complimentory_filter) (mpu6050\_handle\_t sensor, const [**mpu6050\_acce\_value\_t**](#struct-mpu6050_acce_value_t)\*const acce\_value, const [**mpu6050\_gyro\_value\_t**](#struct-mpu6050_gyro_value_t)\*const gyro\_value, [**complimentary\_angle\_t**](#struct-complimentary_angle_t)\*const complimentary\_angle) <br>_Use complimentory filter to calculate roll and pitch._ |
|  esp\_err\_t | [**mpu6050\_config**](#function-mpu6050_config)  <br>_Set accelerometer and gyroscope full scale range._ |
|  esp\_err\_t | [**mpu6050\_config\_interrupts**](#function-mpu6050_config_interrupts) (mpu6050\_handle\_t sensor, const [**mpu6050\_int\_config\_t**](#struct-mpu6050_int_config_t)\*const interrupt\_configuration) <br>_Configure INT pin behavior and setup target GPIO._ |
|  mpu6050\_handle\_t | [**mpu6050\_create**](#function-mpu6050_create) (i2c\_port\_t port, const uint16\_t dev\_addr) <br>_Create and init sensor object and return a sensor handle._ |
|  void | [**mpu6050\_delete**](#function-mpu6050_delete) (mpu6050\_handle\_t sensor) <br>_Delete and release a sensor object._ |
|  esp\_err\_t | [**mpu6050\_disable\_interrupts**](#function-mpu6050_disable_interrupts) (mpu6050\_handle\_t sensor, uint8\_t interrupt\_sources) <br>_Disable specific interrupts from mpu6050._ |
|  esp\_err\_t | [**mpu6050\_enable\_interrupts**](#function-mpu6050_enable_interrupts) (mpu6050\_handle\_t sensor, uint8\_t interrupt\_sources) <br>_Enable specific interrupts from mpu6050._ |
|  esp\_err\_t | [**mpu6050\_get\_acce**](#function-mpu6050_get_acce) (mpu6050\_handle\_t sensor, [**mpu6050\_acce\_value\_t**](#struct-mpu6050_acce_value_t)\*const acce\_value) <br>_Read accelerometer measurements._ |
|  esp\_err\_t | [**mpu6050\_get\_acce\_sensitivity**](#function-mpu6050_get_acce_sensitivity) (mpu6050\_handle\_t sensor, float \*const acce\_sensitivity) <br>_Get accelerometer sensitivity._ |
|  esp\_err\_t | [**mpu6050\_get\_deviceid**](#function-mpu6050_get_deviceid) (mpu6050\_handle\_t sensor, uint8\_t \*const deviceid) <br>_Get device identification of MPU6050._ |
|  esp\_err\_t | [**mpu6050\_get\_gyro**](#function-mpu6050_get_gyro) (mpu6050\_handle\_t sensor, [**mpu6050\_gyro\_value\_t**](#struct-mpu6050_gyro_value_t)\*const gyro\_value) <br>_Read gyro values._ |
|  esp\_err\_t | [**mpu6050\_get\_gyro\_sensitivity**](#function-mpu6050_get_gyro_sensitivity) (mpu6050\_handle\_t sensor, float \*const gyro\_sensitivity) <br>_Get gyroscope sensitivity._ |
|  esp\_err\_t | [**mpu6050\_get\_interrupt\_status**](#function-mpu6050_get_interrupt_status) (mpu6050\_handle\_t sensor, uint8\_t \*const out\_intr\_status) <br>_Get the interrupt status of mpu6050._ |
|  esp\_err\_t | [**mpu6050\_get\_raw\_acce**](#function-mpu6050_get_raw_acce) (mpu6050\_handle\_t sensor, [**mpu6050\_raw\_acce\_value\_t**](#struct-mpu6050_raw_acce_value_t)\*const raw\_acce\_value) <br>_Read raw accelerometer measurements._ |
|  esp\_err\_t | [**mpu6050\_get\_raw\_gyro**](#function-mpu6050_get_raw_gyro) (mpu6050\_handle\_t sensor, [**mpu6050\_raw\_gyro\_value\_t**](#struct-mpu6050_raw_gyro_value_t)\*const raw\_gyro\_value) <br>_Read raw gyroscope measurements._ |
|  esp\_err\_t | [**mpu6050\_get\_temp**](#function-mpu6050_get_temp) (mpu6050\_handle\_t sensor, [**mpu6050\_temp\_value\_t**](#struct-mpu6050_temp_value_t)\*const temp\_value) <br>_Read temperature values._ |
|  uint8\_t | [**mpu6050\_is\_data\_ready\_interrupt**](#function-mpu6050_is_data_ready_interrupt) (uint8\_t interrupt\_status) <br>_Determine if the last mpu6050 interrupt was due to data ready._ |
|  uint8\_t | [**mpu6050\_is\_fifo\_overflow\_interrupt**](#function-mpu6050_is_fifo_overflow_interrupt) (uint8\_t interrupt\_status) <br>_Determine if the last mpu6050 interrupt was triggered by a fifo overflow._ |
|  uint8\_t | [**mpu6050\_is\_i2c\_master\_interrupt**](#function-mpu6050_is_i2c_master_interrupt) (uint8\_t interrupt\_status) <br>_Determine if the last mpu6050 interrupt was an I2C master interrupt._ |
|  esp\_err\_t | [**mpu6050\_register\_isr**](#function-mpu6050_register_isr) (mpu6050\_handle\_t sensor, const mpu6050\_isr\_t isr) <br>_Register an Interrupt Service Routine to handle mpu6050 interrupts._ |
|  esp\_err\_t | [**mpu6050\_sleep**](#function-mpu6050_sleep) (mpu6050\_handle\_t sensor) <br>_Enter sleep mode._ |
|  esp\_err\_t | [**mpu6050\_wake\_up**](#function-mpu6050_wake_up) (mpu6050\_handle\_t sensor) <br>_Wake up MPU6050._ |

## Classes Documentation

### struct `complimentary_angle_t`

Variables:

-  float pitch  <br>
-  float roll  <br>
### struct `mpu6050_acce_value_t`

Variables:

-  float acce_x  <br>
-  float acce_y  <br>
-  float acce_z  <br>
### struct `mpu6050_gyro_value_t`

Variables:

-  float gyro_x  <br>
-  float gyro_y  <br>
-  float gyro_z  <br>
### struct `mpu6050_int_config_t`

Variables:

-   active_level  <br>
-   interrupt_clear_behavior  <br>
-   interrupt_latch  <br>
-  gpio\_num\_t interrupt_pin  <br>
-   pin_mode  <br>
### struct `mpu6050_raw_acce_value_t`

Variables:

-  int16\_t raw_acce_x  <br>
-  int16\_t raw_acce_y  <br>
-  int16\_t raw_acce_z  <br>
### struct `mpu6050_raw_gyro_value_t`

Variables:

-  int16\_t raw_gyro_x  <br>
-  int16\_t raw_gyro_y  <br>
-  int16\_t raw_gyro_z  <br>
### struct `mpu6050_temp_value_t`

Variables:

-  float temp  <br>

## Macros Documentation

### define `MPU6050_I2C_ADDRESS`

```c
#define MPU6050_I2C_ADDRESS 0x68u
```

### define `MPU6050_I2C_ADDRESS_1`

```c
#define MPU6050_I2C_ADDRESS_1 0x69u
```

### define `MPU6050_WHO_AM_I_VAL`

```c
#define MPU6050_WHO_AM_I_VAL 0x68u
```


## Types Documentation

### enum `mpu6050_acce_fs_t`

```c
enum mpu6050_acce_fs_t {
    ACCE_FS_2G = 0,
    ACCE_FS_4G = 1,
    ACCE_FS_8G = 2,
    ACCE_FS_16G = 3
};
```

### enum `mpu6050_gyro_fs_t`

```c
enum mpu6050_gyro_fs_t {
    GYRO_FS_250DPS = 0,
    GYRO_FS_500DPS = 1,
    GYRO_FS_1000DPS = 2,
    GYRO_FS_2000DPS = 3
};
```

### typedef `mpu6050_handle_t`

```c
typedef void* mpu6050_handle_t;
```

### enum `mpu6050_int_clear_t`

```c
enum mpu6050_int_clear_t {
    INTERRUPT_CLEAR_ON_ANY_READ = 0,
    INTERRUPT_CLEAR_ON_STATUS_READ = 1
};
```

### enum `mpu6050_int_latch_t`

```c
enum mpu6050_int_latch_t {
    INTERRUPT_LATCH_50US = 0,
    INTERRUPT_LATCH_UNTIL_CLEARED = 1
};
```

### enum `mpu6050_int_pin_active_level_t`

```c
enum mpu6050_int_pin_active_level_t {
    INTERRUPT_PIN_ACTIVE_HIGH = 0,
    INTERRUPT_PIN_ACTIVE_LOW = 1
};
```

### enum `mpu6050_int_pin_mode_t`

```c
enum mpu6050_int_pin_mode_t {
    INTERRUPT_PIN_PUSH_PULL = 0,
    INTERRUPT_PIN_OPEN_DRAIN = 1
};
```

### typedef `mpu6050_isr_t`

```c
typedef gpio_isr_t mpu6050_isr_t;
```


## Functions Documentation

### function `mpu6050_complimentory_filter`

```c
esp_err_t mpu6050_complimentory_filter (
    mpu6050_handle_t sensor,
    const mpu6050_acce_value_t *const acce_value,
    const mpu6050_gyro_value_t *const gyro_value,
    complimentary_angle_t *const complimentary_angle
) 
```

### function `mpu6050_config`

```c
esp_err_t mpu6050_config (
    mpu6050_handle_t sensor,
    const mpu6050_acce_fs_t acce_fs,
    const mpu6050_gyro_fs_t gyro_fs
) 
```

### function `mpu6050_config_interrupts`

```c
esp_err_t mpu6050_config_interrupts (
    mpu6050_handle_t sensor,
    const mpu6050_int_config_t *const interrupt_configuration
) 
```

### function `mpu6050_create`

```c
mpu6050_handle_t mpu6050_create (
    i2c_port_t port,
    const uint16_t dev_addr
) 
```

### function `mpu6050_delete`

```c
void mpu6050_delete (
    mpu6050_handle_t sensor
) 
```

### function `mpu6050_disable_interrupts`

```c
esp_err_t mpu6050_disable_interrupts (
    mpu6050_handle_t sensor,
    uint8_t interrupt_sources
) 
```

### function `mpu6050_enable_interrupts`

```c
esp_err_t mpu6050_enable_interrupts (
    mpu6050_handle_t sensor,
    uint8_t interrupt_sources
) 
```

### function `mpu6050_get_acce`

```c
esp_err_t mpu6050_get_acce (
    mpu6050_handle_t sensor,
    mpu6050_acce_value_t *const acce_value
) 
```

### function `mpu6050_get_acce_sensitivity`

```c
esp_err_t mpu6050_get_acce_sensitivity (
    mpu6050_handle_t sensor,
    float *const acce_sensitivity
) 
```

### function `mpu6050_get_deviceid`

```c
esp_err_t mpu6050_get_deviceid (
    mpu6050_handle_t sensor,
    uint8_t *const deviceid
) 
```

### function `mpu6050_get_gyro`

```c
esp_err_t mpu6050_get_gyro (
    mpu6050_handle_t sensor,
    mpu6050_gyro_value_t *const gyro_value
) 
```

### function `mpu6050_get_gyro_sensitivity`

```c
esp_err_t mpu6050_get_gyro_sensitivity (
    mpu6050_handle_t sensor,
    float *const gyro_sensitivity
) 
```

### function `mpu6050_get_interrupt_status`

```c
esp_err_t mpu6050_get_interrupt_status (
    mpu6050_handle_t sensor,
    uint8_t *const out_intr_status
) 
```

### function `mpu6050_get_raw_acce`

```c
esp_err_t mpu6050_get_raw_acce (
    mpu6050_handle_t sensor,
    mpu6050_raw_acce_value_t *const raw_acce_value
) 
```

### function `mpu6050_get_raw_gyro`

```c
esp_err_t mpu6050_get_raw_gyro (
    mpu6050_handle_t sensor,
    mpu6050_raw_gyro_value_t *const raw_gyro_value
) 
```

### function `mpu6050_get_temp`

```c
esp_err_t mpu6050_get_temp (
    mpu6050_handle_t sensor,
    mpu6050_temp_value_t *const temp_value
) 
```

### function `mpu6050_is_data_ready_interrupt`

```c
inline uint8_t mpu6050_is_data_ready_interrupt (
    uint8_t interrupt_status
) 
```

### function `mpu6050_is_fifo_overflow_interrupt`

```c
inline uint8_t mpu6050_is_fifo_overflow_interrupt (
    uint8_t interrupt_status
) 
```

### function `mpu6050_is_i2c_master_interrupt`

```c
inline uint8_t mpu6050_is_i2c_master_interrupt (
    uint8_t interrupt_status
) 
```

### function `mpu6050_register_isr`

```c
esp_err_t mpu6050_register_isr (
    mpu6050_handle_t sensor,
    const mpu6050_isr_t isr
) 
```

### function `mpu6050_sleep`

```c
esp_err_t mpu6050_sleep (
    mpu6050_handle_t sensor
) 
```

### function `mpu6050_wake_up`

```c
esp_err_t mpu6050_wake_up (
    mpu6050_handle_t sensor
) 
```


## File components/ssd1306/include/ssd1306.h


## Macros

| Type | Name |
| ---: | :--- |
| define  | [**SSD1306\_HEIGHT**](#define-ssd1306_height)  64<br> |
| define  | [**SSD1306\_I2C\_ADDRESS**](#define-ssd1306_i2c_address)  ((uint8\_t)0x3C)<br>_I2C address._ |
| define  | [**SSD1306\_WIDTH**](#define-ssd1306_width)  128<br> |

## Types

| Type | Name |
| ---: | :--- |
| typedef void \* | [**ssd1306\_handle\_t**](#typedef-ssd1306_handle_t)  <br> |

## Functions

| Type | Name |
| ---: | :--- |
|  void | [**ssd1306\_clear\_screen**](#function-ssd1306_clear_screen) (ssd1306\_handle\_t dev, uint8\_t chFill) <br>_Clear screen._ |
|  ssd1306\_handle\_t | [**ssd1306\_create**](#function-ssd1306_create) (i2c\_port\_t port, uint16\_t dev\_addr) <br>_Create and initialization device object and return a device handle._ |
|  void | [**ssd1306\_delete**](#function-ssd1306_delete) (ssd1306\_handle\_t dev) <br>_Delete and release a device object._ |
|  void | [**ssd1306\_draw\_1616char**](#function-ssd1306_draw_1616char) (ssd1306\_handle\_t dev, uint8\_t chXpos, uint8\_t chYpos, uint8\_t chChar) <br>_display 1616char on (x, y)_ |
|  void | [**ssd1306\_draw\_3216char**](#function-ssd1306_draw_3216char) (ssd1306\_handle\_t dev, uint8\_t chXpos, uint8\_t chYpos, uint8\_t chChar) <br>_display 3216char on (x, y)_ |
|  void | [**ssd1306\_draw\_bitmap**](#function-ssd1306_draw_bitmap) (ssd1306\_handle\_t dev, uint8\_t chXpos, uint8\_t chYpos, const uint8\_t \* pchBmp, uint8\_t chWidth, uint8\_t chHeight) <br>_draw bitmap on (x, y),and set width, height_ |
|  void | [**ssd1306\_draw\_char**](#function-ssd1306_draw_char) (ssd1306\_handle\_t dev, uint8\_t chXpos, uint8\_t chYpos, uint8\_t chChr, uint8\_t chSize, uint8\_t chMode) <br>_display char on (x, y),and set size, mode_ |
|  void | [**ssd1306\_draw\_line**](#function-ssd1306_draw_line) (ssd1306\_handle\_t dev, int16\_t chXpos1, int16\_t chYpos1, int16\_t chXpos2, int16\_t chYpos2) <br>_draw line between two specified points_ |
|  void | [**ssd1306\_draw\_num**](#function-ssd1306_draw_num) (ssd1306\_handle\_t dev, uint8\_t chXpos, uint8\_t chYpos, uint32\_t chNum, uint8\_t chLen, uint8\_t chSize) <br>_display number on (x, y),and set length, size, mode_ |
|  void | [**ssd1306\_draw\_string**](#function-ssd1306_draw_string) (ssd1306\_handle\_t dev, uint8\_t chXpos, uint8\_t chYpos, const uint8\_t \* pchString, uint8\_t chSize, uint8\_t chMode) <br>_Displays a string on the screen._ |
|  void | [**ssd1306\_fill\_point**](#function-ssd1306_fill_point) (ssd1306\_handle\_t dev, uint8\_t chXpos, uint8\_t chYpos, uint8\_t chPoint) <br>_draw point on (x, y)_ |
|  void | [**ssd1306\_fill\_rectangle**](#function-ssd1306_fill_rectangle) (ssd1306\_handle\_t dev, uint8\_t chXpos1, uint8\_t chYpos1, uint8\_t chXpos2, uint8\_t chYpos2, uint8\_t chDot) <br>_Draw rectangle on (x1,y1)-(x2,y2)_ |
|  esp\_err\_t | [**ssd1306\_init**](#function-ssd1306_init) (ssd1306\_handle\_t dev) <br>_device initialization_ |
|  esp\_err\_t | [**ssd1306\_refresh\_gram**](#function-ssd1306_refresh_gram) (ssd1306\_handle\_t dev) <br>_refresh dot matrix panel_ |


## Macros Documentation

### define `SSD1306_HEIGHT`

```c
#define SSD1306_HEIGHT 64
```

### define `SSD1306_I2C_ADDRESS`

```c
#define SSD1306_I2C_ADDRESS ((uint8_t)0x3C)
```

### define `SSD1306_WIDTH`

```c
#define SSD1306_WIDTH 128
```


## Types Documentation

### typedef `ssd1306_handle_t`

```c
typedef void* ssd1306_handle_t;
```


## Functions Documentation

### function `ssd1306_clear_screen`

```c
void ssd1306_clear_screen (
    ssd1306_handle_t dev,
    uint8_t chFill
) 
```

### function `ssd1306_create`

```c
ssd1306_handle_t ssd1306_create (
    i2c_port_t port,
    uint16_t dev_addr
) 
```

### function `ssd1306_delete`

```c
void ssd1306_delete (
    ssd1306_handle_t dev
) 
```

### function `ssd1306_draw_1616char`

```c
void ssd1306_draw_1616char (
    ssd1306_handle_t dev,
    uint8_t chXpos,
    uint8_t chYpos,
    uint8_t chChar
) 
```

### function `ssd1306_draw_3216char`

```c
void ssd1306_draw_3216char (
    ssd1306_handle_t dev,
    uint8_t chXpos,
    uint8_t chYpos,
    uint8_t chChar
) 
```

### function `ssd1306_draw_bitmap`

```c
void ssd1306_draw_bitmap (
    ssd1306_handle_t dev,
    uint8_t chXpos,
    uint8_t chYpos,
    const uint8_t * pchBmp,
    uint8_t chWidth,
    uint8_t chHeight
) 
```

### function `ssd1306_draw_char`

```c
void ssd1306_draw_char (
    ssd1306_handle_t dev,
    uint8_t chXpos,
    uint8_t chYpos,
    uint8_t chChr,
    uint8_t chSize,
    uint8_t chMode
) 
```

### function `ssd1306_draw_line`

```c
void ssd1306_draw_line (
    ssd1306_handle_t dev,
    int16_t chXpos1,
    int16_t chYpos1,
    int16_t chXpos2,
    int16_t chYpos2
) 
```

### function `ssd1306_draw_num`

```c
void ssd1306_draw_num (
    ssd1306_handle_t dev,
    uint8_t chXpos,
    uint8_t chYpos,
    uint32_t chNum,
    uint8_t chLen,
    uint8_t chSize
) 
```

### function `ssd1306_draw_string`

```c
void ssd1306_draw_string (
    ssd1306_handle_t dev,
    uint8_t chXpos,
    uint8_t chYpos,
    const uint8_t * pchString,
    uint8_t chSize,
    uint8_t chMode
) 
```

### function `ssd1306_fill_point`

```c
void ssd1306_fill_point (
    ssd1306_handle_t dev,
    uint8_t chXpos,
    uint8_t chYpos,
    uint8_t chPoint
) 
```

### function `ssd1306_fill_rectangle`

```c
void ssd1306_fill_rectangle (
    ssd1306_handle_t dev,
    uint8_t chXpos1,
    uint8_t chYpos1,
    uint8_t chXpos2,
    uint8_t chYpos2,
    uint8_t chDot
) 
```

### function `ssd1306_init`

```c
esp_err_t ssd1306_init (
    ssd1306_handle_t dev
) 
```

### function `ssd1306_refresh_gram`

```c
esp_err_t ssd1306_refresh_gram (
    ssd1306_handle_t dev
) 
```


## File components/ssd1306/include/ssd1306_fonts.h









## File esp-box-lite/include/bsp/esp-box-lite.h


## Macros

| Type | Name |
| ---: | :--- |
| define  | [**BSP\_I2C\_NUM**](#define-bsp_i2c_num)  CONFIG\_BSP\_I2C\_NUM<br> |
| define  | [**BSP\_I2C\_SCL**](#define-bsp_i2c_scl)  (GPIO\_NUM\_18)<br> |
| define  | [**BSP\_I2C\_SDA**](#define-bsp_i2c_sda)  (GPIO\_NUM\_8)<br> |
| define  | [**BSP\_I2S\_DOUT**](#define-bsp_i2s_dout)  (GPIO\_NUM\_15)<br> |
| define  | [**BSP\_I2S\_DSIN**](#define-bsp_i2s_dsin)  (GPIO\_NUM\_16)<br> |
| define  | [**BSP\_I2S\_DUPLEX\_MONO\_CFG**](#define-bsp_i2s_duplex_mono_cfg) (\_sample\_rate) <br>_Mono Duplex I2S configuration structure._ |
| define  | [**BSP\_I2S\_GPIO\_CFG**](#define-bsp_i2s_gpio_cfg)  <br>_ESP-BOX-Lite I2S pinout._ |
| define  | [**BSP\_I2S\_LCLK**](#define-bsp_i2s_lclk)  (GPIO\_NUM\_47)<br> |
| define  | [**BSP\_I2S\_MCLK**](#define-bsp_i2s_mclk)  (GPIO\_NUM\_2)<br> |
| define  | [**BSP\_I2S\_SCLK**](#define-bsp_i2s_sclk)  (GPIO\_NUM\_17)<br> |
| define  | [**BSP\_LCD\_BACKLIGHT**](#define-bsp_lcd_backlight)  (GPIO\_NUM\_45)<br> |
| define  | [**BSP\_LCD\_CS**](#define-bsp_lcd_cs)  (GPIO\_NUM\_5)<br> |
| define  | [**BSP\_LCD\_DATA0**](#define-bsp_lcd_data0)  (GPIO\_NUM\_6)<br> |
| define  | [**BSP\_LCD\_DC**](#define-bsp_lcd_dc)  (GPIO\_NUM\_4)<br> |
| define  | [**BSP\_LCD\_H\_RES**](#define-bsp_lcd_h_res)  (320)<br> |
| define  | [**BSP\_LCD\_PCLK**](#define-bsp_lcd_pclk)  (GPIO\_NUM\_7)<br> |
| define  | [**BSP\_LCD\_PIXEL\_CLOCK\_HZ**](#define-bsp_lcd_pixel_clock_hz)  (40 \* 1000 \* 1000)<br> |
| define  | [**BSP\_LCD\_RST**](#define-bsp_lcd_rst)  (GPIO\_NUM\_48)<br> |
| define  | [**BSP\_LCD\_SPI\_NUM**](#define-bsp_lcd_spi_num)  (SPI3\_HOST)<br> |
| define  | [**BSP\_LCD\_V\_RES**](#define-bsp_lcd_v_res)  (240)<br> |
| define  | [**BSP\_PMOD1\_IO1**](#define-bsp_pmod1_io1)  GPIO\_NUM\_42<br> |
| define  | [**BSP\_PMOD1\_IO2**](#define-bsp_pmod1_io2)  GPIO\_NUM\_21<br> |
| define  | [**BSP\_PMOD1\_IO3**](#define-bsp_pmod1_io3)  BSP\_USB\_NEG<br> |
| define  | [**BSP\_PMOD1\_IO4**](#define-bsp_pmod1_io4)  BSP\_USB\_POS<br> |
| define  | [**BSP\_PMOD1\_IO5**](#define-bsp_pmod1_io5)  GPIO\_NUM\_38<br> |
| define  | [**BSP\_PMOD1\_IO6**](#define-bsp_pmod1_io6)  GPIO\_NUM\_39<br> |
| define  | [**BSP\_PMOD1\_IO7**](#define-bsp_pmod1_io7)  GPIO\_NUM\_40<br> |
| define  | [**BSP\_PMOD1\_IO8**](#define-bsp_pmod1_io8)  GPIO\_NUM\_41<br> |
| define  | [**BSP\_PMOD2\_IO1**](#define-bsp_pmod2_io1)  GPIO\_NUM\_10<br> |
| define  | [**BSP\_PMOD2\_IO2**](#define-bsp_pmod2_io2)  GPIO\_NUM\_11<br> |
| define  | [**BSP\_PMOD2\_IO3**](#define-bsp_pmod2_io3)  GPIO\_NUM\_13<br> |
| define  | [**BSP\_PMOD2\_IO4**](#define-bsp_pmod2_io4)  GPIO\_NUM\_12<br> |
| define  | [**BSP\_PMOD2\_IO5**](#define-bsp_pmod2_io5)  GPIO\_NUM\_9<br> |
| define  | [**BSP\_PMOD2\_IO6**](#define-bsp_pmod2_io6)  GPIO\_NUM\_43<br> |
| define  | [**BSP\_PMOD2\_IO7**](#define-bsp_pmod2_io7)  GPIO\_NUM\_44<br> |
| define  | [**BSP\_PMOD2\_IO8**](#define-bsp_pmod2_io8)  GPIO\_NUM\_14<br> |
| define  | [**BSP\_POWER\_AMP\_IO**](#define-bsp_power_amp_io)  (GPIO\_NUM\_46)<br> |
| define  | [**BSP\_SPIFFS\_MOUNT\_POINT**](#define-bsp_spiffs_mount_point)  CONFIG\_BSP\_SPIFFS\_MOUNT\_POINT<br> |
| define  | [**BSP\_USB\_NEG**](#define-bsp_usb_neg)  USBPHY\_DM\_NUM<br> |
| define  | [**BSP\_USB\_POS**](#define-bsp_usb_pos)  USBPHY\_DP\_NUM<br> |

## Types

| Type | Name |
| ---: | :--- |
| enum  | [**bsp\_button\_t**](#enum-bsp_button_t)  <br> |

## Functions

| Type | Name |
| ---: | :--- |
|  esp\_codec\_dev\_handle\_t | [**bsp\_audio\_codec\_microphone\_init**](#function-bsp_audio_codec_microphone_init) (void) <br>_Initialize microphone codec device._ |
|  esp\_codec\_dev\_handle\_t | [**bsp\_audio\_codec\_speaker\_init**](#function-bsp_audio_codec_speaker_init) (void) <br>_Initialize speaker codec device._ |
|  esp\_err\_t | [**bsp\_audio\_init**](#function-bsp_audio_init) (const i2s\_std\_config\_t \* i2s\_config, i2s\_chan\_handle\_t \* tx\_channel, i2s\_chan\_handle\_t \* rx\_channel) <br>_Init audio._ |
|  esp\_err\_t | [**bsp\_audio\_poweramp\_enable**](#function-bsp_audio_poweramp_enable) (const bool enable) <br>_Enable/disable audio power amplifier._ |
|  esp\_err\_t | [**bsp\_display\_backlight\_off**](#function-bsp_display_backlight_off) (void) <br>_Turn off display backlight._ |
|  esp\_err\_t | [**bsp\_display\_backlight\_on**](#function-bsp_display_backlight_on) (void) <br>_Turn on display backlight._ |
|  esp\_err\_t | [**bsp\_display\_brightness\_set**](#function-bsp_display_brightness_set) (int brightness\_percent) <br>_Set display's brightness._ |
|  lv\_indev\_t \* | [**bsp\_display\_get\_input\_dev**](#function-bsp_display_get_input_dev) (void) <br>_Get pointer to input device (touch, buttons, ...)_ |
|  bool | [**bsp\_display\_lock**](#function-bsp_display_lock) (uint32\_t timeout\_ms) <br>_Take LVGL mutex._ |
|  void | [**bsp\_display\_rotate**](#function-bsp_display_rotate) (lv\_disp\_t \* disp, lv\_disp\_rot\_t rotation) <br>_Rotate screen._ |
|  lv\_disp\_t \* | [**bsp\_display\_start**](#function-bsp_display_start) (void) <br>_Initialize display._ |
|  void | [**bsp\_display\_unlock**](#function-bsp_display_unlock) (void) <br>_Give LVGL mutex._ |
|  esp\_err\_t | [**bsp\_i2c\_deinit**](#function-bsp_i2c_deinit) (void) <br>_Deinit I2C driver and free its resources._ |
|  esp\_err\_t | [**bsp\_i2c\_init**](#function-bsp_i2c_init) (void) <br>_Init I2C driver._ |
|  esp\_err\_t | [**bsp\_spiffs\_mount**](#function-bsp_spiffs_mount) (void) <br>_Mount SPIFFS to virtual file system._ |
|  esp\_err\_t | [**bsp\_spiffs\_unmount**](#function-bsp_spiffs_unmount) (void) <br>_Unmount SPIFFS from virtual file system._ |


## Macros Documentation

### define `BSP_I2C_NUM`

```c
#define BSP_I2C_NUM CONFIG_BSP_I2C_NUM
```

### define `BSP_I2C_SCL`

```c
#define BSP_I2C_SCL (GPIO_NUM_18)
```

### define `BSP_I2C_SDA`

```c
#define BSP_I2C_SDA (GPIO_NUM_8)
```

### define `BSP_I2S_DOUT`

```c
#define BSP_I2S_DOUT (GPIO_NUM_15)
```

### define `BSP_I2S_DSIN`

```c
#define BSP_I2S_DSIN (GPIO_NUM_16)
```

### define `BSP_I2S_DUPLEX_MONO_CFG`

```c
#define BSP_I2S_DUPLEX_MONO_CFG (
    _sample_rate
) {                                                                                                 \
        .clk_cfg = I2S_STD_CLK_DEFAULT_CONFIG(_sample_rate),                                          \
        .slot_cfg = I2S_STD_PHILIP_SLOT_DEFAULT_CONFIG(I2S_DATA_BIT_WIDTH_16BIT, I2S_SLOT_MODE_MONO), \
        .gpio_cfg = BSP_I2S_GPIO_CFG ,                                                                 \
    }
```

### define `BSP_I2S_GPIO_CFG`

```c
#define BSP_I2S_GPIO_CFG {                          \
        .mclk = BSP_I2S_MCLK,  \
        .bclk = BSP_I2S_SCLK,  \
        .ws = BSP_I2S_LCLK,    \
        .dout = BSP_I2S_DOUT,  \
        .din = BSP_I2S_DSIN,   \
        .invert_flags = {      \
            .mclk_inv = false, \
            .bclk_inv = false, \
            .ws_inv = false,   \
        },                     \
    }
```

### define `BSP_I2S_LCLK`

```c
#define BSP_I2S_LCLK (GPIO_NUM_47)
```

### define `BSP_I2S_MCLK`

```c
#define BSP_I2S_MCLK (GPIO_NUM_2)
```

### define `BSP_I2S_SCLK`

```c
#define BSP_I2S_SCLK (GPIO_NUM_17)
```

### define `BSP_LCD_BACKLIGHT`

```c
#define BSP_LCD_BACKLIGHT (GPIO_NUM_45)
```

### define `BSP_LCD_CS`

```c
#define BSP_LCD_CS (GPIO_NUM_5)
```

### define `BSP_LCD_DATA0`

```c
#define BSP_LCD_DATA0 (GPIO_NUM_6)
```

### define `BSP_LCD_DC`

```c
#define BSP_LCD_DC (GPIO_NUM_4)
```

### define `BSP_LCD_H_RES`

```c
#define BSP_LCD_H_RES (320)
```

### define `BSP_LCD_PCLK`

```c
#define BSP_LCD_PCLK (GPIO_NUM_7)
```

### define `BSP_LCD_PIXEL_CLOCK_HZ`

```c
#define BSP_LCD_PIXEL_CLOCK_HZ (40 * 1000 * 1000)
```

### define `BSP_LCD_RST`

```c
#define BSP_LCD_RST (GPIO_NUM_48)
```

### define `BSP_LCD_SPI_NUM`

```c
#define BSP_LCD_SPI_NUM (SPI3_HOST)
```

### define `BSP_LCD_V_RES`

```c
#define BSP_LCD_V_RES (240)
```

### define `BSP_PMOD1_IO1`

```c
#define BSP_PMOD1_IO1 GPIO_NUM_42
```

### define `BSP_PMOD1_IO2`

```c
#define BSP_PMOD1_IO2 GPIO_NUM_21
```

### define `BSP_PMOD1_IO3`

```c
#define BSP_PMOD1_IO3 BSP_USB_NEG
```

### define `BSP_PMOD1_IO4`

```c
#define BSP_PMOD1_IO4 BSP_USB_POS
```

### define `BSP_PMOD1_IO5`

```c
#define BSP_PMOD1_IO5 GPIO_NUM_38
```

### define `BSP_PMOD1_IO6`

```c
#define BSP_PMOD1_IO6 GPIO_NUM_39
```

### define `BSP_PMOD1_IO7`

```c
#define BSP_PMOD1_IO7 GPIO_NUM_40
```

### define `BSP_PMOD1_IO8`

```c
#define BSP_PMOD1_IO8 GPIO_NUM_41
```

### define `BSP_PMOD2_IO1`

```c
#define BSP_PMOD2_IO1 GPIO_NUM_10
```

### define `BSP_PMOD2_IO2`

```c
#define BSP_PMOD2_IO2 GPIO_NUM_11
```

### define `BSP_PMOD2_IO3`

```c
#define BSP_PMOD2_IO3 GPIO_NUM_13
```

### define `BSP_PMOD2_IO4`

```c
#define BSP_PMOD2_IO4 GPIO_NUM_12
```

### define `BSP_PMOD2_IO5`

```c
#define BSP_PMOD2_IO5 GPIO_NUM_9
```

### define `BSP_PMOD2_IO6`

```c
#define BSP_PMOD2_IO6 GPIO_NUM_43
```

### define `BSP_PMOD2_IO7`

```c
#define BSP_PMOD2_IO7 GPIO_NUM_44
```

### define `BSP_PMOD2_IO8`

```c
#define BSP_PMOD2_IO8 GPIO_NUM_14
```

### define `BSP_POWER_AMP_IO`

```c
#define BSP_POWER_AMP_IO (GPIO_NUM_46)
```

### define `BSP_SPIFFS_MOUNT_POINT`

```c
#define BSP_SPIFFS_MOUNT_POINT CONFIG_BSP_SPIFFS_MOUNT_POINT
```

### define `BSP_USB_NEG`

```c
#define BSP_USB_NEG USBPHY_DM_NUM
```

### define `BSP_USB_POS`

```c
#define BSP_USB_POS USBPHY_DP_NUM
```


## Types Documentation

### enum `bsp_button_t`

```c
enum bsp_button_t {
    BSP_BUTTON_PREV,
    BSP_BUTTON_ENTER,
    BSP_BUTTON_NEXT,
    BSP_BUTTON_NUM
};
```


## Functions Documentation

### function `bsp_audio_codec_microphone_init`

```c
esp_codec_dev_handle_t bsp_audio_codec_microphone_init (
    void
) 
```

### function `bsp_audio_codec_speaker_init`

```c
esp_codec_dev_handle_t bsp_audio_codec_speaker_init (
    void
) 
```

### function `bsp_audio_init`

```c
esp_err_t bsp_audio_init (
    const i2s_std_config_t * i2s_config,
    i2s_chan_handle_t * tx_channel,
    i2s_chan_handle_t * rx_channel
) 
```

### function `bsp_audio_poweramp_enable`

```c
esp_err_t bsp_audio_poweramp_enable (
    const bool enable
) 
```

### function `bsp_display_backlight_off`

```c
esp_err_t bsp_display_backlight_off (
    void
) 
```

### function `bsp_display_backlight_on`

```c
esp_err_t bsp_display_backlight_on (
    void
) 
```

### function `bsp_display_brightness_set`

```c
esp_err_t bsp_display_brightness_set (
    int brightness_percent
) 
```

### function `bsp_display_get_input_dev`

```c
lv_indev_t * bsp_display_get_input_dev (
    void
) 
```

### function `bsp_display_lock`

```c
bool bsp_display_lock (
    uint32_t timeout_ms
) 
```

### function `bsp_display_rotate`

```c
void bsp_display_rotate (
    lv_disp_t * disp,
    lv_disp_rot_t rotation
) 
```

### function `bsp_display_start`

```c
lv_disp_t * bsp_display_start (
    void
) 
```

### function `bsp_display_unlock`

```c
void bsp_display_unlock (
    void
) 
```

### function `bsp_i2c_deinit`

```c
esp_err_t bsp_i2c_deinit (
    void
) 
```

### function `bsp_i2c_init`

```c
esp_err_t bsp_i2c_init (
    void
) 
```

### function `bsp_spiffs_mount`

```c
esp_err_t bsp_spiffs_mount (
    void
) 
```

### function `bsp_spiffs_unmount`

```c
esp_err_t bsp_spiffs_unmount (
    void
) 
```


## File esp-box/include/bsp/esp-box.h


## Macros

| Type | Name |
| ---: | :--- |
| define  | [**BSP\_I2C\_NUM**](#define-bsp_i2c_num)  CONFIG\_BSP\_I2C\_NUM<br> |
| define  | [**BSP\_I2C\_SCL**](#define-bsp_i2c_scl)  (GPIO\_NUM\_18)<br> |
| define  | [**BSP\_I2C\_SDA**](#define-bsp_i2c_sda)  (GPIO\_NUM\_8)<br> |
| define  | [**BSP\_I2S\_DOUT**](#define-bsp_i2s_dout)  (GPIO\_NUM\_15)<br> |
| define  | [**BSP\_I2S\_DSIN**](#define-bsp_i2s_dsin)  (GPIO\_NUM\_16)<br> |
| define  | [**BSP\_I2S\_DUPLEX\_MONO\_CFG**](#define-bsp_i2s_duplex_mono_cfg) (\_sample\_rate) <br>_Mono Duplex I2S configuration structure._ |
| define  | [**BSP\_I2S\_GPIO\_CFG**](#define-bsp_i2s_gpio_cfg)  <br>_ESP-BOX I2S pinout._ |
| define  | [**BSP\_I2S\_LCLK**](#define-bsp_i2s_lclk)  (GPIO\_NUM\_47)<br> |
| define  | [**BSP\_I2S\_MCLK**](#define-bsp_i2s_mclk)  (GPIO\_NUM\_2)<br> |
| define  | [**BSP\_I2S\_SCLK**](#define-bsp_i2s_sclk)  (GPIO\_NUM\_17)<br> |
| define  | [**BSP\_LCD\_BACKLIGHT**](#define-bsp_lcd_backlight)  (GPIO\_NUM\_45)<br> |
| define  | [**BSP\_LCD\_CS**](#define-bsp_lcd_cs)  (GPIO\_NUM\_5)<br> |
| define  | [**BSP\_LCD\_DATA0**](#define-bsp_lcd_data0)  (GPIO\_NUM\_6)<br> |
| define  | [**BSP\_LCD\_DC**](#define-bsp_lcd_dc)  (GPIO\_NUM\_4)<br> |
| define  | [**BSP\_LCD\_H\_RES**](#define-bsp_lcd_h_res)  (320)<br> |
| define  | [**BSP\_LCD\_PCLK**](#define-bsp_lcd_pclk)  (GPIO\_NUM\_7)<br> |
| define  | [**BSP\_LCD\_PIXEL\_CLOCK\_HZ**](#define-bsp_lcd_pixel_clock_hz)  (40 \* 1000 \* 1000)<br> |
| define  | [**BSP\_LCD\_RST**](#define-bsp_lcd_rst)  (GPIO\_NUM\_48)<br> |
| define  | [**BSP\_LCD\_SPI\_NUM**](#define-bsp_lcd_spi_num)  (SPI3\_HOST)<br> |
| define  | [**BSP\_LCD\_TOUCH\_INT**](#define-bsp_lcd_touch_int)  (GPIO\_NUM\_3)<br> |
| define  | [**BSP\_LCD\_V\_RES**](#define-bsp_lcd_v_res)  (240)<br> |
| define  | [**BSP\_MUTE\_STATUS**](#define-bsp_mute_status)  (GPIO\_NUM\_1)<br> |
| define  | [**BSP\_PMOD1\_IO1**](#define-bsp_pmod1_io1)  GPIO\_NUM\_42<br> |
| define  | [**BSP\_PMOD1\_IO2**](#define-bsp_pmod1_io2)  GPIO\_NUM\_21<br> |
| define  | [**BSP\_PMOD1\_IO3**](#define-bsp_pmod1_io3)  BSP\_USB\_NEG<br> |
| define  | [**BSP\_PMOD1\_IO4**](#define-bsp_pmod1_io4)  BSP\_USB\_POS<br> |
| define  | [**BSP\_PMOD1\_IO5**](#define-bsp_pmod1_io5)  GPIO\_NUM\_38<br> |
| define  | [**BSP\_PMOD1\_IO6**](#define-bsp_pmod1_io6)  GPIO\_NUM\_39<br> |
| define  | [**BSP\_PMOD1\_IO7**](#define-bsp_pmod1_io7)  GPIO\_NUM\_40<br> |
| define  | [**BSP\_PMOD1\_IO8**](#define-bsp_pmod1_io8)  GPIO\_NUM\_41<br> |
| define  | [**BSP\_PMOD2\_IO1**](#define-bsp_pmod2_io1)  GPIO\_NUM\_10<br> |
| define  | [**BSP\_PMOD2\_IO2**](#define-bsp_pmod2_io2)  GPIO\_NUM\_11<br> |
| define  | [**BSP\_PMOD2\_IO3**](#define-bsp_pmod2_io3)  GPIO\_NUM\_13<br> |
| define  | [**BSP\_PMOD2\_IO4**](#define-bsp_pmod2_io4)  GPIO\_NUM\_12<br> |
| define  | [**BSP\_PMOD2\_IO5**](#define-bsp_pmod2_io5)  GPIO\_NUM\_9<br> |
| define  | [**BSP\_PMOD2\_IO6**](#define-bsp_pmod2_io6)  GPIO\_NUM\_43<br> |
| define  | [**BSP\_PMOD2\_IO7**](#define-bsp_pmod2_io7)  GPIO\_NUM\_44<br> |
| define  | [**BSP\_PMOD2\_IO8**](#define-bsp_pmod2_io8)  GPIO\_NUM\_14<br> |
| define  | [**BSP\_POWER\_AMP\_IO**](#define-bsp_power_amp_io)  (GPIO\_NUM\_46)<br> |
| define  | [**BSP\_SPIFFS\_MOUNT\_POINT**](#define-bsp_spiffs_mount_point)  CONFIG\_BSP\_SPIFFS\_MOUNT\_POINT<br> |
| define  | [**BSP\_USB\_NEG**](#define-bsp_usb_neg)  USBPHY\_DM\_NUM<br> |
| define  | [**BSP\_USB\_POS**](#define-bsp_usb_pos)  USBPHY\_DP\_NUM<br> |

## Types

| Type | Name |
| ---: | :--- |
| enum  | [**bsp\_button\_t**](#enum-bsp_button_t)  <br> |

## Functions

| Type | Name |
| ---: | :--- |
|  esp\_codec\_dev\_handle\_t | [**bsp\_audio\_codec\_microphone\_init**](#function-bsp_audio_codec_microphone_init) (void) <br>_Initialize microphone codec device._ |
|  esp\_codec\_dev\_handle\_t | [**bsp\_audio\_codec\_speaker\_init**](#function-bsp_audio_codec_speaker_init) (void) <br>_Initialize speaker codec device._ |
|  esp\_err\_t | [**bsp\_audio\_init**](#function-bsp_audio_init) (const i2s\_std\_config\_t \* i2s\_config, i2s\_chan\_handle\_t \* tx\_channel, i2s\_chan\_handle\_t \* rx\_channel) <br>_Init audio._ |
|  esp\_err\_t | [**bsp\_audio\_poweramp\_enable**](#function-bsp_audio_poweramp_enable) (const bool enable) <br>_Enable/disable audio power amplifier._ |
|  bool | [**bsp\_button\_get**](#function-bsp_button_get) (const bsp\_button\_t btn) <br>_Get button's state._ |
|  esp\_err\_t | [**bsp\_button\_init**](#function-bsp_button_init) (const bsp\_button\_t btn) <br>_Set button's GPIO as input._ |
|  esp\_err\_t | [**bsp\_display\_backlight\_off**](#function-bsp_display_backlight_off) (void) <br>_Turn off display backlight._ |
|  esp\_err\_t | [**bsp\_display\_backlight\_on**](#function-bsp_display_backlight_on) (void) <br>_Turn on display backlight._ |
|  esp\_err\_t | [**bsp\_display\_brightness\_set**](#function-bsp_display_brightness_set) (int brightness\_percent) <br>_Set display's brightness._ |
|  lv\_indev\_t \* | [**bsp\_display\_get\_input\_dev**](#function-bsp_display_get_input_dev) (void) <br>_Get pointer to input device (touch, buttons, ...)_ |
|  bool | [**bsp\_display\_lock**](#function-bsp_display_lock) (uint32\_t timeout\_ms) <br>_Take LVGL mutex._ |
|  void | [**bsp\_display\_rotate**](#function-bsp_display_rotate) (lv\_disp\_t \* disp, lv\_disp\_rot\_t rotation) <br>_Rotate screen._ |
|  lv\_disp\_t \* | [**bsp\_display\_start**](#function-bsp_display_start) (void) <br>_Initialize display._ |
|  void | [**bsp\_display\_unlock**](#function-bsp_display_unlock) (void) <br>_Give LVGL mutex._ |
|  esp\_err\_t | [**bsp\_i2c\_deinit**](#function-bsp_i2c_deinit) (void) <br>_Deinit I2C driver and free its resources._ |
|  esp\_err\_t | [**bsp\_i2c\_init**](#function-bsp_i2c_init) (void) <br>_Init I2C driver._ |
|  esp\_err\_t | [**bsp\_spiffs\_mount**](#function-bsp_spiffs_mount) (void) <br>_Mount SPIFFS to virtual file system._ |
|  esp\_err\_t | [**bsp\_spiffs\_unmount**](#function-bsp_spiffs_unmount) (void) <br>_Unmount SPIFFS from virtual file system._ |


## Macros Documentation

### define `BSP_I2C_NUM`

```c
#define BSP_I2C_NUM CONFIG_BSP_I2C_NUM
```

### define `BSP_I2C_SCL`

```c
#define BSP_I2C_SCL (GPIO_NUM_18)
```

### define `BSP_I2C_SDA`

```c
#define BSP_I2C_SDA (GPIO_NUM_8)
```

### define `BSP_I2S_DOUT`

```c
#define BSP_I2S_DOUT (GPIO_NUM_15)
```

### define `BSP_I2S_DSIN`

```c
#define BSP_I2S_DSIN (GPIO_NUM_16)
```

### define `BSP_I2S_DUPLEX_MONO_CFG`

```c
#define BSP_I2S_DUPLEX_MONO_CFG (
    _sample_rate
) {                                                                                                 \
        .clk_cfg = I2S_STD_CLK_DEFAULT_CONFIG(_sample_rate),                                          \
        .slot_cfg = I2S_STD_PHILIP_SLOT_DEFAULT_CONFIG(I2S_DATA_BIT_WIDTH_16BIT, I2S_SLOT_MODE_MONO), \
        .gpio_cfg = BSP_I2S_GPIO_CFG ,                                                                 \
    }
```

### define `BSP_I2S_GPIO_CFG`

```c
#define BSP_I2S_GPIO_CFG {                          \
        .mclk = BSP_I2S_MCLK,  \
        .bclk = BSP_I2S_SCLK,  \
        .ws = BSP_I2S_LCLK,    \
        .dout = BSP_I2S_DOUT,  \
        .din = BSP_I2S_DSIN,   \
        .invert_flags = {      \
            .mclk_inv = false, \
            .bclk_inv = false, \
            .ws_inv = false,   \
        },                     \
    }
```

### define `BSP_I2S_LCLK`

```c
#define BSP_I2S_LCLK (GPIO_NUM_47)
```

### define `BSP_I2S_MCLK`

```c
#define BSP_I2S_MCLK (GPIO_NUM_2)
```

### define `BSP_I2S_SCLK`

```c
#define BSP_I2S_SCLK (GPIO_NUM_17)
```

### define `BSP_LCD_BACKLIGHT`

```c
#define BSP_LCD_BACKLIGHT (GPIO_NUM_45)
```

### define `BSP_LCD_CS`

```c
#define BSP_LCD_CS (GPIO_NUM_5)
```

### define `BSP_LCD_DATA0`

```c
#define BSP_LCD_DATA0 (GPIO_NUM_6)
```

### define `BSP_LCD_DC`

```c
#define BSP_LCD_DC (GPIO_NUM_4)
```

### define `BSP_LCD_H_RES`

```c
#define BSP_LCD_H_RES (320)
```

### define `BSP_LCD_PCLK`

```c
#define BSP_LCD_PCLK (GPIO_NUM_7)
```

### define `BSP_LCD_PIXEL_CLOCK_HZ`

```c
#define BSP_LCD_PIXEL_CLOCK_HZ (40 * 1000 * 1000)
```

### define `BSP_LCD_RST`

```c
#define BSP_LCD_RST (GPIO_NUM_48)
```

### define `BSP_LCD_SPI_NUM`

```c
#define BSP_LCD_SPI_NUM (SPI3_HOST)
```

### define `BSP_LCD_TOUCH_INT`

```c
#define BSP_LCD_TOUCH_INT (GPIO_NUM_3)
```

### define `BSP_LCD_V_RES`

```c
#define BSP_LCD_V_RES (240)
```

### define `BSP_MUTE_STATUS`

```c
#define BSP_MUTE_STATUS (GPIO_NUM_1)
```

### define `BSP_PMOD1_IO1`

```c
#define BSP_PMOD1_IO1 GPIO_NUM_42
```

### define `BSP_PMOD1_IO2`

```c
#define BSP_PMOD1_IO2 GPIO_NUM_21
```

### define `BSP_PMOD1_IO3`

```c
#define BSP_PMOD1_IO3 BSP_USB_NEG
```

### define `BSP_PMOD1_IO4`

```c
#define BSP_PMOD1_IO4 BSP_USB_POS
```

### define `BSP_PMOD1_IO5`

```c
#define BSP_PMOD1_IO5 GPIO_NUM_38
```

### define `BSP_PMOD1_IO6`

```c
#define BSP_PMOD1_IO6 GPIO_NUM_39
```

### define `BSP_PMOD1_IO7`

```c
#define BSP_PMOD1_IO7 GPIO_NUM_40
```

### define `BSP_PMOD1_IO8`

```c
#define BSP_PMOD1_IO8 GPIO_NUM_41
```

### define `BSP_PMOD2_IO1`

```c
#define BSP_PMOD2_IO1 GPIO_NUM_10
```

### define `BSP_PMOD2_IO2`

```c
#define BSP_PMOD2_IO2 GPIO_NUM_11
```

### define `BSP_PMOD2_IO3`

```c
#define BSP_PMOD2_IO3 GPIO_NUM_13
```

### define `BSP_PMOD2_IO4`

```c
#define BSP_PMOD2_IO4 GPIO_NUM_12
```

### define `BSP_PMOD2_IO5`

```c
#define BSP_PMOD2_IO5 GPIO_NUM_9
```

### define `BSP_PMOD2_IO6`

```c
#define BSP_PMOD2_IO6 GPIO_NUM_43
```

### define `BSP_PMOD2_IO7`

```c
#define BSP_PMOD2_IO7 GPIO_NUM_44
```

### define `BSP_PMOD2_IO8`

```c
#define BSP_PMOD2_IO8 GPIO_NUM_14
```

### define `BSP_POWER_AMP_IO`

```c
#define BSP_POWER_AMP_IO (GPIO_NUM_46)
```

### define `BSP_SPIFFS_MOUNT_POINT`

```c
#define BSP_SPIFFS_MOUNT_POINT CONFIG_BSP_SPIFFS_MOUNT_POINT
```

### define `BSP_USB_NEG`

```c
#define BSP_USB_NEG USBPHY_DM_NUM
```

### define `BSP_USB_POS`

```c
#define BSP_USB_POS USBPHY_DP_NUM
```


## Types Documentation

### enum `bsp_button_t`

```c
enum bsp_button_t {
    BSP_BUTTON_CONFIG = GPIO_NUM_0,
    BSP_BUTTON_MUTE = GPIO_NUM_1,
    BSP_BUTTON_MAIN = 100
};
```


## Functions Documentation

### function `bsp_audio_codec_microphone_init`

```c
esp_codec_dev_handle_t bsp_audio_codec_microphone_init (
    void
) 
```

### function `bsp_audio_codec_speaker_init`

```c
esp_codec_dev_handle_t bsp_audio_codec_speaker_init (
    void
) 
```

### function `bsp_audio_init`

```c
esp_err_t bsp_audio_init (
    const i2s_std_config_t * i2s_config,
    i2s_chan_handle_t * tx_channel,
    i2s_chan_handle_t * rx_channel
) 
```

### function `bsp_audio_poweramp_enable`

```c
esp_err_t bsp_audio_poweramp_enable (
    const bool enable
) 
```

### function `bsp_button_get`

```c
bool bsp_button_get (
    const bsp_button_t btn
) 
```

### function `bsp_button_init`

```c
esp_err_t bsp_button_init (
    const bsp_button_t btn
) 
```

### function `bsp_display_backlight_off`

```c
esp_err_t bsp_display_backlight_off (
    void
) 
```

### function `bsp_display_backlight_on`

```c
esp_err_t bsp_display_backlight_on (
    void
) 
```

### function `bsp_display_brightness_set`

```c
esp_err_t bsp_display_brightness_set (
    int brightness_percent
) 
```

### function `bsp_display_get_input_dev`

```c
lv_indev_t * bsp_display_get_input_dev (
    void
) 
```

### function `bsp_display_lock`

```c
bool bsp_display_lock (
    uint32_t timeout_ms
) 
```

### function `bsp_display_rotate`

```c
void bsp_display_rotate (
    lv_disp_t * disp,
    lv_disp_rot_t rotation
) 
```

### function `bsp_display_start`

```c
lv_disp_t * bsp_display_start (
    void
) 
```

### function `bsp_display_unlock`

```c
void bsp_display_unlock (
    void
) 
```

### function `bsp_i2c_deinit`

```c
esp_err_t bsp_i2c_deinit (
    void
) 
```

### function `bsp_i2c_init`

```c
esp_err_t bsp_i2c_init (
    void
) 
```

### function `bsp_spiffs_mount`

```c
esp_err_t bsp_spiffs_mount (
    void
) 
```

### function `bsp_spiffs_unmount`

```c
esp_err_t bsp_spiffs_unmount (
    void
) 
```


## File esp-box/include/bsp/touch.h

## Classes

| Type | Name |
| ---: | :--- |
| struct | [**bsp\_touch\_config\_t**](#struct-bsp_touch_config_t) <br>_BSP touch configuration structure._ |



## Functions

| Type | Name |
| ---: | :--- |
|  esp\_err\_t | [**bsp\_touch\_new**](#function-bsp_touch_new) (const [**bsp\_touch\_config\_t**](#struct-bsp_touch_config_t)\* config, [**esp\_lcd\_touch\_handle\_t**](#struct-esp_lcd_touch_s)\* ret\_touch) <br>_Create new touchscreen._ |

## Classes Documentation

### struct `bsp_touch_config_t`

Variables:

-  void \* dummy  <br>



## Functions Documentation

### function `bsp_touch_new`

```c
esp_err_t bsp_touch_new (
    const bsp_touch_config_t * config,
    esp_lcd_touch_handle_t * ret_touch
) 
```


## File esp32_s3_korvo_2/include/bsp/touch.h

## Classes

| Type | Name |
| ---: | :--- |
| struct | [**bsp\_touch\_config\_t**](#struct-bsp_touch_config_t) <br>_BSP touch configuration structure._ |



## Functions

| Type | Name |
| ---: | :--- |
|  esp\_err\_t | [**bsp\_touch\_new**](#function-bsp_touch_new) (const [**bsp\_touch\_config\_t**](#struct-bsp_touch_config_t)\* config, [**esp\_lcd\_touch\_handle\_t**](#struct-esp_lcd_touch_s)\* ret\_touch) <br>_Create new touchscreen._ |

## Classes Documentation

### struct `bsp_touch_config_t`

Variables:

-  void \* dummy  <br>



## Functions Documentation

### function `bsp_touch_new`

```c
esp_err_t bsp_touch_new (
    const bsp_touch_config_t * config,
    esp_lcd_touch_handle_t * ret_touch
) 
```


## File esp32_azure_iot_kit/include/bsp/esp32_azure_iot_kit.h


## Macros

| Type | Name |
| ---: | :--- |
| define  | [**BSP\_BUTTON\_IO**](#define-bsp_button_io)  GPIO\_NUM\_0<br> |
| define  | [**BSP\_BUZZER\_IO**](#define-bsp_buzzer_io)  GPIO\_NUM\_27<br> |
| define  | [**BSP\_I2C\_NUM**](#define-bsp_i2c_num)  CONFIG\_BSP\_I2C\_NUM<br> |
| define  | [**BSP\_I2C\_SCL\_IO**](#define-bsp_i2c_scl_io)  GPIO\_NUM\_26<br> |
| define  | [**BSP\_I2C\_SDA\_IO**](#define-bsp_i2c_sda_io)  GPIO\_NUM\_25<br> |
| define  | [**BSP\_MOUNT\_POINT**](#define-bsp_mount_point)  CONFIG\_BSP\_uSD\_MOUNT\_POINT<br> |

## Types

| Type | Name |
| ---: | :--- |
| enum  | [**bsp\_i2c\_clk\_speed\_t**](#enum-bsp_i2c_clk_speed_t)  <br> |
| enum  | [**bsp\_led\_t**](#enum-bsp_led_t)  <br> |
| typedef enum bsp\_led\_t | [**bsp\_led\_t**](#typedef-bsp_led_t)  <br> |

## Functions

| Type | Name |
| ---: | :--- |
|  bool | [**bsp\_button\_get**](#function-bsp_button_get) (void) <br>_Get button's state._ |
|  esp\_err\_t | [**bsp\_button\_init**](#function-bsp_button_init) (void) <br>_Set button's GPIO as input._ |
|  esp\_err\_t | [**bsp\_buzzer\_init**](#function-bsp_buzzer_init) (void) <br>_Init buzzer._ |
|  esp\_err\_t | [**bsp\_buzzer\_set**](#function-bsp_buzzer_set) (const bool on) <br>_Enable/disable buzzer._ |
|  esp\_err\_t | [**bsp\_i2c\_deinit**](#function-bsp_i2c_deinit) (void) <br>_Deinit I2C driver and free its resources._ |
|  esp\_err\_t | [**bsp\_i2c\_init**](#function-bsp_i2c_init) (void) <br>_Init I2C driver._ |
|  esp\_err\_t | [**bsp\_i2c\_set\_clk\_speed**](#function-bsp_i2c_set_clk_speed) (bsp\_i2c\_clk\_speed\_t i2c\_clk) <br>_Set I2C clk after initialization of the I2C driver._ |
|  esp\_err\_t | [**bsp\_led\_set**](#function-bsp_led_set) (const bsp\_led\_t led\_io, const bool on) <br>_Turn LED on/off._ |
|  esp\_err\_t | [**bsp\_leds\_init**](#function-bsp_leds_init) (void) <br>_Set LED's GPIOs as output push-pull._ |
|  esp\_err\_t | [**bsp\_sdcard\_mount**](#function-bsp_sdcard_mount) (void) <br>_Mount microSD card to virtual file system._ |
|  esp\_err\_t | [**bsp\_sdcard\_unmount**](#function-bsp_sdcard_unmount) (void) <br>_Unmount micorSD card from virtual file system._ |


## Macros Documentation

### define `BSP_BUTTON_IO`

```c
#define BSP_BUTTON_IO GPIO_NUM_0
```

### define `BSP_BUZZER_IO`

```c
#define BSP_BUZZER_IO GPIO_NUM_27
```

### define `BSP_I2C_NUM`

```c
#define BSP_I2C_NUM CONFIG_BSP_I2C_NUM
```

### define `BSP_I2C_SCL_IO`

```c
#define BSP_I2C_SCL_IO GPIO_NUM_26
```

### define `BSP_I2C_SDA_IO`

```c
#define BSP_I2C_SDA_IO GPIO_NUM_25
```

### define `BSP_MOUNT_POINT`

```c
#define BSP_MOUNT_POINT CONFIG_BSP_uSD_MOUNT_POINT
```


## Types Documentation

### enum `bsp_i2c_clk_speed_t`

```c
enum bsp_i2c_clk_speed_t {
    I2C_CLK_100KHZ = 0,
    I2C_CLK_400KHZ = 1,
    I2C_CLK_600KHZ = 2
};
```

### enum `bsp_led_t`

```c
enum bsp_led_t {
    BSP_LED_WIFI = GPIO_NUM_32,
    BSP_LED_AZURE = GPIO_NUM_33
};
```

### typedef `bsp_led_t`

```c
typedef enum bsp_led_t bsp_led_t;
```


## Functions Documentation

### function `bsp_button_get`

```c
bool bsp_button_get (
    void
) 
```

### function `bsp_button_init`

```c
esp_err_t bsp_button_init (
    void
) 
```

### function `bsp_buzzer_init`

```c
esp_err_t bsp_buzzer_init (
    void
) 
```

### function `bsp_buzzer_set`

```c
esp_err_t bsp_buzzer_set (
    const bool on
) 
```

### function `bsp_i2c_deinit`

```c
esp_err_t bsp_i2c_deinit (
    void
) 
```

### function `bsp_i2c_init`

```c
esp_err_t bsp_i2c_init (
    void
) 
```

### function `bsp_i2c_set_clk_speed`

```c
esp_err_t bsp_i2c_set_clk_speed (
    bsp_i2c_clk_speed_t i2c_clk
) 
```

### function `bsp_led_set`

```c
esp_err_t bsp_led_set (
    const bsp_led_t led_io,
    const bool on
) 
```

### function `bsp_leds_init`

```c
esp_err_t bsp_leds_init (
    void
) 
```

### function `bsp_sdcard_mount`

```c
esp_err_t bsp_sdcard_mount (
    void
) 
```

### function `bsp_sdcard_unmount`

```c
esp_err_t bsp_sdcard_unmount (
    void
) 
```


## File esp32_c3_lcdkit/include/bsp/esp32_c3_lcdkit.h


## Macros

| Type | Name |
| ---: | :--- |
| define  | [**BSP\_ENCODER\_A**](#define-bsp_encoder_a)  (GPIO\_NUM\_10)<br> |
| define  | [**BSP\_ENCODER\_B**](#define-bsp_encoder_b)  (GPIO\_NUM\_6)<br> |
| define  | [**BSP\_I2S\_CLK**](#define-bsp_i2s_clk)  (GPIO\_NUM\_NC)<br> |
| define  | [**BSP\_I2S\_DOUT**](#define-bsp_i2s_dout)  (GPIO\_NUM\_3)<br> |
| define  | [**BSP\_LCD\_BACKLIGHT**](#define-bsp_lcd_backlight)  (GPIO\_NUM\_5)<br> |
| define  | [**BSP\_LCD\_CS**](#define-bsp_lcd_cs)  (GPIO\_NUM\_7)<br> |
| define  | [**BSP\_LCD\_DATA0**](#define-bsp_lcd_data0)  (GPIO\_NUM\_0)<br> |
| define  | [**BSP\_LCD\_DC**](#define-bsp_lcd_dc)  (GPIO\_NUM\_2)<br> |
| define  | [**BSP\_LCD\_H\_RES**](#define-bsp_lcd_h_res)  (240)<br> |
| define  | [**BSP\_LCD\_PCLK**](#define-bsp_lcd_pclk)  (GPIO\_NUM\_1)<br> |
| define  | [**BSP\_LCD\_PIXEL\_CLOCK\_HZ**](#define-bsp_lcd_pixel_clock_hz)  (80 \* 1000 \* 1000)<br> |
| define  | [**BSP\_LCD\_RST**](#define-bsp_lcd_rst)  (GPIO\_NUM\_NC)<br> |
| define  | [**BSP\_LCD\_SPI\_NUM**](#define-bsp_lcd_spi_num)  (SPI2\_HOST)<br> |
| define  | [**BSP\_LCD\_V\_RES**](#define-bsp_lcd_v_res)  (240)<br> |
| define  | [**BSP\_RGB\_CTRL**](#define-bsp_rgb_ctrl)  (GPIO\_NUM\_8)<br> |
| define  | [**BSP\_SPIFFS\_MOUNT\_POINT**](#define-bsp_spiffs_mount_point)  CONFIG\_BSP\_SPIFFS\_MOUNT\_POINT<br> |
| define  | [**BSP\_USB\_NEG**](#define-bsp_usb_neg)  USBPHY\_DM\_NUM<br> |
| define  | [**BSP\_USB\_POS**](#define-bsp_usb_pos)  USBPHY\_DP\_NUM<br> |

## Types

| Type | Name |
| ---: | :--- |
| enum  | [**bsp\_button\_t**](#enum-bsp_button_t)  <br> |

## Functions

| Type | Name |
| ---: | :--- |
|  esp\_codec\_dev\_handle\_t | [**bsp\_audio\_codec\_speaker\_init**](#function-bsp_audio_codec_speaker_init) (void) <br>_Initialize speaker codec device._ |
|  esp\_err\_t | [**bsp\_audio\_init**](#function-bsp_audio_init) (const i2s\_pdm\_tx\_config\_t \* i2s\_config, i2s\_chan\_handle\_t \* tx\_channel) <br>_Init audio._ |
|  esp\_err\_t | [**bsp\_display\_backlight\_off**](#function-bsp_display_backlight_off) (void) <br>_Turn off display backlight._ |
|  esp\_err\_t | [**bsp\_display\_backlight\_on**](#function-bsp_display_backlight_on) (void) <br>_Turn on display backlight._ |
|  esp\_err\_t | [**bsp\_display\_brightness\_set**](#function-bsp_display_brightness_set) (int brightness\_percent) <br>_Set display's brightness._ |
|  lv\_indev\_t \* | [**bsp\_display\_get\_input\_dev**](#function-bsp_display_get_input_dev) (void) <br>_Get pointer to input device (touch, buttons, ...)_ |
|  bool | [**bsp\_display\_lock**](#function-bsp_display_lock) (uint32\_t timeout\_ms) <br>_Take LVGL mutex._ |
|  void | [**bsp\_display\_rotate**](#function-bsp_display_rotate) (lv\_disp\_t \* disp, lv\_disp\_rot\_t rotation) <br>_Rotate screen._ |
|  lv\_disp\_t \* | [**bsp\_display\_start**](#function-bsp_display_start) (void) <br>_Initialize display._ |
|  void | [**bsp\_display\_unlock**](#function-bsp_display_unlock) (void) <br>_Give LVGL mutex._ |
|  esp\_err\_t | [**bsp\_led\_init**](#function-bsp_led_init) () <br>_Initialize WS2812._ |
|  esp\_err\_t | [**bsp\_led\_rgb\_set**](#function-bsp_led_rgb_set) (uint8\_t r, uint8\_t g, uint8\_t b) <br>_Set RGB for a specific pixel._ |
|  esp\_err\_t | [**bsp\_spiffs\_mount**](#function-bsp_spiffs_mount) (void) <br>_Mount SPIFFS to virtual file system._ |
|  esp\_err\_t | [**bsp\_spiffs\_unmount**](#function-bsp_spiffs_unmount) (void) <br>_Unmount SPIFFS from virtual file system._ |


## Macros Documentation

### define `BSP_ENCODER_A`

```c
#define BSP_ENCODER_A (GPIO_NUM_10)
```

### define `BSP_ENCODER_B`

```c
#define BSP_ENCODER_B (GPIO_NUM_6)
```

### define `BSP_I2S_CLK`

```c
#define BSP_I2S_CLK (GPIO_NUM_NC)
```

### define `BSP_I2S_DOUT`

```c
#define BSP_I2S_DOUT (GPIO_NUM_3)
```

### define `BSP_LCD_BACKLIGHT`

```c
#define BSP_LCD_BACKLIGHT (GPIO_NUM_5)
```

### define `BSP_LCD_CS`

```c
#define BSP_LCD_CS (GPIO_NUM_7)
```

### define `BSP_LCD_DATA0`

```c
#define BSP_LCD_DATA0 (GPIO_NUM_0)
```

### define `BSP_LCD_DC`

```c
#define BSP_LCD_DC (GPIO_NUM_2)
```

### define `BSP_LCD_H_RES`

```c
#define BSP_LCD_H_RES (240)
```

### define `BSP_LCD_PCLK`

```c
#define BSP_LCD_PCLK (GPIO_NUM_1)
```

### define `BSP_LCD_PIXEL_CLOCK_HZ`

```c
#define BSP_LCD_PIXEL_CLOCK_HZ (80 * 1000 * 1000)
```

### define `BSP_LCD_RST`

```c
#define BSP_LCD_RST (GPIO_NUM_NC)
```

### define `BSP_LCD_SPI_NUM`

```c
#define BSP_LCD_SPI_NUM (SPI2_HOST)
```

### define `BSP_LCD_V_RES`

```c
#define BSP_LCD_V_RES (240)
```

### define `BSP_RGB_CTRL`

```c
#define BSP_RGB_CTRL (GPIO_NUM_8)
```

### define `BSP_SPIFFS_MOUNT_POINT`

```c
#define BSP_SPIFFS_MOUNT_POINT CONFIG_BSP_SPIFFS_MOUNT_POINT
```

### define `BSP_USB_NEG`

```c
#define BSP_USB_NEG USBPHY_DM_NUM
```

### define `BSP_USB_POS`

```c
#define BSP_USB_POS USBPHY_DP_NUM
```


## Types Documentation

### enum `bsp_button_t`

```c
enum bsp_button_t {
    BSP_BTN_PRESS = GPIO_NUM_9
};
```


## Functions Documentation

### function `bsp_audio_codec_speaker_init`

```c
esp_codec_dev_handle_t bsp_audio_codec_speaker_init (
    void
) 
```

### function `bsp_audio_init`

```c
esp_err_t bsp_audio_init (
    const i2s_pdm_tx_config_t * i2s_config,
    i2s_chan_handle_t * tx_channel
) 
```

### function `bsp_display_backlight_off`

```c
esp_err_t bsp_display_backlight_off (
    void
) 
```

### function `bsp_display_backlight_on`

```c
esp_err_t bsp_display_backlight_on (
    void
) 
```

### function `bsp_display_brightness_set`

```c
esp_err_t bsp_display_brightness_set (
    int brightness_percent
) 
```

### function `bsp_display_get_input_dev`

```c
lv_indev_t * bsp_display_get_input_dev (
    void
) 
```

### function `bsp_display_lock`

```c
bool bsp_display_lock (
    uint32_t timeout_ms
) 
```

### function `bsp_display_rotate`

```c
void bsp_display_rotate (
    lv_disp_t * disp,
    lv_disp_rot_t rotation
) 
```

### function `bsp_display_start`

```c
lv_disp_t * bsp_display_start (
    void
) 
```

### function `bsp_display_unlock`

```c
void bsp_display_unlock (
    void
) 
```

### function `bsp_led_init`

```c
esp_err_t bsp_led_init () 
```

### function `bsp_led_rgb_set`

```c
esp_err_t bsp_led_rgb_set (
    uint8_t r,
    uint8_t g,
    uint8_t b
) 
```

### function `bsp_spiffs_mount`

```c
esp_err_t bsp_spiffs_mount (
    void
) 
```

### function `bsp_spiffs_unmount`

```c
esp_err_t bsp_spiffs_unmount (
    void
) 
```


## File esp32_lyrat/include/bsp/esp32_lyrat.h


## Macros

| Type | Name |
| ---: | :--- |
| define  | [**BSP\_BUTTON\_MODE\_IO**](#define-bsp_button_mode_io)  (GPIO\_NUM\_39)<br> |
| define  | [**BSP\_BUTTON\_PLAY\_TOUCH**](#define-bsp_button_play_touch)  (TOUCH\_PAD\_NUM8)<br> |
| define  | [**BSP\_BUTTON\_REC\_IO**](#define-bsp_button_rec_io)  (GPIO\_NUM\_36)<br> |
| define  | [**BSP\_BUTTON\_SET\_TOUCH**](#define-bsp_button_set_touch)  (TOUCH\_PAD\_NUM9)<br> |
| define  | [**BSP\_BUTTON\_VOLDOWN\_TOUCH**](#define-bsp_button_voldown_touch)  (TOUCH\_PAD\_NUM4)<br> |
| define  | [**BSP\_BUTTON\_VOLUP\_TOUCH**](#define-bsp_button_volup_touch)  (TOUCH\_PAD\_NUM7)<br> |
| define  | [**BSP\_I2C\_NUM**](#define-bsp_i2c_num)  CONFIG\_BSP\_I2C\_NUM<br> |
| define  | [**BSP\_I2C\_SCL**](#define-bsp_i2c_scl)  (GPIO\_NUM\_23)<br> |
| define  | [**BSP\_I2C\_SDA**](#define-bsp_i2c_sda)  (GPIO\_NUM\_18)<br> |
| define  | [**BSP\_I2S\_DOUT**](#define-bsp_i2s_dout)  (GPIO\_NUM\_26)<br> |
| define  | [**BSP\_I2S\_DSIN**](#define-bsp_i2s_dsin)  (GPIO\_NUM\_35)<br> |
| define  | [**BSP\_I2S\_LCLK**](#define-bsp_i2s_lclk)  (GPIO\_NUM\_25)<br> |
| define  | [**BSP\_I2S\_MCLK**](#define-bsp_i2s_mclk)  (GPIO\_NUM\_0)<br> |
| define  | [**BSP\_I2S\_SCLK**](#define-bsp_i2s_sclk)  (GPIO\_NUM\_5)<br> |
| define  | [**BSP\_POWER\_AMP\_IO**](#define-bsp_power_amp_io)  (GPIO\_NUM\_21)<br> |
| define  | [**BSP\_SD\_CLK**](#define-bsp_sd_clk)  (GPIO\_NUM\_14)<br> |
| define  | [**BSP\_SD\_CMD**](#define-bsp_sd_cmd)  (GPIO\_NUM\_15)<br> |
| define  | [**BSP\_SD\_D0**](#define-bsp_sd_d0)  (GPIO\_NUM\_2)<br> |
| define  | [**BSP\_SD\_D1**](#define-bsp_sd_d1)  (GPIO\_NUM\_4)<br> |
| define  | [**BSP\_SD\_D2**](#define-bsp_sd_d2)  (GPIO\_NUM\_12)<br> |
| define  | [**BSP\_SD\_D3**](#define-bsp_sd_d3)  (GPIO\_NUM\_13)<br> |
| define  | [**BSP\_SD\_MOUNT\_POINT**](#define-bsp_sd_mount_point)  CONFIG\_BSP\_SD\_MOUNT\_POINT<br> |
| define  | [**BSP\_SPIFFS\_MOUNT\_POINT**](#define-bsp_spiffs_mount_point)  CONFIG\_BSP\_SPIFFS\_MOUNT\_POINT<br> |

## Types

| Type | Name |
| ---: | :--- |
| enum  | [**bsp\_button\_t**](#enum-bsp_button_t)  <br> |
| enum  | [**bsp\_led\_t**](#enum-bsp_led_t)  <br> |
| typedef enum bsp\_led\_t | [**bsp\_led\_t**](#typedef-bsp_led_t)  <br> |

## Functions

| Type | Name |
| ---: | :--- |
|  esp\_codec\_dev\_handle\_t | [**bsp\_audio\_codec\_microphone\_init**](#function-bsp_audio_codec_microphone_init) (void) <br>_Initialize microphone codec device._ |
|  esp\_codec\_dev\_handle\_t | [**bsp\_audio\_codec\_speaker\_init**](#function-bsp_audio_codec_speaker_init) (void) <br>_Initialize speaker codec device._ |
|  const audio\_codec\_data\_if\_t \* | [**bsp\_audio\_get\_codec\_itf**](#function-bsp_audio_get_codec_itf) (void) <br>_Get codec I2S interface (initialized in bsp\_audio\_init)_ |
|  esp\_err\_t | [**bsp\_audio\_init**](#function-bsp_audio_init) (const i2s\_std\_config\_t \* i2s\_config) <br>_Init audio._ |
|  esp\_err\_t | [**bsp\_i2c\_deinit**](#function-bsp_i2c_deinit) (void) <br>_Deinit I2C driver and free its resources._ |
|  esp\_err\_t | [**bsp\_i2c\_init**](#function-bsp_i2c_init) (void) <br>_Init I2C driver._ |
|  esp\_err\_t | [**bsp\_iot\_button\_create**](#function-bsp_iot_button_create) (button\_handle\_t btn\_array, int \* btn\_cnt, int btn\_array\_size) <br>_Initialize all buttons._ |
|  esp\_err\_t | [**bsp\_led\_set**](#function-bsp_led_set) (const bsp\_led\_t led\_io, const bool on) <br>_Turn LED on/off._ |
|  esp\_err\_t | [**bsp\_leds\_init**](#function-bsp_leds_init) (void) <br>_Set LED's GPIOs as output push-pull._ |
|  esp\_err\_t | [**bsp\_sdcard\_mount**](#function-bsp_sdcard_mount) (void) <br>_Mount microSD card to virtual file system._ |
|  esp\_err\_t | [**bsp\_sdcard\_unmount**](#function-bsp_sdcard_unmount) (void) <br>_Unmount microSD card from virtual file system._ |
|  esp\_err\_t | [**bsp\_spiffs\_mount**](#function-bsp_spiffs_mount) (void) <br>_Mount SPIFFS to virtual file system._ |
|  esp\_err\_t | [**bsp\_spiffs\_unmount**](#function-bsp_spiffs_unmount) (void) <br>_Unmount SPIFFS from virtual file system._ |


## Macros Documentation

### define `BSP_BUTTON_MODE_IO`

```c
#define BSP_BUTTON_MODE_IO (GPIO_NUM_39)
```

### define `BSP_BUTTON_PLAY_TOUCH`

```c
#define BSP_BUTTON_PLAY_TOUCH (TOUCH_PAD_NUM8)
```

### define `BSP_BUTTON_REC_IO`

```c
#define BSP_BUTTON_REC_IO (GPIO_NUM_36)
```

### define `BSP_BUTTON_SET_TOUCH`

```c
#define BSP_BUTTON_SET_TOUCH (TOUCH_PAD_NUM9)
```

### define `BSP_BUTTON_VOLDOWN_TOUCH`

```c
#define BSP_BUTTON_VOLDOWN_TOUCH (TOUCH_PAD_NUM4)
```

### define `BSP_BUTTON_VOLUP_TOUCH`

```c
#define BSP_BUTTON_VOLUP_TOUCH (TOUCH_PAD_NUM7)
```

### define `BSP_I2C_NUM`

```c
#define BSP_I2C_NUM CONFIG_BSP_I2C_NUM
```

### define `BSP_I2C_SCL`

```c
#define BSP_I2C_SCL (GPIO_NUM_23)
```

### define `BSP_I2C_SDA`

```c
#define BSP_I2C_SDA (GPIO_NUM_18)
```

### define `BSP_I2S_DOUT`

```c
#define BSP_I2S_DOUT (GPIO_NUM_26)
```

### define `BSP_I2S_DSIN`

```c
#define BSP_I2S_DSIN (GPIO_NUM_35)
```

### define `BSP_I2S_LCLK`

```c
#define BSP_I2S_LCLK (GPIO_NUM_25)
```

### define `BSP_I2S_MCLK`

```c
#define BSP_I2S_MCLK (GPIO_NUM_0)
```

### define `BSP_I2S_SCLK`

```c
#define BSP_I2S_SCLK (GPIO_NUM_5)
```

### define `BSP_POWER_AMP_IO`

```c
#define BSP_POWER_AMP_IO (GPIO_NUM_21)
```

### define `BSP_SD_CLK`

```c
#define BSP_SD_CLK (GPIO_NUM_14)
```

### define `BSP_SD_CMD`

```c
#define BSP_SD_CMD (GPIO_NUM_15)
```

### define `BSP_SD_D0`

```c
#define BSP_SD_D0 (GPIO_NUM_2)
```

### define `BSP_SD_D1`

```c
#define BSP_SD_D1 (GPIO_NUM_4)
```

### define `BSP_SD_D2`

```c
#define BSP_SD_D2 (GPIO_NUM_12)
```

### define `BSP_SD_D3`

```c
#define BSP_SD_D3 (GPIO_NUM_13)
```

### define `BSP_SD_MOUNT_POINT`

```c
#define BSP_SD_MOUNT_POINT CONFIG_BSP_SD_MOUNT_POINT
```

### define `BSP_SPIFFS_MOUNT_POINT`

```c
#define BSP_SPIFFS_MOUNT_POINT CONFIG_BSP_SPIFFS_MOUNT_POINT
```


## Types Documentation

### enum `bsp_button_t`

```c
enum bsp_button_t {
    BSP_BUTTON_REC = 0,
    BSP_BUTTON_MODE,
    BSP_BUTTON_PLAY,
    BSP_BUTTON_SET,
    BSP_BUTTON_VOLUP,
    BSP_BUTTON_VOLDOWN,
    BSP_BUTTON_NUM
};
```

### enum `bsp_led_t`

```c
enum bsp_led_t {
    BSP_LED_GREEN = GPIO_NUM_22
};
```

### typedef `bsp_led_t`

```c
typedef enum bsp_led_t bsp_led_t;
```


## Functions Documentation

### function `bsp_audio_codec_microphone_init`

```c
esp_codec_dev_handle_t bsp_audio_codec_microphone_init (
    void
) 
```

### function `bsp_audio_codec_speaker_init`

```c
esp_codec_dev_handle_t bsp_audio_codec_speaker_init (
    void
) 
```

### function `bsp_audio_get_codec_itf`

```c
const audio_codec_data_if_t * bsp_audio_get_codec_itf (
    void
) 
```

### function `bsp_audio_init`

```c
esp_err_t bsp_audio_init (
    const i2s_std_config_t * i2s_config
) 
```

### function `bsp_i2c_deinit`

```c
esp_err_t bsp_i2c_deinit (
    void
) 
```

### function `bsp_i2c_init`

```c
esp_err_t bsp_i2c_init (
    void
) 
```

### function `bsp_iot_button_create`

```c
esp_err_t bsp_iot_button_create (
    button_handle_t btn_array,
    int * btn_cnt,
    int btn_array_size
) 
```

### function `bsp_led_set`

```c
esp_err_t bsp_led_set (
    const bsp_led_t led_io,
    const bool on
) 
```

### function `bsp_leds_init`

```c
esp_err_t bsp_leds_init (
    void
) 
```

### function `bsp_sdcard_mount`

```c
esp_err_t bsp_sdcard_mount (
    void
) 
```

### function `bsp_sdcard_unmount`

```c
esp_err_t bsp_sdcard_unmount (
    void
) 
```

### function `bsp_spiffs_mount`

```c
esp_err_t bsp_spiffs_mount (
    void
) 
```

### function `bsp_spiffs_unmount`

```c
esp_err_t bsp_spiffs_unmount (
    void
) 
```


## File esp32_s2_kaluga_kit/include/bsp/esp32_s2_kaluga_kit.h


## Macros

| Type | Name |
| ---: | :--- |
| define  | [**BSP\_BUTTONS\_IO**](#define-bsp_buttons_io)  (GPIO\_NUM\_6)<br> |
| define  | [**BSP\_CAMERA\_D0**](#define-bsp_camera_d0)  (GPIO\_NUM\_36)<br> |
| define  | [**BSP\_CAMERA\_D1**](#define-bsp_camera_d1)  (GPIO\_NUM\_37)<br> |
| define  | [**BSP\_CAMERA\_D2**](#define-bsp_camera_d2)  (GPIO\_NUM\_41)<br> |
| define  | [**BSP\_CAMERA\_D3**](#define-bsp_camera_d3)  (GPIO\_NUM\_42)<br> |
| define  | [**BSP\_CAMERA\_D4**](#define-bsp_camera_d4)  (GPIO\_NUM\_39)<br> |
| define  | [**BSP\_CAMERA\_D5**](#define-bsp_camera_d5)  (GPIO\_NUM\_40)<br> |
| define  | [**BSP\_CAMERA\_D6**](#define-bsp_camera_d6)  (GPIO\_NUM\_21)<br> |
| define  | [**BSP\_CAMERA\_D7**](#define-bsp_camera_d7)  (GPIO\_NUM\_38)<br> |
| define  | [**BSP\_CAMERA\_DEFAULT\_CONFIG**](#define-bsp_camera_default_config)  <br>_Kaluga camera default configuration._ |
| define  | [**BSP\_CAMERA\_HSYNC**](#define-bsp_camera_hsync)  (GPIO\_NUM\_3)<br> |
| define  | [**BSP\_CAMERA\_PCLK**](#define-bsp_camera_pclk)  (GPIO\_NUM\_33)<br> |
| define  | [**BSP\_CAMERA\_VSYNC**](#define-bsp_camera_vsync)  (GPIO\_NUM\_2)<br> |
| define  | [**BSP\_CAMERA\_XCLK**](#define-bsp_camera_xclk)  (GPIO\_NUM\_1)<br> |
| define  | [**BSP\_ES8311\_SCLK\_CONFIG**](#define-bsp_es8311_sclk_config) (\_sample\_rate) <br>_ES8311 init structure._ |
| define  | [**BSP\_I2C\_NUM**](#define-bsp_i2c_num)  CONFIG\_BSP\_I2C\_NUM<br> |
| define  | [**BSP\_I2C\_SCL**](#define-bsp_i2c_scl)  (GPIO\_NUM\_7)<br> |
| define  | [**BSP\_I2C\_SDA**](#define-bsp_i2c_sda)  (GPIO\_NUM\_8)<br> |
| define  | [**BSP\_I2S\_DOUT**](#define-bsp_i2s_dout)  (GPIO\_NUM\_12)<br> |
| define  | [**BSP\_I2S\_DSIN**](#define-bsp_i2s_dsin)  (GPIO\_NUM\_34)<br> |
| define  | [**BSP\_I2S\_DUPLEX\_MONO\_CFG**](#define-bsp_i2s_duplex_mono_cfg) (\_sample\_rate) <br>_Mono Duplex I2S configuration structure._ |
| define  | [**BSP\_I2S\_GPIO\_CFG**](#define-bsp_i2s_gpio_cfg)  <br>_Kaluga-kit I2S pinout._ |
| define  | [**BSP\_I2S\_LCLK**](#define-bsp_i2s_lclk)  (GPIO\_NUM\_17)<br> |
| define  | [**BSP\_I2S\_MCLK**](#define-bsp_i2s_mclk)  (GPIO\_NUM\_35)<br> |
| define  | [**BSP\_I2S\_SCLK**](#define-bsp_i2s_sclk)  (GPIO\_NUM\_18)<br> |
| define  | [**BSP\_LCD\_DC**](#define-bsp_lcd_dc)  (GPIO\_NUM\_13)<br> |
| define  | [**BSP\_LCD\_DRAW\_BUFF\_DOUBLE**](#define-bsp_lcd_draw_buff_double)  (0)<br> |
| define  | [**BSP\_LCD\_DRAW\_BUFF\_SIZE**](#define-bsp_lcd_draw_buff_size)  (BSP\_LCD\_H\_RES \* BSP\_LCD\_V\_RES)<br> |
| define  | [**BSP\_LCD\_H\_RES**](#define-bsp_lcd_h_res)  (320)<br> |
| define  | [**BSP\_LCD\_PIXEL\_CLOCK\_HZ**](#define-bsp_lcd_pixel_clock_hz)  (40 \* 1000 \* 1000)<br> |
| define  | [**BSP\_LCD\_RST**](#define-bsp_lcd_rst)  (GPIO\_NUM\_16)<br> |
| define  | [**BSP\_LCD\_SPI\_CLK**](#define-bsp_lcd_spi_clk)  (GPIO\_NUM\_15)<br> |
| define  | [**BSP\_LCD\_SPI\_CS**](#define-bsp_lcd_spi_cs)  (GPIO\_NUM\_11)<br> |
| define  | [**BSP\_LCD\_SPI\_MOSI**](#define-bsp_lcd_spi_mosi)  (GPIO\_NUM\_9)<br> |
| define  | [**BSP\_LCD\_SPI\_NUM**](#define-bsp_lcd_spi_num)  (SPI3\_HOST)<br> |
| define  | [**BSP\_LCD\_V\_RES**](#define-bsp_lcd_v_res)  (240)<br> |
| define  | [**BSP\_LEDSTRIP\_IO**](#define-bsp_ledstrip_io)  (GPIO\_NUM\_45)<br> |
| define  | [**BSP\_POWER\_AMP\_IO**](#define-bsp_power_amp_io)  (GPIO\_NUM\_10)<br> |
| define  | [**BSP\_TOUCH\_BUTTON\_GUARD**](#define-bsp_touch_button_guard)  (GPIO\_NUM\_4)<br> |
| define  | [**BSP\_TOUCH\_BUTTON\_NETWORK**](#define-bsp_touch_button_network)  (GPIO\_NUM\_11)<br> |
| define  | [**BSP\_TOUCH\_BUTTON\_PHOTO**](#define-bsp_touch_button_photo)  (GPIO\_NUM\_6)<br> |
| define  | [**BSP\_TOUCH\_BUTTON\_PLAY**](#define-bsp_touch_button_play)  (GPIO\_NUM\_2)<br> |
| define  | [**BSP\_TOUCH\_BUTTON\_RECORD**](#define-bsp_touch_button_record)  (GPIO\_NUM\_5)<br> |
| define  | [**BSP\_TOUCH\_BUTTON\_VOLDOWN**](#define-bsp_touch_button_voldown)  (GPIO\_NUM\_3)<br> |
| define  | [**BSP\_TOUCH\_BUTTON\_VOLUP**](#define-bsp_touch_button_volup)  (GPIO\_NUM\_1)<br> |
| define  | [**BSP\_TOUCH\_SHELED\_ELECT**](#define-bsp_touch_sheled_elect)  (GPIO\_NUM\_14)<br> |

## Types

| Type | Name |
| ---: | :--- |
| enum  | [**bsp\_button\_t**](#enum-bsp_button_t)  <br> |
| enum  | [**bsp\_touchpad\_button\_t**](#enum-bsp_touchpad_button_t)  <br> |

## Functions

| Type | Name |
| ---: | :--- |
|  esp\_err\_t | [**bsp\_audio\_init**](#function-bsp_audio_init) (const i2s\_std\_config\_t \* i2s\_config, i2s\_chan\_handle\_t \* tx\_channel, i2s\_chan\_handle\_t \* rx\_channel) <br>_Init audio._ |
|  esp\_err\_t | [**bsp\_audio\_poweramp\_enable**](#function-bsp_audio_poweramp_enable) (bool enable) <br>_Enable/disable audio power amplifier._ |
|  esp\_err\_t | [**bsp\_display\_backlight\_off**](#function-bsp_display_backlight_off) (void) <br>_Turn off display backlight._ |
|  esp\_err\_t | [**bsp\_display\_backlight\_on**](#function-bsp_display_backlight_on) (void) <br>_Turn on display backlight._ |
|  lv\_indev\_t \* | [**bsp\_display\_get\_input\_dev**](#function-bsp_display_get_input_dev) (void) <br>_Get pointer to input device (touch, buttons, ...)_ |
|  bool | [**bsp\_display\_lock**](#function-bsp_display_lock) (uint32\_t timeout\_ms) <br>_Take LVGL mutex._ |
|  void | [**bsp\_display\_rotate**](#function-bsp_display_rotate) (lv\_disp\_t \* disp, lv\_disp\_rot\_t rotation) <br>_Rotate screen._ |
|  lv\_disp\_t \* | [**bsp\_display\_start**](#function-bsp_display_start) (void) <br>_Initialize display and graphics library._ |
|  void | [**bsp\_display\_unlock**](#function-bsp_display_unlock) (void) <br>_Give LVGL mutex._ |
|  esp\_err\_t | [**bsp\_i2c\_deinit**](#function-bsp_i2c_deinit) (void) <br>_Deinit I2C driver and free its resources._ |
|  esp\_err\_t | [**bsp\_i2c\_init**](#function-bsp_i2c_init) (void) <br>_Init I2C driver._ |
|  esp\_err\_t | [**bsp\_touchpad\_calibrate**](#function-bsp_touchpad_calibrate) (bsp\_touchpad\_button\_t tch\_pad, float tch\_threshold) <br>_Calibrate touch threshold._ |
|  esp\_err\_t | [**bsp\_touchpad\_deinit**](#function-bsp_touchpad_deinit) (void) <br>_Deinit buttons on Touchpad board._ |
|  esp\_err\_t | [**bsp\_touchpad\_init**](#function-bsp_touchpad_init) (intr\_handler\_t fn) <br>_Init buttons on Touchpad board._ |


## Macros Documentation

### define `BSP_BUTTONS_IO`

```c
#define BSP_BUTTONS_IO (GPIO_NUM_6)
```

### define `BSP_CAMERA_D0`

```c
#define BSP_CAMERA_D0 (GPIO_NUM_36)
```

### define `BSP_CAMERA_D1`

```c
#define BSP_CAMERA_D1 (GPIO_NUM_37)
```

### define `BSP_CAMERA_D2`

```c
#define BSP_CAMERA_D2 (GPIO_NUM_41)
```

### define `BSP_CAMERA_D3`

```c
#define BSP_CAMERA_D3 (GPIO_NUM_42)
```

### define `BSP_CAMERA_D4`

```c
#define BSP_CAMERA_D4 (GPIO_NUM_39)
```

### define `BSP_CAMERA_D5`

```c
#define BSP_CAMERA_D5 (GPIO_NUM_40)
```

### define `BSP_CAMERA_D6`

```c
#define BSP_CAMERA_D6 (GPIO_NUM_21)
```

### define `BSP_CAMERA_D7`

```c
#define BSP_CAMERA_D7 (GPIO_NUM_38)
```

### define `BSP_CAMERA_DEFAULT_CONFIG`

```c
#define BSP_CAMERA_DEFAULT_CONFIG {                                     \
        .pin_pwdn = GPIO_NUM_NC,          \
        .pin_reset = GPIO_NUM_NC,         \
        .pin_xclk = BSP_CAMERA_XCLK,      \
        .pin_sccb_sda = GPIO_NUM_NC,      \
        .pin_sccb_scl = GPIO_NUM_NC,      \
        .pin_d7 = BSP_CAMERA_D7 ,          \
        .pin_d6 = BSP_CAMERA_D6 ,          \
        .pin_d5 = BSP_CAMERA_D5 ,          \
        .pin_d4 = BSP_CAMERA_D4 ,          \
        .pin_d3 = BSP_CAMERA_D3 ,          \
        .pin_d2 = BSP_CAMERA_D2 ,          \
        .pin_d1 = BSP_CAMERA_D1 ,          \
        .pin_d0 = BSP_CAMERA_D0 ,          \
        .pin_vsync = BSP_CAMERA_VSYNC,    \
        .pin_href = BSP_CAMERA_HSYNC,     \
        .pin_pclk = BSP_CAMERA_PCLK,      \
        .xclk_freq_hz = 16000000,         \
        .ledc_timer = LEDC_TIMER_0,       \
        .ledc_channel = LEDC_CHANNEL_0,   \
        .pixel_format = PIXFORMAT_RGB565, \
        .frame_size = FRAMESIZE_QVGA,     \
        .jpeg_quality = 12,               \
        .fb_count = 2,                    \
        .fb_location = CAMERA_FB_IN_PSRAM,\
        .sccb_i2c_port = BSP_I2C_NUM,     \
    }
```

### define `BSP_CAMERA_HSYNC`

```c
#define BSP_CAMERA_HSYNC (GPIO_NUM_3)
```

### define `BSP_CAMERA_PCLK`

```c
#define BSP_CAMERA_PCLK (GPIO_NUM_33)
```

### define `BSP_CAMERA_VSYNC`

```c
#define BSP_CAMERA_VSYNC (GPIO_NUM_2)
```

### define `BSP_CAMERA_XCLK`

```c
#define BSP_CAMERA_XCLK (GPIO_NUM_1)
```

### define `BSP_ES8311_SCLK_CONFIG`

```c
#define BSP_ES8311_SCLK_CONFIG (
    _sample_rate
) {                                        \
        .mclk_from_mclk_pin = false,         \
        .mclk_inverted = false,              \
        .sclk_inverted = false,              \
        .sample_frequency = _sample_rate     \
    }
```

### define `BSP_I2C_NUM`

```c
#define BSP_I2C_NUM CONFIG_BSP_I2C_NUM
```

### define `BSP_I2C_SCL`

```c
#define BSP_I2C_SCL (GPIO_NUM_7)
```

### define `BSP_I2C_SDA`

```c
#define BSP_I2C_SDA (GPIO_NUM_8)
```

### define `BSP_I2S_DOUT`

```c
#define BSP_I2S_DOUT (GPIO_NUM_12)
```

### define `BSP_I2S_DSIN`

```c
#define BSP_I2S_DSIN (GPIO_NUM_34)
```

### define `BSP_I2S_DUPLEX_MONO_CFG`

```c
#define BSP_I2S_DUPLEX_MONO_CFG (
    _sample_rate
) {                                                                                                 \
        .clk_cfg = I2S_STD_CLK_DEFAULT_CONFIG(_sample_rate),                                          \
        .slot_cfg = I2S_STD_PHILIP_SLOT_DEFAULT_CONFIG(I2S_DATA_BIT_WIDTH_16BIT, I2S_SLOT_MODE_MONO), \
        .gpio_cfg = BSP_I2S_GPIO_CFG ,                                                                 \
    }
```

### define `BSP_I2S_GPIO_CFG`

```c
#define BSP_I2S_GPIO_CFG {                          \
        .mclk = BSP_I2S_MCLK,  \
        .bclk = BSP_I2S_SCLK,  \
        .ws = BSP_I2S_LCLK,    \
        .dout = BSP_I2S_DOUT,  \
        .din = BSP_I2S_DSIN,   \
        .invert_flags = {      \
            .mclk_inv = false, \
            .bclk_inv = false, \
            .ws_inv = false,   \
        },                     \
    }
```

### define `BSP_I2S_LCLK`

```c
#define BSP_I2S_LCLK (GPIO_NUM_17)
```

### define `BSP_I2S_MCLK`

```c
#define BSP_I2S_MCLK (GPIO_NUM_35)
```

### define `BSP_I2S_SCLK`

```c
#define BSP_I2S_SCLK (GPIO_NUM_18)
```

### define `BSP_LCD_DC`

```c
#define BSP_LCD_DC (GPIO_NUM_13)
```

### define `BSP_LCD_DRAW_BUFF_DOUBLE`

```c
#define BSP_LCD_DRAW_BUFF_DOUBLE (0)
```

### define `BSP_LCD_DRAW_BUFF_SIZE`

```c
#define BSP_LCD_DRAW_BUFF_SIZE (BSP_LCD_H_RES * BSP_LCD_V_RES)
```

### define `BSP_LCD_H_RES`

```c
#define BSP_LCD_H_RES (320)
```

### define `BSP_LCD_PIXEL_CLOCK_HZ`

```c
#define BSP_LCD_PIXEL_CLOCK_HZ (40 * 1000 * 1000)
```

### define `BSP_LCD_RST`

```c
#define BSP_LCD_RST (GPIO_NUM_16)
```

### define `BSP_LCD_SPI_CLK`

```c
#define BSP_LCD_SPI_CLK (GPIO_NUM_15)
```

### define `BSP_LCD_SPI_CS`

```c
#define BSP_LCD_SPI_CS (GPIO_NUM_11)
```

### define `BSP_LCD_SPI_MOSI`

```c
#define BSP_LCD_SPI_MOSI (GPIO_NUM_9)
```

### define `BSP_LCD_SPI_NUM`

```c
#define BSP_LCD_SPI_NUM (SPI3_HOST)
```

### define `BSP_LCD_V_RES`

```c
#define BSP_LCD_V_RES (240)
```

### define `BSP_LEDSTRIP_IO`

```c
#define BSP_LEDSTRIP_IO (GPIO_NUM_45)
```

### define `BSP_POWER_AMP_IO`

```c
#define BSP_POWER_AMP_IO (GPIO_NUM_10)
```

### define `BSP_TOUCH_BUTTON_GUARD`

```c
#define BSP_TOUCH_BUTTON_GUARD (GPIO_NUM_4)
```

### define `BSP_TOUCH_BUTTON_NETWORK`

```c
#define BSP_TOUCH_BUTTON_NETWORK (GPIO_NUM_11)
```

### define `BSP_TOUCH_BUTTON_PHOTO`

```c
#define BSP_TOUCH_BUTTON_PHOTO (GPIO_NUM_6)
```

### define `BSP_TOUCH_BUTTON_PLAY`

```c
#define BSP_TOUCH_BUTTON_PLAY (GPIO_NUM_2)
```

### define `BSP_TOUCH_BUTTON_RECORD`

```c
#define BSP_TOUCH_BUTTON_RECORD (GPIO_NUM_5)
```

### define `BSP_TOUCH_BUTTON_VOLDOWN`

```c
#define BSP_TOUCH_BUTTON_VOLDOWN (GPIO_NUM_3)
```

### define `BSP_TOUCH_BUTTON_VOLUP`

```c
#define BSP_TOUCH_BUTTON_VOLUP (GPIO_NUM_1)
```

### define `BSP_TOUCH_SHELED_ELECT`

```c
#define BSP_TOUCH_SHELED_ELECT (GPIO_NUM_14)
```


## Types Documentation

### enum `bsp_button_t`

```c
enum bsp_button_t {
    BSP_BUTTON_REC = 0,
    BSP_BUTTON_MODE,
    BSP_BUTTON_PLAY,
    BSP_BUTTON_SET,
    BSP_BUTTON_VOLDOWN,
    BSP_BUTTON_VOLUP,
    BSP_BUTTON_NUM
};
```

### enum `bsp_touchpad_button_t`

```c
enum bsp_touchpad_button_t {
    TOUCH_BUTTON_PLAY = TOUCH_PAD_NUM2,
    TOUCH_BUTTON_PHOTO = TOUCH_PAD_NUM6,
    TOUCH_BUTTON_NETWORK = TOUCH_PAD_NUM11,
    TOUCH_BUTTON_RECORD = TOUCH_PAD_NUM5,
    TOUCH_BUTTON_VOLUP = TOUCH_PAD_NUM1,
    TOUCH_BUTTON_VOLDOWN = TOUCH_PAD_NUM3,
    TOUCH_BUTTON_GUARD = TOUCH_PAD_NUM4,
    TOUCH_SHELED_ELECT = TOUCH_PAD_NUM14,
    TOUCH_BUTTON_NUM = 7
};
```


## Functions Documentation

### function `bsp_audio_init`

```c
esp_err_t bsp_audio_init (
    const i2s_std_config_t * i2s_config,
    i2s_chan_handle_t * tx_channel,
    i2s_chan_handle_t * rx_channel
) 
```

### function `bsp_audio_poweramp_enable`

```c
esp_err_t bsp_audio_poweramp_enable (
    bool enable
) 
```

### function `bsp_display_backlight_off`

```c
esp_err_t bsp_display_backlight_off (
    void
) 
```

### function `bsp_display_backlight_on`

```c
esp_err_t bsp_display_backlight_on (
    void
) 
```

### function `bsp_display_get_input_dev`

```c
lv_indev_t * bsp_display_get_input_dev (
    void
) 
```

### function `bsp_display_lock`

```c
bool bsp_display_lock (
    uint32_t timeout_ms
) 
```

### function `bsp_display_rotate`

```c
void bsp_display_rotate (
    lv_disp_t * disp,
    lv_disp_rot_t rotation
) 
```

### function `bsp_display_start`

```c
lv_disp_t * bsp_display_start (
    void
) 
```

### function `bsp_display_unlock`

```c
void bsp_display_unlock (
    void
) 
```

### function `bsp_i2c_deinit`

```c
esp_err_t bsp_i2c_deinit (
    void
) 
```

### function `bsp_i2c_init`

```c
esp_err_t bsp_i2c_init (
    void
) 
```

### function `bsp_touchpad_calibrate`

```c
esp_err_t bsp_touchpad_calibrate (
    bsp_touchpad_button_t tch_pad,
    float tch_threshold
) 
```

### function `bsp_touchpad_deinit`

```c
esp_err_t bsp_touchpad_deinit (
    void
) 
```

### function `bsp_touchpad_init`

```c
esp_err_t bsp_touchpad_init (
    intr_handler_t fn
) 
```


## File esp-box-lite/include/bsp/display.h

## Classes

| Type | Name |
| ---: | :--- |
| struct | [**bsp\_display\_config\_t**](#struct-bsp_display_config_t) <br>_BSP display configuration structure._ |

## Macros

| Type | Name |
| ---: | :--- |
| define  | [**BSP\_LCD\_BIGENDIAN**](#define-bsp_lcd_bigendian)  (1)<br> |
| define  | [**BSP\_LCD\_BITS\_PER\_PIXEL**](#define-bsp_lcd_bits_per_pixel)  (16)<br> |
| define  | [**BSP\_LCD\_COLOR\_FORMAT**](#define-bsp_lcd_color_format)  (ESP\_LCD\_COLOR\_FORMAT\_RGB565)<br> |
| define  | [**BSP\_LCD\_COLOR\_SPACE**](#define-bsp_lcd_color_space)  (ESP\_LCD\_COLOR\_SPACE\_RGB)<br> |
| define  | [**ESP\_LCD\_COLOR\_FORMAT\_RGB565**](#define-esp_lcd_color_format_rgb565)  (1)<br> |
| define  | [**ESP\_LCD\_COLOR\_FORMAT\_RGB888**](#define-esp_lcd_color_format_rgb888)  (2)<br> |


## Functions

| Type | Name |
| ---: | :--- |
|  esp\_err\_t | [**bsp\_display\_new**](#function-bsp_display_new) (const [**bsp\_display\_config\_t**](#struct-bsp_display_config_t)\* config, esp\_lcd\_panel\_handle\_t \* ret\_panel, esp\_lcd\_panel\_io\_handle\_t \* ret\_io) <br>_Create new display panel._ |

## Classes Documentation

### struct `bsp_display_config_t`

Variables:

-  int max_transfer_sz  <br>

## Macros Documentation

### define `BSP_LCD_BIGENDIAN`

```c
#define BSP_LCD_BIGENDIAN (1)
```

### define `BSP_LCD_BITS_PER_PIXEL`

```c
#define BSP_LCD_BITS_PER_PIXEL (16)
```

### define `BSP_LCD_COLOR_FORMAT`

```c
#define BSP_LCD_COLOR_FORMAT (ESP_LCD_COLOR_FORMAT_RGB565)
```

### define `BSP_LCD_COLOR_SPACE`

```c
#define BSP_LCD_COLOR_SPACE (ESP_LCD_COLOR_SPACE_RGB)
```

### define `ESP_LCD_COLOR_FORMAT_RGB565`

```c
#define ESP_LCD_COLOR_FORMAT_RGB565 (1)
```

### define `ESP_LCD_COLOR_FORMAT_RGB888`

```c
#define ESP_LCD_COLOR_FORMAT_RGB888 (2)
```



## Functions Documentation

### function `bsp_display_new`

```c
esp_err_t bsp_display_new (
    const bsp_display_config_t * config,
    esp_lcd_panel_handle_t * ret_panel,
    esp_lcd_panel_io_handle_t * ret_io
) 
```


## File esp-box/include/bsp/display.h

## Classes

| Type | Name |
| ---: | :--- |
| struct | [**bsp\_display\_config\_t**](#struct-bsp_display_config_t) <br>_BSP display configuration structure._ |

## Macros

| Type | Name |
| ---: | :--- |
| define  | [**BSP\_LCD\_BIGENDIAN**](#define-bsp_lcd_bigendian)  (1)<br> |
| define  | [**BSP\_LCD\_BITS\_PER\_PIXEL**](#define-bsp_lcd_bits_per_pixel)  (16)<br> |
| define  | [**BSP\_LCD\_COLOR\_FORMAT**](#define-bsp_lcd_color_format)  (ESP\_LCD\_COLOR\_FORMAT\_RGB565)<br> |
| define  | [**BSP\_LCD\_COLOR\_SPACE**](#define-bsp_lcd_color_space)  (ESP\_LCD\_COLOR\_SPACE\_BGR)<br> |
| define  | [**ESP\_LCD\_COLOR\_FORMAT\_RGB565**](#define-esp_lcd_color_format_rgb565)  (1)<br> |
| define  | [**ESP\_LCD\_COLOR\_FORMAT\_RGB888**](#define-esp_lcd_color_format_rgb888)  (2)<br> |


## Functions

| Type | Name |
| ---: | :--- |
|  esp\_err\_t | [**bsp\_display\_new**](#function-bsp_display_new) (const [**bsp\_display\_config\_t**](#struct-bsp_display_config_t)\* config, esp\_lcd\_panel\_handle\_t \* ret\_panel, esp\_lcd\_panel\_io\_handle\_t \* ret\_io) <br>_Create new display panel._ |

## Classes Documentation

### struct `bsp_display_config_t`

Variables:

-  int max_transfer_sz  <br>

## Macros Documentation

### define `BSP_LCD_BIGENDIAN`

```c
#define BSP_LCD_BIGENDIAN (1)
```

### define `BSP_LCD_BITS_PER_PIXEL`

```c
#define BSP_LCD_BITS_PER_PIXEL (16)
```

### define `BSP_LCD_COLOR_FORMAT`

```c
#define BSP_LCD_COLOR_FORMAT (ESP_LCD_COLOR_FORMAT_RGB565)
```

### define `BSP_LCD_COLOR_SPACE`

```c
#define BSP_LCD_COLOR_SPACE (ESP_LCD_COLOR_SPACE_BGR)
```

### define `ESP_LCD_COLOR_FORMAT_RGB565`

```c
#define ESP_LCD_COLOR_FORMAT_RGB565 (1)
```

### define `ESP_LCD_COLOR_FORMAT_RGB888`

```c
#define ESP_LCD_COLOR_FORMAT_RGB888 (2)
```



## Functions Documentation

### function `bsp_display_new`

```c
esp_err_t bsp_display_new (
    const bsp_display_config_t * config,
    esp_lcd_panel_handle_t * ret_panel,
    esp_lcd_panel_io_handle_t * ret_io
) 
```


## File esp32_c3_lcdkit/include/bsp/display.h

## Classes

| Type | Name |
| ---: | :--- |
| struct | [**bsp\_display\_config\_t**](#struct-bsp_display_config_t) <br>_BSP display configuration structure._ |

## Macros

| Type | Name |
| ---: | :--- |
| define  | [**BSP\_LCD\_BIGENDIAN**](#define-bsp_lcd_bigendian)  (1)<br> |
| define  | [**BSP\_LCD\_BITS\_PER\_PIXEL**](#define-bsp_lcd_bits_per_pixel)  (16)<br> |
| define  | [**BSP\_LCD\_COLOR\_FORMAT**](#define-bsp_lcd_color_format)  (ESP\_LCD\_COLOR\_FORMAT\_RGB565)<br> |
| define  | [**BSP\_LCD\_COLOR\_SPACE**](#define-bsp_lcd_color_space)  (ESP\_LCD\_COLOR\_SPACE\_BGR)<br> |
| define  | [**ESP\_LCD\_COLOR\_FORMAT\_RGB565**](#define-esp_lcd_color_format_rgb565)  (1)<br> |
| define  | [**ESP\_LCD\_COLOR\_FORMAT\_RGB888**](#define-esp_lcd_color_format_rgb888)  (2)<br> |


## Functions

| Type | Name |
| ---: | :--- |
|  esp\_err\_t | [**bsp\_display\_new**](#function-bsp_display_new) (const [**bsp\_display\_config\_t**](#struct-bsp_display_config_t)\* config, esp\_lcd\_panel\_handle\_t \* ret\_panel, esp\_lcd\_panel\_io\_handle\_t \* ret\_io) <br>_Create new display panel._ |

## Classes Documentation

### struct `bsp_display_config_t`

Variables:

-  int max_transfer_sz  <br>

## Macros Documentation

### define `BSP_LCD_BIGENDIAN`

```c
#define BSP_LCD_BIGENDIAN (1)
```

### define `BSP_LCD_BITS_PER_PIXEL`

```c
#define BSP_LCD_BITS_PER_PIXEL (16)
```

### define `BSP_LCD_COLOR_FORMAT`

```c
#define BSP_LCD_COLOR_FORMAT (ESP_LCD_COLOR_FORMAT_RGB565)
```

### define `BSP_LCD_COLOR_SPACE`

```c
#define BSP_LCD_COLOR_SPACE (ESP_LCD_COLOR_SPACE_BGR)
```

### define `ESP_LCD_COLOR_FORMAT_RGB565`

```c
#define ESP_LCD_COLOR_FORMAT_RGB565 (1)
```

### define `ESP_LCD_COLOR_FORMAT_RGB888`

```c
#define ESP_LCD_COLOR_FORMAT_RGB888 (2)
```



## Functions Documentation

### function `bsp_display_new`

```c
esp_err_t bsp_display_new (
    const bsp_display_config_t * config,
    esp_lcd_panel_handle_t * ret_panel,
    esp_lcd_panel_io_handle_t * ret_io
) 
```


## File esp32_s2_kaluga_kit/include/bsp/display.h

## Classes

| Type | Name |
| ---: | :--- |
| struct | [**bsp\_display\_config\_t**](#struct-bsp_display_config_t) <br>_BSP display configuration structure._ |

## Macros

| Type | Name |
| ---: | :--- |
| define  | [**BSP\_LCD\_BIGENDIAN**](#define-bsp_lcd_bigendian)  (1)<br> |
| define  | [**BSP\_LCD\_BITS\_PER\_PIXEL**](#define-bsp_lcd_bits_per_pixel)  (16)<br> |
| define  | [**BSP\_LCD\_COLOR\_FORMAT**](#define-bsp_lcd_color_format)  (ESP\_LCD\_COLOR\_FORMAT\_RGB565)<br> |
| define  | [**BSP\_LCD\_COLOR\_SPACE**](#define-bsp_lcd_color_space)  (ESP\_LCD\_COLOR\_SPACE\_RGB)<br> |
| define  | [**ESP\_LCD\_COLOR\_FORMAT\_RGB565**](#define-esp_lcd_color_format_rgb565)  (1)<br> |
| define  | [**ESP\_LCD\_COLOR\_FORMAT\_RGB888**](#define-esp_lcd_color_format_rgb888)  (2)<br> |


## Functions

| Type | Name |
| ---: | :--- |
|  esp\_err\_t | [**bsp\_display\_new**](#function-bsp_display_new) (const [**bsp\_display\_config\_t**](#struct-bsp_display_config_t)\* config, esp\_lcd\_panel\_handle\_t \* ret\_panel, esp\_lcd\_panel\_io\_handle\_t \* ret\_io) <br>_Create new display panel._ |

## Classes Documentation

### struct `bsp_display_config_t`

Variables:

-  int max_transfer_sz  <br>

## Macros Documentation

### define `BSP_LCD_BIGENDIAN`

```c
#define BSP_LCD_BIGENDIAN (1)
```

### define `BSP_LCD_BITS_PER_PIXEL`

```c
#define BSP_LCD_BITS_PER_PIXEL (16)
```

### define `BSP_LCD_COLOR_FORMAT`

```c
#define BSP_LCD_COLOR_FORMAT (ESP_LCD_COLOR_FORMAT_RGB565)
```

### define `BSP_LCD_COLOR_SPACE`

```c
#define BSP_LCD_COLOR_SPACE (ESP_LCD_COLOR_SPACE_RGB)
```

### define `ESP_LCD_COLOR_FORMAT_RGB565`

```c
#define ESP_LCD_COLOR_FORMAT_RGB565 (1)
```

### define `ESP_LCD_COLOR_FORMAT_RGB888`

```c
#define ESP_LCD_COLOR_FORMAT_RGB888 (2)
```



## Functions Documentation

### function `bsp_display_new`

```c
esp_err_t bsp_display_new (
    const bsp_display_config_t * config,
    esp_lcd_panel_handle_t * ret_panel,
    esp_lcd_panel_io_handle_t * ret_io
) 
```


## File esp32_s3_eye/include/bsp/display.h

## Classes

| Type | Name |
| ---: | :--- |
| struct | [**bsp\_display\_config\_t**](#struct-bsp_display_config_t) <br>_BSP display configuration structure._ |

## Macros

| Type | Name |
| ---: | :--- |
| define  | [**BSP\_LCD\_BIGENDIAN**](#define-bsp_lcd_bigendian)  (1)<br> |
| define  | [**BSP\_LCD\_BITS\_PER\_PIXEL**](#define-bsp_lcd_bits_per_pixel)  (16)<br> |
| define  | [**BSP\_LCD\_COLOR\_FORMAT**](#define-bsp_lcd_color_format)  (ESP\_LCD\_COLOR\_FORMAT\_RGB565)<br> |
| define  | [**BSP\_LCD\_COLOR\_SPACE**](#define-bsp_lcd_color_space)  (ESP\_LCD\_COLOR\_SPACE\_RGB)<br> |
| define  | [**ESP\_LCD\_COLOR\_FORMAT\_RGB565**](#define-esp_lcd_color_format_rgb565)  (1)<br> |
| define  | [**ESP\_LCD\_COLOR\_FORMAT\_RGB888**](#define-esp_lcd_color_format_rgb888)  (2)<br> |


## Functions

| Type | Name |
| ---: | :--- |
|  esp\_err\_t | [**bsp\_display\_new**](#function-bsp_display_new) (const [**bsp\_display\_config\_t**](#struct-bsp_display_config_t)\* config, esp\_lcd\_panel\_handle\_t \* ret\_panel, esp\_lcd\_panel\_io\_handle\_t \* ret\_io) <br>_Create new display panel._ |

## Classes Documentation

### struct `bsp_display_config_t`

Variables:

-  int max_transfer_sz  <br>

## Macros Documentation

### define `BSP_LCD_BIGENDIAN`

```c
#define BSP_LCD_BIGENDIAN (1)
```

### define `BSP_LCD_BITS_PER_PIXEL`

```c
#define BSP_LCD_BITS_PER_PIXEL (16)
```

### define `BSP_LCD_COLOR_FORMAT`

```c
#define BSP_LCD_COLOR_FORMAT (ESP_LCD_COLOR_FORMAT_RGB565)
```

### define `BSP_LCD_COLOR_SPACE`

```c
#define BSP_LCD_COLOR_SPACE (ESP_LCD_COLOR_SPACE_RGB)
```

### define `ESP_LCD_COLOR_FORMAT_RGB565`

```c
#define ESP_LCD_COLOR_FORMAT_RGB565 (1)
```

### define `ESP_LCD_COLOR_FORMAT_RGB888`

```c
#define ESP_LCD_COLOR_FORMAT_RGB888 (2)
```



## Functions Documentation

### function `bsp_display_new`

```c
esp_err_t bsp_display_new (
    const bsp_display_config_t * config,
    esp_lcd_panel_handle_t * ret_panel,
    esp_lcd_panel_io_handle_t * ret_io
) 
```


## File esp32_s3_korvo_2/include/bsp/display.h

## Classes

| Type | Name |
| ---: | :--- |
| struct | [**bsp\_display\_config\_t**](#struct-bsp_display_config_t) <br>_BSP display configuration structure._ |

## Macros

| Type | Name |
| ---: | :--- |
| define  | [**BSP\_LCD\_BIGENDIAN**](#define-bsp_lcd_bigendian)  (1)<br> |
| define  | [**BSP\_LCD\_BITS\_PER\_PIXEL**](#define-bsp_lcd_bits_per_pixel)  (16)<br> |
| define  | [**BSP\_LCD\_COLOR\_FORMAT**](#define-bsp_lcd_color_format)  (ESP\_LCD\_COLOR\_FORMAT\_RGB565)<br> |
| define  | [**BSP\_LCD\_COLOR\_SPACE**](#define-bsp_lcd_color_space)  (ESP\_LCD\_COLOR\_SPACE\_BGR)<br> |
| define  | [**ESP\_LCD\_COLOR\_FORMAT\_RGB565**](#define-esp_lcd_color_format_rgb565)  (1)<br> |
| define  | [**ESP\_LCD\_COLOR\_FORMAT\_RGB888**](#define-esp_lcd_color_format_rgb888)  (2)<br> |


## Functions

| Type | Name |
| ---: | :--- |
|  esp\_err\_t | [**bsp\_display\_new**](#function-bsp_display_new) (const [**bsp\_display\_config\_t**](#struct-bsp_display_config_t)\* config, esp\_lcd\_panel\_handle\_t \* ret\_panel, esp\_lcd\_panel\_io\_handle\_t \* ret\_io) <br>_Create new display panel._ |

## Classes Documentation

### struct `bsp_display_config_t`

Variables:

-  int max_transfer_sz  <br>

## Macros Documentation

### define `BSP_LCD_BIGENDIAN`

```c
#define BSP_LCD_BIGENDIAN (1)
```

### define `BSP_LCD_BITS_PER_PIXEL`

```c
#define BSP_LCD_BITS_PER_PIXEL (16)
```

### define `BSP_LCD_COLOR_FORMAT`

```c
#define BSP_LCD_COLOR_FORMAT (ESP_LCD_COLOR_FORMAT_RGB565)
```

### define `BSP_LCD_COLOR_SPACE`

```c
#define BSP_LCD_COLOR_SPACE (ESP_LCD_COLOR_SPACE_BGR)
```

### define `ESP_LCD_COLOR_FORMAT_RGB565`

```c
#define ESP_LCD_COLOR_FORMAT_RGB565 (1)
```

### define `ESP_LCD_COLOR_FORMAT_RGB888`

```c
#define ESP_LCD_COLOR_FORMAT_RGB888 (2)
```



## Functions Documentation

### function `bsp_display_new`

```c
esp_err_t bsp_display_new (
    const bsp_display_config_t * config,
    esp_lcd_panel_handle_t * ret_panel,
    esp_lcd_panel_io_handle_t * ret_io
) 
```


## File esp32_s3_usb_otg/include/bsp/display.h

## Classes

| Type | Name |
| ---: | :--- |
| struct | [**bsp\_display\_config\_t**](#struct-bsp_display_config_t) <br>_BSP display configuration structure._ |

## Macros

| Type | Name |
| ---: | :--- |
| define  | [**BSP\_LCD\_BIGENDIAN**](#define-bsp_lcd_bigendian)  (1)<br> |
| define  | [**BSP\_LCD\_BITS\_PER\_PIXEL**](#define-bsp_lcd_bits_per_pixel)  (16)<br> |
| define  | [**BSP\_LCD\_COLOR\_FORMAT**](#define-bsp_lcd_color_format)  (ESP\_LCD\_COLOR\_FORMAT\_RGB565)<br> |
| define  | [**BSP\_LCD\_COLOR\_SPACE**](#define-bsp_lcd_color_space)  (ESP\_LCD\_COLOR\_SPACE\_RGB)<br> |
| define  | [**ESP\_LCD\_COLOR\_FORMAT\_RGB565**](#define-esp_lcd_color_format_rgb565)  (1)<br> |
| define  | [**ESP\_LCD\_COLOR\_FORMAT\_RGB888**](#define-esp_lcd_color_format_rgb888)  (2)<br> |


## Functions

| Type | Name |
| ---: | :--- |
|  esp\_err\_t | [**bsp\_display\_new**](#function-bsp_display_new) (const [**bsp\_display\_config\_t**](#struct-bsp_display_config_t)\* config, esp\_lcd\_panel\_handle\_t \* ret\_panel, esp\_lcd\_panel\_io\_handle\_t \* ret\_io) <br>_Create new display panel._ |

## Classes Documentation

### struct `bsp_display_config_t`

Variables:

-  int max_transfer_sz  <br>

## Macros Documentation

### define `BSP_LCD_BIGENDIAN`

```c
#define BSP_LCD_BIGENDIAN (1)
```

### define `BSP_LCD_BITS_PER_PIXEL`

```c
#define BSP_LCD_BITS_PER_PIXEL (16)
```

### define `BSP_LCD_COLOR_FORMAT`

```c
#define BSP_LCD_COLOR_FORMAT (ESP_LCD_COLOR_FORMAT_RGB565)
```

### define `BSP_LCD_COLOR_SPACE`

```c
#define BSP_LCD_COLOR_SPACE (ESP_LCD_COLOR_SPACE_RGB)
```

### define `ESP_LCD_COLOR_FORMAT_RGB565`

```c
#define ESP_LCD_COLOR_FORMAT_RGB565 (1)
```

### define `ESP_LCD_COLOR_FORMAT_RGB888`

```c
#define ESP_LCD_COLOR_FORMAT_RGB888 (2)
```



## Functions Documentation

### function `bsp_display_new`

```c
esp_err_t bsp_display_new (
    const bsp_display_config_t * config,
    esp_lcd_panel_handle_t * ret_panel,
    esp_lcd_panel_io_handle_t * ret_io
) 
```


## File esp_wrover_kit/include/bsp/display.h

## Classes

| Type | Name |
| ---: | :--- |
| struct | [**bsp\_display\_config\_t**](#struct-bsp_display_config_t) <br>_BSP display configuration structure._ |

## Macros

| Type | Name |
| ---: | :--- |
| define  | [**BSP\_LCD\_BIGENDIAN**](#define-bsp_lcd_bigendian)  (1)<br> |
| define  | [**BSP\_LCD\_BITS\_PER\_PIXEL**](#define-bsp_lcd_bits_per_pixel)  (16)<br> |
| define  | [**BSP\_LCD\_COLOR\_FORMAT**](#define-bsp_lcd_color_format)  (ESP\_LCD\_COLOR\_FORMAT\_RGB565)<br> |
| define  | [**BSP\_LCD\_COLOR\_SPACE**](#define-bsp_lcd_color_space)  (ESP\_LCD\_COLOR\_SPACE\_RGB)<br> |
| define  | [**ESP\_LCD\_COLOR\_FORMAT\_RGB565**](#define-esp_lcd_color_format_rgb565)  (1)<br> |
| define  | [**ESP\_LCD\_COLOR\_FORMAT\_RGB888**](#define-esp_lcd_color_format_rgb888)  (2)<br> |


## Functions

| Type | Name |
| ---: | :--- |
|  esp\_err\_t | [**bsp\_display\_new**](#function-bsp_display_new) (const [**bsp\_display\_config\_t**](#struct-bsp_display_config_t)\* config, esp\_lcd\_panel\_handle\_t \* ret\_panel, esp\_lcd\_panel\_io\_handle\_t \* ret\_io) <br>_Create new display panel._ |

## Classes Documentation

### struct `bsp_display_config_t`

Variables:

-  int max_transfer_sz  <br>

## Macros Documentation

### define `BSP_LCD_BIGENDIAN`

```c
#define BSP_LCD_BIGENDIAN (1)
```

### define `BSP_LCD_BITS_PER_PIXEL`

```c
#define BSP_LCD_BITS_PER_PIXEL (16)
```

### define `BSP_LCD_COLOR_FORMAT`

```c
#define BSP_LCD_COLOR_FORMAT (ESP_LCD_COLOR_FORMAT_RGB565)
```

### define `BSP_LCD_COLOR_SPACE`

```c
#define BSP_LCD_COLOR_SPACE (ESP_LCD_COLOR_SPACE_RGB)
```

### define `ESP_LCD_COLOR_FORMAT_RGB565`

```c
#define ESP_LCD_COLOR_FORMAT_RGB565 (1)
```

### define `ESP_LCD_COLOR_FORMAT_RGB888`

```c
#define ESP_LCD_COLOR_FORMAT_RGB888 (2)
```



## Functions Documentation

### function `bsp_display_new`

```c
esp_err_t bsp_display_new (
    const bsp_display_config_t * config,
    esp_lcd_panel_handle_t * ret_panel,
    esp_lcd_panel_io_handle_t * ret_io
) 
```


## File esp-box-lite/include/bsp/esp-bsp.h









## File esp-box/include/bsp/esp-bsp.h









## File esp32_azure_iot_kit/include/bsp/esp-bsp.h









## File esp32_c3_lcdkit/include/bsp/esp-bsp.h









## File esp32_lyrat/include/bsp/esp-bsp.h









## File esp32_s2_kaluga_kit/include/bsp/esp-bsp.h









## File esp32_s3_eye/include/bsp/esp-bsp.h









## File esp32_s3_korvo_2/include/bsp/esp-bsp.h









## File esp32_s3_lcd_ev_board/include/bsp/esp-bsp.h









## File esp32_s3_usb_otg/include/bsp/esp-bsp.h









## File esp_wrover_kit/include/bsp/esp-bsp.h









## File esp32_s3_eye/include/bsp/esp32_s3_eye.h


## Macros

| Type | Name |
| ---: | :--- |
| define  | [**BSP\_BUTTONS\_IO**](#define-bsp_buttons_io)  (GPIO\_NUM\_1)<br> |
| define  | [**BSP\_CAMERA\_D0**](#define-bsp_camera_d0)  (GPIO\_NUM\_11)<br> |
| define  | [**BSP\_CAMERA\_D1**](#define-bsp_camera_d1)  (GPIO\_NUM\_9)<br> |
| define  | [**BSP\_CAMERA\_D2**](#define-bsp_camera_d2)  (GPIO\_NUM\_8)<br> |
| define  | [**BSP\_CAMERA\_D3**](#define-bsp_camera_d3)  (GPIO\_NUM\_10)<br> |
| define  | [**BSP\_CAMERA\_D4**](#define-bsp_camera_d4)  (GPIO\_NUM\_12)<br> |
| define  | [**BSP\_CAMERA\_D5**](#define-bsp_camera_d5)  (GPIO\_NUM\_18)<br> |
| define  | [**BSP\_CAMERA\_D6**](#define-bsp_camera_d6)  (GPIO\_NUM\_17)<br> |
| define  | [**BSP\_CAMERA\_D7**](#define-bsp_camera_d7)  (GPIO\_NUM\_16)<br> |
| define  | [**BSP\_CAMERA\_DEFAULT\_CONFIG**](#define-bsp_camera_default_config)  <br>_ESP32-S3-EYE camera default configuration._ |
| define  | [**BSP\_CAMERA\_HSYNC**](#define-bsp_camera_hsync)  (GPIO\_NUM\_7)<br> |
| define  | [**BSP\_CAMERA\_PCLK**](#define-bsp_camera_pclk)  (GPIO\_NUM\_13)<br> |
| define  | [**BSP\_CAMERA\_VSYNC**](#define-bsp_camera_vsync)  (GPIO\_NUM\_6)<br> |
| define  | [**BSP\_CAMERA\_XCLK**](#define-bsp_camera_xclk)  (GPIO\_NUM\_15)<br> |
| define  | [**BSP\_I2C\_NUM**](#define-bsp_i2c_num)  CONFIG\_BSP\_I2C\_NUM<br> |
| define  | [**BSP\_I2C\_SCL**](#define-bsp_i2c_scl)  (GPIO\_NUM\_5)<br> |
| define  | [**BSP\_I2C\_SDA**](#define-bsp_i2c_sda)  (GPIO\_NUM\_4)<br> |
| define  | [**BSP\_I2S\_DIN**](#define-bsp_i2s_din)  (GPIO\_NUM\_2)<br> |
| define  | [**BSP\_I2S\_GPIO\_CFG**](#define-bsp_i2s_gpio_cfg) () <br>_ESP32-S3-EYE I2S pinout._ |
| define  | [**BSP\_I2S\_LCLK**](#define-bsp_i2s_lclk)  (GPIO\_NUM\_42)<br> |
| define  | [**BSP\_I2S\_SCLK**](#define-bsp_i2s_sclk)  (GPIO\_NUM\_41)<br> |
| define  | [**BSP\_I2S\_SIMPLEX\_MONO\_CFG**](#define-bsp_i2s_simplex_mono_cfg) () <br>_Mono Simplex I2S configuration structure._ |
| define  | [**BSP\_LCD\_BACKLIGHT**](#define-bsp_lcd_backlight)  (GPIO\_NUM\_48)<br> |
| define  | [**BSP\_LCD\_DC**](#define-bsp_lcd_dc)  (GPIO\_NUM\_43)<br> |
| define  | [**BSP\_LCD\_DRAW\_BUFF\_DOUBLE**](#define-bsp_lcd_draw_buff_double)  (0)<br> |
| define  | [**BSP\_LCD\_DRAW\_BUFF\_SIZE**](#define-bsp_lcd_draw_buff_size)  (BSP\_LCD\_H\_RES \* BSP\_LCD\_V\_RES)<br> |
| define  | [**BSP\_LCD\_H\_RES**](#define-bsp_lcd_h_res)  (240)<br> |
| define  | [**BSP\_LCD\_PIXEL\_CLOCK\_HZ**](#define-bsp_lcd_pixel_clock_hz)  (80 \* 1000 \* 1000)<br> |
| define  | [**BSP\_LCD\_RST**](#define-bsp_lcd_rst)  (GPIO\_NUM\_NC)<br> |
| define  | [**BSP\_LCD\_SPI\_CLK**](#define-bsp_lcd_spi_clk)  (GPIO\_NUM\_21)<br> |
| define  | [**BSP\_LCD\_SPI\_CS**](#define-bsp_lcd_spi_cs)  (GPIO\_NUM\_44)<br> |
| define  | [**BSP\_LCD\_SPI\_MOSI**](#define-bsp_lcd_spi_mosi)  (GPIO\_NUM\_47)<br> |
| define  | [**BSP\_LCD\_SPI\_NUM**](#define-bsp_lcd_spi_num)  (SPI3\_HOST)<br> |
| define  | [**BSP\_LCD\_V\_RES**](#define-bsp_lcd_v_res)  (240)<br> |
| define  | [**BSP\_MIC\_SAMPLE\_RATE**](#define-bsp_mic_sample_rate)  (48000u)<br>_Sample rate of MSM261S4030H0._ |
| define  | [**BSP\_MOUNT\_POINT**](#define-bsp_mount_point)  CONFIG\_BSP\_SD\_MOUNT\_POINT<br> |
| define  | [**BSP\_SD\_CLK**](#define-bsp_sd_clk)  (GPIO\_NUM\_39)<br> |
| define  | [**BSP\_SD\_CMD**](#define-bsp_sd_cmd)  (GPIO\_NUM\_38)<br> |
| define  | [**BSP\_SD\_D0**](#define-bsp_sd_d0)  (GPIO\_NUM\_40)<br> |

## Types

| Type | Name |
| ---: | :--- |
| enum  | [**bsp\_button\_t**](#enum-bsp_button_t)  <br> |
| enum  | [**bsp\_led\_t**](#enum-bsp_led_t)  <br> |
| typedef enum bsp\_led\_t | [**bsp\_led\_t**](#typedef-bsp_led_t)  <br> |

## Functions

| Type | Name |
| ---: | :--- |
|  esp\_err\_t | [**bsp\_audio\_init**](#function-bsp_audio_init) (const i2s\_std\_config\_t \* i2s\_config, i2s\_chan\_handle\_t \* tx\_channel, i2s\_chan\_handle\_t \* rx\_channel) <br>_Init audio._ |
|  esp\_err\_t | [**bsp\_display\_backlight\_off**](#function-bsp_display_backlight_off) (void) <br>_Turn off display backlight._ |
|  esp\_err\_t | [**bsp\_display\_backlight\_on**](#function-bsp_display_backlight_on) (void) <br>_Turn on display backlight._ |
|  esp\_err\_t | [**bsp\_display\_brightness\_set**](#function-bsp_display_brightness_set) (int brightness\_percent) <br>_Set display's brightness._ |
|  lv\_indev\_t \* | [**bsp\_display\_get\_input\_dev**](#function-bsp_display_get_input_dev) (void) <br>_Get pointer to input device (touch, buttons, ...)_ |
|  bool | [**bsp\_display\_lock**](#function-bsp_display_lock) (uint32\_t timeout\_ms) <br>_Take LVGL mutex._ |
|  void | [**bsp\_display\_rotate**](#function-bsp_display_rotate) (lv\_disp\_t \* disp, lv\_disp\_rot\_t rotation) <br>_Rotate screen._ |
|  lv\_disp\_t \* | [**bsp\_display\_start**](#function-bsp_display_start) (void) <br>_Initialize display._ |
|  void | [**bsp\_display\_unlock**](#function-bsp_display_unlock) (void) <br>_Give LVGL mutex._ |
|  esp\_err\_t | [**bsp\_i2c\_deinit**](#function-bsp_i2c_deinit) (void) <br>_Deinit I2C driver and free its resources._ |
|  esp\_err\_t | [**bsp\_i2c\_init**](#function-bsp_i2c_init) (void) <br>_Init I2C driver._ |
|  esp\_err\_t | [**bsp\_led\_set**](#function-bsp_led_set) (const bsp\_led\_t led\_io, const bool on) <br>_Turn LED on/off._ |
|  esp\_err\_t | [**bsp\_leds\_init**](#function-bsp_leds_init) (void) <br>_Set LED's GPIOs as output push-pull._ |
|  esp\_err\_t | [**bsp\_sdcard\_mount**](#function-bsp_sdcard_mount) (void) <br>_Mount microSD card to virtual file system._ |
|  esp\_err\_t | [**bsp\_sdcard\_unmount**](#function-bsp_sdcard_unmount) (void) <br>_Unmount microSD card from virtual file system._ |


## Macros Documentation

### define `BSP_BUTTONS_IO`

```c
#define BSP_BUTTONS_IO (GPIO_NUM_1)
```

### define `BSP_CAMERA_D0`

```c
#define BSP_CAMERA_D0 (GPIO_NUM_11)
```

### define `BSP_CAMERA_D1`

```c
#define BSP_CAMERA_D1 (GPIO_NUM_9)
```

### define `BSP_CAMERA_D2`

```c
#define BSP_CAMERA_D2 (GPIO_NUM_8)
```

### define `BSP_CAMERA_D3`

```c
#define BSP_CAMERA_D3 (GPIO_NUM_10)
```

### define `BSP_CAMERA_D4`

```c
#define BSP_CAMERA_D4 (GPIO_NUM_12)
```

### define `BSP_CAMERA_D5`

```c
#define BSP_CAMERA_D5 (GPIO_NUM_18)
```

### define `BSP_CAMERA_D6`

```c
#define BSP_CAMERA_D6 (GPIO_NUM_17)
```

### define `BSP_CAMERA_D7`

```c
#define BSP_CAMERA_D7 (GPIO_NUM_16)
```

### define `BSP_CAMERA_DEFAULT_CONFIG`

```c
#define BSP_CAMERA_DEFAULT_CONFIG {                                     \
        .pin_pwdn = GPIO_NUM_NC,          \
        .pin_reset = GPIO_NUM_NC,         \
        .pin_xclk = BSP_CAMERA_XCLK,      \
        .pin_sccb_sda = GPIO_NUM_NC,      \
        .pin_sccb_scl = GPIO_NUM_NC,      \
        .pin_d7 = BSP_CAMERA_D7 ,          \
        .pin_d6 = BSP_CAMERA_D6 ,          \
        .pin_d5 = BSP_CAMERA_D5 ,          \
        .pin_d4 = BSP_CAMERA_D4 ,          \
        .pin_d3 = BSP_CAMERA_D3 ,          \
        .pin_d2 = BSP_CAMERA_D2 ,          \
        .pin_d1 = BSP_CAMERA_D1 ,          \
        .pin_d0 = BSP_CAMERA_D0 ,          \
        .pin_vsync = BSP_CAMERA_VSYNC,    \
        .pin_href = BSP_CAMERA_HSYNC,     \
        .pin_pclk = BSP_CAMERA_PCLK,      \
        .xclk_freq_hz = 16000000,         \
        .ledc_timer = LEDC_TIMER_0,       \
        .ledc_channel = LEDC_CHANNEL_0,   \
        .pixel_format = PIXFORMAT_RGB565, \
        .frame_size = FRAMESIZE_240X240,  \
        .jpeg_quality = 12,               \
        .fb_count = 2,                    \
        .fb_location = CAMERA_FB_IN_PSRAM,\
        .sccb_i2c_port = BSP_I2C_NUM,     \
    }
```

### define `BSP_CAMERA_HSYNC`

```c
#define BSP_CAMERA_HSYNC (GPIO_NUM_7)
```

### define `BSP_CAMERA_PCLK`

```c
#define BSP_CAMERA_PCLK (GPIO_NUM_13)
```

### define `BSP_CAMERA_VSYNC`

```c
#define BSP_CAMERA_VSYNC (GPIO_NUM_6)
```

### define `BSP_CAMERA_XCLK`

```c
#define BSP_CAMERA_XCLK (GPIO_NUM_15)
```

### define `BSP_I2C_NUM`

```c
#define BSP_I2C_NUM CONFIG_BSP_I2C_NUM
```

### define `BSP_I2C_SCL`

```c
#define BSP_I2C_SCL (GPIO_NUM_5)
```

### define `BSP_I2C_SDA`

```c
#define BSP_I2C_SDA (GPIO_NUM_4)
```

### define `BSP_I2S_DIN`

```c
#define BSP_I2S_DIN (GPIO_NUM_2)
```

### define `BSP_I2S_GPIO_CFG`

```c
#define BSP_I2S_GPIO_CFG (
    
) {                          \
        .mclk = GPIO_NUM_NC,   \
        .bclk = BSP_I2S_SCLK,  \
        .ws = BSP_I2S_LCLK,    \
        .dout = GPIO_NUM_NC,   \
        .din = BSP_I2S_DIN,    \
        .invert_flags = {      \
            .mclk_inv = false, \
            .bclk_inv = false, \
            .ws_inv = false,   \
        },                     \
    }
```

### define `BSP_I2S_LCLK`

```c
#define BSP_I2S_LCLK (GPIO_NUM_42)
```

### define `BSP_I2S_SCLK`

```c
#define BSP_I2S_SCLK (GPIO_NUM_41)
```

### define `BSP_I2S_SIMPLEX_MONO_CFG`

```c
#define BSP_I2S_SIMPLEX_MONO_CFG (
    
) {                                                   \
        .clk_cfg = {                                    \
            .sample_rate_hz = BSP_MIC_SAMPLE_RATE ,      \
            .clk_src = I2S_CLK_SRC_DEFAULT,             \
            .mclk_multiple = I2S_MCLK_MULTIPLE_384,     \
        },                                              \
        .slot_cfg = {                                   \
            .data_bit_width = I2S_DATA_BIT_WIDTH_24BIT, \
            .slot_bit_width = I2S_SLOT_BIT_WIDTH_32BIT, \
            .slot_mode = I2S_SLOT_MODE_MONO,            \
            .slot_mask = I2S_STD_SLOT_LEFT,             \
            .ws_width = 32,                             \
            .ws_pol = false,                            \
            .bit_shift = true,                          \
            .left_align = true,                         \
            .big_endian = false,                        \
            .bit_order_lsb = false,                     \
        },                                              \
        .gpio_cfg = BSP_I2S_GPIO_CFG (),                 \
    }
```

### define `BSP_LCD_BACKLIGHT`

```c
#define BSP_LCD_BACKLIGHT (GPIO_NUM_48)
```

### define `BSP_LCD_DC`

```c
#define BSP_LCD_DC (GPIO_NUM_43)
```

### define `BSP_LCD_DRAW_BUFF_DOUBLE`

```c
#define BSP_LCD_DRAW_BUFF_DOUBLE (0)
```

### define `BSP_LCD_DRAW_BUFF_SIZE`

```c
#define BSP_LCD_DRAW_BUFF_SIZE (BSP_LCD_H_RES * BSP_LCD_V_RES)
```

### define `BSP_LCD_H_RES`

```c
#define BSP_LCD_H_RES (240)
```

### define `BSP_LCD_PIXEL_CLOCK_HZ`

```c
#define BSP_LCD_PIXEL_CLOCK_HZ (80 * 1000 * 1000)
```

### define `BSP_LCD_RST`

```c
#define BSP_LCD_RST (GPIO_NUM_NC)
```

### define `BSP_LCD_SPI_CLK`

```c
#define BSP_LCD_SPI_CLK (GPIO_NUM_21)
```

### define `BSP_LCD_SPI_CS`

```c
#define BSP_LCD_SPI_CS (GPIO_NUM_44)
```

### define `BSP_LCD_SPI_MOSI`

```c
#define BSP_LCD_SPI_MOSI (GPIO_NUM_47)
```

### define `BSP_LCD_SPI_NUM`

```c
#define BSP_LCD_SPI_NUM (SPI3_HOST)
```

### define `BSP_LCD_V_RES`

```c
#define BSP_LCD_V_RES (240)
```

### define `BSP_MIC_SAMPLE_RATE`

```c
#define BSP_MIC_SAMPLE_RATE (48000u)
```

### define `BSP_MOUNT_POINT`

```c
#define BSP_MOUNT_POINT CONFIG_BSP_SD_MOUNT_POINT
```

### define `BSP_SD_CLK`

```c
#define BSP_SD_CLK (GPIO_NUM_39)
```

### define `BSP_SD_CMD`

```c
#define BSP_SD_CMD (GPIO_NUM_38)
```

### define `BSP_SD_D0`

```c
#define BSP_SD_D0 (GPIO_NUM_40)
```


## Types Documentation

### enum `bsp_button_t`

```c
enum bsp_button_t {
    BSP_BUTTON_MENU = 0,
    BSP_BUTTON_DOWN,
    BSP_BUTTON_UP,
    BSP_BUTTON_PLAY,
    BSP_BUTTON_NUM
};
```

### enum `bsp_led_t`

```c
enum bsp_led_t {
    BSP_LED_GREEN = GPIO_NUM_3
};
```

### typedef `bsp_led_t`

```c
typedef enum bsp_led_t bsp_led_t;
```


## Functions Documentation

### function `bsp_audio_init`

```c
esp_err_t bsp_audio_init (
    const i2s_std_config_t * i2s_config,
    i2s_chan_handle_t * tx_channel,
    i2s_chan_handle_t * rx_channel
) 
```

### function `bsp_display_backlight_off`

```c
esp_err_t bsp_display_backlight_off (
    void
) 
```

### function `bsp_display_backlight_on`

```c
esp_err_t bsp_display_backlight_on (
    void
) 
```

### function `bsp_display_brightness_set`

```c
esp_err_t bsp_display_brightness_set (
    int brightness_percent
) 
```

### function `bsp_display_get_input_dev`

```c
lv_indev_t * bsp_display_get_input_dev (
    void
) 
```

### function `bsp_display_lock`

```c
bool bsp_display_lock (
    uint32_t timeout_ms
) 
```

### function `bsp_display_rotate`

```c
void bsp_display_rotate (
    lv_disp_t * disp,
    lv_disp_rot_t rotation
) 
```

### function `bsp_display_start`

```c
lv_disp_t * bsp_display_start (
    void
) 
```

### function `bsp_display_unlock`

```c
void bsp_display_unlock (
    void
) 
```

### function `bsp_i2c_deinit`

```c
esp_err_t bsp_i2c_deinit (
    void
) 
```

### function `bsp_i2c_init`

```c
esp_err_t bsp_i2c_init (
    void
) 
```

### function `bsp_led_set`

```c
esp_err_t bsp_led_set (
    const bsp_led_t led_io,
    const bool on
) 
```

### function `bsp_leds_init`

```c
esp_err_t bsp_leds_init (
    void
) 
```

### function `bsp_sdcard_mount`

```c
esp_err_t bsp_sdcard_mount (
    void
) 
```

### function `bsp_sdcard_unmount`

```c
esp_err_t bsp_sdcard_unmount (
    void
) 
```


## File esp-box-lite/priv_include/bsp_err_check.h


## Macros

| Type | Name |
| ---: | :--- |
| define  | [**BSP\_ERROR\_CHECK**](#define-bsp_error_check) (x, ret) <br> |
| define  | [**BSP\_ERROR\_CHECK\_RETURN\_ERR**](#define-bsp_error_check_return_err) (x) <br> |
| define  | [**BSP\_ERROR\_CHECK\_RETURN\_NULL**](#define-bsp_error_check_return_null) (x) <br> |
| define  | [**BSP\_NULL\_CHECK**](#define-bsp_null_check) (x, ret) <br> |
| define  | [**BSP\_NULL\_CHECK**](#define-bsp_null_check) (x, ret) <br> |
| define  | [**BSP\_NULL\_CHECK\_GOTO**](#define-bsp_null_check_goto) (x, goto\_tag) <br> |




## Macros Documentation

### define `BSP_ERROR_CHECK`

```c
#define BSP_ERROR_CHECK (
    x,
    ret
) do { \
        if (unlikely((x) != ESP_OK)) {    \
            return ret;                   \
        }                                 \
    } while(0)
```

### define `BSP_ERROR_CHECK_RETURN_ERR`

```c
#define BSP_ERROR_CHECK_RETURN_ERR (
    x
) do { \
        esp_err_t err_rc_ = (x);            \
        if (unlikely(err_rc_ != ESP_OK)) {  \
            return err_rc_;                 \
        }                                   \
    } while(0)
```

### define `BSP_ERROR_CHECK_RETURN_NULL`

```c
#define BSP_ERROR_CHECK_RETURN_NULL (
    x
) do { \
        if (unlikely((x) != ESP_OK)) {      \
            return NULL;                    \
        }                                   \
    } while(0)
```

### define `BSP_NULL_CHECK`

```c
#define BSP_NULL_CHECK (
    x,
    ret
) do { \
        if ((x) == NULL) {          \
            return ret;             \
        }                           \
    } while(0)
```

### define `BSP_NULL_CHECK`

```c
#define BSP_NULL_CHECK (
    x,
    ret
) do { \
        if ((x) == NULL) {          \
            return ret;             \
        }                           \
    } while(0)
```

### define `BSP_NULL_CHECK_GOTO`

```c
#define BSP_NULL_CHECK_GOTO (
    x,
    goto_tag
) do { \
        if ((x) == NULL) {      \
            goto goto_tag;      \
        }                       \
    } while(0)
```




## File esp-box/priv_include/bsp_err_check.h


## Macros

| Type | Name |
| ---: | :--- |
| define  | [**BSP\_ERROR\_CHECK**](#define-bsp_error_check) (x, ret) <br> |
| define  | [**BSP\_ERROR\_CHECK\_RETURN\_ERR**](#define-bsp_error_check_return_err) (x) <br> |
| define  | [**BSP\_ERROR\_CHECK\_RETURN\_NULL**](#define-bsp_error_check_return_null) (x) <br> |
| define  | [**BSP\_NULL\_CHECK**](#define-bsp_null_check) (x, ret) <br> |
| define  | [**BSP\_NULL\_CHECK**](#define-bsp_null_check) (x, ret) <br> |
| define  | [**BSP\_NULL\_CHECK\_GOTO**](#define-bsp_null_check_goto) (x, goto\_tag) <br> |




## Macros Documentation

### define `BSP_ERROR_CHECK`

```c
#define BSP_ERROR_CHECK (
    x,
    ret
) do { \
        if (unlikely((x) != ESP_OK)) {    \
            return ret;                   \
        }                                 \
    } while(0)
```

### define `BSP_ERROR_CHECK_RETURN_ERR`

```c
#define BSP_ERROR_CHECK_RETURN_ERR (
    x
) do { \
        esp_err_t err_rc_ = (x);            \
        if (unlikely(err_rc_ != ESP_OK)) {  \
            return err_rc_;                 \
        }                                   \
    } while(0)
```

### define `BSP_ERROR_CHECK_RETURN_NULL`

```c
#define BSP_ERROR_CHECK_RETURN_NULL (
    x
) do { \
        if (unlikely((x) != ESP_OK)) {      \
            return NULL;                    \
        }                                   \
    } while(0)
```

### define `BSP_NULL_CHECK`

```c
#define BSP_NULL_CHECK (
    x,
    ret
) do { \
        if ((x) == NULL) {          \
            return ret;             \
        }                           \
    } while(0)
```

### define `BSP_NULL_CHECK`

```c
#define BSP_NULL_CHECK (
    x,
    ret
) do { \
        if ((x) == NULL) {          \
            return ret;             \
        }                           \
    } while(0)
```

### define `BSP_NULL_CHECK_GOTO`

```c
#define BSP_NULL_CHECK_GOTO (
    x,
    goto_tag
) do { \
        if ((x) == NULL) {      \
            goto goto_tag;      \
        }                       \
    } while(0)
```




## File esp32_azure_iot_kit/priv_include/bsp_err_check.h


## Macros

| Type | Name |
| ---: | :--- |
| define  | [**BSP\_ERROR\_CHECK**](#define-bsp_error_check) (x, ret) <br> |
| define  | [**BSP\_ERROR\_CHECK\_RETURN\_ERR**](#define-bsp_error_check_return_err) (x) <br> |
| define  | [**BSP\_ERROR\_CHECK\_RETURN\_NULL**](#define-bsp_error_check_return_null) (x) <br> |
| define  | [**BSP\_NULL\_CHECK**](#define-bsp_null_check) (x, ret) <br> |
| define  | [**BSP\_NULL\_CHECK**](#define-bsp_null_check) (x, ret) <br> |
| define  | [**BSP\_NULL\_CHECK\_GOTO**](#define-bsp_null_check_goto) (x, goto\_tag) <br> |




## Macros Documentation

### define `BSP_ERROR_CHECK`

```c
#define BSP_ERROR_CHECK (
    x,
    ret
) do { \
        if (unlikely((x) != ESP_OK)) {    \
            return ret;                   \
        }                                 \
    } while(0)
```

### define `BSP_ERROR_CHECK_RETURN_ERR`

```c
#define BSP_ERROR_CHECK_RETURN_ERR (
    x
) do { \
        esp_err_t err_rc_ = (x);            \
        if (unlikely(err_rc_ != ESP_OK)) {  \
            return err_rc_;                 \
        }                                   \
    } while(0)
```

### define `BSP_ERROR_CHECK_RETURN_NULL`

```c
#define BSP_ERROR_CHECK_RETURN_NULL (
    x
) do { \
        if (unlikely((x) != ESP_OK)) {      \
            return NULL;                    \
        }                                   \
    } while(0)
```

### define `BSP_NULL_CHECK`

```c
#define BSP_NULL_CHECK (
    x,
    ret
) do { \
        if ((x) == NULL) {          \
            return ret;             \
        }                           \
    } while(0)
```

### define `BSP_NULL_CHECK`

```c
#define BSP_NULL_CHECK (
    x,
    ret
) do { \
        if ((x) == NULL) {          \
            return ret;             \
        }                           \
    } while(0)
```

### define `BSP_NULL_CHECK_GOTO`

```c
#define BSP_NULL_CHECK_GOTO (
    x,
    goto_tag
) do { \
        if ((x) == NULL) {      \
            goto goto_tag;      \
        }                       \
    } while(0)
```




## File esp32_c3_lcdkit/priv_include/bsp_err_check.h


## Macros

| Type | Name |
| ---: | :--- |
| define  | [**BSP\_ERROR\_CHECK**](#define-bsp_error_check) (x, ret) <br> |
| define  | [**BSP\_ERROR\_CHECK\_RETURN\_ERR**](#define-bsp_error_check_return_err) (x) <br> |
| define  | [**BSP\_ERROR\_CHECK\_RETURN\_NULL**](#define-bsp_error_check_return_null) (x) <br> |
| define  | [**BSP\_NULL\_CHECK**](#define-bsp_null_check) (x, ret) <br> |
| define  | [**BSP\_NULL\_CHECK**](#define-bsp_null_check) (x, ret) <br> |
| define  | [**BSP\_NULL\_CHECK\_GOTO**](#define-bsp_null_check_goto) (x, goto\_tag) <br> |




## Macros Documentation

### define `BSP_ERROR_CHECK`

```c
#define BSP_ERROR_CHECK (
    x,
    ret
) do { \
        if (unlikely((x) != ESP_OK)) {    \
            return ret;                   \
        }                                 \
    } while(0)
```

### define `BSP_ERROR_CHECK_RETURN_ERR`

```c
#define BSP_ERROR_CHECK_RETURN_ERR (
    x
) do { \
        esp_err_t err_rc_ = (x);            \
        if (unlikely(err_rc_ != ESP_OK)) {  \
            return err_rc_;                 \
        }                                   \
    } while(0)
```

### define `BSP_ERROR_CHECK_RETURN_NULL`

```c
#define BSP_ERROR_CHECK_RETURN_NULL (
    x
) do { \
        if (unlikely((x) != ESP_OK)) {      \
            return NULL;                    \
        }                                   \
    } while(0)
```

### define `BSP_NULL_CHECK`

```c
#define BSP_NULL_CHECK (
    x,
    ret
) do { \
        if ((x) == NULL) {          \
            return ret;             \
        }                           \
    } while(0)
```

### define `BSP_NULL_CHECK`

```c
#define BSP_NULL_CHECK (
    x,
    ret
) do { \
        if ((x) == NULL) {          \
            return ret;             \
        }                           \
    } while(0)
```

### define `BSP_NULL_CHECK_GOTO`

```c
#define BSP_NULL_CHECK_GOTO (
    x,
    goto_tag
) do { \
        if ((x) == NULL) {      \
            goto goto_tag;      \
        }                       \
    } while(0)
```




## File esp32_lyrat/priv_include/bsp_err_check.h


## Macros

| Type | Name |
| ---: | :--- |
| define  | [**BSP\_ERROR\_CHECK**](#define-bsp_error_check) (x, ret) <br> |
| define  | [**BSP\_ERROR\_CHECK\_RETURN\_ERR**](#define-bsp_error_check_return_err) (x) <br> |
| define  | [**BSP\_ERROR\_CHECK\_RETURN\_NULL**](#define-bsp_error_check_return_null) (x) <br> |
| define  | [**BSP\_NULL\_CHECK**](#define-bsp_null_check) (x, ret) <br> |
| define  | [**BSP\_NULL\_CHECK**](#define-bsp_null_check) (x, ret) <br> |
| define  | [**BSP\_NULL\_CHECK\_GOTO**](#define-bsp_null_check_goto) (x, goto\_tag) <br> |




## Macros Documentation

### define `BSP_ERROR_CHECK`

```c
#define BSP_ERROR_CHECK (
    x,
    ret
) do { \
        if (unlikely((x) != ESP_OK)) {    \
            return ret;                   \
        }                                 \
    } while(0)
```

### define `BSP_ERROR_CHECK_RETURN_ERR`

```c
#define BSP_ERROR_CHECK_RETURN_ERR (
    x
) do { \
        esp_err_t err_rc_ = (x);            \
        if (unlikely(err_rc_ != ESP_OK)) {  \
            return err_rc_;                 \
        }                                   \
    } while(0)
```

### define `BSP_ERROR_CHECK_RETURN_NULL`

```c
#define BSP_ERROR_CHECK_RETURN_NULL (
    x
) do { \
        if (unlikely((x) != ESP_OK)) {      \
            return NULL;                    \
        }                                   \
    } while(0)
```

### define `BSP_NULL_CHECK`

```c
#define BSP_NULL_CHECK (
    x,
    ret
) do { \
        if ((x) == NULL) {          \
            return ret;             \
        }                           \
    } while(0)
```

### define `BSP_NULL_CHECK`

```c
#define BSP_NULL_CHECK (
    x,
    ret
) do { \
        if ((x) == NULL) {          \
            return ret;             \
        }                           \
    } while(0)
```

### define `BSP_NULL_CHECK_GOTO`

```c
#define BSP_NULL_CHECK_GOTO (
    x,
    goto_tag
) do { \
        if ((x) == NULL) {      \
            goto goto_tag;      \
        }                       \
    } while(0)
```




## File esp32_s2_kaluga_kit/priv_include/bsp_err_check.h


## Macros

| Type | Name |
| ---: | :--- |
| define  | [**BSP\_ERROR\_CHECK**](#define-bsp_error_check) (x, ret) <br> |
| define  | [**BSP\_ERROR\_CHECK\_RETURN\_ERR**](#define-bsp_error_check_return_err) (x) <br> |
| define  | [**BSP\_ERROR\_CHECK\_RETURN\_NULL**](#define-bsp_error_check_return_null) (x) <br> |
| define  | [**BSP\_NULL\_CHECK**](#define-bsp_null_check) (x, ret) <br> |
| define  | [**BSP\_NULL\_CHECK**](#define-bsp_null_check) (x, ret) <br> |
| define  | [**BSP\_NULL\_CHECK\_GOTO**](#define-bsp_null_check_goto) (x, goto\_tag) <br> |




## Macros Documentation

### define `BSP_ERROR_CHECK`

```c
#define BSP_ERROR_CHECK (
    x,
    ret
) do { \
        if (unlikely((x) != ESP_OK)) {    \
            return ret;                   \
        }                                 \
    } while(0)
```

### define `BSP_ERROR_CHECK_RETURN_ERR`

```c
#define BSP_ERROR_CHECK_RETURN_ERR (
    x
) do { \
        esp_err_t err_rc_ = (x);            \
        if (unlikely(err_rc_ != ESP_OK)) {  \
            return err_rc_;                 \
        }                                   \
    } while(0)
```

### define `BSP_ERROR_CHECK_RETURN_NULL`

```c
#define BSP_ERROR_CHECK_RETURN_NULL (
    x
) do { \
        if (unlikely((x) != ESP_OK)) {      \
            return NULL;                    \
        }                                   \
    } while(0)
```

### define `BSP_NULL_CHECK`

```c
#define BSP_NULL_CHECK (
    x,
    ret
) do { \
        if ((x) == NULL) {          \
            return ret;             \
        }                           \
    } while(0)
```

### define `BSP_NULL_CHECK`

```c
#define BSP_NULL_CHECK (
    x,
    ret
) do { \
        if ((x) == NULL) {          \
            return ret;             \
        }                           \
    } while(0)
```

### define `BSP_NULL_CHECK_GOTO`

```c
#define BSP_NULL_CHECK_GOTO (
    x,
    goto_tag
) do { \
        if ((x) == NULL) {      \
            goto goto_tag;      \
        }                       \
    } while(0)
```




## File esp32_s3_eye/priv_include/bsp_err_check.h


## Macros

| Type | Name |
| ---: | :--- |
| define  | [**BSP\_ERROR\_CHECK**](#define-bsp_error_check) (x, ret) <br> |
| define  | [**BSP\_ERROR\_CHECK\_RETURN\_ERR**](#define-bsp_error_check_return_err) (x) <br> |
| define  | [**BSP\_ERROR\_CHECK\_RETURN\_NULL**](#define-bsp_error_check_return_null) (x) <br> |
| define  | [**BSP\_NULL\_CHECK**](#define-bsp_null_check) (x, ret) <br> |
| define  | [**BSP\_NULL\_CHECK**](#define-bsp_null_check) (x, ret) <br> |
| define  | [**BSP\_NULL\_CHECK\_GOTO**](#define-bsp_null_check_goto) (x, goto\_tag) <br> |




## Macros Documentation

### define `BSP_ERROR_CHECK`

```c
#define BSP_ERROR_CHECK (
    x,
    ret
) do { \
        if (unlikely((x) != ESP_OK)) {    \
            return ret;                   \
        }                                 \
    } while(0)
```

### define `BSP_ERROR_CHECK_RETURN_ERR`

```c
#define BSP_ERROR_CHECK_RETURN_ERR (
    x
) do { \
        esp_err_t err_rc_ = (x);            \
        if (unlikely(err_rc_ != ESP_OK)) {  \
            return err_rc_;                 \
        }                                   \
    } while(0)
```

### define `BSP_ERROR_CHECK_RETURN_NULL`

```c
#define BSP_ERROR_CHECK_RETURN_NULL (
    x
) do { \
        if (unlikely((x) != ESP_OK)) {      \
            return NULL;                    \
        }                                   \
    } while(0)
```

### define `BSP_NULL_CHECK`

```c
#define BSP_NULL_CHECK (
    x,
    ret
) do { \
        if ((x) == NULL) {          \
            return ret;             \
        }                           \
    } while(0)
```

### define `BSP_NULL_CHECK`

```c
#define BSP_NULL_CHECK (
    x,
    ret
) do { \
        if ((x) == NULL) {          \
            return ret;             \
        }                           \
    } while(0)
```

### define `BSP_NULL_CHECK_GOTO`

```c
#define BSP_NULL_CHECK_GOTO (
    x,
    goto_tag
) do { \
        if ((x) == NULL) {      \
            goto goto_tag;      \
        }                       \
    } while(0)
```




## File esp32_s3_korvo_2/priv_include/bsp_err_check.h


## Macros

| Type | Name |
| ---: | :--- |
| define  | [**BSP\_ERROR\_CHECK**](#define-bsp_error_check) (x, ret) <br> |
| define  | [**BSP\_ERROR\_CHECK\_RETURN\_ERR**](#define-bsp_error_check_return_err) (x) <br> |
| define  | [**BSP\_ERROR\_CHECK\_RETURN\_NULL**](#define-bsp_error_check_return_null) (x) <br> |
| define  | [**BSP\_NULL\_CHECK**](#define-bsp_null_check) (x, ret) <br> |
| define  | [**BSP\_NULL\_CHECK**](#define-bsp_null_check) (x, ret) <br> |
| define  | [**BSP\_NULL\_CHECK\_GOTO**](#define-bsp_null_check_goto) (x, goto\_tag) <br> |




## Macros Documentation

### define `BSP_ERROR_CHECK`

```c
#define BSP_ERROR_CHECK (
    x,
    ret
) do { \
        if (unlikely((x) != ESP_OK)) {    \
            return ret;                   \
        }                                 \
    } while(0)
```

### define `BSP_ERROR_CHECK_RETURN_ERR`

```c
#define BSP_ERROR_CHECK_RETURN_ERR (
    x
) do { \
        esp_err_t err_rc_ = (x);            \
        if (unlikely(err_rc_ != ESP_OK)) {  \
            return err_rc_;                 \
        }                                   \
    } while(0)
```

### define `BSP_ERROR_CHECK_RETURN_NULL`

```c
#define BSP_ERROR_CHECK_RETURN_NULL (
    x
) do { \
        if (unlikely((x) != ESP_OK)) {      \
            return NULL;                    \
        }                                   \
    } while(0)
```

### define `BSP_NULL_CHECK`

```c
#define BSP_NULL_CHECK (
    x,
    ret
) do { \
        if ((x) == NULL) {          \
            return ret;             \
        }                           \
    } while(0)
```

### define `BSP_NULL_CHECK`

```c
#define BSP_NULL_CHECK (
    x,
    ret
) do { \
        if ((x) == NULL) {          \
            return ret;             \
        }                           \
    } while(0)
```

### define `BSP_NULL_CHECK_GOTO`

```c
#define BSP_NULL_CHECK_GOTO (
    x,
    goto_tag
) do { \
        if ((x) == NULL) {      \
            goto goto_tag;      \
        }                       \
    } while(0)
```




## File esp32_s3_lcd_ev_board/priv_include/bsp_err_check.h


## Macros

| Type | Name |
| ---: | :--- |
| define  | [**BSP\_ERROR\_CHECK\_RETURN\_ERR**](#define-bsp_error_check_return_err) (x) <br> |
| define  | [**BSP\_ERROR\_CHECK\_RETURN\_NULL**](#define-bsp_error_check_return_null) (x) <br> |
| define  | [**BSP\_NULL\_CHECK**](#define-bsp_null_check) (x, ret) <br> |
| define  | [**BSP\_NULL\_CHECK\_GOTO**](#define-bsp_null_check_goto) (x, goto\_tag) <br> |




## Macros Documentation

### define `BSP_ERROR_CHECK_RETURN_ERR`

```c
#define BSP_ERROR_CHECK_RETURN_ERR (
    x
) do { \
        esp_err_t err_rc_ = (x);            \
        if (unlikely(err_rc_ != ESP_OK)) {  \
            return err_rc_;                 \
        }                                   \
    } while(0)
```

### define `BSP_ERROR_CHECK_RETURN_NULL`

```c
#define BSP_ERROR_CHECK_RETURN_NULL (
    x
) do { \
        if (unlikely((x) != ESP_OK)) {      \
            return NULL;                    \
        }                                   \
    } while(0)
```

### define `BSP_NULL_CHECK`

```c
#define BSP_NULL_CHECK (
    x,
    ret
) do { \
        if ((x) == NULL) {          \
            return ret;             \
        }                           \
    } while(0)
```

### define `BSP_NULL_CHECK_GOTO`

```c
#define BSP_NULL_CHECK_GOTO (
    x,
    goto_tag
) do { \
        if ((x) == NULL) {      \
            goto goto_tag;      \
        }                       \
    } while(0)
```




## File esp32_s3_usb_otg/priv_include/bsp_err_check.h


## Macros

| Type | Name |
| ---: | :--- |
| define  | [**BSP\_ERROR\_CHECK**](#define-bsp_error_check) (x, ret) <br> |
| define  | [**BSP\_ERROR\_CHECK\_RETURN\_ERR**](#define-bsp_error_check_return_err) (x) <br> |
| define  | [**BSP\_ERROR\_CHECK\_RETURN\_NULL**](#define-bsp_error_check_return_null) (x) <br> |
| define  | [**BSP\_NULL\_CHECK**](#define-bsp_null_check) (x, ret) <br> |
| define  | [**BSP\_NULL\_CHECK**](#define-bsp_null_check) (x, ret) <br> |
| define  | [**BSP\_NULL\_CHECK\_GOTO**](#define-bsp_null_check_goto) (x, goto\_tag) <br> |




## Macros Documentation

### define `BSP_ERROR_CHECK`

```c
#define BSP_ERROR_CHECK (
    x,
    ret
) do { \
        if (unlikely((x) != ESP_OK)) {    \
            return ret;                   \
        }                                 \
    } while(0)
```

### define `BSP_ERROR_CHECK_RETURN_ERR`

```c
#define BSP_ERROR_CHECK_RETURN_ERR (
    x
) do { \
        esp_err_t err_rc_ = (x);            \
        if (unlikely(err_rc_ != ESP_OK)) {  \
            return err_rc_;                 \
        }                                   \
    } while(0)
```

### define `BSP_ERROR_CHECK_RETURN_NULL`

```c
#define BSP_ERROR_CHECK_RETURN_NULL (
    x
) do { \
        if (unlikely((x) != ESP_OK)) {      \
            return NULL;                    \
        }                                   \
    } while(0)
```

### define `BSP_NULL_CHECK`

```c
#define BSP_NULL_CHECK (
    x,
    ret
) do { \
        if ((x) == NULL) {          \
            return ret;             \
        }                           \
    } while(0)
```

### define `BSP_NULL_CHECK`

```c
#define BSP_NULL_CHECK (
    x,
    ret
) do { \
        if ((x) == NULL) {          \
            return ret;             \
        }                           \
    } while(0)
```

### define `BSP_NULL_CHECK_GOTO`

```c
#define BSP_NULL_CHECK_GOTO (
    x,
    goto_tag
) do { \
        if ((x) == NULL) {      \
            goto goto_tag;      \
        }                       \
    } while(0)
```




## File esp_wrover_kit/priv_include/bsp_err_check.h


## Macros

| Type | Name |
| ---: | :--- |
| define  | [**BSP\_ERROR\_CHECK**](#define-bsp_error_check) (x, ret) <br> |
| define  | [**BSP\_ERROR\_CHECK\_RETURN\_ERR**](#define-bsp_error_check_return_err) (x) <br> |
| define  | [**BSP\_ERROR\_CHECK\_RETURN\_NULL**](#define-bsp_error_check_return_null) (x) <br> |
| define  | [**BSP\_NULL\_CHECK**](#define-bsp_null_check) (x, ret) <br> |
| define  | [**BSP\_NULL\_CHECK**](#define-bsp_null_check) (x, ret) <br> |
| define  | [**BSP\_NULL\_CHECK\_GOTO**](#define-bsp_null_check_goto) (x, goto\_tag) <br> |




## Macros Documentation

### define `BSP_ERROR_CHECK`

```c
#define BSP_ERROR_CHECK (
    x,
    ret
) do { \
        if (unlikely((x) != ESP_OK)) {    \
            return ret;                   \
        }                                 \
    } while(0)
```

### define `BSP_ERROR_CHECK_RETURN_ERR`

```c
#define BSP_ERROR_CHECK_RETURN_ERR (
    x
) do { \
        esp_err_t err_rc_ = (x);            \
        if (unlikely(err_rc_ != ESP_OK)) {  \
            return err_rc_;                 \
        }                                   \
    } while(0)
```

### define `BSP_ERROR_CHECK_RETURN_NULL`

```c
#define BSP_ERROR_CHECK_RETURN_NULL (
    x
) do { \
        if (unlikely((x) != ESP_OK)) {      \
            return NULL;                    \
        }                                   \
    } while(0)
```

### define `BSP_NULL_CHECK`

```c
#define BSP_NULL_CHECK (
    x,
    ret
) do { \
        if ((x) == NULL) {          \
            return ret;             \
        }                           \
    } while(0)
```

### define `BSP_NULL_CHECK`

```c
#define BSP_NULL_CHECK (
    x,
    ret
) do { \
        if ((x) == NULL) {          \
            return ret;             \
        }                           \
    } while(0)
```

### define `BSP_NULL_CHECK_GOTO`

```c
#define BSP_NULL_CHECK_GOTO (
    x,
    goto_tag
) do { \
        if ((x) == NULL) {      \
            goto goto_tag;      \
        }                       \
    } while(0)
```




## File esp32_s3_korvo_2/include/bsp/esp32_s3_korvo_2.h


## Macros

| Type | Name |
| ---: | :--- |
| define  | [**BSP\_BATTERY\_VOLTAGE**](#define-bsp_battery_voltage)  (GPIO\_NUM\_6)<br> |
| define  | [**BSP\_BATTERY\_VOLTAGE\_DIV**](#define-bsp_battery_voltage_div)  (4)<br> |
| define  | [**BSP\_BUTTONS\_IO**](#define-bsp_buttons_io)  (GPIO\_NUM\_5)<br> |
| define  | [**BSP\_CAMERA\_D0**](#define-bsp_camera_d0)  (GPIO\_NUM\_13)<br> |
| define  | [**BSP\_CAMERA\_D1**](#define-bsp_camera_d1)  (GPIO\_NUM\_47)<br> |
| define  | [**BSP\_CAMERA\_D2**](#define-bsp_camera_d2)  (GPIO\_NUM\_14)<br> |
| define  | [**BSP\_CAMERA\_D3**](#define-bsp_camera_d3)  (GPIO\_NUM\_3)<br> |
| define  | [**BSP\_CAMERA\_D4**](#define-bsp_camera_d4)  (GPIO\_NUM\_12)<br> |
| define  | [**BSP\_CAMERA\_D5**](#define-bsp_camera_d5)  (GPIO\_NUM\_42)<br> |
| define  | [**BSP\_CAMERA\_D6**](#define-bsp_camera_d6)  (GPIO\_NUM\_41)<br> |
| define  | [**BSP\_CAMERA\_D7**](#define-bsp_camera_d7)  (GPIO\_NUM\_39)<br> |
| define  | [**BSP\_CAMERA\_DEFAULT\_CONFIG**](#define-bsp_camera_default_config)  <br>_ESP32-S3-Korvo-2 camera default configuration._ |
| define  | [**BSP\_CAMERA\_HSYNC**](#define-bsp_camera_hsync)  (GPIO\_NUM\_38)<br> |
| define  | [**BSP\_CAMERA\_PCLK**](#define-bsp_camera_pclk)  (GPIO\_NUM\_11)<br> |
| define  | [**BSP\_CAMERA\_VSYNC**](#define-bsp_camera_vsync)  (GPIO\_NUM\_21)<br> |
| define  | [**BSP\_CAMERA\_XCLK**](#define-bsp_camera_xclk)  (GPIO\_NUM\_40)<br> |
| define  | [**BSP\_I2C\_NUM**](#define-bsp_i2c_num)  CONFIG\_BSP\_I2C\_NUM<br> |
| define  | [**BSP\_I2C\_SCL**](#define-bsp_i2c_scl)  (GPIO\_NUM\_18)<br> |
| define  | [**BSP\_I2C\_SDA**](#define-bsp_i2c_sda)  (GPIO\_NUM\_17)<br> |
| define  | [**BSP\_I2S\_DOUT**](#define-bsp_i2s_dout)  (GPIO\_NUM\_8)<br> |
| define  | [**BSP\_I2S\_DSIN**](#define-bsp_i2s_dsin)  (GPIO\_NUM\_10)<br> |
| define  | [**BSP\_I2S\_LCLK**](#define-bsp_i2s_lclk)  (GPIO\_NUM\_45)<br> |
| define  | [**BSP\_I2S\_MCLK**](#define-bsp_i2s_mclk)  (GPIO\_NUM\_16)<br> |
| define  | [**BSP\_I2S\_SCLK**](#define-bsp_i2s_sclk)  (GPIO\_NUM\_9)<br> |
| define  | [**BSP\_IO\_EXPANDER\_I2C\_ADDRESS**](#define-bsp_io_expander_i2c_address)  ([**ESP\_IO\_EXPANDER\_I2C\_TCA9554A\_ADDRESS\_000**](#define-esp_io_expander_i2c_tca9554a_address_000))<br> |
| define  | [**BSP\_LCD\_BACKLIGHT**](#define-bsp_lcd_backlight)  (GPIO\_NUM\_NC)<br> |
| define  | [**BSP\_LCD\_CS**](#define-bsp_lcd_cs)  (GPIO\_NUM\_NC)<br> |
| define  | [**BSP\_LCD\_DATA0**](#define-bsp_lcd_data0)  (GPIO\_NUM\_0)<br> |
| define  | [**BSP\_LCD\_DC**](#define-bsp_lcd_dc)  (GPIO\_NUM\_2)<br> |
| define  | [**BSP\_LCD\_DRAW\_BUFF\_DOUBLE**](#define-bsp_lcd_draw_buff_double)  (1)<br> |
| define  | [**BSP\_LCD\_DRAW\_BUFF\_SIZE**](#define-bsp_lcd_draw_buff_size)  (BSP\_LCD\_H\_RES \* 50)<br> |
| define  | [**BSP\_LCD\_H\_RES**](#define-bsp_lcd_h_res)  (320)<br> |
| define  | [**BSP\_LCD\_IO\_BACKLIGHT**](#define-bsp_lcd_io_backlight)  (IO\_EXPANDER\_PIN\_NUM\_1)<br> |
| define  | [**BSP\_LCD\_IO\_CS**](#define-bsp_lcd_io_cs)  (IO\_EXPANDER\_PIN\_NUM\_3)<br> |
| define  | [**BSP\_LCD\_IO\_RST**](#define-bsp_lcd_io_rst)  (IO\_EXPANDER\_PIN\_NUM\_2)<br> |
| define  | [**BSP\_LCD\_PCLK**](#define-bsp_lcd_pclk)  (GPIO\_NUM\_1)<br> |
| define  | [**BSP\_LCD\_PIXEL\_CLOCK\_HZ**](#define-bsp_lcd_pixel_clock_hz)  (40 \* 1000 \* 1000)<br> |
| define  | [**BSP\_LCD\_RST**](#define-bsp_lcd_rst)  (GPIO\_NUM\_NC)<br> |
| define  | [**BSP\_LCD\_SPI\_NUM**](#define-bsp_lcd_spi_num)  (SPI3\_HOST)<br> |
| define  | [**BSP\_LCD\_TOUCH\_INT**](#define-bsp_lcd_touch_int)  (GPIO\_NUM\_NC)<br> |
| define  | [**BSP\_LCD\_V\_RES**](#define-bsp_lcd_v_res)  (240)<br> |
| define  | [**BSP\_MOUNT\_POINT**](#define-bsp_mount_point)  CONFIG\_BSP\_SD\_MOUNT\_POINT<br> |
| define  | [**BSP\_POWER\_AMP\_IO**](#define-bsp_power_amp_io)  (GPIO\_NUM\_48)<br> |
| define  | [**BSP\_SD\_CLK**](#define-bsp_sd_clk)  (GPIO\_NUM\_15)<br> |
| define  | [**BSP\_SD\_CMD**](#define-bsp_sd_cmd)  (GPIO\_NUM\_7)<br> |
| define  | [**BSP\_SD\_D0**](#define-bsp_sd_d0)  (GPIO\_NUM\_4)<br> |
| define  | [**BSP\_SPIFFS\_MOUNT\_POINT**](#define-bsp_spiffs_mount_point)  CONFIG\_BSP\_SPIFFS\_MOUNT\_POINT<br> |

## Types

| Type | Name |
| ---: | :--- |
| enum  | [**bsp\_button\_t**](#enum-bsp_button_t)  <br> |
| enum  | [**bsp\_led\_t**](#enum-bsp_led_t)  <br> |
| typedef enum bsp\_led\_t | [**bsp\_led\_t**](#typedef-bsp_led_t)  <br> |

## Functions

| Type | Name |
| ---: | :--- |
|  esp\_codec\_dev\_handle\_t | [**bsp\_audio\_codec\_microphone\_init**](#function-bsp_audio_codec_microphone_init) (void) <br>_Initialize microphone codec device._ |
|  esp\_codec\_dev\_handle\_t | [**bsp\_audio\_codec\_speaker\_init**](#function-bsp_audio_codec_speaker_init) (void) <br>_Initialize speaker codec device._ |
|  bool | [**bsp\_button\_get**](#function-bsp_button_get) (const bsp\_button\_t btn) <br>_Get button's state._ |
|  esp\_err\_t | [**bsp\_button\_init**](#function-bsp_button_init) (const bsp\_button\_t btn) <br>_Set button's GPIO as input._ |
|  esp\_err\_t | [**bsp\_display\_backlight\_off**](#function-bsp_display_backlight_off) (void) <br>_Turn off display backlight._ |
|  esp\_err\_t | [**bsp\_display\_backlight\_on**](#function-bsp_display_backlight_on) (void) <br>_Turn on display backlight._ |
|  esp\_err\_t | [**bsp\_display\_brightness\_set**](#function-bsp_display_brightness_set) (int brightness\_percent) <br>_Set display's brightness._ |
|  lv\_indev\_t \* | [**bsp\_display\_get\_input\_dev**](#function-bsp_display_get_input_dev) (void) <br>_Get pointer to input device (touch, buttons, ...)_ |
|  bool | [**bsp\_display\_lock**](#function-bsp_display_lock) (uint32\_t timeout\_ms) <br>_Take LVGL mutex._ |
|  void | [**bsp\_display\_rotate**](#function-bsp_display_rotate) (lv\_disp\_t \* disp, lv\_disp\_rot\_t rotation) <br>_Rotate screen._ |
|  lv\_disp\_t \* | [**bsp\_display\_start**](#function-bsp_display_start) (void) <br>_Initialize display._ |
|  void | [**bsp\_display\_unlock**](#function-bsp_display_unlock) (void) <br>_Give LVGL mutex._ |
|  esp\_err\_t | [**bsp\_i2c\_deinit**](#function-bsp_i2c_deinit) (void) <br>_Deinit I2C driver and free its resources._ |
|  esp\_err\_t | [**bsp\_i2c\_init**](#function-bsp_i2c_init) (void) <br>_Init I2C driver._ |
|   | [**bsp\_io\_expander\_init**](#function-bsp_io_expander_init) (void) <br>_Init IO expander chip TCA9554._ |
|  esp\_err\_t | [**bsp\_iot\_button\_create**](#function-bsp_iot_button_create) (button\_handle\_t btn\_array, int \* btn\_cnt, int btn\_array\_size) <br>_Initialize all buttons._ |
|  esp\_err\_t | [**bsp\_led\_set**](#function-bsp_led_set) (const bsp\_led\_t led\_io, const bool on) <br>_Turn LED on/off._ |
|  esp\_err\_t | [**bsp\_leds\_init**](#function-bsp_leds_init) (void) <br>_Set LED's GPIOs as output push-pull._ |
|  esp\_err\_t | [**bsp\_sdcard\_mount**](#function-bsp_sdcard_mount) (void) <br>_Mount microSD card to virtual file system._ |
|  esp\_err\_t | [**bsp\_sdcard\_unmount**](#function-bsp_sdcard_unmount) (void) <br>_Unmount microSD card from virtual file system._ |
|  esp\_err\_t | [**bsp\_spiffs\_mount**](#function-bsp_spiffs_mount) (void) <br>_Mount SPIFFS to virtual file system._ |
|  esp\_err\_t | [**bsp\_spiffs\_unmount**](#function-bsp_spiffs_unmount) (void) <br>_Unmount SPIFFS from virtual file system._ |
|  int | [**bsp\_voltage\_battery\_get**](#function-bsp_voltage_battery_get) (void) <br>_Get battery voltage._ |
|  esp\_err\_t | [**bsp\_voltage\_init**](#function-bsp_voltage_init) (void) <br>_Init voltage measurements._ |


## Macros Documentation

### define `BSP_BATTERY_VOLTAGE`

```c
#define BSP_BATTERY_VOLTAGE (GPIO_NUM_6)
```

### define `BSP_BATTERY_VOLTAGE_DIV`

```c
#define BSP_BATTERY_VOLTAGE_DIV (4)
```

### define `BSP_BUTTONS_IO`

```c
#define BSP_BUTTONS_IO (GPIO_NUM_5)
```

### define `BSP_CAMERA_D0`

```c
#define BSP_CAMERA_D0 (GPIO_NUM_13)
```

### define `BSP_CAMERA_D1`

```c
#define BSP_CAMERA_D1 (GPIO_NUM_47)
```

### define `BSP_CAMERA_D2`

```c
#define BSP_CAMERA_D2 (GPIO_NUM_14)
```

### define `BSP_CAMERA_D3`

```c
#define BSP_CAMERA_D3 (GPIO_NUM_3)
```

### define `BSP_CAMERA_D4`

```c
#define BSP_CAMERA_D4 (GPIO_NUM_12)
```

### define `BSP_CAMERA_D5`

```c
#define BSP_CAMERA_D5 (GPIO_NUM_42)
```

### define `BSP_CAMERA_D6`

```c
#define BSP_CAMERA_D6 (GPIO_NUM_41)
```

### define `BSP_CAMERA_D7`

```c
#define BSP_CAMERA_D7 (GPIO_NUM_39)
```

### define `BSP_CAMERA_DEFAULT_CONFIG`

```c
#define BSP_CAMERA_DEFAULT_CONFIG {                                     \
        .pin_pwdn = GPIO_NUM_NC,          \
        .pin_reset = GPIO_NUM_NC,         \
        .pin_xclk = BSP_CAMERA_XCLK,      \
        .pin_sccb_sda = GPIO_NUM_NC,      \
        .pin_sccb_scl = GPIO_NUM_NC,      \
        .pin_d7 = BSP_CAMERA_D7 ,          \
        .pin_d6 = BSP_CAMERA_D6 ,          \
        .pin_d5 = BSP_CAMERA_D5 ,          \
        .pin_d4 = BSP_CAMERA_D4 ,          \
        .pin_d3 = BSP_CAMERA_D3 ,          \
        .pin_d2 = BSP_CAMERA_D2 ,          \
        .pin_d1 = BSP_CAMERA_D1 ,          \
        .pin_d0 = BSP_CAMERA_D0 ,          \
        .pin_vsync = BSP_CAMERA_VSYNC,    \
        .pin_href = BSP_CAMERA_HSYNC,     \
        .pin_pclk = BSP_CAMERA_PCLK,      \
        .xclk_freq_hz = 16000000,         \
        .ledc_timer = LEDC_TIMER_0,       \
        .ledc_channel = LEDC_CHANNEL_0,   \
        .pixel_format = PIXFORMAT_RGB565, \
        .frame_size = FRAMESIZE_240X240,  \
        .jpeg_quality = 12,               \
        .fb_count = 2,                    \
        .fb_location = CAMERA_FB_IN_PSRAM,\
        .sccb_i2c_port = BSP_I2C_NUM,     \
    }
```

### define `BSP_CAMERA_HSYNC`

```c
#define BSP_CAMERA_HSYNC (GPIO_NUM_38)
```

### define `BSP_CAMERA_PCLK`

```c
#define BSP_CAMERA_PCLK (GPIO_NUM_11)
```

### define `BSP_CAMERA_VSYNC`

```c
#define BSP_CAMERA_VSYNC (GPIO_NUM_21)
```

### define `BSP_CAMERA_XCLK`

```c
#define BSP_CAMERA_XCLK (GPIO_NUM_40)
```

### define `BSP_I2C_NUM`

```c
#define BSP_I2C_NUM CONFIG_BSP_I2C_NUM
```

### define `BSP_I2C_SCL`

```c
#define BSP_I2C_SCL (GPIO_NUM_18)
```

### define `BSP_I2C_SDA`

```c
#define BSP_I2C_SDA (GPIO_NUM_17)
```

### define `BSP_I2S_DOUT`

```c
#define BSP_I2S_DOUT (GPIO_NUM_8)
```

### define `BSP_I2S_DSIN`

```c
#define BSP_I2S_DSIN (GPIO_NUM_10)
```

### define `BSP_I2S_LCLK`

```c
#define BSP_I2S_LCLK (GPIO_NUM_45)
```

### define `BSP_I2S_MCLK`

```c
#define BSP_I2S_MCLK (GPIO_NUM_16)
```

### define `BSP_I2S_SCLK`

```c
#define BSP_I2S_SCLK (GPIO_NUM_9)
```

### define `BSP_IO_EXPANDER_I2C_ADDRESS`

```c
#define BSP_IO_EXPANDER_I2C_ADDRESS ( ESP_IO_EXPANDER_I2C_TCA9554A_ADDRESS_000 )
```

### define `BSP_LCD_BACKLIGHT`

```c
#define BSP_LCD_BACKLIGHT (GPIO_NUM_NC)
```

### define `BSP_LCD_CS`

```c
#define BSP_LCD_CS (GPIO_NUM_NC)
```

### define `BSP_LCD_DATA0`

```c
#define BSP_LCD_DATA0 (GPIO_NUM_0)
```

### define `BSP_LCD_DC`

```c
#define BSP_LCD_DC (GPIO_NUM_2)
```

### define `BSP_LCD_DRAW_BUFF_DOUBLE`

```c
#define BSP_LCD_DRAW_BUFF_DOUBLE (1)
```

### define `BSP_LCD_DRAW_BUFF_SIZE`

```c
#define BSP_LCD_DRAW_BUFF_SIZE (BSP_LCD_H_RES * 50)
```

### define `BSP_LCD_H_RES`

```c
#define BSP_LCD_H_RES (320)
```

### define `BSP_LCD_IO_BACKLIGHT`

```c
#define BSP_LCD_IO_BACKLIGHT (IO_EXPANDER_PIN_NUM_1)
```

### define `BSP_LCD_IO_CS`

```c
#define BSP_LCD_IO_CS (IO_EXPANDER_PIN_NUM_3)
```

### define `BSP_LCD_IO_RST`

```c
#define BSP_LCD_IO_RST (IO_EXPANDER_PIN_NUM_2)
```

### define `BSP_LCD_PCLK`

```c
#define BSP_LCD_PCLK (GPIO_NUM_1)
```

### define `BSP_LCD_PIXEL_CLOCK_HZ`

```c
#define BSP_LCD_PIXEL_CLOCK_HZ (40 * 1000 * 1000)
```

### define `BSP_LCD_RST`

```c
#define BSP_LCD_RST (GPIO_NUM_NC)
```

### define `BSP_LCD_SPI_NUM`

```c
#define BSP_LCD_SPI_NUM (SPI3_HOST)
```

### define `BSP_LCD_TOUCH_INT`

```c
#define BSP_LCD_TOUCH_INT (GPIO_NUM_NC)
```

### define `BSP_LCD_V_RES`

```c
#define BSP_LCD_V_RES (240)
```

### define `BSP_MOUNT_POINT`

```c
#define BSP_MOUNT_POINT CONFIG_BSP_SD_MOUNT_POINT
```

### define `BSP_POWER_AMP_IO`

```c
#define BSP_POWER_AMP_IO (GPIO_NUM_48)
```

### define `BSP_SD_CLK`

```c
#define BSP_SD_CLK (GPIO_NUM_15)
```

### define `BSP_SD_CMD`

```c
#define BSP_SD_CMD (GPIO_NUM_7)
```

### define `BSP_SD_D0`

```c
#define BSP_SD_D0 (GPIO_NUM_4)
```

### define `BSP_SPIFFS_MOUNT_POINT`

```c
#define BSP_SPIFFS_MOUNT_POINT CONFIG_BSP_SPIFFS_MOUNT_POINT
```


## Types Documentation

### enum `bsp_button_t`

```c
enum bsp_button_t {
    BSP_BUTTON_REC = 0,
    BSP_BUTTON_MUTE,
    BSP_BUTTON_PLAY,
    BSP_BUTTON_SET,
    BSP_BUTTON_VOLDOWN,
    BSP_BUTTON_VOLUP,
    BSP_BUTTON_MAIN,
    BSP_BUTTON_NUM
};
```

### enum `bsp_led_t`

```c
enum bsp_led_t {
    BSP_LED_BLUE = IO_EXPANDER_PIN_NUM_6,
    BSP_LED_RED = IO_EXPANDER_PIN_NUM_7
};
```

### typedef `bsp_led_t`

```c
typedef enum bsp_led_t bsp_led_t;
```


## Functions Documentation

### function `bsp_audio_codec_microphone_init`

```c
esp_codec_dev_handle_t bsp_audio_codec_microphone_init (
    void
) 
```

### function `bsp_audio_codec_speaker_init`

```c
esp_codec_dev_handle_t bsp_audio_codec_speaker_init (
    void
) 
```

### function `bsp_button_get`

```c
bool bsp_button_get (
    const bsp_button_t btn
) 
```

### function `bsp_button_init`

```c
esp_err_t bsp_button_init (
    const bsp_button_t btn
) 
```

### function `bsp_display_backlight_off`

```c
esp_err_t bsp_display_backlight_off (
    void
) 
```

### function `bsp_display_backlight_on`

```c
esp_err_t bsp_display_backlight_on (
    void
) 
```

### function `bsp_display_brightness_set`

```c
esp_err_t bsp_display_brightness_set (
    int brightness_percent
) 
```

### function `bsp_display_get_input_dev`

```c
lv_indev_t * bsp_display_get_input_dev (
    void
) 
```

### function `bsp_display_lock`

```c
bool bsp_display_lock (
    uint32_t timeout_ms
) 
```

### function `bsp_display_rotate`

```c
void bsp_display_rotate (
    lv_disp_t * disp,
    lv_disp_rot_t rotation
) 
```

### function `bsp_display_start`

```c
lv_disp_t * bsp_display_start (
    void
) 
```

### function `bsp_display_unlock`

```c
void bsp_display_unlock (
    void
) 
```

### function `bsp_i2c_deinit`

```c
esp_err_t bsp_i2c_deinit (
    void
) 
```

### function `bsp_i2c_init`

```c
esp_err_t bsp_i2c_init (
    void
) 
```

### function `bsp_io_expander_init`

```c
esp_io_expander_handle_t bsp_io_expander_init (
    void
) 
```

### function `bsp_iot_button_create`

```c
esp_err_t bsp_iot_button_create (
    button_handle_t btn_array,
    int * btn_cnt,
    int btn_array_size
) 
```

### function `bsp_led_set`

```c
esp_err_t bsp_led_set (
    const bsp_led_t led_io,
    const bool on
) 
```

### function `bsp_leds_init`

```c
esp_err_t bsp_leds_init (
    void
) 
```

### function `bsp_sdcard_mount`

```c
esp_err_t bsp_sdcard_mount (
    void
) 
```

### function `bsp_sdcard_unmount`

```c
esp_err_t bsp_sdcard_unmount (
    void
) 
```

### function `bsp_spiffs_mount`

```c
esp_err_t bsp_spiffs_mount (
    void
) 
```

### function `bsp_spiffs_unmount`

```c
esp_err_t bsp_spiffs_unmount (
    void
) 
```

### function `bsp_voltage_battery_get`

```c
int bsp_voltage_battery_get (
    void
) 
```

### function `bsp_voltage_init`

```c
esp_err_t bsp_voltage_init (
    void
) 
```


## File esp32_s3_lcd_ev_board/include/bsp/esp32_s3_lcd_ev_board.h


## Macros

| Type | Name |
| ---: | :--- |
| define  | [**BSP\_ES8311\_SCLK\_CONFIG**](#define-bsp_es8311_sclk_config) (\_sample\_rate) <br>_ES8311 init structure._ |
| define  | [**BSP\_I2C\_NUM**](#define-bsp_i2c_num)  (CONFIG\_BSP\_I2C\_NUM)<br> |
| define  | [**BSP\_I2C\_SCL**](#define-bsp_i2c_scl)  (GPIO\_NUM\_18)<br> |
| define  | [**BSP\_I2C\_SDA**](#define-bsp_i2c_sda)  (GPIO\_NUM\_8)<br> |
| define  | [**BSP\_I2S\_DOUT**](#define-bsp_i2s_dout)  (GPIO\_NUM\_6)<br> |
| define  | [**BSP\_I2S\_DSIN**](#define-bsp_i2s_dsin)  (GPIO\_NUM\_15)<br> |
| define  | [**BSP\_I2S\_DUPLEX\_MONO\_CFG**](#define-bsp_i2s_duplex_mono_cfg) (\_sample\_rate) <br>_Mono Duplex I2S configuration structure._ |
| define  | [**BSP\_I2S\_GPIO\_CFG**](#define-bsp_i2s_gpio_cfg)  <br>_ESP32-S3-LCD-EV-BOARD I2S pinout._ |
| define  | [**BSP\_I2S\_LCLK**](#define-bsp_i2s_lclk)  (GPIO\_NUM\_7)<br> |
| define  | [**BSP\_I2S\_MCLK**](#define-bsp_i2s_mclk)  (GPIO\_NUM\_5)<br> |
| define  | [**BSP\_I2S\_SCLK**](#define-bsp_i2s_sclk)  (GPIO\_NUM\_16)<br> |
| define  | [**BSP\_IO\_EXPANDER\_I2C\_ADDRESS**](#define-bsp_io_expander_i2c_address)  ([**ESP\_IO\_EXPANDER\_I2C\_TCA9554\_ADDRESS\_000**](#define-esp_io_expander_i2c_tca9554_address_000))<br> |
| define  | [**BSP\_POWER\_AMP\_IO**](#define-bsp_power_amp_io)  (IO\_EXPANDER\_PIN\_NUM\_0)<br> |
| define  | [**BSP\_USB\_NEG**](#define-bsp_usb_neg)  (USBPHY\_DM\_NUM)<br> |
| define  | [**BSP\_USB\_POS**](#define-bsp_usb_pos)  (USBPHY\_DP\_NUM)<br> |
| define  | [**LVGL\_BUFFER\_HEIGHT**](#define-lvgl_buffer_height)  (CONFIG\_BSP\_DISPLAY\_LVGL\_BUF\_HEIGHT)<br> |
| define  | [**LVGL\_BUFFER\_MALLOC**](#define-lvgl_buffer_malloc)  (MALLOC\_CAP\_INTERNAL | MALLOC\_CAP\_8BIT)<br> |
| define  | [**LVGL\_TICK\_PERIOD\_MS**](#define-lvgl_tick_period_ms)  (CONFIG\_BSP\_DISPLAY\_LVGL\_TICK)<br> |

## Types

| Type | Name |
| ---: | :--- |
| enum  | [**bsp\_button\_t**](#enum-bsp_button_t)  <br> |

## Functions

| Type | Name |
| ---: | :--- |
|  esp\_err\_t | [**bsp\_audio\_init**](#function-bsp_audio_init) (const i2s\_std\_config\_t \* i2s\_config, i2s\_chan\_handle\_t \* tx\_channel, i2s\_chan\_handle\_t \* rx\_channel) <br>_Init audio._ |
|  esp\_err\_t | [**bsp\_audio\_poweramp\_enable**](#function-bsp_audio_poweramp_enable) (const bool enable) <br>_Enable/disable audio power amplifier._ |
|  bool | [**bsp\_button\_get**](#function-bsp_button_get) (const bsp\_button\_t btn) <br>_Get button's state._ |
|  esp\_err\_t | [**bsp\_button\_init**](#function-bsp_button_init) (const bsp\_button\_t btn) <br>_Set button's GPIO as input._ |
|  esp\_err\_t | [**bsp\_display\_backlight\_off**](#function-bsp_display_backlight_off) (void) <br>_Turn off display backlight (Useless, just for compatibility)_ |
|  esp\_err\_t | [**bsp\_display\_backlight\_on**](#function-bsp_display_backlight_on) (void) <br>_Turn on display backlight (Useless, just for compatibility)_ |
|  esp\_err\_t | [**bsp\_display\_brightness\_set**](#function-bsp_display_brightness_set) (int brightness\_percent) <br>_Set display's brightness (Useless, just for compatibility)_ |
|  lv\_indev\_t \* | [**bsp\_display\_get\_input\_dev**](#function-bsp_display_get_input_dev) (void) <br>_Get pointer to input device (touch, buttons, ...)_ |
|  bool | [**bsp\_display\_lock**](#function-bsp_display_lock) (uint32\_t timeout\_ms) <br>_Take LVGL mutex._ |
|  void | [**bsp\_display\_rotate**](#function-bsp_display_rotate) (lv\_disp\_t \* disp, lv\_disp\_rot\_t rotation) <br>_Rotate screen._ |
|  lv\_disp\_t \* | [**bsp\_display\_start**](#function-bsp_display_start) (void) <br>_Initialize display._ |
|  void | [**bsp\_display\_unlock**](#function-bsp_display_unlock) (void) <br>_Give LVGL mutex._ |
|  esp\_err\_t | [**bsp\_i2c\_deinit**](#function-bsp_i2c_deinit) (void) <br>_Deinit I2C driver and free its resources._ |
|  esp\_err\_t | [**bsp\_i2c\_init**](#function-bsp_i2c_init) (void) <br>_Init I2C driver._ |
|   | [**bsp\_io\_expander\_init**](#function-bsp_io_expander_init) (void) <br>_Init IO expander chip TCA9554._ |


## Macros Documentation

### define `BSP_ES8311_SCLK_CONFIG`

```c
#define BSP_ES8311_SCLK_CONFIG (
    _sample_rate
) {                                        \
        .mclk_from_mclk_pin = false,         \
        .mclk_inverted = false,              \
        .sclk_inverted = false,              \
        .sample_frequency = _sample_rate     \
    }
```

### define `BSP_I2C_NUM`

```c
#define BSP_I2C_NUM (CONFIG_BSP_I2C_NUM)
```

### define `BSP_I2C_SCL`

```c
#define BSP_I2C_SCL (GPIO_NUM_18)
```

### define `BSP_I2C_SDA`

```c
#define BSP_I2C_SDA (GPIO_NUM_8)
```

### define `BSP_I2S_DOUT`

```c
#define BSP_I2S_DOUT (GPIO_NUM_6)
```

### define `BSP_I2S_DSIN`

```c
#define BSP_I2S_DSIN (GPIO_NUM_15)
```

### define `BSP_I2S_DUPLEX_MONO_CFG`

```c
#define BSP_I2S_DUPLEX_MONO_CFG (
    _sample_rate
) {                                                                                                 \
        .clk_cfg = I2S_STD_CLK_DEFAULT_CONFIG(_sample_rate),                                          \
        .slot_cfg = I2S_STD_PHILIP_SLOT_DEFAULT_CONFIG(I2S_DATA_BIT_WIDTH_16BIT, I2S_SLOT_MODE_MONO), \
        .gpio_cfg = BSP_I2S_GPIO_CFG ,                                                                 \
    }
```

### define `BSP_I2S_GPIO_CFG`

```c
#define BSP_I2S_GPIO_CFG {                          \
        .mclk = BSP_I2S_MCLK,  \
        .bclk = BSP_I2S_SCLK,  \
        .ws = BSP_I2S_LCLK,    \
        .dout = BSP_I2S_DOUT,  \
        .din = BSP_I2S_DSIN,   \
        .invert_flags = {      \
            .mclk_inv = false, \
            .bclk_inv = false, \
            .ws_inv = false,   \
        },                     \
    }
```

### define `BSP_I2S_LCLK`

```c
#define BSP_I2S_LCLK (GPIO_NUM_7)
```

### define `BSP_I2S_MCLK`

```c
#define BSP_I2S_MCLK (GPIO_NUM_5)
```

### define `BSP_I2S_SCLK`

```c
#define BSP_I2S_SCLK (GPIO_NUM_16)
```

### define `BSP_IO_EXPANDER_I2C_ADDRESS`

```c
#define BSP_IO_EXPANDER_I2C_ADDRESS ( ESP_IO_EXPANDER_I2C_TCA9554_ADDRESS_000 )
```

### define `BSP_POWER_AMP_IO`

```c
#define BSP_POWER_AMP_IO (IO_EXPANDER_PIN_NUM_0)
```

### define `BSP_USB_NEG`

```c
#define BSP_USB_NEG (USBPHY_DM_NUM)
```

### define `BSP_USB_POS`

```c
#define BSP_USB_POS (USBPHY_DP_NUM)
```

### define `LVGL_BUFFER_HEIGHT`

```c
#define LVGL_BUFFER_HEIGHT (CONFIG_BSP_DISPLAY_LVGL_BUF_HEIGHT)
```

### define `LVGL_BUFFER_MALLOC`

```c
#define LVGL_BUFFER_MALLOC (MALLOC_CAP_INTERNAL | MALLOC_CAP_8BIT)
```

### define `LVGL_TICK_PERIOD_MS`

```c
#define LVGL_TICK_PERIOD_MS (CONFIG_BSP_DISPLAY_LVGL_TICK)
```


## Types Documentation

### enum `bsp_button_t`

```c
enum bsp_button_t {
    BSP_BUTTON_BOOT = GPIO_NUM_0
};
```


## Functions Documentation

### function `bsp_audio_init`

```c
esp_err_t bsp_audio_init (
    const i2s_std_config_t * i2s_config,
    i2s_chan_handle_t * tx_channel,
    i2s_chan_handle_t * rx_channel
) 
```

### function `bsp_audio_poweramp_enable`

```c
esp_err_t bsp_audio_poweramp_enable (
    const bool enable
) 
```

### function `bsp_button_get`

```c
bool bsp_button_get (
    const bsp_button_t btn
) 
```

### function `bsp_button_init`

```c
esp_err_t bsp_button_init (
    const bsp_button_t btn
) 
```

### function `bsp_display_backlight_off`

```c
esp_err_t bsp_display_backlight_off (
    void
) 
```

### function `bsp_display_backlight_on`

```c
esp_err_t bsp_display_backlight_on (
    void
) 
```

### function `bsp_display_brightness_set`

```c
esp_err_t bsp_display_brightness_set (
    int brightness_percent
) 
```

### function `bsp_display_get_input_dev`

```c
lv_indev_t * bsp_display_get_input_dev (
    void
) 
```

### function `bsp_display_lock`

```c
bool bsp_display_lock (
    uint32_t timeout_ms
) 
```

### function `bsp_display_rotate`

```c
void bsp_display_rotate (
    lv_disp_t * disp,
    lv_disp_rot_t rotation
) 
```

### function `bsp_display_start`

```c
lv_disp_t * bsp_display_start (
    void
) 
```

### function `bsp_display_unlock`

```c
void bsp_display_unlock (
    void
) 
```

### function `bsp_i2c_deinit`

```c
esp_err_t bsp_i2c_deinit (
    void
) 
```

### function `bsp_i2c_init`

```c
esp_err_t bsp_i2c_init (
    void
) 
```

### function `bsp_io_expander_init`

```c
esp_io_expander_handle_t bsp_io_expander_init (
    void
) 
```


## File esp32_s3_lcd_ev_board/priv_include/bsp_sub_board.h



## Types

| Type | Name |
| ---: | :--- |
| typedef bool(\* | [**bsp\_lcd\_trans\_done\_cb\_t**](#typedef-bsp_lcd_trans_done_cb_t)  <br>_LCD transmit done callback function type._ |

## Functions

| Type | Name |
| ---: | :--- |
|  esp\_lcd\_panel\_handle\_t | [**bsp\_lcd\_init**](#function-bsp_lcd_init) (void \* arg) <br>_Init LCD panel._ |
|  esp\_err\_t | [**bsp\_lcd\_register\_trans\_done\_callback**](#function-bsp_lcd_register_trans_done_callback) (bsp\_lcd\_trans\_done\_cb\_t callback) <br>_Register a callback function which will be called when LCD finish refreshing._ |
|   | [**bsp\_touch\_panel\_init**](#function-bsp_touch_panel_init) (void) <br>_Init touch panel._ |



## Types Documentation

### typedef `bsp_lcd_trans_done_cb_t`

```c
typedef bool(* bsp_lcd_trans_done_cb_t) (esp_lcd_panel_handle_t handle);
```


## Functions Documentation

### function `bsp_lcd_init`

```c
esp_lcd_panel_handle_t bsp_lcd_init (
    void * arg
) 
```

### function `bsp_lcd_register_trans_done_callback`

```c
esp_err_t bsp_lcd_register_trans_done_callback (
    bsp_lcd_trans_done_cb_t callback
) 
```

### function `bsp_touch_panel_init`

```c
esp_lcd_touch_handle_t bsp_touch_panel_init (
    void
) 
```


## File esp32_s3_usb_otg/include/bsp/esp32_s3_usb_otg.h


## Macros

| Type | Name |
| ---: | :--- |
| define  | [**BSP\_BATTERY\_BOOST\_EN**](#define-bsp_battery_boost_en)  (GPIO\_NUM\_13)<br> |
| define  | [**BSP\_BATTERY\_VOLTAGE**](#define-bsp_battery_voltage)  (GPIO\_NUM\_2)<br> |
| define  | [**BSP\_BATTERY\_VOLTAGE\_DIV**](#define-bsp_battery_voltage_div)  (2)<br> |
| define  | [**BSP\_LCD\_BACKLIGHT**](#define-bsp_lcd_backlight)  (GPIO\_NUM\_9)<br> |
| define  | [**BSP\_LCD\_DC**](#define-bsp_lcd_dc)  (GPIO\_NUM\_4)<br> |
| define  | [**BSP\_LCD\_DRAW\_BUFF\_DOUBLE**](#define-bsp_lcd_draw_buff_double)  (1)<br> |
| define  | [**BSP\_LCD\_DRAW\_BUFF\_SIZE**](#define-bsp_lcd_draw_buff_size)  (BSP\_LCD\_H\_RES \* 30)<br> |
| define  | [**BSP\_LCD\_H\_RES**](#define-bsp_lcd_h_res)  (240)<br> |
| define  | [**BSP\_LCD\_PIXEL\_CLOCK\_HZ**](#define-bsp_lcd_pixel_clock_hz)  (40 \* 1000 \* 1000)<br> |
| define  | [**BSP\_LCD\_RST**](#define-bsp_lcd_rst)  (GPIO\_NUM\_8)<br> |
| define  | [**BSP\_LCD\_SPI\_CLK**](#define-bsp_lcd_spi_clk)  (GPIO\_NUM\_6)<br> |
| define  | [**BSP\_LCD\_SPI\_CS**](#define-bsp_lcd_spi_cs)  (GPIO\_NUM\_5)<br> |
| define  | [**BSP\_LCD\_SPI\_MOSI**](#define-bsp_lcd_spi_mosi)  (GPIO\_NUM\_7)<br> |
| define  | [**BSP\_LCD\_SPI\_NUM**](#define-bsp_lcd_spi_num)  (SPI3\_HOST)<br> |
| define  | [**BSP\_LCD\_V\_RES**](#define-bsp_lcd_v_res)  (240)<br> |
| define  | [**BSP\_MOUNT\_POINT**](#define-bsp_mount_point)  CONFIG\_BSP\_uSD\_MOUNT\_POINT<br> |
| define  | [**BSP\_SD\_CLK**](#define-bsp_sd_clk)  (GPIO\_NUM\_36)<br> |
| define  | [**BSP\_SD\_CMD**](#define-bsp_sd_cmd)  (GPIO\_NUM\_35)<br> |
| define  | [**BSP\_SD\_D0**](#define-bsp_sd_d0)  (GPIO\_NUM\_37)<br> |
| define  | [**BSP\_SD\_D1**](#define-bsp_sd_d1)  (GPIO\_NUM\_38)<br> |
| define  | [**BSP\_SD\_D2**](#define-bsp_sd_d2)  (GPIO\_NUM\_33)<br> |
| define  | [**BSP\_SD\_D3**](#define-bsp_sd_d3)  (GPIO\_NUM\_34)<br> |
| define  | [**BSP\_USB\_DEV\_VBUS\_EN**](#define-bsp_usb_dev_vbus_en)  (GPIO\_NUM\_12)<br> |
| define  | [**BSP\_USB\_HOST\_VOLTAGE**](#define-bsp_usb_host_voltage)  (GPIO\_NUM\_1)<br> |
| define  | [**BSP\_USB\_HOST\_VOLTAGE\_DIV**](#define-bsp_usb_host_voltage_div)  (3.7f)<br> |
| define  | [**BSP\_USB\_LIMIT\_EN**](#define-bsp_usb_limit_en)  (GPIO\_NUM\_17)<br> |
| define  | [**BSP\_USB\_MODE\_SEL**](#define-bsp_usb_mode_sel)  (GPIO\_NUM\_18)<br> |
| define  | [**BSP\_USB\_NEG**](#define-bsp_usb_neg)  USBPHY\_DM\_NUM<br> |
| define  | [**BSP\_USB\_POS**](#define-bsp_usb_pos)  USBPHY\_DP\_NUM<br> |

## Types

| Type | Name |
| ---: | :--- |
| enum  | [**bsp\_button\_t**](#enum-bsp_button_t)  <br> |
| enum  | [**bsp\_led\_t**](#enum-bsp_led_t)  <br> |
| typedef enum bsp\_led\_t | [**bsp\_led\_t**](#typedef-bsp_led_t)  <br> |
| enum  | [**bsp\_usb\_host\_power\_mode\_t**](#enum-bsp_usb_host_power_mode_t)  <br>_Power modes of USB Host connector._ |
| typedef  | [**bsp\_usb\_host\_power\_mode\_t**](#typedef-bsp_usb_host_power_mode_t)  <br>_Power modes of USB Host connector._ |

## Functions

| Type | Name |
| ---: | :--- |
|  bool | [**bsp\_button\_get**](#function-bsp_button_get) (const bsp\_button\_t btn) <br>_Get button's state._ |
|  esp\_err\_t | [**bsp\_button\_init**](#function-bsp_button_init) (void) <br>_Set button's GPIO as input._ |
|  esp\_err\_t | [**bsp\_display\_backlight\_off**](#function-bsp_display_backlight_off) (void) <br>_Turn off display backlight._ |
|  esp\_err\_t | [**bsp\_display\_backlight\_on**](#function-bsp_display_backlight_on) (void) <br>_Turn on display backlight._ |
|  esp\_err\_t | [**bsp\_display\_brightness\_set**](#function-bsp_display_brightness_set) (int brightness\_percent) <br>_Set display's brightness._ |
|  lv\_indev\_t \* | [**bsp\_display\_get\_input\_dev**](#function-bsp_display_get_input_dev) (void) <br>_Get pointer to input device (touch, buttons, ...)_ |
|  bool | [**bsp\_display\_lock**](#function-bsp_display_lock) (uint32\_t timeout\_ms) <br>_Take LVGL mutex._ |
|  void | [**bsp\_display\_rotate**](#function-bsp_display_rotate) (lv\_disp\_t \* disp, lv\_disp\_rot\_t rotation) <br>_Rotate screen._ |
|  lv\_disp\_t \* | [**bsp\_display\_start**](#function-bsp_display_start) (void) <br>_Initialize display._ |
|  void | [**bsp\_display\_unlock**](#function-bsp_display_unlock) (void) <br>_Give LVGL mutex._ |
|  esp\_err\_t | [**bsp\_led\_set**](#function-bsp_led_set) (const bsp\_led\_t led\_io, const bool on) <br>_Turn LED on/off._ |
|  esp\_err\_t | [**bsp\_leds\_init**](#function-bsp_leds_init) (void) <br>_Set LED's GPIOs as output push-pull._ |
|  esp\_err\_t | [**bsp\_sdcard\_mount**](#function-bsp_sdcard_mount) (void) <br>_Mount microSD card to virtual file system._ |
|  esp\_err\_t | [**bsp\_sdcard\_unmount**](#function-bsp_sdcard_unmount) (void) <br>_Unmount microSD card from virtual file system._ |
|  esp\_err\_t | [**bsp\_usb\_host\_power\_mode**](#function-bsp_usb_host_power_mode)  <br>_Select power source of USB Host connector._ |
|  esp\_err\_t | [**bsp\_usb\_host\_start**](#function-bsp_usb_host_start)  <br>_Start USB host._ |
|  esp\_err\_t | [**bsp\_usb\_host\_stop**](#function-bsp_usb_host_stop) (void) <br>_Stop USB host._ |
|  esp\_err\_t | [**bsp\_usb\_mode\_select\_device**](#function-bsp_usb_mode_select_device) (void) <br>_Switch ESP32-S3-USB-OTG to USB device mode._ |
|  esp\_err\_t | [**bsp\_usb\_mode\_select\_host**](#function-bsp_usb_mode_select_host) (void) <br>_Switch ESP32-S3-USB-OTG to USB host mode._ |
|  int | [**bsp\_voltage\_battery\_get**](#function-bsp_voltage_battery_get) (void) <br>_Get battery voltage._ |
|  esp\_err\_t | [**bsp\_voltage\_init**](#function-bsp_voltage_init) (void) <br>_Init voltage measurements._ |
|  int | [**bsp\_voltage\_usb\_get**](#function-bsp_voltage_usb_get) (void) <br>_Get USB device connector voltage._ |


## Macros Documentation

### define `BSP_BATTERY_BOOST_EN`

```c
#define BSP_BATTERY_BOOST_EN (GPIO_NUM_13)
```

### define `BSP_BATTERY_VOLTAGE`

```c
#define BSP_BATTERY_VOLTAGE (GPIO_NUM_2)
```

### define `BSP_BATTERY_VOLTAGE_DIV`

```c
#define BSP_BATTERY_VOLTAGE_DIV (2)
```

### define `BSP_LCD_BACKLIGHT`

```c
#define BSP_LCD_BACKLIGHT (GPIO_NUM_9)
```

### define `BSP_LCD_DC`

```c
#define BSP_LCD_DC (GPIO_NUM_4)
```

### define `BSP_LCD_DRAW_BUFF_DOUBLE`

```c
#define BSP_LCD_DRAW_BUFF_DOUBLE (1)
```

### define `BSP_LCD_DRAW_BUFF_SIZE`

```c
#define BSP_LCD_DRAW_BUFF_SIZE (BSP_LCD_H_RES * 30)
```

### define `BSP_LCD_H_RES`

```c
#define BSP_LCD_H_RES (240)
```

### define `BSP_LCD_PIXEL_CLOCK_HZ`

```c
#define BSP_LCD_PIXEL_CLOCK_HZ (40 * 1000 * 1000)
```

### define `BSP_LCD_RST`

```c
#define BSP_LCD_RST (GPIO_NUM_8)
```

### define `BSP_LCD_SPI_CLK`

```c
#define BSP_LCD_SPI_CLK (GPIO_NUM_6)
```

### define `BSP_LCD_SPI_CS`

```c
#define BSP_LCD_SPI_CS (GPIO_NUM_5)
```

### define `BSP_LCD_SPI_MOSI`

```c
#define BSP_LCD_SPI_MOSI (GPIO_NUM_7)
```

### define `BSP_LCD_SPI_NUM`

```c
#define BSP_LCD_SPI_NUM (SPI3_HOST)
```

### define `BSP_LCD_V_RES`

```c
#define BSP_LCD_V_RES (240)
```

### define `BSP_MOUNT_POINT`

```c
#define BSP_MOUNT_POINT CONFIG_BSP_uSD_MOUNT_POINT
```

### define `BSP_SD_CLK`

```c
#define BSP_SD_CLK (GPIO_NUM_36)
```

### define `BSP_SD_CMD`

```c
#define BSP_SD_CMD (GPIO_NUM_35)
```

### define `BSP_SD_D0`

```c
#define BSP_SD_D0 (GPIO_NUM_37)
```

### define `BSP_SD_D1`

```c
#define BSP_SD_D1 (GPIO_NUM_38)
```

### define `BSP_SD_D2`

```c
#define BSP_SD_D2 (GPIO_NUM_33)
```

### define `BSP_SD_D3`

```c
#define BSP_SD_D3 (GPIO_NUM_34)
```

### define `BSP_USB_DEV_VBUS_EN`

```c
#define BSP_USB_DEV_VBUS_EN (GPIO_NUM_12)
```

### define `BSP_USB_HOST_VOLTAGE`

```c
#define BSP_USB_HOST_VOLTAGE (GPIO_NUM_1)
```

### define `BSP_USB_HOST_VOLTAGE_DIV`

```c
#define BSP_USB_HOST_VOLTAGE_DIV (3.7f)
```

### define `BSP_USB_LIMIT_EN`

```c
#define BSP_USB_LIMIT_EN (GPIO_NUM_17)
```

### define `BSP_USB_MODE_SEL`

```c
#define BSP_USB_MODE_SEL (GPIO_NUM_18)
```

### define `BSP_USB_NEG`

```c
#define BSP_USB_NEG USBPHY_DM_NUM
```

### define `BSP_USB_POS`

```c
#define BSP_USB_POS USBPHY_DP_NUM
```


## Types Documentation

### enum `bsp_button_t`

```c
enum bsp_button_t {
    BSP_BUTTON_OK = GPIO_NUM_0,
    BSP_BUTTON_DW = GPIO_NUM_11,
    BSP_BUTTON_UP = GPIO_NUM_10,
    BSP_BUTTON_MENU = GPIO_NUM_14,
    BSP_USB_OVERCURRENT = GPIO_NUM_21
};
```

### enum `bsp_led_t`

```c
enum bsp_led_t {
    BSP_LED_GREEN = GPIO_NUM_15,
    BSP_LED_YELLOW = GPIO_NUM_16
};
```

### typedef `bsp_led_t`

```c
typedef enum bsp_led_t bsp_led_t;
```

### enum `bsp_usb_host_power_mode_t`

```c
enum bsp_usb_host_power_mode_t {
    BSP_USB_HOST_POWER_MODE_OFF,
    BSP_USB_HOST_POWER_MODE_BATTERY,
    BSP_USB_HOST_POWER_MODE_USB_DEV
};
```

### typedef `bsp_usb_host_power_mode_t`

```c
typedef enum bsp_usb_host_power_mode_t bsp_usb_host_power_mode_t;
```


## Functions Documentation

### function `bsp_button_get`

```c
bool bsp_button_get (
    const bsp_button_t btn
) 
```

### function `bsp_button_init`

```c
esp_err_t bsp_button_init (
    void
) 
```

### function `bsp_display_backlight_off`

```c
esp_err_t bsp_display_backlight_off (
    void
) 
```

### function `bsp_display_backlight_on`

```c
esp_err_t bsp_display_backlight_on (
    void
) 
```

### function `bsp_display_brightness_set`

```c
esp_err_t bsp_display_brightness_set (
    int brightness_percent
) 
```

### function `bsp_display_get_input_dev`

```c
lv_indev_t * bsp_display_get_input_dev (
    void
) 
```

### function `bsp_display_lock`

```c
bool bsp_display_lock (
    uint32_t timeout_ms
) 
```

### function `bsp_display_rotate`

```c
void bsp_display_rotate (
    lv_disp_t * disp,
    lv_disp_rot_t rotation
) 
```

### function `bsp_display_start`

```c
lv_disp_t * bsp_display_start (
    void
) 
```

### function `bsp_display_unlock`

```c
void bsp_display_unlock (
    void
) 
```

### function `bsp_led_set`

```c
esp_err_t bsp_led_set (
    const bsp_led_t led_io,
    const bool on
) 
```

### function `bsp_leds_init`

```c
esp_err_t bsp_leds_init (
    void
) 
```

### function `bsp_sdcard_mount`

```c
esp_err_t bsp_sdcard_mount (
    void
) 
```

### function `bsp_sdcard_unmount`

```c
esp_err_t bsp_sdcard_unmount (
    void
) 
```

### function `bsp_usb_host_power_mode`

```c
esp_err_t bsp_usb_host_power_mode (
    bsp_usb_host_power_mode_t mode,
    bool limit_500mA
) 
```

### function `bsp_usb_host_start`

```c
esp_err_t bsp_usb_host_start (
    bsp_usb_host_power_mode_t mode,
    bool limit_500mA
) 
```

### function `bsp_usb_host_stop`

```c
esp_err_t bsp_usb_host_stop (
    void
) 
```

### function `bsp_usb_mode_select_device`

```c
esp_err_t bsp_usb_mode_select_device (
    void
) 
```

### function `bsp_usb_mode_select_host`

```c
esp_err_t bsp_usb_mode_select_host (
    void
) 
```

### function `bsp_voltage_battery_get`

```c
int bsp_voltage_battery_get (
    void
) 
```

### function `bsp_voltage_init`

```c
esp_err_t bsp_voltage_init (
    void
) 
```

### function `bsp_voltage_usb_get`

```c
int bsp_voltage_usb_get (
    void
) 
```


## File esp_wrover_kit/include/bsp/esp_wrover_kit.h


## Macros

| Type | Name |
| ---: | :--- |
| define  | [**BSP\_LCD\_BACKLIGHT**](#define-bsp_lcd_backlight)  (GPIO\_NUM\_5)<br> |
| define  | [**BSP\_LCD\_DC**](#define-bsp_lcd_dc)  (GPIO\_NUM\_21)<br> |
| define  | [**BSP\_LCD\_DRAW\_BUFF\_DOUBLE**](#define-bsp_lcd_draw_buff_double)  (1)<br> |
| define  | [**BSP\_LCD\_DRAW\_BUFF\_SIZE**](#define-bsp_lcd_draw_buff_size)  (BSP\_LCD\_H\_RES \* 30)<br> |
| define  | [**BSP\_LCD\_H\_RES**](#define-bsp_lcd_h_res)  (240)<br> |
| define  | [**BSP\_LCD\_PIXEL\_CLOCK\_HZ**](#define-bsp_lcd_pixel_clock_hz)  (40 \* 1000 \* 1000)<br> |
| define  | [**BSP\_LCD\_RST**](#define-bsp_lcd_rst)  (GPIO\_NUM\_18)<br> |
| define  | [**BSP\_LCD\_SPI\_CLK**](#define-bsp_lcd_spi_clk)  (GPIO\_NUM\_19)<br> |
| define  | [**BSP\_LCD\_SPI\_CS**](#define-bsp_lcd_spi_cs)  (GPIO\_NUM\_22)<br> |
| define  | [**BSP\_LCD\_SPI\_MISO**](#define-bsp_lcd_spi_miso)  (GPIO\_NUM\_25)<br> |
| define  | [**BSP\_LCD\_SPI\_MOSI**](#define-bsp_lcd_spi_mosi)  (GPIO\_NUM\_23)<br> |
| define  | [**BSP\_LCD\_SPI\_NUM**](#define-bsp_lcd_spi_num)  (SPI2\_HOST)<br> |
| define  | [**BSP\_LCD\_V\_RES**](#define-bsp_lcd_v_res)  (320)<br> |
| define  | [**BSP\_MOUNT\_POINT**](#define-bsp_mount_point)  CONFIG\_BSP\_uSD\_MOUNT\_POINT<br> |
| define  | [**BSP\_SD\_CLK**](#define-bsp_sd_clk)  (GPIO\_NUM\_14)<br> |
| define  | [**BSP\_SD\_CMD**](#define-bsp_sd_cmd)  (GPIO\_NUM\_15)<br> |
| define  | [**BSP\_SD\_D0**](#define-bsp_sd_d0)  (GPIO\_NUM\_2)<br> |
| define  | [**BSP\_SD\_D1**](#define-bsp_sd_d1)  (GPIO\_NUM\_4)<br> |
| define  | [**BSP\_SD\_D2**](#define-bsp_sd_d2)  (GPIO\_NUM\_12)<br> |
| define  | [**BSP\_SD\_D3**](#define-bsp_sd_d3)  (GPIO\_NUM\_13)<br> |
| define  | [**BSP\_SD\_DET**](#define-bsp_sd_det)  (GPIO\_NUM\_21)<br> |

## Types

| Type | Name |
| ---: | :--- |
| enum  | [**bsp\_button\_t**](#enum-bsp_button_t)  <br> |
| enum  | [**bsp\_led\_t**](#enum-bsp_led_t)  <br> |
| typedef enum bsp\_led\_t | [**bsp\_led\_t**](#typedef-bsp_led_t)  <br> |

## Functions

| Type | Name |
| ---: | :--- |
|  bool | [**bsp\_button\_get**](#function-bsp_button_get) (const bsp\_button\_t btn) <br>_Get button's state._ |
|  esp\_err\_t | [**bsp\_button\_init**](#function-bsp_button_init) (const bsp\_button\_t btn) <br>_Set button's GPIO as input._ |
|  esp\_err\_t | [**bsp\_display\_backlight\_off**](#function-bsp_display_backlight_off) (void) <br>_Turn off display backlight._ |
|  esp\_err\_t | [**bsp\_display\_backlight\_on**](#function-bsp_display_backlight_on) (void) <br>_Turn on display backlight._ |
|  esp\_err\_t | [**bsp\_display\_brightness\_set**](#function-bsp_display_brightness_set) (int brightness\_percent) <br>_Set display's brightness._ |
|  lv\_indev\_t \* | [**bsp\_display\_get\_input\_dev**](#function-bsp_display_get_input_dev) (void) <br>_Get pointer to input device (touch, buttons, ...)_ |
|  bool | [**bsp\_display\_lock**](#function-bsp_display_lock) (uint32\_t timeout\_ms) <br>_Take LVGL mutex._ |
|  void | [**bsp\_display\_rotate**](#function-bsp_display_rotate) (lv\_disp\_t \* disp, lv\_disp\_rot\_t rotation) <br>_Rotate screen._ |
|  lv\_disp\_t \* | [**bsp\_display\_start**](#function-bsp_display_start) (void) <br>_Initialize display._ |
|  void | [**bsp\_display\_unlock**](#function-bsp_display_unlock) (void) <br>_Give LVGL mutex._ |
|  esp\_err\_t | [**bsp\_led\_set**](#function-bsp_led_set) (const bsp\_led\_t led\_io, const bool on) <br>_Turn LED on/off._ |
|  esp\_err\_t | [**bsp\_leds\_init**](#function-bsp_leds_init) (void) <br>_Set LED's GPIOs as output push-pull._ |
|  esp\_err\_t | [**bsp\_sdcard\_mount**](#function-bsp_sdcard_mount) (void) <br>_Mount microSD card to virtual file system._ |
|  esp\_err\_t | [**bsp\_sdcard\_unmount**](#function-bsp_sdcard_unmount) (void) <br>_Unmount micorSD card from virtual file system._ |


## Macros Documentation

### define `BSP_LCD_BACKLIGHT`

```c
#define BSP_LCD_BACKLIGHT (GPIO_NUM_5)
```

### define `BSP_LCD_DC`

```c
#define BSP_LCD_DC (GPIO_NUM_21)
```

### define `BSP_LCD_DRAW_BUFF_DOUBLE`

```c
#define BSP_LCD_DRAW_BUFF_DOUBLE (1)
```

### define `BSP_LCD_DRAW_BUFF_SIZE`

```c
#define BSP_LCD_DRAW_BUFF_SIZE (BSP_LCD_H_RES * 30)
```

### define `BSP_LCD_H_RES`

```c
#define BSP_LCD_H_RES (240)
```

### define `BSP_LCD_PIXEL_CLOCK_HZ`

```c
#define BSP_LCD_PIXEL_CLOCK_HZ (40 * 1000 * 1000)
```

### define `BSP_LCD_RST`

```c
#define BSP_LCD_RST (GPIO_NUM_18)
```

### define `BSP_LCD_SPI_CLK`

```c
#define BSP_LCD_SPI_CLK (GPIO_NUM_19)
```

### define `BSP_LCD_SPI_CS`

```c
#define BSP_LCD_SPI_CS (GPIO_NUM_22)
```

### define `BSP_LCD_SPI_MISO`

```c
#define BSP_LCD_SPI_MISO (GPIO_NUM_25)
```

### define `BSP_LCD_SPI_MOSI`

```c
#define BSP_LCD_SPI_MOSI (GPIO_NUM_23)
```

### define `BSP_LCD_SPI_NUM`

```c
#define BSP_LCD_SPI_NUM (SPI2_HOST)
```

### define `BSP_LCD_V_RES`

```c
#define BSP_LCD_V_RES (320)
```

### define `BSP_MOUNT_POINT`

```c
#define BSP_MOUNT_POINT CONFIG_BSP_uSD_MOUNT_POINT
```

### define `BSP_SD_CLK`

```c
#define BSP_SD_CLK (GPIO_NUM_14)
```

### define `BSP_SD_CMD`

```c
#define BSP_SD_CMD (GPIO_NUM_15)
```

### define `BSP_SD_D0`

```c
#define BSP_SD_D0 (GPIO_NUM_2)
```

### define `BSP_SD_D1`

```c
#define BSP_SD_D1 (GPIO_NUM_4)
```

### define `BSP_SD_D2`

```c
#define BSP_SD_D2 (GPIO_NUM_12)
```

### define `BSP_SD_D3`

```c
#define BSP_SD_D3 (GPIO_NUM_13)
```

### define `BSP_SD_DET`

```c
#define BSP_SD_DET (GPIO_NUM_21)
```


## Types Documentation

### enum `bsp_button_t`

```c
enum bsp_button_t {
    BSP_BUTTON_BOOT = GPIO_NUM_0
};
```

### enum `bsp_led_t`

```c
enum bsp_led_t {
    BSP_LED_RED = GPIO_NUM_0,
    BSP_LED_GREEN = GPIO_NUM_2,
    BSP_LED_BLUE = GPIO_NUM_4
};
```

### typedef `bsp_led_t`

```c
typedef enum bsp_led_t bsp_led_t;
```


## Functions Documentation

### function `bsp_button_get`

```c
bool bsp_button_get (
    const bsp_button_t btn
) 
```

### function `bsp_button_init`

```c
esp_err_t bsp_button_init (
    const bsp_button_t btn
) 
```

### function `bsp_display_backlight_off`

```c
esp_err_t bsp_display_backlight_off (
    void
) 
```

### function `bsp_display_backlight_on`

```c
esp_err_t bsp_display_backlight_on (
    void
) 
```

### function `bsp_display_brightness_set`

```c
esp_err_t bsp_display_brightness_set (
    int brightness_percent
) 
```

### function `bsp_display_get_input_dev`

```c
lv_indev_t * bsp_display_get_input_dev (
    void
) 
```

### function `bsp_display_lock`

```c
bool bsp_display_lock (
    uint32_t timeout_ms
) 
```

### function `bsp_display_rotate`

```c
void bsp_display_rotate (
    lv_disp_t * disp,
    lv_disp_rot_t rotation
) 
```

### function `bsp_display_start`

```c
lv_disp_t * bsp_display_start (
    void
) 
```

### function `bsp_display_unlock`

```c
void bsp_display_unlock (
    void
) 
```

### function `bsp_led_set`

```c
esp_err_t bsp_led_set (
    const bsp_led_t led_io,
    const bool on
) 
```

### function `bsp_leds_init`

```c
esp_err_t bsp_leds_init (
    void
) 
```

### function `bsp_sdcard_mount`

```c
esp_err_t bsp_sdcard_mount (
    void
) 
```

### function `bsp_sdcard_unmount`

```c
esp_err_t bsp_sdcard_unmount (
    void
) 
```


-------
generated by commit 7ff86f5c6e35c4980afcefb97f0352e01dbee605 at Tue Jul 25 09:40:24 2023