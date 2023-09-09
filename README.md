# Intermidiate Tasks

## Task 3

create category & subcategory system wherecategory has many sub categories.
also sub category can have many subcategories and so on recrusively.

Example:

Fashion => Male Fashion => watch => smart watch
Electronics => Laptop => Component => Ram

category have active column in it boolean;

create api for that

-   /categories return all main and active categories

-   /categories/{id} return the category with and it's active subcategories and parent category { parent doesnt need to be checked active or false}

-   /categories/{id}/all return all it's sub categories and their subcategories and all till last.

-   /subcategory/{id} return the sub category and it's category till first;
-   /subcategories return all main categories with all nested childrens

## Write Tests for Task 4
