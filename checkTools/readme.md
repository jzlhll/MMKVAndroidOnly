https://developer.android.google.cn/guide/practices/page-sizes?hl=zh-cn#groovy_1

chmod +x ...

unzip APK_NAME.apk -d /tmp/my_apk_out
alignment.sh /tmp/my_apk_out | grep "arm64-v8a"

zipalign -c -P 16 -v 4 APK_NAME.apk
