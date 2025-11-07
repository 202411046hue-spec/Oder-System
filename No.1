from flask import Flask, render_template, request, redirect

app = Flask(__name__)

orders = []

@app.route('/')
def menu():
    menu_items = [
        {'name': 'コーヒー', 'price': 400, 'category': 'ドリンク'},
        {'name': '紅茶', 'price': 350, 'category': 'ドリンク'},
        {'name': 'サンドイッチ', 'price': 600, 'category': 'フード'},
        {'name': 'チーズケーキ', 'price': 450, 'category': 'デザート'},
    ]
    return render_template('menu.html', menu_items=menu_items)

@app.route('/order', methods=['POST'])
def order():
    item = request.form.get('item')
    orders.append(item)
    return redirect('/')

@app.route('/admin')
def admin():
    return render_template('admin.html', orders=orders)

if __name__ == '__main__':
    app.run(debug=True)
