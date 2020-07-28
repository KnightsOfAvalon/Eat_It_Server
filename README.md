# Eat_It_App README

This is a sister app for the [Eat_It_App](https://github.com/KnightsOfAvalon/Eat_It_App).

Please note that this app no longer has a google-services.json file in the "app" folder. Also, the Firebase project that I connected this app to in order to test functionality no longer exists. If you are interested in trying this app out for yourself, you will have to create your own Firebase project to connect to. For your convenience, I have included some sample .json data below that you can use to initially populate your Firebase database. Simply copy and paste the data into a .json file and upload that .json file to your Firebase database.

## Sample .json Data

{
  "Category" : {
    "01" : {
      "Image" : "https://images.pexels.com/photos/724022/pexels-photo-724022.jpeg?auto=compress&cs=tinysrgb&dpr=2&h=750&w=1260",
      "Name" : "FINGER FOODS"
    },
    "02" : {
      "Image" : "https://images.pexels.com/photos/539451/pexels-photo-539451.jpeg?auto=compress&cs=tinysrgb&dpr=1&w=500",
      "Name" : "WESTERN SOUPS"
    },
    "03" : {
      "Image" : "https://images.pexels.com/photos/3662103/pexels-photo-3662103.jpeg?auto=compress&cs=tinysrgb&dpr=1&w=500",
      "Name" : "EASTERN SOUPS"
    },
    "04" : {
      "Image" : "https://images.pexels.com/photos/1600711/pexels-photo-1600711.jpeg?auto=compress&cs=tinysrgb&dpr=1&w=500",
      "Name" : "SANDWICHES"
    },
    "05" : {
      "Image" : "https://images.pexels.com/photos/208537/pexels-photo-208537.jpeg?auto=compress&cs=tinysrgb&dpr=1&w=500",
      "Name" : "PIZZA"
    },
    "06" : {
      "Image" : "https://images.pexels.com/photos/803963/pexels-photo-803963.jpeg?auto=compress&cs=tinysrgb&dpr=1&w=500",
      "Name" : "PASTA"
    },
    "07" : {
      "Image" : "https://images.pexels.com/photos/1123250/pexels-photo-1123250.jpeg?auto=compress&cs=tinysrgb&dpr=1&w=500",
      "Name" : "CHICKEN"
    },
    "08" : {
      "Image" : "https://images.pexels.com/photos/842142/pexels-photo-842142.jpeg?auto=compress&cs=tinysrgb&dpr=1&w=500",
      "Name" : "FISH"
    },
    "09" : {
      "Image" : "https://images.pexels.com/photos/4553031/pexels-photo-4553031.jpeg?auto=compress&cs=tinysrgb&dpr=1&w=500",
      "Name" : "CHINESE VEGETARIAN"
    },
    "10" : {
      "Image" : "https://images.pexels.com/photos/291528/pexels-photo-291528.jpeg?auto=compress&cs=tinysrgb&dpr=1&w=500",
      "Name" : "DESSERT DELIGHTS"
    },
    "11" : {
      "Image" : "https://images.pexels.com/photos/3026806/pexels-photo-3026806.jpeg?auto=compress&cs=tinysrgb&dpr=1&w=500",
      "Name" : "SNACKS"
    }
  },
  "Food" : {
    "01" : {
      "Description" : "Lorem ipsum dolor sit amet, consectetur adipisicing elit. Voluptates magnam ullam tenetur voluptatum quod accusantium nostrum quasi porro similique est",
      "Discount" : "0",
      "Image" : "https://cdn.pixabay.com/photo/2015/02/26/08/29/cheese-slicer-650029__340.jpg",
      "MenuId" : "01",
      "Name" : "CHEESE PLATTER",
      "Price" : "11"
    },
    "02" : {
      "Description" : "Lorem ipsum dolor sit amet, consectetur adipisicing elit. Voluptates magnam ullam tenetur voluptatum quod accusantium nostrum quasi porro similique est",
      "Discount" : "0",
      "Image" : "https://cdn.pixabay.com/photo/2018/07/15/19/54/bruschetta-3540405__340.jpg",
      "MenuId" : "01",
      "Name" : "TOASTY BITES",
      "Price" : "12"
    },
    "03" : {
      "Description" : "Lorem ipsum dolor sit amet, consectetur adipisicing elit. Voluptates magnam ullam tenetur voluptatum quod accusantium nostrum quasi porro similique est",
      "Discount" : "0",
      "Image" : "https://cdn.pixabay.com/photo/2019/04/13/20/22/chunks-4125516__340.jpg",
      "MenuId" : "01",
      "Name" : "MASTER PLATTER",
      "Price" : "13"
    },
    "04" : {
      "Description" : "Lorem ipsum dolor sit amet, consectetur adipisicing elit. Voluptates magnam ullam tenetur voluptatum quod accusantium nostrum quasi porro similique est",
      "Discount" : "0",
      "Image" : "https://images.pexels.com/photos/539451/pexels-photo-539451.jpeg?auto=compress&cs=tinysrgb&dpr=1&w=500",
      "MenuId" : "02",
      "Name" : "HOUSE SOUP",
      "Price" : "8"
    },
    "05" : {
      "Description" : "Lorem ipsum dolor sit amet, consectetur adipisicing elit. Voluptates magnam ullam tenetur voluptatum quod accusantium nostrum quasi porro similique est",
      "Discount" : "0",
      "Image" : "https://images.pexels.com/photos/1437655/pexels-photo-1437655.jpeg?auto=compress&cs=tinysrgb&dpr=1&w=500",
      "MenuId" : "02",
      "Name" : "PUMPKIN SOUP",
      "Price" : "8"
    },
    "06" : {
      "Description" : "Lorem ipsum dolor sit amet, consectetur adipisicing elit. Voluptates magnam ullam tenetur voluptatum quod accusantium nostrum quasi porro similique est",
      "Discount" : "0",
      "Image" : "https://images.pexels.com/photos/1907244/pexels-photo-1907244.jpeg?auto=compress&cs=tinysrgb&dpr=1&w=500",
      "MenuId" : "02",
      "Name" : "BEEFY SOUP",
      "Price" : "8"
    },
    "07" : {
      "Description" : "Lorem ipsum dolor sit amet, consectetur adipisicing elit. Voluptates magnam ullam tenetur voluptatum quod accusantium nostrum quasi porro similique est",
      "Discount" : "0",
      "Image" : "https://images.pexels.com/photos/3662104/pexels-photo-3662104.jpeg?auto=compress&cs=tinysrgb&dpr=1&w=500",
      "MenuId" : "03",
      "Name" : "CREAMY SOUP",
      "Price" : "8"
    },
    "08" : {
      "Description" : "Lorem ipsum dolor sit amet, consectetur adipisicing elit. Voluptates magnam ullam tenetur voluptatum quod accusantium nostrum quasi porro similique est",
      "Discount" : "0",
      "Image" : "https://images.pexels.com/photos/884600/pexels-photo-884600.jpeg?auto=compress&cs=tinysrgb&dpr=1&w=500",
      "MenuId" : "03",
      "Name" : "HOUSE RAMEN",
      "Price" : "8"
    },
    "09" : {
      "Description" : "Lorem ipsum dolor sit amet, consectetur adipisicing elit. Voluptates magnam ullam tenetur voluptatum quod accusantium nostrum quasi porro similique est",
      "Discount" : "0",
      "Image" : "https://images.pexels.com/photos/3903586/pexels-photo-3903586.jpeg?auto=compress&cs=tinysrgb&dpr=1&w=500",
      "MenuId" : "03",
      "Name" : "HOUSE PHO",
      "Price" : "8"
    },
    "10" : {
      "Description" : "Lorem ipsum dolor sit amet, consectetur adipisicing elit. Voluptates magnam ullam tenetur voluptatum quod accusantium nostrum quasi porro similique est",
      "Discount" : "0",
      "Image" : "https://images.pexels.com/photos/1647163/pexels-photo-1647163.jpeg?auto=compress&cs=tinysrgb&dpr=1&w=500",
      "MenuId" : "04",
      "Name" : "VEGETARIAN DOUBLE-DECKER",
      "Price" : "17"
    },
    "11" : {
      "Description" : "Lorem ipsum dolor sit amet, consectetur adipisicing elit. Voluptates magnam ullam tenetur voluptatum quod accusantium nostrum quasi porro similique est",
      "Discount" : "0",
      "Image" : "https://images.pexels.com/photos/1600711/pexels-photo-1600711.jpeg?auto=compress&cs=tinysrgb&dpr=1&w=500",
      "MenuId" : "04",
      "Name" : "CHIPOTLE SOUTHWESTERN",
      "Price" : "18"
    },
    "12" : {
      "Description" : "Lorem ipsum dolor sit amet, consectetur adipisicing elit. Voluptates magnam ullam tenetur voluptatum quod accusantium nostrum quasi porro similique est",
      "Discount" : "0",
      "Image" : "https://images.pexels.com/photos/7390/pexels-photo.jpg?auto=compress&cs=tinysrgb&dpr=1&w=500",
      "MenuId" : "04",
      "Name" : "CROISSANT SUB CLUB",
      "Price" : "20"
    },
    "13" : {
      "Description" : "Lorem ipsum dolor sit amet, consectetur adipisicing elit. Voluptates magnam ullam tenetur voluptatum quod accusantium nostrum quasi porro similique est",
      "Discount" : "0",
      "Image" : "https://images.pexels.com/photos/825661/pexels-photo-825661.jpeg?auto=compress&cs=tinysrgb&dpr=1&w=500",
      "MenuId" : "05",
      "Name" : "ORIGINAL PEPPERONI",
      "Price" : "21"
    },
    "14" : {
      "Description" : "Lorem ipsum dolor sit amet, consectetur adipisicing elit. Voluptates magnam ullam tenetur voluptatum quod accusantium nostrum quasi porro similique est",
      "Discount" : "0",
      "Image" : "https://images.pexels.com/photos/803290/pexels-photo-803290.jpeg?auto=compress&cs=tinysrgb&dpr=1&w=500",
      "MenuId" : "05",
      "Name" : "SPECIAL SUPREME",
      "Price" : "22"
    },
    "15" : {
      "Description" : "Lorem ipsum dolor sit amet, consectetur adipisicing elit. Voluptates magnam ullam tenetur voluptatum quod accusantium nostrum quasi porro similique est",
      "Discount" : "0",
      "Image" : "https://images.pexels.com/photos/2619967/pexels-photo-2619967.jpeg?auto=compress&cs=tinysrgb&dpr=1&w=500",
      "MenuId" : "05",
      "Name" : "VEGGIE PIZZA",
      "Price" : "1000"
    },
    "16" : {
      "Description" : "Lorem ipsum dolor sit amet, consectetur adipisicing elit. Voluptates magnam ullam tenetur voluptatum quod accusantium nostrum quasi porro similique est",
      "Discount" : "0",
      "Image" : "https://images.pexels.com/photos/803963/pexels-photo-803963.jpeg?auto=compress&cs=tinysrgb&dpr=1&w=500",
      "MenuId" : "06",
      "Name" : "ALFREDO PASTA",
      "Price" : "25"
    },
    "17" : {
      "Description" : "Lorem ipsum dolor sit amet, consectetur adipisicing elit. Voluptates magnam ullam tenetur voluptatum quod accusantium nostrum quasi porro similique est",
      "Discount" : "0",
      "Image" : "https://images.pexels.com/photos/2433979/pexels-photo-2433979.jpeg?auto=compress&cs=tinysrgb&dpr=1&w=500",
      "MenuId" : "06",
      "Name" : "NEW ORLEANS PASTA",
      "Price" : "27"
    },
    "18" : {
      "Description" : "Lorem ipsum dolor sit amet, consectetur adipisicing elit. Voluptates magnam ullam tenetur voluptatum quod accusantium nostrum quasi porro similique est",
      "Discount" : "0",
      "Image" : "https://images.pexels.com/photos/128408/pexels-photo-128408.jpeg?auto=compress&cs=tinysrgb&dpr=1&w=500",
      "MenuId" : "06",
      "Name" : "SPAGHETTI W/ MEAT SAUCE",
      "Price" : "22"
    },
    "19" : {
      "Description" : "Lorem ipsum dolor sit amet, consectetur adipisicing elit. Voluptates magnam ullam tenetur voluptatum quod accusantium nostrum quasi porro similique est",
      "Discount" : "0",
      "Image" : "https://images.pexels.com/photos/461198/pexels-photo-461198.jpeg?auto=compress&cs=tinysrgb&dpr=1&w=500",
      "MenuId" : "07",
      "Name" : "CHICKEN WRAP",
      "Price" : "15"
    },
    "20" : {
      "Description" : "Lorem ipsum dolor sit amet, consectetur adipisicing elit. Voluptates magnam ullam tenetur voluptatum quod accusantium nostrum quasi porro similique est",
      "Discount" : "0",
      "Image" : "https://images.pexels.com/photos/1123250/pexels-photo-1123250.jpeg?auto=compress&cs=tinysrgb&dpr=1&w=500",
      "MenuId" : "07",
      "Name" : "CHICKEN TENDERS",
      "Price" : "12"
    },
    "21" : {
      "Description" : "Lorem ipsum dolor sit amet, consectetur adipisicing elit. Voluptates magnam ullam tenetur voluptatum quod accusantium nostrum quasi porro similique est",
      "Discount" : "0",
      "Image" : "https://images.pexels.com/photos/1624487/pexels-photo-1624487.jpeg?auto=compress&cs=tinysrgb&dpr=1&w=500",
      "MenuId" : "07",
      "Name" : "CHICKEN RICE BOWL",
      "Price" : "15"
    },
    "22" : {
      "Description" : "Lorem ipsum dolor sit amet, consectetur adipisicing elit. Voluptates magnam ullam tenetur voluptatum quod accusantium nostrum quasi porro similique est",
      "Discount" : "0",
      "Image" : "https://images.pexels.com/photos/4409306/pexels-photo-4409306.jpeg?auto=compress&cs=tinysrgb&dpr=1&w=500",
      "MenuId" : "08",
      "Name" : "TERIYAKI FISH",
      "Price" : "18"
    },
    "23" : {
      "Description" : "Lorem ipsum dolor sit amet, consectetur adipisicing elit. Voluptates magnam ullam tenetur voluptatum quod accusantium nostrum quasi porro similique est",
      "Discount" : "0",
      "Image" : "https://images.pexels.com/photos/842142/pexels-photo-842142.jpeg?auto=compress&cs=tinysrgb&dpr=1&w=500",
      "MenuId" : "08",
      "Name" : "LEMON PEPPER GRILLED FISH",
      "Price" : "16"
    },
    "24" : {
      "Description" : "Lorem ipsum dolor sit amet, consectetur adipisicing elit. Voluptates magnam ullam tenetur voluptatum quod accusantium nostrum quasi porro similique est",
      "Discount" : "0",
      "Image" : "https://images.pexels.com/photos/9210/food-japanese-food-photography-sushi.jpg?auto=compress&cs=tinysrgb&dpr=1&w=500",
      "MenuId" : "08",
      "Name" : "SUSHI PLATTER",
      "Price" : "26"
    },
    "25" : {
      "Description" : "Lorem ipsum dolor sit amet, consectetur adipisicing elit. Voluptates magnam ullam tenetur voluptatum quod accusantium nostrum quasi porro similique est",
      "Discount" : "0",
      "Image" : "https://images.pexels.com/photos/2347311/pexels-photo-2347311.jpeg?auto=compress&cs=tinysrgb&dpr=1&w=500",
      "MenuId" : "09",
      "Name" : "VEGGIE NOODLE BOWL",
      "Price" : "17"
    },
    "26" : {
      "Description" : "Lorem ipsum dolor sit amet, consectetur adipisicing elit. Voluptates magnam ullam tenetur voluptatum quod accusantium nostrum quasi porro similique est",
      "Discount" : "0",
      "Image" : "https://images.pexels.com/photos/1098545/pexels-photo-1098545.jpeg?auto=compress&cs=tinysrgb&dpr=1&w=500",
      "MenuId" : "09",
      "Name" : "VEGGIE STEAMED BUNS",
      "Price" : "16"
    },
    "27" : {
      "Description" : "Lorem ipsum dolor sit amet, consectetur adipisicing elit. Voluptates magnam ullam tenetur voluptatum quod accusantium nostrum quasi porro similique est",
      "Discount" : "0",
      "Image" : "https://images.pexels.com/photos/1640777/pexels-photo-1640777.jpeg?auto=compress&cs=tinysrgb&dpr=1&w=500",
      "MenuId" : "09",
      "Name" : "VEGETABLE SALAD",
      "Price" : "16"
    },
    "28" : {
      "Description" : "Lorem ipsum dolor sit amet, consectetur adipisicing elit. Voluptates magnam ullam tenetur voluptatum quod accusantium nostrum quasi porro similique est",
      "Discount" : "0",
      "Image" : "https://images.pexels.com/photos/291528/pexels-photo-291528.jpeg?auto=compress&cs=tinysrgb&dpr=1&w=500",
      "MenuId" : "10",
      "Name" : "DEVIL'S FOOD CAKE",
      "Price" : "12"
    },
    "29" : {
      "Description" : "Lorem ipsum dolor sit amet, consectetur adipisicing elit. Voluptates magnam ullam tenetur voluptatum quod accusantium nostrum quasi porro similique est",
      "Discount" : "0",
      "Image" : "https://images.pexels.com/photos/1028704/pexels-photo-1028704.jpeg?auto=compress&cs=tinysrgb&dpr=1&w=500",
      "MenuId" : "10",
      "Name" : "ASSORTED CUPCAKES",
      "Price" : "10"
    },
    "30" : {
      "Description" : "Lorem ipsum dolor sit amet, consectetur adipisicing elit. Voluptates magnam ullam tenetur voluptatum quod accusantium nostrum quasi porro similique est",
      "Discount" : "0",
      "Image" : "https://images.pexels.com/photos/3323686/pexels-photo-3323686.jpeg?auto=compress&cs=tinysrgb&dpr=1&w=500",
      "MenuId" : "10",
      "Name" : "ORIGINAL CHEESECAKE",
      "Price" : "13"
    },
    "31" : {
      "Description" : "Lorem ipsum dolor sit amet, consectetur adipisicing elit. Voluptates magnam ullam tenetur voluptatum quod accusantium nostrum quasi porro similique est",
      "Discount" : "0",
      "Image" : "https://images.pexels.com/photos/479628/pexels-photo-479628.jpeg?auto=compress&cs=tinysrgb&dpr=1&w=500",
      "MenuId" : "11",
      "Name" : "HANDMADE KETTLE CHIPS",
      "Price" : "7"
    },
    "32" : {
      "Description" : "Lorem ipsum dolor sit amet, consectetur adipisicing elit. Voluptates magnam ullam tenetur voluptatum quod accusantium nostrum quasi porro similique est",
      "Discount" : "0",
      "Image" : "https://images.pexels.com/photos/3872351/pexels-photo-3872351.jpeg?auto=compress&cs=tinysrgb&dpr=1&w=500",
      "MenuId" : "11",
      "Name" : "VEGGIE DIPPERS",
      "Price" : "7"
    },
    "33" : {
      "Description" : "Lorem ipsum dolor sit amet, consectetur adipisicing elit. Voluptates magnam ullam tenetur voluptatum quod accusantium nostrum quasi porro similique est",
      "Discount" : "0",
      "Image" : "https://images.pexels.com/photos/2103947/pexels-photo-2103947.jpeg?auto=compress&cs=tinysrgb&dpr=1&w=500",
      "MenuId" : "11",
      "Name" : "FRUIT & OAT YOGURT",
      "Price" : "7"
    }
  },
  "User" : {
    "0988564333" : {
      "Name" : "Tom Cruise",
      "Password" : "1234",
"IsStaff":"false"
    },
    "0988564858" : {
      "Name" : "Eddy",
      "Password" : "1234",
"IsStaff":"false"
    },
    "8520457858" : {
      "Name" : "Ally",
      "Password" : "ABCD",
"IsStaff":"false"
    },
"1111" : {
      "Name" : "Me",
      "Password" : "1234",
"IsStaff":"true"
    }
  }
}

