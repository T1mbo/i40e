Changelog for i40e-2.17.4
===========================================================================
Fix queues reservation scheme
Fix BUG use WQ_MEM_RECLAIM flag for workqueue
Fix XDP_REDIRECT/XDP xmit ring cleanup race
Fix oops at i40e_rebuild()
Fix reset bw limit when DCB enabled with 1 TC
Fix potential out of bounds array access vsi->info.queue_mapping
Fix dmesg trace displaying causing error
Fix VF failed to init adminq: -53
Fix can't ping over QinQ tunnel
Fix pre-set max number of queues for VF
Fix incorrect FW version for outer vlan processing
Fix setting X710 MAC clock frequency if no link
Fix PTP on 5Gb links
Fix i40e_dbg_dump_desc() ring dumping
Fix skipping of iw client when in kdump
Add supported FVL FW API version to 1.15
Add support for vf-vlan-prune-disable flag
Add guard for hw-tc-offload flag if creating TC filters
Add cpu_online macro definition for old kernels
Add additional info to PHY type error
Refactor parameters name in i40e_print_input_set
Refactor arrow operator usage in i40e_update_adq_vsi_queues()
Refactor Rx path for re-use
