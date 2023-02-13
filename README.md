<html lang="en">
    <head>
        <meta charset="utf-8" />
        <meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no" />
        <meta name="description" content="" />
        <meta name="author" content="" />
        <title>DATA Department of TCI Khorasan{% endblock %}
       
    </head>
    <body>
        <!-- Responsive navbar-->
        <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
            <div class="container px-5">
                <a class="navbar-brand" href="">Network Resource Allocation</a>
                <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation"><span class="navbar-toggler-icon"></span></button>
                <div class="collapse navbar-collapse" id="navbarSupportedContent">
                    <ul class="navbar-nav ms-auto mb-2 mb-lg-0">
                        <li class="nav-item"><a class="nav-link" aria-current="page" 
                            href="{% url 'home' %}">Home</a></li>
                        <li class="nav-item"><a class="nav-link"
                            href="{% url 'search' %}">Search</a></li> 
                        <li class="nav-item"><a class="nav-link" 
                            href="{% url 'gateway' %}">Reserve</a></li>
                        <li class="nav-item"><a class="nav-link" 
                            href="{% url 'report' %}">Report</a></li>
                        {% if user.is_authenticated %}
                            <li class="nav-item"><a class="nav-link" 
                                href="{% url 'logout' %}">Logout</a></li>
                        {% else %}
                            <li class="nav-item"><a class="nav-link" 
                                href="{% url 'login' %}">Login</a></li>
                        {% endif%}
                        <li class="nav-item"><a class="nav-link" 
                            href="{% url 'about' %}">About</a></li>
                    </ul>
                </div>
            </div>
        </nav>
        <!-- Page Content-->
        <header id="main_header">
           
        </header>

        <main>
           
        </main>

        <!-- Footer-->
        <footer class="py-5 bg-dark">
                <div class="container px-4 px-lg-5"><p class="m-0 text-center text-white">Copyright &copy;  TCI-Khorasan 2023</p></div>
        </footer>
        <!-- Bootstrap core JS-->
        
            <!-- Core theme JS-->
        
    </body>
</html>
