# 火星 8.7.1 Modified APK

## 修改内容
- 域名替换: app.supermarsapp.com → app.xgp.cc.cd (主), app.huoxingbox.com → ding.i888.asia (副)
- RSA 公钥已替换
- LSParanoid 混淆保持不变

## 合并命令 (Linux/OpenWRT)
```bash
cat part_* > huoxing871_modified.apk
```

## 合并命令 (Windows)
```cmd
copy /b part_aa+part_ab+part_ac+part_ad+part_ae+part_af+part_ag huoxing871_modified.apk
```

## 校验
文件大小应为: 308417823 bytes (约294MB)
