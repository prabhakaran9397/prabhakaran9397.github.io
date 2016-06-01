---
layout: post
title: Binary to Decimal conversion in C
---
[Binary representation](http://www.practice.geeksforgeeks.org/problem-page.php?pid=602) solved.		
{% highlight C %}
#include<stdio.h>
int main(void)
{
	int n, i;
	scanf("%d",&n);
	for(i=13; i>-1; i--)
		printf("%d",(n>>i)&1);
	putchar(10); //newline
	return 0;
}
{% endhighlight %}