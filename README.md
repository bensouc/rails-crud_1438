##See all restaurants
  #get "/restaurants", to: "restaurants#index" OK
##See details about one restaurant
  #get "restaurants/:id", to: "restaurants#show" OK
##Create a restaurant
  #get "restaurants/new", to: "restaurants#new", as: :new_restaurant
  #post "restaurants", to: "restaurants#create"
##Update a restaurant OK
  #get "restaurants/:id/edit", to: "restaurants#edit", as: :edit_restaurant
   #patch "restaurants/:id", to: "restaurants#update"

##Destroy a restaurant 
  #delete "restaurants/:id", to "restaurants#destroy"
