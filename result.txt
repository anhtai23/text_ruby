# check co xem duoc phim 18+
def check(age)
	if(age>18)
		puts " duoc xem"
	else
		puts "khong duoc xem " 	
	end
end	

check 88

# duyệt qua 1 mảng các số nguyên và in ra số nguyên 
def check(arr)
	arr.each{|a|  puts a}
end

check([1,2,3,4])

# viết thử 1 function tính bội số chung nhỏ nhất của 2 số nguyên duong
def BCNN(a,b)
	a.lcm(b) 
end	

puts BCNN(2,4)

# ví dụ cụ thể có đầy đủ begin, rescue, ensure
def text
	begin 
		puts 10/5
	rescue
		puts "Chao Mung Den Cty Nus"
	ensure
		puts "chao mung "
	end
end	

text

