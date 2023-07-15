# BE Project REST-Rant

BE-REST-Rant is an app where users can review restaurants.

# Routes

 **Method** | **Path**                  | **Purpose**                                          
------------|---------------------------|------------------------------------------------------
 GET        | /                         | Home page                                            
 GET        | /places                   | Places index page                                    
 POST       | /places                   | Create new place                                     
 GET        | /places/new               | Form page for creating a new place                   
 GET        | /places/:id               | Details about a particular place                     
 PUT        | /places/:id               | Update a particular place                            
 GET        | /places/:id/edit          | Form page for editing an existing place              
 DELETE     | /places/:id               | Delete a particular place                            
 POST       | /places/:id/rant          | Create a rant \(comment\) about a particular place   
 DELETE     | /places/:id/rant/:rantId  | Delete a rant \(comment\) about a particular place   
 GET        | \*                        | 404 page  \(matches any route not defined above\)    



# Places Table

 **City**    | **State** | **Cuisines** | **Pics** 
-------------|-----------|--------------|----------
 Raleigh     | NC        | American     |          
 Charlotte   | NC        | Chinese      |          
 Rocky Mount | NC        | Japanese     |          
 Roanoke     | VA        | American     |          
 Roanoke     | VA        | Chinese      |          
             |           |              |          



# Places array

 **Field Name** | **Data Type** 
----------------|----------------
 name           | string         
 city           | string         
 state          | string         
 cuisines       | string         
 pic            | string (a URL) 

