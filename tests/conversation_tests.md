## Story from conversation with 1113692518 on May 21st 2020

* greet: hi
    - utter_greet
* search_transactions: how much did i spend on [Starbucks](vendor_name)?
    - slot{"vendor_name":"Starbucks"}
    - transact_search_form
    - form{"name":"transact_search_form"}
    - slot{"search_type":"spend"}
    - slot{"requested_slot":"time"}
* check_earnings: [last month](time)
    - slot{"time":"last month"}
    - transact_search_form
    - slot{"time":"last month"}
    - slot{"start_time":"Apr 2020"}
    - slot{"end_time":"May 2020"}
    - slot{"grain":"month"}
    - slot{"time":null}
    - slot{"start_time":null}
    - slot{"end_time":null}
    - slot{"grain":null}
    - slot{"search_type":null}
    - form{"name":null}
    - slot{"requested_slot":null}
* thankyou: cool thanks
