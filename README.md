# Create-for-2
fn main() {     const WIDTH: usize = 20;  // ширина конверта     const HEIGHT: usize = 10; // висота конверта      // Верхня частина конверта     for i in 0..WIDTH {         if i == 0 {             print!(" /");         } else if i == WIDTH - 1 {             print!("\\ ");         } else {             print!(" ");         }     }     println!();
