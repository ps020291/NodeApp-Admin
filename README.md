## Node Js Admin Panel URL

  # https://ps020291.herokuapp.com 
  
  Node Application Using Handlebars Template Engines and Connected with Cloud MongoDB. 
  
    **Database Connection with MongoDB
    
    mongooseConnect : function(){
        mongoose.connect("mongodb://localhost:27017/nodeapp", (err)=>{
          if(err) console.log("Error "+err);
          else console.log("Connected to MongoDB");
        });
     }
  
  
  
## Modules :

   #### LoggedIn Users:
         User Registeration with encrypted Password using bcrypt\
         User List
         User Update
         User Delete
        
   #### Banners Management:
        Banner Add   (Upload Banner Image Using Multer)
        Banner List
        Banner Update
        Banner Delete
        
   #### Category Management
        Category Add  (Upload Category Image Using Multer)
        Category List
        Category Update
        Category Delete
        
   #### Brand Management
        Brand Add  (Upload Brand Image Using Multer)
        Brand List
        Brand Update
        Brand Delete
        
   #### Customer Management
        Customer Add  (Upload Customer Profile Image Using Multer)
        Customer List
        Customer Update
        Customer Delete
        
        
        
        
        
        
         
    
