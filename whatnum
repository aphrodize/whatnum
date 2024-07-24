package main

import (
	"fmt"
	"math/rand"
	"time"
)

func main() {
	rand.Seed(time.Now().UnixNano())
	secretNumber := rand.Intn(10) // สุ่มตัวเลขระหว่าง 0 ถึง 9

	fmt.Println("ทายตัวเลขที่ฉันคิด (0-9):")
	var guess int
	_, err := fmt.Scan(&guess)

	if err != nil {
		fmt.Println("กรุณาใส่ตัวเลขที่ถูกต้อง")
		return
	}

	if guess == secretNumber {
		fmt.Println("ยินดีด้วย! คุณทายถูกตัวเลข")
	} else {
		fmt.Println("เสียใจด้วย, ตัวเลขที่ถูกต้องคือ:", secretNumber)
	}
}
