evaluatenum
===========
puts "pick a number from 0 to 100"
num = gets.chomp.to_i
	if num >= 100
		puts "your number is equal or greater than 100"
	elsif num >= 50
		puts "your number is from 50 to 99"
	elsif num < 50 && num > 0
		puts "your number is less than 50"
	else
		puts "your number is not from 0 to 100!"
	end
