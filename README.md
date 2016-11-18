#Вывод меню по методологии БЭМ

>wp_nav_menu(array( 
>
>	"theme_location" => "top_menu",  
>	"container" => "div",  
>	"container_class" => "menu",  
>	"menu_class" => "menu-list",  
>	"menu_id" => "main-menu",  
>	"walker" => new walker_bem_menu('menu'), // наш волкер который переделывает меню 
>
>)); 
