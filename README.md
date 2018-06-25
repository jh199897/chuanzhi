# chuanzhi
这是一个很强的项目

form flask import Flask

app = Flask(__name)

@app.route('/')
def index():
  return  'index'
