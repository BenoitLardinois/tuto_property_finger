Voici comment lancer le programme :

DANS LE TERMINAL, TAPER LES COMMANDES SUIVANTES :

- git clone https://github.com/BenoitLardinois/tuto_property_finger.git

- cd tuto_property_finger/

- bundle install

- rails db:create

- rails db:migrate

- npm install

- rails server

(laisser tourner le serveur)
PUIS, DANS VOTRE NAVIGATEUR, SAISIR L'URL :

- http://localhost:3000/



1) générer les routes (routes.rb)
2) main.html.erb
3) Gemfile 
4) development.rb (config.action_mailer.default_url_options = { host: 'localhost', port: 3000 })
5) application.html.erb (layouts)
6) générer migration DeviseCreateAccounts
7) creation migration CreateProperties
9) property.rb (models)
10) account.rb (models)
11) _public.html.erb (générer controller) (nav)
12) _footer.html.erb (générer controller) (layouts)
13) new.html.erb (sessions)
14) devise.scss
15) new.html.erb (registrations)
16) modifier application_controller.rb 
17) _dashboard.html.erb (générer controller)
18) dashboard.scss
19) index.html.erb (dashboard)
20) _sidebar.html.erb (nav)
21) properties.scss
22) properties_controller (create)
23) https://feathericons.com
24) index.html.erb (properties)
25) _form.html.erb (properties)
26) edit.html.erb (properties)
27) _validation.html.erb (layouts)
28) show.html.erb (properties)
30) public.scss (assets/stylesheets)
31) créer un dossier uploader (dans app)
32) photo_uploader.rb (uploader)
33) application.yml (config)
34) carrierwave.rb (initializers)
ATTENTION PAS DE CLE AMAZON AWS !!!!!!
35) _latest_properties.html.erb (properties)
36) properties_helper.rb
37) public_controller.rb (controller) 
38) dashboard_controoller 
39) _agent_details.html.erb (view in properties)
40) generate migration parking_spaces
41) generate migration details:text
42) création d’un dossier includes dans app/javascript
43) properties.js dans app/javascript/includes
44) application.js
45) mac$ yarn add jquery popper.js  AND mac$ yarn add bootstrap
46) environnement.js dans config/webpack
47) application.css (modification)
48) edit.html.erb (registrations)
49) new migration add_image_to_accounts
50) application_helper.rb
51) profile_picture_uploader.rb in uploaders
52) $ yarn add @fortawesome/fontawesome-free
53) Rename  _latest_properties.html.erb ro _list.html.erb
54) favicon.io and put the folder in app/assests/images
55) yarn add toastr
56) new routes     get "/profile/:id" => 'dashboard#profile', as: :profile
57) profile.html.erb in dashboard view
58) rails g migration add_for_sale_to_properties for_sale:boolean
59) rails g migration add_available_date_to_properties available_date:datetime
60) rails g migration add_telephone_to_accounts telephone:string
61) _send_email_modal.html.erb
62) contact_mailer.rb in app/mailers
63) new folder contact_mailer in views
64) email_agent.html.erb in views/contact_mailer
65) email_agent.text.erb in views/contact_mailer
66) rails g migration add_admin_to_accounts admin:boolean
67) admin_controller.rb
68) folder admin in views
69) accounts.html.erb in views/admin
70) _user.html.erb in views/layouts/nav/
71) _admin.html.erb in views/layouts/nav/
72) rails g migration add_status_to_properties status:string
73) rails g migration add_details_to_accounts details:text
74) rails g scaffold Post title:string url:string summary:string body:text image:string active:boolean
75) latest.html.erb in views/posts
76) _list.html.erb in views/posts