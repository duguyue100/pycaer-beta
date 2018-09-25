{{autogenerated}}

---

## DAVIS240C Bias Example

```json
{
    "DiffBn_coarse": 4,
    "DiffBn_fine": 39,
    "ONBn_coarse": 6,
    "ONBn_fine": 200,
    "OFFBn_coarse": 4,
    "OFFBn_fine": 0,
    "APSCasEPC_coarse": 5,
    "APSCasEPC_fine": 185,
    "DiffCasBNC_coarse": 5,
    "DiffCasBNC_fine": 115,
    "APSROSFBn_coarse": 6,
    "APSROSFBn_fine": 219,
    "LocalBufBn_coarse": 5,
    "LocalBufBn_fine": 164,
    "PixInvBn_coarse": 5,
    "PixInvBn_fine": 129,
    "PrBp_coarse": 2,
    "PrBp_fine": 58,
    "PrSFBp_coarse": 1,
    "PrSFBp_fine": 33,
    "RefrBp_coarse": 4,
    "RefrBp_fine": 25,
    "AEPdBn_coarse": 6,
    "AEPdBn_fine": 91,
    "LcolTimeoutBn_coarse": 5,
    "LcolTimeoutBn_fine": 49,
    "AEPuXBp_coarse": 4,
    "AEPuXBp_fine": 80,
    "AEPuYBp_coarse": 7,
    "AEPuYBp_fine": 152,
    "IFThrBn_coarse": 5,
    "IFThrBn_fine": 255,
    "IFRefrBn_coarse": 5,
    "IFRefrBn_fine": 255,
    "PadFollBn_coarse": 7,
    "PadFollBn_fine": 215,
    "APSOverflowLevelBn_coarse": 6,
    "APSOverflowLevelBn_fine": 253,
    "BiasBuffer_coarse": 5,
    "BiasBuffer_fine": 254,
    "aps_enabled": true,
    "dvs_enabled": true,
    "exposure": 4000,
    "autoexposure": true, 
    "frame_delay": 0,
    "imu_enabled": true,
    "imu_acc_scale": 3,
    "imu_gyro_scale": 3,
    "imu_low_pass_filter": 0,
    "noise_filter_configs": {
		"sw_background_activity_two_levels": true,
		"sw_background_activity_check_polarity": true,
		"sw_background_activity_support_min": 2,
		"sw_background_activity_support_max": 8,
		"sw_background_activity_time": 2000,
		"sw_background_activity_enable": true,
		"sw_refractory_period_time": 200,
		"sw_refractory_period_enable": true,
		"sw_hotpixel_enable": true,
		"sw_hotpixel_learn": true
	}
}
```

## DAVIS346B Bias Example

```json
{
    "ADC_RefHigh_volt": 24,
    "ADC_RefHigh_curr": 7,
    "ADC_RefLow_volt": 1,
    "ADC_RefLow_curr": 7,
    "LocalBufBn_coarse": 5,
    "LocalBufBn_fine": 164,
    "PadFollBn_coarse": 7,
    "PadFollBn_fine": 215,
    "DiffBn_coarse": 4,
    "DiffBn_fine": 39,
    "ONBn_coarse": 6,
    "ONBn_fine": 255,
    "OFFBn_coarse": 4,
    "OFFBn_fine": 0,
    "PixInvBn_coarse": 5,
    "PixInvBn_fine": 129,
    "PrBp_coarse": 2,
    "PrBp_fine": 255,
    "PrSFBp_coarse": 1,
    "PrSFBp_fine": 199,
    "RefrBp_coarse": 3,
    "RefrBp_fine": 7,
    "ReadoutBufBp_coarse": 6,
    "ReadoutBufBp_fine": 20,
    "APSROSFBn_coarse": 6,
    "APSROSFBn_fine": 219,
    "ADCCompBp_coarse": 5,
    "ADCCompBp_fine": 20,
    "COLSELLowBn_coarse": 0,
    "COLSELLowBn_fine": 1,
    "DACBufBp_coarse": 6,
    "DACBufBp_fine": 60,
    "LcolTimeoutBn_coarse": 5,
    "LcolTimeoutBn_fine": 49,
    "AEPdBn_coarse": 6,
    "AEPdBn_fine": 91,
    "AEPuXBp_coarse": 4,
    "AEPuXBp_fine": 80,
    "AEPuYBp_coarse": 7,
    "AEPuYBp_fine": 152,
    "IFRefrBn_coarse": 5,
    "IFRefrBn_fine": 255,
    "IFThrBn_coarse": 5,
    "IFThrBn_fine": 255,
    "BiasBuffer_coarse": 5,
    "BiasBuffer_fine": 254,
    "aps_enabled": true,
    "dvs_enabled": true,
    "exposure": 4000,
    "autoexposure": true,
    "frame_delay": 0,
    "imu_enabled": true,
    "imu_acc_scale": 3,
    "imu_gyro_scale": 3,
    "imu_low_pass_filter": 0,
    "background_activity_filter_enabled": false,
    "background_activity_filter_time": 80,
    "refractory_period_enabled": true,
    "refractory_period_time": 2,
    "noise_filter_configs": {
		"sw_background_activity_two_levels": true,
		"sw_background_activity_check_polarity": true,
		"sw_background_activity_support_min": 2,
		"sw_background_activity_support_max": 8,
		"sw_background_activity_time": 2000,
		"sw_background_activity_enable": true,
		"sw_refractory_period_time": 200,
		"sw_refractory_period_enable": true,
		"sw_hotpixel_enable": true,
		"sw_hotpixel_learn": true
	}
}
```