add_library(citra_core STATIC
    3ds.h
    arm/arm_interface.h
    arm/dyncom/arm_dyncom.cpp
    arm/dyncom/arm_dyncom.h
    arm/dyncom/arm_dyncom_dec.cpp
    arm/dyncom/arm_dyncom_dec.h
    arm/dyncom/arm_dyncom_interpreter.cpp
    arm/dyncom/arm_dyncom_interpreter.h
    arm/dyncom/arm_dyncom_run.h
    arm/dyncom/arm_dyncom_thumb.cpp
    arm/dyncom/arm_dyncom_thumb.h
    arm/dyncom/arm_dyncom_trans.cpp
    arm/dyncom/arm_dyncom_trans.h
    arm/exclusive_monitor.cpp
    arm/exclusive_monitor.h
    arm/skyeye_common/arm_regformat.h
    arm/skyeye_common/armstate.cpp
    arm/skyeye_common/armstate.h
    arm/skyeye_common/armsupp.cpp
    arm/skyeye_common/armsupp.h
    arm/skyeye_common/vfp/asm_vfp.h
    arm/skyeye_common/vfp/vfp.cpp
    arm/skyeye_common/vfp/vfp.h
    arm/skyeye_common/vfp/vfp_helper.h
    arm/skyeye_common/vfp/vfpdouble.cpp
    arm/skyeye_common/vfp/vfpinstr.cpp
    arm/skyeye_common/vfp/vfpsingle.cpp
    cheats/cheat_base.cpp
    cheats/cheat_base.h
    cheats/cheats.cpp
    cheats/cheats.h
    cheats/gateway_cheat.cpp
    cheats/gateway_cheat.h
    core.cpp
    core.h
    core_timing.cpp
    core_timing.h
    dumping/backend.cpp
    dumping/backend.h
    dumping/ffmpeg_backend.cpp
    dumping/ffmpeg_backend.h
    file_sys/archive_backend.cpp
    file_sys/archive_backend.h
    file_sys/archive_extsavedata.cpp
    file_sys/archive_extsavedata.h
    file_sys/archive_ncch.cpp
    file_sys/archive_ncch.h
    file_sys/archive_other_savedata.cpp
    file_sys/archive_other_savedata.h
    file_sys/archive_savedata.cpp
    file_sys/archive_savedata.h
    file_sys/archive_sdmc.cpp
    file_sys/archive_sdmc.h
    file_sys/archive_sdmcwriteonly.cpp
    file_sys/archive_sdmcwriteonly.h
    file_sys/archive_selfncch.cpp
    file_sys/archive_selfncch.h
    file_sys/archive_source_sd_savedata.cpp
    file_sys/archive_source_sd_savedata.h
    file_sys/archive_systemsavedata.cpp
    file_sys/archive_systemsavedata.h
    file_sys/cia_common.h
    file_sys/cia_container.cpp
    file_sys/cia_container.h
    file_sys/directory_backend.h
    file_sys/disk_archive.cpp
    file_sys/disk_archive.h
    file_sys/errors.h
    file_sys/file_backend.h
    file_sys/delay_generator.cpp
    file_sys/delay_generator.h
    file_sys/ivfc_archive.cpp
    file_sys/ivfc_archive.h
    file_sys/layered_fs.cpp
    file_sys/layered_fs.h
    file_sys/ncch_container.cpp
    file_sys/ncch_container.h
    file_sys/patch.cpp
    file_sys/patch.h
    file_sys/path_parser.cpp
    file_sys/path_parser.h
    file_sys/plugin_3gx.cpp
    file_sys/plugin_3gx.h
    file_sys/plugin_3gx_bootloader.h
    file_sys/romfs_reader.cpp
    file_sys/romfs_reader.h
    file_sys/savedata_archive.cpp
    file_sys/savedata_archive.h
    file_sys/seed_db.cpp
    file_sys/seed_db.h
    file_sys/ticket.cpp
    file_sys/ticket.h
    file_sys/title_metadata.cpp
    file_sys/title_metadata.h
    frontend/applets/default_applets.cpp
    frontend/applets/default_applets.h
    frontend/applets/mii_selector.cpp
    frontend/applets/mii_selector.h
    frontend/applets/swkbd.cpp
    frontend/applets/swkbd.h
    frontend/camera/blank_camera.cpp
    frontend/camera/blank_camera.h
    frontend/camera/factory.cpp
    frontend/camera/factory.h
    frontend/camera/interface.cpp
    frontend/camera/interface.h
    frontend/emu_window.cpp
    frontend/emu_window.h
    frontend/framebuffer_layout.cpp
    frontend/framebuffer_layout.h
    frontend/image_interface.cpp
    frontend/image_interface.h
    frontend/input.h
    gdbstub/gdbstub.cpp
    gdbstub/gdbstub.h
    gdbstub/hio.cpp
    gdbstub/hio.h
    hle/applets/applet.cpp
    hle/applets/applet.h
    hle/applets/erreula.cpp
    hle/applets/erreula.h
    hle/applets/mii_selector.cpp
    hle/applets/mii_selector.h
    hle/applets/mint.cpp
    hle/applets/mint.h
    hle/applets/swkbd.cpp
    hle/applets/swkbd.h
    hle/ipc.h
    hle/ipc_helpers.h
    hle/kernel/address_arbiter.cpp
    hle/kernel/address_arbiter.h
    hle/kernel/client_port.cpp
    hle/kernel/client_port.h
    hle/kernel/client_session.cpp
    hle/kernel/client_session.h
    hle/kernel/config_mem.cpp
    hle/kernel/config_mem.h
    hle/kernel/errors.h
    hle/kernel/event.cpp
    hle/kernel/event.h
    hle/kernel/handle_table.cpp
    hle/kernel/handle_table.h
    hle/kernel/hle_ipc.cpp
    hle/kernel/hle_ipc.h
    hle/kernel/ipc.cpp
    hle/kernel/ipc.h
    hle/kernel/ipc_debugger/recorder.cpp
    hle/kernel/ipc_debugger/recorder.h
    hle/kernel/kernel.cpp
    hle/kernel/kernel.h
    hle/kernel/memory.cpp
    hle/kernel/memory.h
    hle/kernel/mutex.cpp
    hle/kernel/mutex.h
    hle/kernel/object.cpp
    hle/kernel/object.h
    hle/kernel/process.cpp
    hle/kernel/process.h
    hle/kernel/resource_limit.cpp
    hle/kernel/resource_limit.h
    hle/kernel/semaphore.cpp
    hle/kernel/semaphore.h
    hle/kernel/server_port.cpp
    hle/kernel/server_port.h
    hle/kernel/server_session.cpp
    hle/kernel/server_session.h
    hle/kernel/session.h
    hle/kernel/session.cpp
    hle/kernel/shared_memory.cpp
    hle/kernel/shared_memory.h
    hle/kernel/shared_page.cpp
    hle/kernel/shared_page.h
    hle/kernel/svc.cpp
    hle/kernel/svc.h
    hle/kernel/svc_wrapper.h
    hle/kernel/thread.cpp
    hle/kernel/thread.h
    hle/kernel/timer.cpp
    hle/kernel/timer.h
    hle/kernel/vm_manager.cpp
    hle/kernel/vm_manager.h
    hle/kernel/wait_object.cpp
    hle/kernel/wait_object.h
    hle/mii.h
    hle/mii.cpp
    hle/result.h
    hle/romfs.cpp
    hle/romfs.h
    hle/service/ac/ac.cpp
    hle/service/ac/ac.h
    hle/service/ac/ac_i.cpp
    hle/service/ac/ac_i.h
    hle/service/ac/ac_u.cpp
    hle/service/ac/ac_u.h
    hle/service/act/act.cpp
    hle/service/act/act.h
    hle/service/act/act_a.cpp
    hle/service/act/act_a.h
    hle/service/act/act_u.cpp
    hle/service/act/act_u.h
    hle/service/am/am.cpp
    hle/service/am/am.h
    hle/service/am/am_app.cpp
    hle/service/am/am_app.h
    hle/service/am/am_net.cpp
    hle/service/am/am_net.h
    hle/service/am/am_sys.cpp
    hle/service/am/am_sys.h
    hle/service/am/am_u.cpp
    hle/service/am/am_u.h
    hle/service/apt/applet_manager.cpp
    hle/service/apt/applet_manager.h
    hle/service/apt/apt.cpp
    hle/service/apt/apt.h
    hle/service/apt/apt_a.cpp
    hle/service/apt/apt_a.h
    hle/service/apt/apt_s.cpp
    hle/service/apt/apt_s.h
    hle/service/apt/apt_u.cpp
    hle/service/apt/apt_u.h
    hle/service/apt/ns.cpp
    hle/service/apt/ns.h
    hle/service/apt/ns_c.cpp
    hle/service/apt/ns_c.h
    hle/service/apt/ns_s.cpp
    hle/service/apt/ns_s.h
    hle/service/apt/bcfnt/bcfnt.cpp
    hle/service/apt/bcfnt/bcfnt.h
    hle/service/apt/errors.h
    hle/service/boss/boss.cpp
    hle/service/boss/boss.h
    hle/service/boss/boss_p.cpp
    hle/service/boss/boss_p.h
    hle/service/boss/boss_u.cpp
    hle/service/boss/boss_u.h
    hle/service/boss/online_service.cpp
    hle/service/boss/online_service.h
    hle/service/cam/cam.cpp
    hle/service/cam/cam.h
    hle/service/cam/cam_c.cpp
    hle/service/cam/cam_c.h
    hle/service/cam/cam_params.h
    hle/service/cam/cam_q.cpp
    hle/service/cam/cam_q.h
    hle/service/cam/cam_s.cpp
    hle/service/cam/cam_s.h
    hle/service/cam/cam_u.cpp
    hle/service/cam/cam_u.h
    hle/service/cam/y2r_u.cpp
    hle/service/cam/y2r_u.h
    hle/service/cecd/cecd.cpp
    hle/service/cecd/cecd.h
    hle/service/cecd/cecd_ndm.cpp
    hle/service/cecd/cecd_ndm.h
    hle/service/cecd/cecd_s.cpp
    hle/service/cecd/cecd_s.h
    hle/service/cecd/cecd_u.cpp
    hle/service/cecd/cecd_u.h
    hle/service/cfg/cfg.cpp
    hle/service/cfg/cfg.h
    hle/service/cfg/cfg_defaults.cpp
    hle/service/cfg/cfg_defaults.h
    hle/service/cfg/cfg_i.cpp
    hle/service/cfg/cfg_i.h
    hle/service/cfg/cfg_nor.cpp
    hle/service/cfg/cfg_nor.h
    hle/service/cfg/cfg_s.cpp
    hle/service/cfg/cfg_s.h
    hle/service/cfg/cfg_u.cpp
    hle/service/cfg/cfg_u.h
    hle/service/csnd/csnd_snd.cpp
    hle/service/csnd/csnd_snd.h
    hle/service/dlp/dlp.cpp
    hle/service/dlp/dlp.h
    hle/service/dlp/dlp_clnt.cpp
    hle/service/dlp/dlp_clnt.h
    hle/service/dlp/dlp_fkcl.cpp
    hle/service/dlp/dlp_fkcl.h
    hle/service/dlp/dlp_srvr.cpp
    hle/service/dlp/dlp_srvr.h
    hle/service/dsp/dsp_dsp.cpp
    hle/service/dsp/dsp_dsp.h
    hle/service/err/err_f.cpp
    hle/service/err/err_f.h
    hle/service/frd/frd.cpp
    hle/service/frd/frd.h
    hle/service/frd/frd_a.cpp
    hle/service/frd/frd_a.h
    hle/service/frd/frd_u.cpp
    hle/service/frd/frd_u.h
    hle/service/fs/archive.cpp
    hle/service/fs/archive.h
    hle/service/fs/directory.cpp
    hle/service/fs/directory.h
    hle/service/fs/file.cpp
    hle/service/fs/file.h
    hle/service/fs/fs_user.cpp
    hle/service/fs/fs_user.h
    hle/service/gsp/gsp.cpp
    hle/service/gsp/gsp.h
    hle/service/gsp/gsp_gpu.cpp
    hle/service/gsp/gsp_gpu.h
    hle/service/gsp/gsp_lcd.cpp
    hle/service/gsp/gsp_lcd.h
    hle/service/hid/hid.cpp
    hle/service/hid/hid.h
    hle/service/hid/hid_spvr.cpp
    hle/service/hid/hid_spvr.h
    hle/service/hid/hid_user.cpp
    hle/service/hid/hid_user.h
    hle/service/http/http_c.cpp
    hle/service/http/http_c.h
    hle/service/ir/extra_hid.cpp
    hle/service/ir/extra_hid.h
    hle/service/ir/ir.cpp
    hle/service/ir/ir.h
    hle/service/ir/ir_rst.cpp
    hle/service/ir/ir_rst.h
    hle/service/ir/ir_u.cpp
    hle/service/ir/ir_u.h
    hle/service/ir/ir_user.cpp
    hle/service/ir/ir_user.h
    hle/service/ldr_ro/cro_helper.cpp
    hle/service/ldr_ro/cro_helper.h
    hle/service/ldr_ro/ldr_ro.cpp
    hle/service/ldr_ro/ldr_ro.h
    hle/service/mic/mic_u.cpp
    hle/service/mic/mic_u.h
    hle/service/mvd/mvd.cpp
    hle/service/mvd/mvd.h
    hle/service/mvd/mvd_std.cpp
    hle/service/mvd/mvd_std.h
    hle/service/ndm/ndm_u.cpp
    hle/service/ndm/ndm_u.h
    hle/service/news/news.cpp
    hle/service/news/news.h
    hle/service/news/news_s.cpp
    hle/service/news/news_s.h
    hle/service/news/news_u.cpp
    hle/service/news/news_u.h
    hle/service/nfc/amiibo_crypto.cpp
    hle/service/nfc/amiibo_crypto.h
    hle/service/nfc/nfc.cpp
    hle/service/nfc/nfc.h
    hle/service/nfc/nfc_device.cpp
    hle/service/nfc/nfc_device.h
    hle/service/nfc/nfc_m.cpp
    hle/service/nfc/nfc_m.h
    hle/service/nfc/nfc_results.h
    hle/service/nfc/nfc_types.h
    hle/service/nfc/nfc_u.cpp
    hle/service/nfc/nfc_u.h
    hle/service/nim/nim.cpp
    hle/service/nim/nim.h
    hle/service/nim/nim_aoc.cpp
    hle/service/nim/nim_aoc.h
    hle/service/nim/nim_s.cpp
    hle/service/nim/nim_s.h
    hle/service/nim/nim_u.cpp
    hle/service/nim/nim_u.h
    hle/service/nwm/nwm.cpp
    hle/service/nwm/nwm.h
    hle/service/nwm/nwm_cec.cpp
    hle/service/nwm/nwm_cec.h
    hle/service/nwm/nwm_ext.cpp
    hle/service/nwm/nwm_ext.h
    hle/service/nwm/nwm_inf.cpp
    hle/service/nwm/nwm_inf.h
    hle/service/nwm/nwm_sap.cpp
    hle/service/nwm/nwm_sap.h
    hle/service/nwm/nwm_soc.cpp
    hle/service/nwm/nwm_soc.h
    hle/service/nwm/nwm_tst.cpp
    hle/service/nwm/nwm_tst.h
    hle/service/nwm/nwm_uds.cpp
    hle/service/nwm/nwm_uds.h
    hle/service/nwm/uds_beacon.cpp
    hle/service/nwm/uds_beacon.h
    hle/service/nwm/uds_connection.cpp
    hle/service/nwm/uds_connection.h
    hle/service/nwm/uds_data.cpp
    hle/service/nwm/uds_data.h
    hle/service/plgldr/plgldr.cpp
    hle/service/plgldr/plgldr.h
    hle/service/pm/pm.cpp
    hle/service/pm/pm.h
    hle/service/pm/pm_app.cpp
    hle/service/pm/pm_app.h
    hle/service/pm/pm_dbg.cpp
    hle/service/pm/pm_dbg.h
    hle/service/ps/ps_ps.cpp
    hle/service/ps/ps_ps.h
    hle/service/ptm/ptm.cpp
    hle/service/ptm/ptm.h
    hle/service/ptm/ptm_gets.cpp
    hle/service/ptm/ptm_gets.h
    hle/service/ptm/ptm_play.cpp
    hle/service/ptm/ptm_play.h
    hle/service/ptm/ptm_sets.cpp
    hle/service/ptm/ptm_sets.h
    hle/service/ptm/ptm_sysm.cpp
    hle/service/ptm/ptm_sysm.h
    hle/service/ptm/ptm_u.cpp
    hle/service/ptm/ptm_u.h
    hle/service/pxi/dev.cpp
    hle/service/pxi/dev.h
    hle/service/pxi/pxi.cpp
    hle/service/pxi/pxi.h
    hle/service/qtm/qtm.cpp
    hle/service/qtm/qtm.h
    hle/service/qtm/qtm_c.cpp
    hle/service/qtm/qtm_c.h
    hle/service/qtm/qtm_s.cpp
    hle/service/qtm/qtm_s.h
    hle/service/qtm/qtm_sp.cpp
    hle/service/qtm/qtm_sp.h
    hle/service/qtm/qtm_u.cpp
    hle/service/qtm/qtm_u.h
    hle/service/service.cpp
    hle/service/service.h
    hle/service/sm/sm.cpp
    hle/service/sm/sm.h
    hle/service/sm/srv.cpp
    hle/service/sm/srv.h
    hle/service/soc/soc_u.cpp
    hle/service/soc/soc_u.h
    hle/service/ssl/ssl_c.cpp
    hle/service/ssl/ssl_c.h
    hw/aes/arithmetic128.cpp
    hw/aes/arithmetic128.h
    hw/aes/ccm.cpp
    hw/aes/ccm.h
    hw/aes/key.cpp
    hw/aes/key.h
    hw/gpu.cpp
    hw/gpu.h
    hw/hw.cpp
    hw/hw.h
    hw/lcd.cpp
    hw/lcd.h
    hw/rsa/rsa.cpp
    hw/rsa/rsa.h
    hw/y2r.cpp
    hw/y2r.h
    loader/3dsx.cpp
    loader/3dsx.h
    loader/elf.cpp
    loader/elf.h
    loader/loader.cpp
    loader/loader.h
    loader/ncch.cpp
    loader/ncch.h
    loader/smdh.cpp
    loader/smdh.h
    memory.cpp
    memory.h
    movie.cpp
    movie.h
    nus_download.cpp
    nus_download.h
    perf_stats.cpp
    perf_stats.h
    precompiled_headers.h
    savestate.cpp
    savestate.h
    savestate_data.h
    system_titles.cpp
    system_titles.h
    telemetry_session.cpp
    telemetry_session.h
    tracer/citrace.h
    tracer/recorder.cpp
    tracer/recorder.h
)

create_target_directory_groups(citra_core)

target_link_libraries(citra_core PUBLIC citra_common PRIVATE audio_core network video_core)
target_link_libraries(citra_core PRIVATE Boost::boost Boost::serialization Boost::iostreams httplib)
target_link_libraries(citra_core PUBLIC dds-ktx PRIVATE cryptopp fmt lodepng open_source_archives)

if (ENABLE_WEB_SERVICE)
    target_link_libraries(citra_core PRIVATE web_service)
endif()

if (ENABLE_SCRIPTING)
    target_compile_definitions(citra_core PUBLIC -DENABLE_SCRIPTING)
    target_sources(citra_core PRIVATE
        rpc/packet.cpp
        rpc/packet.h
        rpc/rpc_server.cpp
        rpc/rpc_server.h
        rpc/server.cpp
        rpc/server.h
        rpc/udp_server.cpp
        rpc/udp_server.h
    )
endif()

if ("x86_64" IN_LIST ARCHITECTURE OR "arm64" IN_LIST ARCHITECTURE)
    target_sources(citra_core PRIVATE
        arm/dynarmic/arm_dynarmic.cpp
        arm/dynarmic/arm_dynarmic.h
        arm/dynarmic/arm_dynarmic_cp15.cpp
        arm/dynarmic/arm_dynarmic_cp15.h
        arm/dynarmic/arm_exclusive_monitor.cpp
        arm/dynarmic/arm_exclusive_monitor.h
        arm/dynarmic/arm_tick_counts.cpp
        arm/dynarmic/arm_tick_counts.h
    )
    target_link_libraries(citra_core PRIVATE dynarmic)
endif()

if (CITRA_USE_PRECOMPILED_HEADERS)
    target_precompile_headers(citra_core PRIVATE precompiled_headers.h)
endif()
