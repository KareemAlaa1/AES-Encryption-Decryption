transcript on
if {[file exists rtl_work]} {
	vdel -lib rtl_work -all
}
vlib rtl_work
vmap work rtl_work

vlog -vlog01compat -work work +incdir+C:/Users/kokob/Desktop/AES_Encryption/AES_Encryption {C:/Users/kokob/Desktop/AES_Encryption/AES_Encryption/Wrapper.v}
vlog -vlog01compat -work work +incdir+C:/Users/kokob/Desktop/AES_Encryption/AES_Encryption {C:/Users/kokob/Desktop/AES_Encryption/AES_Encryption/SubBytes.v}
vlog -vlog01compat -work work +incdir+C:/Users/kokob/Desktop/AES_Encryption/AES_Encryption {C:/Users/kokob/Desktop/AES_Encryption/AES_Encryption/ShiftRows.v}
vlog -vlog01compat -work work +incdir+C:/Users/kokob/Desktop/AES_Encryption/AES_Encryption {C:/Users/kokob/Desktop/AES_Encryption/AES_Encryption/sbox.v}
vlog -vlog01compat -work work +incdir+C:/Users/kokob/Desktop/AES_Encryption/AES_Encryption {C:/Users/kokob/Desktop/AES_Encryption/AES_Encryption/mixColumns3.v}
vlog -vlog01compat -work work +incdir+C:/Users/kokob/Desktop/AES_Encryption/AES_Encryption {C:/Users/kokob/Desktop/AES_Encryption/AES_Encryption/KeyGeneration_256.v}
vlog -vlog01compat -work work +incdir+C:/Users/kokob/Desktop/AES_Encryption/AES_Encryption {C:/Users/kokob/Desktop/AES_Encryption/AES_Encryption/KeyGeneration_192.v}
vlog -vlog01compat -work work +incdir+C:/Users/kokob/Desktop/AES_Encryption/AES_Encryption {C:/Users/kokob/Desktop/AES_Encryption/AES_Encryption/KeyGeneration_128.v}
vlog -vlog01compat -work work +incdir+C:/Users/kokob/Desktop/AES_Encryption/AES_Encryption {C:/Users/kokob/Desktop/AES_Encryption/AES_Encryption/KeyGeneration256.v}
vlog -vlog01compat -work work +incdir+C:/Users/kokob/Desktop/AES_Encryption/AES_Encryption {C:/Users/kokob/Desktop/AES_Encryption/AES_Encryption/KeyGeneration192.v}
vlog -vlog01compat -work work +incdir+C:/Users/kokob/Desktop/AES_Encryption/AES_Encryption {C:/Users/kokob/Desktop/AES_Encryption/AES_Encryption/KeyGeneration.v}
vlog -vlog01compat -work work +incdir+C:/Users/kokob/Desktop/AES_Encryption/AES_Encryption {C:/Users/kokob/Desktop/AES_Encryption/AES_Encryption/KeyExpansion.v}
vlog -vlog01compat -work work +incdir+C:/Users/kokob/Desktop/AES_Encryption/AES_Encryption {C:/Users/kokob/Desktop/AES_Encryption/AES_Encryption/InvSubBytes.v}
vlog -vlog01compat -work work +incdir+C:/Users/kokob/Desktop/AES_Encryption/AES_Encryption {C:/Users/kokob/Desktop/AES_Encryption/AES_Encryption/InvShiftRows.v}
vlog -vlog01compat -work work +incdir+C:/Users/kokob/Desktop/AES_Encryption/AES_Encryption {C:/Users/kokob/Desktop/AES_Encryption/AES_Encryption/InverseMixColumns.v}
vlog -vlog01compat -work work +incdir+C:/Users/kokob/Desktop/AES_Encryption/AES_Encryption {C:/Users/kokob/Desktop/AES_Encryption/AES_Encryption/InverseCipher.v}
vlog -vlog01compat -work work +incdir+C:/Users/kokob/Desktop/AES_Encryption/AES_Encryption {C:/Users/kokob/Desktop/AES_Encryption/AES_Encryption/Cipher.v}
vlog -vlog01compat -work work +incdir+C:/Users/kokob/Desktop/AES_Encryption/AES_Encryption {C:/Users/kokob/Desktop/AES_Encryption/AES_Encryption/AddRoundKey.v}

vlog -vlog01compat -work work +incdir+C:/Users/kokob/Desktop/AES_Encryption/AES_Encryption {C:/Users/kokob/Desktop/AES_Encryption/AES_Encryption/Wrapper.v}

vsim -t 1ps -L altera_ver -L lpm_ver -L sgate_ver -L altera_mf_ver -L altera_lnsim_ver -L cyclonev_ver -L cyclonev_hssi_ver -L cyclonev_pcie_hip_ver -L rtl_work -L work -voptargs="+acc"  Wrapper_tb

add wave *
view structure
view signals
run -all
