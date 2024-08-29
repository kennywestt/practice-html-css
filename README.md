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
    <script>
        /*
        직사각형을 출력하는 함수를 구현하세요
        직사각형 넓이, 둘레 출력
        직사각형 함수 안에서
            직사각형의 넓이, 둘레를 계산하는 함수
            직사각형의 넓이, 둘레를 출력하는 함수를
            호출하여 구현
        */

        function areaCalculate(width, height) {
            let area = width * height;
            return area;
        }

        function borderCalculate(width, height) {
            let border = 2 * (width + height);
            return border;
        }

        function printCalculate(width, height, area, border) {
            document.write("넓이: ", area, "<br>");
            document.write("둘레: ", border, "<br>");
        }

        function calculate(width, height) {
            let area = areaCalculate(width, height);
            let border = borderCalculate(width, height);
            printCalculate(width, height, area, border);
            return {area: area, border: border}
        }


        calculate(
            [3, 3],
            [4, 4]
        );
    </script>

