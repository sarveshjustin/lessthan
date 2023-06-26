# lessthan
```
module ab (a,b,c,f);
  input a,b,c,d;
  output f;
assign f = (~a&~b) | (~a&~c);
endmodule
```
