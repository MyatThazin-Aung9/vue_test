# vue_test (not cli)

# learn/test with CDN => development version

See [Configuration Reference](https://v2.vuejs.org/v2/guide/).

# vue syntax

new Vue({ <br>
  // options <br>
  el: '#test',<br>
  data: {<br>
          message: 'Start vue'<br>
        }<br>
  methods: {<br>
              //option function<br>
           }  
})<br>

# parameters flow of vuejs

The **Vue function** takes an object as an argument, which contains various options for configuring the Vue instance. Some of the most commonly used options include:

**el:** This option specifies the DOM element that the Vue instance should be associated with. The value of this option can be a CSS selector string, or a reference to a DOM element.

**data:** This option contains the data that will be used by the Vue instance. It should be an object with properties that correspond to the data that you want to use in the app.

**methods:** This option contains the methods that will be available to the Vue instance. It should be an object with properties that correspond to the methods that you want to use in the app.  They can be defined as functions in the methods property of the options object. 

**computed:** This option is similar the function of methods property except need to return and when data binding, no need to add ().
