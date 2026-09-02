module tester;

reg [4:0] a = 0;
reg [4:0] b = 0;
wire [9:0] sum;

dut test1(
    .a(a),
    .b(b),
    .res(sum)
);

initial begin

    $monitor("a=%d, b=%d, sum=%d", a, b, sum);

    for (a = 1; a < 10; a = a + 1) begin
        b = a;
        #2;
    end

end

endmodule
