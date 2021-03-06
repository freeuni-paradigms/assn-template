## სექციის ლიდერის checklist
1. ამ თემფლეითის გამოყენებით შექმენით ახალი რეპოზიტორია `freeuni-paradigms` ორგანიზაციაში. რეპოზიტორიის სახელი უნდა იყოს სტენფორდის ფორმატით, დავალების ფოლდერს რაც ქვია.  template repository-ს გამოყენების ინსტრუქცია თუ დაგჭირდათ არის [აქ](https://docs.github.com/en/free-pro-team@latest/github/creating-cloning-and-archiving-repositories/creating-a-repository-from-a-template)
2. დააკლონირეთ ახალი რეპოზიტორია. კლასრუმიდან გადმოწერეთ დავალების ფაილები და გადაიტანეთ (data-ს გარდა). გადაიტანეთ ინსტრუქციაც. საბოლოოდ ყველაფერი ერთ directory level-ზე უნა იყოს (subfolder და ა.შ არა. ნახეთ წინა დავალებები). დააკომიტეთ (initial files ან რამე ეგეთი სახელით)
3.  შექმენით ახალი ბრენჩი და ყველა მომავალი ცვლილება იქ გააკეთეთ. ბოლოს გახსენით pull request. რამე კითხვა თუ გქონდათ, არ ხართ დარწმუნებული ან არ იცით როგორ გააკეთოთ, ამ pull request-ზე დაწერეთ და დაგეხმარებით.

### ცვლილებები
- [ ] `README.md` ფაილში შეცვალეთ development ინსტრუქციების შესაბამისი ნაწილები
- [ ] `setup.sh` და `zip.sh` ფაილებში მოძებნეთ TODO-თი მონიშნული ხაზები/ნაწილები და ჩაანაცვლეთ რელევანტური ინფორმაციით
- [ ] თუ დავალებას აქვს data დირექტორია, შექმენით ახალი რეპოზიტორია (დავალების სახელიდა მიუწერეთ `-data`, სახელის მაგალითისთვის ნახეთ მეორე დავალება), ატვირთეთ იქ  და დაამატეთ submodule-ად (`git submodule add new_repo`)

**ამ ყველაფრის გაკეთების შემდეგ წაშალეთ ტექსტი დასაწყისიდან ამ ხაზის ჩათვლით**

## ინსტრუქცია
- დააკლონირეთ რეპოზიტორია
- გახსენით ტერმინალი და გაუშვით `sh setup.sh` ან `./setup.sh`

### development

პრერეკვიზიტები. valgrind, zip 

```sh
sudo apt-get install valgrind #ubuntu
yay -S valgrind #arch
```

build

```sh
make
```

test

```sh
TODO
```

test-all (თუ ბევრი ტესტია, თუ არა და წაშალეთ. მაგალითისთვის პირველი დავალების README ნახეთ. ფრჩხილებში რაც წერია ორივე შემთხვევაში წაშალეთ)
```sh
```
### შეფასება
`TODO`

### ატვირთვა
google classroom-ზე.

#### version 1 ავტომატურად
გახსენით ტერმინალი და გაუშვით `./zip.sh`

#### version 2 manual
1. დაზიპეთ ფაილები `imdb.cc six-degrees.cc`. **აუცილებელია იყოს `.zip` და არა rar**. დაზიპეთ **მხოლოდ** ეს ფაილები (სხვა ფაილებში ცვლილებები არ მიიღება) და არა დირექტორია
2. დაარქვით ზიპს თქვენი მეილის id


## კითხვები და დახმარება
თუ დავალებასთან დაკავშირებით კითხვა გქონდათ ან ტექნიკური დახმარება დაგჭირდათ:
1. ნახეთ შედით github.com-ზე დავალების გვერდზე და გახსენით [`faq.md`](./faq.md) ფაილი
2. თუ FAQ-ში არ არის, გადადით github-ზე დავალების `issues` განყოფილებაში. თუ ვინმეს უკვე აქვს დამატებული თქვენი კითხვა, დააკომენტარეთ რომ თქვენც გაქვთ, თუ საჭიროდ ჩათვლით დაურთეთ error message, სისტემის მონაცემები და ა.შ
3. თუ ვერცერთგან ვერ იპოვეთ, შექმენით ახალი `issue`

