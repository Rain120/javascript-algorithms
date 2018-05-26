# Fibonacci Number

In mathematics, the Fibonacci numbers are the numbers in the following 
integer sequence, called the Fibonacci sequence, and characterized by 
the fact that every number after the first two is the sum of the two 
preceding ones:
<br />
在数学中，斐波那契数是以下整数序列中的数字，称为斐波那契数列，其特征在于前两个数之后的每个数都是前两个数之和：

`0, 1, 1, 2, 3, 5, 8, 13, 21, 34, 55, 89, 144, ...`

A tiling with squares whose side lengths are successive Fibonacci numbers
<br />
平方的边长连续斐波那契数

![Fibonacci](https://upload.wikimedia.org/wikipedia/commons/d/db/34%2A21-FibonacciBlocks.png)

The Fibonacci spiral: an approximation of the golden spiral created by drawing circular arcs connecting the opposite corners of squares in the Fibonacci tiling;[4] this one uses squares of sizes 1, 1, 2, 3, 5, 8, 13 and 21.
<br />
斐波那契螺旋线：通过绘制连接斐波纳契平铺中正方形对角的圆弧形成的金色螺旋线的近似值; [4]这个螺旋线使用尺寸为1，1，2，3，5，8，13和21 。

![Fibonacci Spiral](https://upload.wikimedia.org/wikipedia/commons/2/2e/FibonacciSpiral.svg)

## Code 
```
export default function fibonacci(number) {
  if (number === 0) {
    return 0;
  }else if (number === 1 || number === 2) {
    return 1;
  }
    return fibonacci(number - 1 ) + fibonacci(number -2)
}
```

## References

[Wikipedia](https://en.wikipedia.org/wiki/Fibonacci_number)
