# რესტორანი "სახელი თვითონ მოიფიქრეთ"

თქვენთან მოვიდა რესტორნის მფლობელი და სურს რომ დაგიკვეთოთ მთლიანი მენეჯმენტის სისტემა. იგი უნდა ითვალისწინებდეს შემდეგ ფუნქციონალს

-   სისტემის პირველადი ინსტალაციის იმიტაცია
-   პროგრამას უნდა ქონდეს მომხმარებლების სისტემა
-   მცირე ბუღალტერიის წარმოების სისტემა
-   მცირე სასაწყობე მეურნეობის მართვის სისტემა
-   სამზარეულოს და კერძების მართვის სისტემა
-   რესტორნის კლიენტებთან მუშაობის სისტემა

## სისისტემის პირველადი ინსტალაციის იმიტაცია
პირველად გაშვებამდე თქვენი პროგრამა უნდა მოიცავდეს მხოლოდ პითონის ფაილებს, README.md, Requirements.txt და .gitignore ფაილებს. პირველად გაშვების შემდგომ უნდა შეიქმნას დამხმარე საქაღალდეები და ფაილები.
ეს მოგვცემს პროგრამის პირველადი დაინსტალირების იმიტაციას.

## პროგრამას უნდა ქონდეს მომხმარებლების სისტემა

ამ სისტემაში უნდა იყოს შესაძლებელი კონკრეტული მომხმარებლების და მათი როლების დარეგისტრირება, შეცვლა და წაშლა, გირჩევთ როლები გაწეროთ წინასწარ პარამეტრებში. ამ სისტემაზე წვდომა უნდა ქონდეს მხოლოდ 'admin' როლის მქონე მომხმარებელს. რეგისტრაციის დროს აუცილებელი ველებია მომხმარებლის სახელი და პაროლი, სხვა ველები არ არის აუცილებელი თუმცა საჭიროა მეილის ფორმატის ვალიდაცია თუ მომხმარებელმა შეიყვანა მეილი, პაროლის ვალიდაცია (უნდა შეიცავდეს მაღალი და დაბალი რეგისტრის ასოებს, რიცხვს და პუნტქუაციის სიმბოლოებს, უნდა იყოს მინიმუმ 8 სიმბოლო). იმ შემთხვევაში თუ პაროლი არ აკმაყოფილებს ვალიდაციის მოთხოვნებს მაინც დავუშვათ მსგავსი პაროლები ოღონდ მივცეთ შეტყობინება რომ იგი არ შეეასბამება კრიტერიუმენს და უნდა დაგვიდასტუროს მომხმარებელმა. ასევე პაროლი ჰეშირებული უნდა შეინახოთ, ამისთვის შეგიძლიათ გამოიყენოთ bcrypt ან სხვა რამე. აკრეფის დროს პაროლი არ უნდა ჩანდეს, ამისთვის გამოიყენეთ getpass.
გაითვალისწინეთ რომ თუ მომხმარებლის როლი არ არის 'admin' მას არ შეუძლია თავისი ექაუნთის წაშლა ან რედაქტირება ან ახალი ექაუნთის შექმნა.

## მცირე ბუღალტერიის წარმოების სისტემა

ეს სისტემა ითვალისწინებს მცირე ბუღალტერიის წარმოებას, რაც გულისხმობს ახალი დისტრიბუტორული კომპანიების რეგისტრაციას,ასევე მათგან მიღებული ინვოისების რეგისტრაციას, დისტრიბუტორებისთვის დავალიანების გადახდას, საწყობში არსებული მარაგების რეპორტის მიღება სადაც გამოჩნდება არსებული მარაგები და მათი ღირებულება. მოგება ზარალის წარმოება მითითებული დროის ინტერვალში მონაცემების შესაბამისად, სტაფის ხელფასების გადახდა, მენიუში კერძების ფასების დადგენა


## მცირე სასაწყობე მეურნეობის მართვის სისტემა
ამ სისტემაში შესაძლებელი უნდა იყოს ახალი პროდუქტის მიღება დისტრიბუტორებისგან, საწყობში არსებული მარაგების რეპორტის მიღება ოღონდ ფასების გარეშე, ასევე სამზარეულოდან მიღებული შეკვეთების მიხედვიდ მარაგების გაცემა, და საჭიროების შემთხვევაში მარაგების გადაყრა (გაფუჭებული მარაგების ჩამოწერის იმიტაცია)

## სამზარეულოს და კერძების მართვის სისტემა
აქ მზარეულს უნდა ქონდეს საშუალება შექმნას ახალი კერძი, მიუთითოს საჭირო ინგრედიენტები და რაოდენობები, შეცვალოს კერძი ან წაშაოს. ასევე მიიღოს შეკვეთები, მოამზადოს და გასცეს მიმტანებზე

## რესტორნის კლიენტებთან მუშაობის სისტემა
ამ სისტემაში იმუშავებს მიმტანის როლის მქონე მომხმარებელი სადაც იქნება შესაძლებლობა კერძების შეკვეთების მიღების მაგიდების მიხედვით. ასევე ამ შეკვეთების მიცემა სამზარეულოსთვის და შემდგომ კლიენტებთან შეკვეთის მიტანა, ასევე ანგარიშსწორების განხორციელება შესაბამისი საკომისიოს მიხედვით.

# შეფასების კრიტერიუმები
-   პროგრამის ჩართვიდან ხელმისაწვდომი უნდა იყოს ყველა ფუნქცია, არ უნდა დაგვჭირდეს პროგრამის გათიშვა და სხვა ფაილის გაშვება
-   გამოიყენეთ venv და git
-   აუცილებელია README.md ფაილი ინსტრუქციით
-   კოდი უნდა იყოს სუფთა და სტრუქტურირებული
-   დაიცავით კოდის წერის მთავარი პრინციპი, არ გაიმეორო კოდი
-   აუცილებელია კომენტარებეი სადაც ასახული იქნება არა ის რას აკეთებს არამედ რისთვის არის საჭირო
-   მოერიდეთ ჰარდკოდით წერას, ყველა საჭირო პარამეტრები გაიტანეთ ცალკე
-   ვიზუალიზაციისთვის შეგიძლიათ გამოიყენოთ tabulate.

## Hints
დროის დაწოზგვის მიზნით გაძლევთ რამოდენიმე მითითებებს:
აქ არის მოცემული ჩემეული admin სტრუქტურა, თუმცა შეგიძლიათ თქვენ შეცვალოთ ეს სტრუქტურა
```
departments = {
    'admin': [
        {
        'initiate restorant': [
                            'create necessary files',
                            'check all files',
                            'add tables number',
                            'add salary percent',
                            'add margin percent',
                            'add comission percent',
                            ],
        'user management': [
                        'add new user',
                        'edit user',
                        'delete user',
                        ], 
        'accountant management': [
                                'get financial report',
                                'get warehouse balance',
                                'calculate dish cost',
                                'add new distributor',
                                'pay debt',
                                'pay salaries',
                                ], 
        'warehouse management': [
                                'get warehouse balance',
                                'add new product',
                                'extract product',
                                'drop product',
                                ],
        'kitchen management': [
                                'add new dish',
                                'edit dish',
                                'delete dish',
                                'get orders',
                                'prepare orders',
                                'give orders',
                                ], 
        'waiters management': [
                                'get order',
                                'add order to kitchen',
                                'get order from kitchen',
                                'give order to client'
                                'get payment',
                                ]
        }
            ]
}
```

# წარმატებებს გისურვებთ !!!
