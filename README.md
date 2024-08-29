-------------------
HTML, CSS practice

##html##
1.Text
2.Content
3.Anchor
4.Table
5.Form
6.Media

##CSS##
1.Div
2.Font
3.Display (flex)
4.Overflow
5.Position
6.Selector
7.Paint
8.Layout
9.Import
function calculate(dimensions1, dimensions2) {
    // 넓이 계산 함수
    function area(length, width) {
        return length * width;
    }

    // 둘레 계산 함수
    function perimeter(length, width) {
        return 2 * (length + width);
    }

    // 직사각형 1의 넓이와 둘레 계산 및 출력
    const length1 = dimensions1[0];
    const width1 = dimensions1[1];
    document.write(`직사각형 1의 넓이: ${area(length1, width1)}<br>`);
    document.write(`직사각형 1의 둘레: ${perimeter(length1, width1)}<br>`);

    // 직사각형 2의 넓이와 둘레 계산 및 출력
    const length2 = dimensions2[0];
    const width2 = dimensions2[1];
    document.write(`직사각형 2의 넓이: ${area(length2, width2)}<br>`);
    document.write(`직사각형 2의 둘레: ${perimeter(length2, width2)}<br>`);
}

// 함수 호출
calculate([3, 3], [4, 4]);
