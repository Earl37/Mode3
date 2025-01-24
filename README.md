Three separate classes are created and termed Policyholder, Products and Payments, with attributes and methods related to each assigned. In addition, each class is encapsulated to manage its own attributes and behaviour.  

We then update our code by adding methods to register, suspend, and reactivate a policyholder under that respective class. Nothing changes under the Products and Payment classes. When registering a policyholder, their status will now indicate “Active.” When we suspend the policyholder, their status will return to “Suspended.” When the policyholder has been reactivated, it will print “Active.” We add the else clause to avoid redundant suspensions and reactivations.

Under the Payment class, we update our code by def process_payment(self): for payment processing, def send_reminder(self, current_date): for reminders for non-payments prior to the due date, given the current date and def calculate_penalty(self,current_date): to compute the penalties due based on the current date minus the due date.

The next set of methods to implement affects the Product class. Here, we added methods, namely: def create_product for new products, which are then included in the class-level dictionary, def update_product(): which updates the product particulars, def remove_product(): which suspends a product and def display_all_products(): which shows all products plus their statuses.

Finally, we add methods to include policyholder information and payments details.
