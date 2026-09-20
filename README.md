<div align="right">
  welcome to my epic profile, here's my facecam:
  <img width="175" height="130" alt="ok" src="https://github.com/user-attachments/assets/4257f2d1-bb7b-4372-8d4c-bd44f011985a" />
</div>

---
### Hey, I'm Gavff! 🐸🌹
- Just a hobbyist Ruby programmer.
- I totally know what I'm doing.
- I definitely have a ton of professional experience. <img width="14" height="19" alt="kappa" src="https://github.com/user-attachments/assets/f98c61b4-7fdf-4b39-9716-a092dc030b51" />
- The name is pronounced "gaff".

### Ruby is cool  <img width="16" height="16" alt="Ruby_logo" src="https://github.com/user-attachments/assets/34344d86-fd89-4f38-a899-c97ab04d13ad" />

```bash
gem install lzstring
```

```ruby
require "net/http"
require "json"
require "lzstring"

STDOUT.sync = true
data = Net::HTTP.get(URI("https://raw.githubusercontent.com/EmirXK/bad_apple/master/framesData.lz"))
frames = JSON.parse(LZString.decompress_from_base64(data))

print "\e[H\e[2J"
frames.each do |frame|
  print "\e[H", frame.gsub("\\n", "\n")
  sleep 0.03
end
```
*very cool...*
<div align="left">
  <img width="150" height="100" alt="love" src="https://github.com/user-attachments/assets/80901d55-72d1-49f1-9f7e-2117e864e536" />
</div>
