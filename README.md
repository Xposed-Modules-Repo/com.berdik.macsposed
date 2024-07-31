# MACsposed
<img align="left" src="https://raw.githubusercontent.com/DavidBerdik/MACsposed/master/images/ic_launcher-playstore.png" width="140" />

Historically, setting a custom MAC address on Android was very easy for rooted users. Starting with Android 12, however, Google's implementation of MAC address randomization has made it impossible, as the MAC address is always changed when the network state is altered. If you have encountered this problem, then you need MACsposed! MACsposed is an Xposed module that blocks the MAC address randomizer on Android 12 through 14 and allows you to once again make use of your favorite tools for setting your MAC address. Simply install MACsposed, enable it, and go back to randomizing your MAC address using your favorite tools for doing so!

**⚠️ WARNING:** MACsposed is intended for rooted devices running Android 12 through 14 and requires Xposed. The required Xposed variant to use is LSPosed. Other Xposed variants will not work. Additionally, this module cannot be guaranteed to work on all devices. In the worst case, it can cause a bootloop. Use at your own risk.

<p align="center">
  <a href="https://play.google.com/store/apps/details?id=com.berdik.macsposed">
    <img src="https://raw.githubusercontent.com/DavidBerdik/MACsposed/master/images/google-play-badge.png" height="80" />
  </a>
</p>