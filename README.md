# go-Vlan-Scanner

基于Fscan进行企业定制，定制的部分包括加入内部CMS历史版本漏洞识别规则、针对用户名/密码爆破字典进行定制，提高SSH、FTP、Mysql、RDP等密码爆破成功率。

Based on Fscan, enterprise customization includes adding internal CMS historical version vulnerability detection rules and customizing username/password brute force dictionaries to improve the success rate of password cracking for SSH, FTP, MySQL, RDP, etc.


### use
PS C:\Users\Administrator\Desktop\scan> C:\Users\Administrator\Desktop\scan\mgtj_vlan.exe
```
    #  #       #                             ########           #
    #   ##    ###      ##############   #         ##       #    ##  #
    #    ##  ##        ##         ##    ##     ## #     ##### ########
    # #############    ##         ##     ##  #  ##  #     ##    ## ##
    #      ##          ## ####### ##     #   #########    ## ##########
    #  ###########     ##   ##    ##      #  ## ## ##    ##     ## ##
    #      ##          ##   ## #  ##   ##### ########    # #  #######
    ################   ## ####### ##     ##  ## ## ##   #####   ## #
    #      ##          ##   ###   ##     ##  ## ## ##     ##    ##
    #      ##          ##   ####  ##     ##  ########     ## ########
    # #############    ##   ## ## ##     ##  ## ## ##   # ##    ##
    #     ## #         ##   ## #  ##     ##  ## ## ##    ### #########
    #    ##   ##       #############     ### ## # ###     ###   ##
    #   ##     ###     ##         ##    ## ###     #     ## ### #
    #  ##       ####   #############   ##   ##########   #   ##########
    ###           #    #          #     #    ########   #      #######
```
                                                              网信安检查工具-C段漏洞扫描
           example: mgtj_vlan.exe -h 10.217.7.1/24
           example: mgtj_vlan.exe -u http://10.217.7.1:1801/web.html
PS C:\Users\Administrator\Desktop\scan>