`https://www.reddit.com/r/linuxaudio/comments/f5y7k9/focusrite_scarlett_solo_shuts_off_when_its_not_in/`

if you are using interface in Pulseaudio, try this - pactl unload-module module-suspend-on-idle
