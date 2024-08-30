from functions import sort_amount,add_data,delete_data_date,search_transaction
Transaction=[
    {"date":"21-8-2024","amount":"200","description":"fruits"},
    {"date":"22-8-2024","amount":"100","description":"petrol"},
    {"date":"23-8-2024","amount":"500","description":"snacks"},
    {"date":"24-8-2024","amount":"2000","description":"grocary"},
]
flag=True
while flag:
  print("Expense Tracker App")
  print("1.Adding transaction")
  print("2.Searching transaction")
  print("3.Sorting transaction")
  print("4.Deleting transaction")
  print("5. Display transaction")
  print("6. Exit")
  print("7. sum amount")
  Choice=int(input("Enter a choice: "))
  if Choice == 1:
    Transaction=add_data(Transaction)
  elif Choice == 2:
    date = input("Enter the date to search for: ")
    Transaction= search_transaction(date)
  elif Choice == 3:
   Transaction= sorting_transaction(Transaction)
  elif Choice == 4:
    Transaction= delete_data(Transaction)
  elif Choice == 5:
    print(Transaction)
  elif Choice == 6:
    print("Exited")
    flag=False


def sum_amount(transaction):
  sum=0
  year=input("Enter year: ")
  for transaction in transaction:
    if transaction['date'][0:4] == year:
      sum+=transaction['amount']
  return transaction
