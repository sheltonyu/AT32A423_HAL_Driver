from building import *
import os

cwd = GetCurrentDir()
path = [os.path.join(cwd, 'inc')]
src_path = os.path.join(cwd, 'src')

CPPDEFINES = ['USE_STDPERIPH_DRIVER']

src = [
os.path.join(src_path, 'at32a423_acc.c'),
os.path.join(src_path, 'at32a423_adc.c'),

os.path.join(src_path, 'at32a423_can.c'),
os.path.join(src_path, 'at32a423_crc.c'),
os.path.join(src_path, 'at32a423_crm.c'),
os.path.join(src_path, 'at32a423_dac.c'),
os.path.join(src_path, 'at32a423_debug.c'),
os.path.join(src_path, 'at32a423_dma.c'),
os.path.join(src_path, 'at32a423_ertc.c'),
os.path.join(src_path, 'at32a423_exint.c'),
os.path.join(src_path, 'at32a423_flash.c'),
os.path.join(src_path, 'at32a423_gpio.c'),
os.path.join(src_path, 'at32a423_i2c.c'),
os.path.join(src_path, 'at32a423_misc.c'),
os.path.join(src_path, 'at32a423_pwc.c'),
os.path.join(src_path, 'at32a423_scfg.c'),
os.path.join(src_path, 'at32a423_spi.c'),
os.path.join(src_path, 'at32a423_tmr.c'),
os.path.join(src_path, 'at32a423_usart.c'),
os.path.join(src_path, 'at32a423_usb.c'),
os.path.join(src_path, 'at32a423_wdt.c'),
os.path.join(src_path, 'at32a423_wwdt.c'),
os.path.join(src_path, 'at32a423_xmc.c'),
]

group = DefineGroup('libraries', src, depend = ['PKG_USING_AT32A423_HAL_DRIVER'], CPPPATH = path, CPPDEFINES = CPPDEFINES)

Return('group')
