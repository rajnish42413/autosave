# autosave
save input data as draft in js


# Call the function inputStore() on the target form fields and done.

$("#exampleFormControlInput1").inputStore();

$("#exampleFormControlSelect1").inputStore();

$("#exampleFormControlTextarea1").inputStore();

$("#exampleCheck1").inputStore();

# Set the expire date of the cookies. Default: 365.

$("#exampleFormControlInput1").inputStore({
    expire: 120
});

# Customize the cookie name.
   $("#exampleFormControlInput1").inputStore({
        name:this.attr("name")
      });
# Enable/disable the debug mode.
    $("#exampleFormControlInput1").inputStore({
      debug:false
   });
   
   
   
## Happy Coding

