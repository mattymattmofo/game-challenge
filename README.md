<h1>Welcome to the Game Challenge!</h1>
<p>Grab the files and drop them into your UDK install dir.</p>
<hr />

<h2>Quick start for side scroll platformer:</h2>

<p>After cloning repository and placing files in UDK file structure you will need to edit a config INI file and set game type in the map.</p>

<ol>
  <li>Open \UDKGame\Config\DefaultEngine.ini - Add <strong>+EditPackages=StarterPlatformGame</strong> under [UnrealEd.EditorEngine]</li>
  <li>Start Unreal Frontend (\Binaries\UnrealFrontend.exe), click clone and rename the profile to your liking</li>
  <li>Maps to cook: Remove any maps, then add StarterPlatformMap.udk (That should be the only map your cooking)</li>
  <li>Click Script - This will drop down. Click Full Compile</li>
  <li>Start UDK Editor, click UnrealEd button</li>
  <li>Open the map StarterPlatformMap.udk
    <ul>
      <li>Goto View > World Properties</li>
      <li>Click Game Type to expand</li>
      <li>From Default Game Type drop down select SPG_GameInfo and save the map</li>
    </ul>
  </li>
  <li>Now your ready to play. Click the green play button in the top right (Opens new window). If you click the blue play button it will launch the game in the viewport.</li>
</ol>

<hr />

<p>I will be adding more about UnrealScript and where to begin building our game.</p>
