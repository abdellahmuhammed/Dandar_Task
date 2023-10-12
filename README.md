//task1  
//Make a function using dart that prints that shape ( use 2 for statement )

void main() {
  for (int i = 0; i < 5; i++) {
    var stars = '';
    for (int j = (5 - i); j > 1; j--) {
      stars += ' ';
    }
    for (int j = 0; j <= i; j++) {
      stars += '* ';
    }
    print(stars);
  }
}

// task 2 



