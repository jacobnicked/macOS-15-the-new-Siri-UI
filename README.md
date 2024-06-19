# macOS 15 - the new Siri UI
Enable the new Siri UI on macOS Sequoia 15.

<p><kbd><img src="files/thenewsiriui.png"></kbd></p>

## How to enable or disable
### Enabling
<ol>
  <li>Open Terminal.
    <ul>
      <li>Open Launchpad or press F4 on your Apple keyboard, go to the Other folder and look for Terminal.</li>
      <li>Open Launchpad or press F4 on your Apple keyboard and search "Terminal".</li>
      <li>Press ⌘/⊞ + Space and search "Terminal".</li>
    </ul>
  <li>
    Copy the command below and paste it into the Terminal app.<br />
    
    defaults write com.apple.assistant bypassDeviceSupportsSAE -bool true && killall Siri && killall SystemUIServer
    
  </li>
  <li>Press Enter to enable the new UI and you are done!</li>
</ol>

### Disabling
<ol>
  <li>Open Terminal.
    <ul>
      <li>Open Launchpad or press F4 on your Apple keyboard, go to the Other folder and look for Terminal.</li>
      <li>Open Launchpad or press F4 on your Apple keyboard and search "Terminal".</li>
      <li>Press ⌘/⊞ + Space and search "Terminal".</li>
    </ul>
  <li>
    Copy the command below and paste it into the Terminal app.<br />
    
    defaults write com.apple.assistant bypassDeviceSupportsSAE -bool false && killall Siri && killall SystemUIServer
    
  </li>
  <li>Press Enter to disable the new UI and you are done!</li>
</ol>
<p>No sudo command is required!</p>

<br>
