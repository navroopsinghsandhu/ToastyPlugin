# ToastyPlugin
It’s an Android Cordova plugin that grants your application the ability to display Android’s Toasts - Toasts are the text messages that pop up at the bottom of the screen and then disappear

1. To add this plugin to your project run the following command in the root folder:                                                           
    cordova plugin add https://github.com/navroopsinghsandhu/ToastyPlugin.git                                                                         
2. Then add the following code in www/index.js of your project                                                                                                    
    window.plugins.toastyPlugin.show('It feels toasty in here!', 'long', function() {                                                                               
          console.log('Excelsior!');                                                                                                            
        }, function(err) {                                                                                                                                      
          console.log('Uh oh... ' + err);                                                                                                                   
        }); 
