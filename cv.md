## Dzmitry Anatska

***
## Contacts

* [e-mail](mailto:anatskodr@gmail.com)
* [LinkedIn](https://www.linkedin.com/in/dima-anatsko/)
##Summary

I want to develop in the field of web development and benefit people
##Skills

####Technical
Python, Django, Flask, PostgreSQL, Django REST Framework, Git, GitHub, Docker, Linux, HTML, CSS, Bootstrap, Jinja2, Celery, Redis, SQL, JSON, YAML, XML, CSV, BeautifulSoup, Postman, Flake8, PyCharm.

####Leadership
Team management, planning, control, independence, communication and prompt problem solving.
##Сode example

```python
@app.route('/marakas/api/v1.0/products/<int:product_id>', methods=['GET'])
@cache.cached(timeout=60, key_prefix=make_cache_key)
def index(product_id):
    page = request.args.get('page', default=1, type=int)
    offset = request.args.get('offset', default=1, type=int)
    data = get_data(product_id, page, offset)
    if data:
        return jsonify(data)
    return jsonify({'error': 'Not found'}), 404
```
##Projects

__CRM system for coffee shops based on Django__

The online application allows you to keep warehouse, management and financial records. Distribution of roles of Director and bartender. Functions of acceptance of goods, storage of goods in a warehouse, write-off from a warehouse are implemented. Formation of technological maps of cooking. Automatic calculation of the cost of finished products. Calculating the profitability of the cafe.
Tools & Technologies: Python, Django, PostgreSQL, HTML/CSS, Bootstrap, Jinja2.

__Internet-shop on Django__

Online store with sorting and filtering options. Customizable pagination for displaying large amounts of information. With the function of sending emails about promotions and sales. You can choose one of three languages for displaying content.
Tools & Technologies: Python, Django, PostgreSQL, HTML/CSS, Bootstrap, Celery, Redis, Django REST Framework.

__Parsers__

Parser for searching, collecting and retrieving information from various sites (depending on requirement).
Tools & Technologies: Python, BeautifulSoup, HTML, XML, CSV.
##Education

__Coding School TeachMeSkills__
_Python Developer • December, 2019 — June, 2020_
Python web application development, databases processing, implementation front-end using template Django, test coverage, functional programming, OOP.

__Coursera__
_Python Developer • September, 2019 — December, 2019_
The basics of programming in Python

__Belarusian State University of Informatics and Radioelectronics__
_Engineer • September, 2000 — June, 2005_
Higher engineering education
##English

At the time of writing the resume - pre-intermediate. But I am constantly working on improving my English
