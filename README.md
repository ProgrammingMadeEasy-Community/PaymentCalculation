# PaymentCalculation
A simple JavaScript project to balance payment calculations

This project is a simple JavaScript project which implements some problem solving logic to make it easier for ushers to calculate Sunday collections faster to save precious time and track descripancies that may occcur due to human errors.

Workflow:
* User loads webpage.
* Webpage loads and displays only the general box and the total calculations section.
* User get prompt for number of boxes passed.
* Boxes get generated dynamically based on user input.
* User selects boxes title, based on a dropdown menu or custom input.
* User fills boxes input field with amount of money per dinominations represented by the input field.
* The subtotal of each denomination is calculated as `(amount * dinomination)` and stored as the text content in front of each input field.
* On the General box section, the subtotal of each denomination is summed and stored as the text content in a separate column, wth rows corresponding to each denomination.
* The subtotal of each denomination is compared to the total amount of the dinomination in the general section and the difference is recorded in the descripancies column beside the subtotal column.