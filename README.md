<div align="right">

  [![Linkedin: nandangpk](https://img.shields.io/badge/Nandang_Permana_Kusuma-white?style=flat-square&logo=Linkedin&logoColor=blue)](https://www.linkedin.com/in/nandang-permana-kusuma-10519a248/)
  [![Instagram: nandangpk](https://img.shields.io/badge/%40nandangpk-white?style=flat-square&logo=Instagram)](https://www.instagram.com/nandangpk)

</div>


```ruby
  my = Developer.find_by(:username => "nandangpk")
  p my.detail

  =>
  {
    :about => {
      :name => "Nandang Permana Kusuma",
      :gender => "Male",
      :tagline => "Not Your Average Software Engineer"
    },
    :skills => {
      :programming_language => [
        {"Ruby" => ["Ruby on Rails"]},
        {"PHP" => ["Laravel"]},
        {"Go" => ["Gin Gonic"]},
        {"Javascript" => ["ReactJS", "Ionic"]},
        {"Dart" => ["Flutter"]}
      ],
      :technology_stack => [
        {"Frontend" => ["ReactJS", "jQuery"]},
        {"Backend" => ["Ruby on Rails", "Gin Gonic", "Laravel"]},
        {"Mobile" => ["Flutter", "Ionic with ReactJS"]},
        {"Database" => ["MySQL", "PostgreSQL"]}
      ],
      :others => [
        {"Bot" => ["Telegram", "Discord"]},
        {"CSS" => ["Bootstrap", "Tailwind", "UIkit"]},
        {"MVC" => ["Ruby on Rails", "Laravel"]},
        {"Web Server" => ["Apache", "Nginx"]},
        {"Architecture" => ["Monolithic", "Microservice"]},
        {"REST API Docs" => ["Postman", "Swagger"]},
        {"Package Manager" => ["Yarn", "NPM"]},
        {"Port Forwarding" => ["Ngrok", "LocalTunnel"]},
        {"Operating System" => ["Windows", "Linux"]}
      ]
    }
  }
```
