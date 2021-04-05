git checkout --orphan newBranch # yeni branch oluşturuyoruz
git add -A  # dosyaları yeni branch'e ekleyelim
git commit -m "Mesaj" # dosyaları commit Etme
git branch -D master  # master branch'i silme
git branch -m master  # Mevcut branch'i master branch yaptık
git push -f origin master  # github'daki master branch'e Force push
git gc --aggressive --prune=all     # eski dosyaları silme
