# Banking Management System

Summary 
> ငွေသွင်း ငွေလွှဲ ပြုလုပ်သည့်အခါ ဘဏ် staff ကနေ အသုံးပြုရတဲ့ စနစ်ဖြစ်တယ်။ ကိုယ်‌‌ ငွေလွှဲချင်တဲ့ account နံပါတ်ကို ဘဏ် staff အားပြောပြပြီးတော့မှ ဘဏ် staff ကနေ တစ်ဆင့် ငွေသွင်း ငွေလွှဲ‌ ပြုလုပ်ပေးနိုင်တဲ့  Service မျိုး ဖြစ်ပါတယ်။



ပါ၀င်မည့် Menu များကတော့
- General Setup
  - [State List](#state-and-township-list)
  - [Township List](#state-and-township-list)
- Account
  - [Create Account](#create-account)
  - [Account List](#account-list)
- Transaction
  - [Transfer](#transfer)
  - [Deposit](#deposit)
  - [Withdraw](#withdraw)
- Report
  - [Transaction History](#transaction-history)

-----
  

### State and Township List
State And Township Data တွေကို ဤ [Link](https://themimu.info/place-codes) ကနေ ထုတ်ယူထားတယ်။ Account ဖွင့်ရာတွင်အသုံးပြုတယ်။ ဘယ်နေရာ ဒေသမှာ ဖွင့်ထားသလဲဆိုတာ သိဖို့အတွက် ဖြစ်တယ်။

-----

### Create Account
ဘဏ်တွင် ငွေသွင်း ငွေလွှဲ service များကိုအသုံးပြုလိုပါက ဘဏ်တွင် account ဖွင့်ရပါမည်။

-----

### Account List

ဘဏ်တွင် customer များဖွင့်ခဲ့သော account များကိုကြည့်ရှုလို့ရမယ်။

-----


### Transfer

Customer ငွေလွှဲချင်သည့် အကောင့်ထဲသို့ ဘဏ် Staff မှ တစ်ဆင့် လွှဲပြောင်းပေးနိုင်ပါသည်။

> ငွေလွှဲတဲ့အခါ Account Table ထဲက မိမိ Account ရဲ့ Balance ကို အရင်လောက်မလောက် စစ်မယ်။ Account Table ထဲမှာရှိတဲ့ ကိုယ့်ရဲ့ Balance ကို
အရင် နုတ်ပေးရမယ်။ လက်ရှိ 1000, လွှဲတာ 200 ဆို 800 ပဲဖြစ်ရပါမယ်။ Balance Update လုပ်ပေးရပါမယ်။
ပြီးရင် လွှဲပေးလိုက်တဲ့ Account ကျတော့ Amount ကို ပေါင်းပေးရမယ်။ လက်ရှိ 200, လွှဲလိုက်တာ 200 ဆို
စုစုပေါင်း သူ့လက်ကျန်က 400 ဖြစ်ရပါမယ်။ လွှဲမယ့်သူဆီက နုတ်ပြီး လက်ခံရမယ့်သူဆီ ပေါင်းပေးရမယ်ဆိုတဲ့ သဘောပါ။


-----

### Deposit

Customer Account ထဲသို့ ငွေ Amount တွေကိုထည့်သွင်းလို့ရနိုင်ပါသည်။

> Form မှာ Account ကို Popup နဲ့ ရှာလို့ရမယ် အဲ့ထဲက တစ်ခုကို ရွေးမယ် ထည့်ချင်တဲ့ Amount ကိုရိုက်ထည့်မယ် Add ကိုနှိပ်တဲ့အခါ Account Table မှ Balance ကို လက်ရှိ ရိုက်ထည့်ထားသော Amount နှင့် ပေါင်းပေးရပါမယ်
အရင် 1000, လက်ရှိ ရိုက်ထားသော Amount 3000 ဆိုရင် စုစုပေါင်း Balance က 4000 ဖြစ်ရပါမယ်။
-----

### Withdraw

Customer Account ထဲမှ ငွေ Amount တွေကိုထုတ်ယူလို့ရပါမည်။

Logic
> ဒါကတော့ သူက ငွေထုတ်တာမို့ Account Table ထဲက ငွေကို နုတ်ယူပေးရမယ်။ ငွေထုတ်မယူခင်တော့ Balance လောက်မလောက် အရင်စစ်ပေးရမယ်။ စစ်လို့အဆင်ပြေမှသာ 
ငွေထုတ်ခွင့်ပေးရပါမယ်။

-----

### Transaction History

Customer ငွေလွှဲသွားတဲ့ account တွေကို Date အလိုက်ကြည့်ရှုလို့ရတဲ့ Report ဖြစ်ပါတယ်။

-----