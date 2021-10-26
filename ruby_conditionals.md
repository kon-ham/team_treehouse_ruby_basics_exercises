- Using comparison operators, test whether the number 2 is less than the number 3. (We know, it is, but see if you can express that in code.) Pass the result to puts. Then test whether the number 5 is greater than the number 6. Pass that result to puts as well.

    ```
    puts 2 < 3

    puts 5 > 6
    ```

- Define a method named check_speed that takes a single number representing a car's speed as a parameter. If the speed is over 55, check_speed should print the message "too fast". If the speed is under 55, check_speed should print the message "too slow". And if the speed is exactly 55, check_speed should print the message "speed OK".

    ```
    def check_speed(speed_of_car)
        if speed_of_car > 55
            puts "too fast"
        elsif speed_of_car < 55
            puts "too slow"
        elsif speed_of_car == 55
            puts "speed OK"
        end
    end
    ```
