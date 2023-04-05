{% include head.html %}
    <div class="container-flued blog-container" style='background-image:url({{page.featured-image}})'>
        <div class="banner-featured ">
            <div class="banner-title article-heading">
                <h1>{{page.title}}</h1>
                <span>10/14/2023</span>
            </div>
        </div>
    </div>
    <div class="container">
    <section>
        {% for post in site.categories.pre-training limit: 1 %}
        <div class="menu">
            <a href="/{{post.category}}/"><h2>{{post.title}}</h2></a>    
        </div>
        {% endfor %}   
    </section>
    </div>
{% include foot.html %}





