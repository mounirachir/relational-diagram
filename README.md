# relational-diagram

hotel (<u>hotel_id</u>, hotel_name, #room_id, #employee_id)

type (<u>type_id</u>, type_name, #hotel_id)

employee (<u>epmloyee_id</u>, employee_name, employee_speciality)

room (<u>room_id</u>, floor)

category (<u>category_id</u>, category_name, price, beds_numbers, #room_id)

leads (<u>leads_id</u>, #employee_id)
