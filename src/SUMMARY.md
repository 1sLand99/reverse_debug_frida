# 逆向调试利器：Frida

* [前言](README.md)
* [Frida概览](frida_overview/README.md)
  * [代码和架构](frida_overview/code_arch.md)
  * [文档和资料](frida_overview/doc_refer/README.md)
* [安装和升级](install_upgrade/README.md)
  * [安装Frida](install_upgrade/install_frida/README.md)
    * [电脑端](install_upgrade/install_frida/pc/README.md)
      * [Mac](install_upgrade/install_frida/pc/mac.md)
    * [移动端](install_upgrade/install_frida/mobile/README.md)
      * [iOS](install_upgrade/install_frida/mobile/ios.md)
      * [Android](install_upgrade/install_frida/mobile/android.md)
  * [升级Frida](install_upgrade/upgrade_frida.md)
* [使用Frida](use_frida/README.md)
  * [Frida典型使用逻辑](use_frida/typical_logic/README.md)
  * [frida](use_frida/frida_cli/README.md)
    * [调试目标方式](use_frida/frida_cli/debug_target.md)
    * [写js脚本](use_frida/frida_cli/js_script.md)
    * [典型使用方式](use_frida/frida_cli/typical_usage.md)
    * [iOS的ObjC](use_frida/frida_cli/ios_objc/README.md)
      * [ObjC的参数](use_frida/frida_cli/ios_objc/objc_para.md)
      * [ObjC的变量类型](use_frida/frida_cli/ios_objc/objc_var_type.md)
    * [数据类型](use_frida/frida_cli/data_type/README.md)
      * [NativePointer](use_frida/frida_cli/data_type/nativepointer.md)
    * [Frida的Stalker](use_frida/frida_cli/frida_stalker.md)
  * [frida-trace](use_frida/frida_trace/README.md)
    * [help语法](use_frida/frida_trace/help.md)
  * [frida-tools](use_frida/frida_tools/README.md)
    * [frida-ps](use_frida/frida_tools/frida_ps.md)
    * [frida-ls](use_frida/frida_tools/frida_ls.md)
    * [frida-ls-devices](use_frida/frida_tools/frida_ls_devices.md)
  * [其他相关](use_frida/other_related/README.md)
    * [frida-server](use_frida/other_related/frida_server.md)
* [Frida用法举例](frida_example/README.md)
* [经验心得](summary_note/README.md)
  * [hook函数](summary_note/hook_func/README.md)
    * [frida](summary_note/hook_func/frida/README.md)
      * [Interceptor](summary_note/hook_func/frida/interceptor/README.md)
        * [Stalker](summary_note/hook_func/frida/interceptor/stalker.md)
    * [frida-trace](summary_note/hook_func/frida_trace.md)
    * [常用iOS函数](summary_note/hook_func/common_ios_func.md)
  * [js](summary_note/js/README.md)
    * [console.log日志](summary_note/js/console_log.md)
  * [自己编译frida-server](summary_note/build_frida_server/README.md)
* [常见问题](common_issue/README.md)
  * [通用](common_issue/universal/README.md)
    * [Process terminated](common_issue/universal/process_terminated.md)
    * [unable to find process with name](common_issue/universal/unable_find_process.md)
    * [unable to attach to the specified proces](common_issue/universal/unable_to_attach_to_the_specified_proces.md)
    * [--no-pause和--pause](common_issue/universal/pause_or_no_pause.md)
    * [Bad access due to invalid address](common_issue/universal/bad_access_invalid_address.md)
    * [ValueError file descriptor cannot be a negative integer](common_issue/universal/file_descriptor_cannot_negative_integer.md)
    * [卡死在Spawning](common_issue/universal/stuck_spawning.md)
  * [iOS](common_issue/ios/README.md)
    * [XinaA15中的frida](common_issue/ios/xinaa15_frida.md)
    * [need Gadget to attach on jailed iOS](common_issue/ios/need_gadget_attach.md)
    * [导致iPhone重启](common_issue/ios/iphone_reboot.md)
    * [Waiting for USB device to appear](common_issue/ios/waiting_usb_device_appear.md)
    * [unable to intercept function at](common_issue/ios/unable_intercept_function_at.md)
  * [Android](common_issue/android/README.md)
    * [Java和js变量的映射关系](common_issue/android/java_js_mapping.md)
    * [java.lang.ClassNotFoundException](common_issue/android/java_lang_classnotfoundexception.md)
* [基于Frida的工具](frida_base_tool/README.md)
* [Frida的用途](frida_use_case/README.md)
  * [反调试](frida_use_case/anti_debug.md)
  * [辅助反混淆](frida_use_case/anti_obfuscation.md)
  * [绕过参数加密](frida_use_case/bypass_encrypted_para.md)
  * [逆向app](frida_use_case/reverse_app/README.md)
* [附录](appendix/README.md)
  * [参考资料](appendix/reference.md)
