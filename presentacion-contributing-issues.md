title: Issues y Contributing
output: index.html
controls: false
progress: true
style: style.css

--
# Issues y Contributing
## Cómo le respondemos a nuestra hermosa comunidad

-- separator
### Items de un repo "contribuible"

* `CONTRIBUTING.md`
* `ISSUE_TEMPLATE.md`
* `PULL_REQUEST_TEMPLATE.md`
* `LICENSE.md` (no abordamos)

Ver [Helping people contribute to your project](https://help.github.com/articles/helping-people-contribute-to-your-project/)

Ver [Contributing to Open Source on GitHub](https://guides.github.com/activities/contributing-to-open-source/)

--
### CONTRIBUTING.MD

* Código de conducta general  (**general**) _@solpar hace una primera versión de esto ayudada por @ignacio_
* Estándares a seguir  (**general y específico**) _@beni + @gonzalobb hacen una primera revisión / discusión de esto y luego lo ven con @ignacio (lo digo así xq me parece más eficiente, pero si les parece los 3 a la vez también me parece bien)_
* Decisiones de diseño que conocer (**específico**)  _Dijimos que no va en el CONTRIBUTING.md , va en el README.md y se solicita leer bien el resto de la documentación_
* Tipos de contribuciones posibles (**ambas**)
   + Reportar un bug - _issue_ (**hacer template**)  _@gonzalobb  hace primera versión y revisa con @ignacio  y/o @beni_
   + Sugerir una mejora - _issue_ (**hacer template**)  _@ignacio hace primera versión y revisa con @gonzalobb y/o @beni_
   + Mejorar documentación - _pull request_
   + Begginer issues - _pull request_
   + Dejar una idea - _issue_
   + Tomar y solucionar issues existentes - _pull request_
* Cómo hacer un pull request (requisitos) (**ambas**) _Esto lo podemos dejar para más adelante, total tenemos bastante con las otras tareas me parece_

--
### CONTRIBUTING.MD (ejemplos)

Ver [CONTRIBUTING template de cookiecutter](https://github.com/audreyr/cookiecutter-pypackage/blob/master/CONTRIBUTING.rst)

Ver [Contributing to Atom](https://github.com/atom/atom/blob/master/CONTRIBUTING.md)

Ver [Contributing to Docker](https://github.com/docker/docker/blob/master/CONTRIBUTING.md)

Ver [Contributing to AngularJS](https://github.com/angular/angular.js/blob/master/CONTRIBUTING.md)

Ver [How to contribute to Ruby on Rails](https://github.com/rails/rails/blob/master/CONTRIBUTING.md)

Ver [Contributing to Ruby on Rails](http://edgeguides.rubyonrails.org/contributing_to_ruby_on_rails.html)

--
### ISSUE_TEMPLATE.MD (ejemplos)

Ver [React native](https://github.com/facebook/react-native/issues/new)

Modelo de [ISSUE_TEMPLATE de cookiecutter](https://github.com/audreyr/cookiecutter-pypackage/blob/master/.github/ISSUE_TEMPLATE.md)

    * {{ cookiecutter.project_name }} version:
    * Python version:
    * Operating System:

    ### Description
    Describe what you were trying to get done.
    Tell us what happened, what went wrong, and what you expected to happen.

    ### What I Did

    ```
    Paste the command(s) you ran and the output.
    If there was a crash, please include the traceback here.
    ```
