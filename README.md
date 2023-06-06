<h1 align="center">
  <b>Blokhin Artyom</b>
</h1>

Hey! I'm Artyom Blokhin, also know as a student, currently living in Moscow, Russia. I am actively looking for a part-time job, if you have any suggestions, contact me by <a href="https://telegram.me/akrov">**telegram**</a> or by <a href="mailto:akrovart@gmail.com">**e-mail**</a>.
<br>

<p>
<div align="center">
  <img src="https://img.shields.io/badge/Python-98b982?style=for-the-badge&logo=Python&logoColor=98b982&labelColor=282828"/>
  <img src="https://img.shields.io/badge/Golang-4DAFE1?style=for-the-badge&logo=goland&logoColor=4DAFE1&labelColor=282828"/>
</div>
</p>

```python
class ArtyomBlokhin():
  def __init__(self):
    self.name = "Artyom Blokhin"
    self.username = "akrovv"
    self.location = "Moscow, Russia"
    self.telegram = "@akrov"

  def get_info(self):
    return {
      'name': self.name,
      'username': self.username,
      'location': self.location,
      'telegram': self.telegram
    }

@app.route('/api/artyom', methods=['GET'])
def get_artyom_info():
  artyom = ArtyomBlokhin()
  info = artyom.get_info()
  return jsonify(info)

if __name__ == "__main__":
  app.run()
```

## My Statistics

<br/>
<p align="left">
  <img width="49.5%" src="https://github-readme-stats.vercel.app/api?username=akrovv&show_icons=true&theme=gruvbox&hide_border=True"/>
    <img width="49.5%" src="http://github-readme-streak-stats.herokuapp.com?user=akrovv&theme=gruvbox&hide_border=true&border_radius=3"/>
</p>
<br>


