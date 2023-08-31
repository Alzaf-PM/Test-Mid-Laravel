# Intermidiate Tasks

## Task 1
i have 2 sms api twillo & nexmo.
but only one is active at a time depend on env

send an sms to user

-   after an user create
-   if user update is password send the new password to sms

## Task 2

create category & subcategory system wherecategory has many sub categories.
also sub category can have many subcategories and so on recrusively.

category have active column in it boolean;

create api for that

-   /categories return all main and active categories

-   /categories/{id} return the category with and it's active subcategories and parent category { parent doesnt need to be checked active or false}

-   /categories/{id}/all return all it's sub categories and their subcategories and all till last.

-   /subcategory/{id} return the sub category and it's category till first;
-   /subcategories return all main categories with all nested childrens

Example:

Fashion => Male Fashion => watch => smart watch
Electronics => Laptop => Component => Ram

## Task 3

Write Tests for Task 3
