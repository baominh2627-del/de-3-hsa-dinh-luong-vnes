## File: data.js

``js
export const examData = [
  {
    id: "q1",
    type: "mcq",
    question: "Cho hàm số $y = \\frac{2x+1}{x-2}$ có đồ thị $(C)$. Hỏi có tất cả bao nhiêu điểm thuộc đồ thị $(C)$ mà tiếp tuyến của $(C)$ tại điểm đó tạo với hai trục tọa độ một tam giác có diện tích bằng $\\frac{2}{5}$?",
    options: ["4", "5", "2", "3"],
    correctAnswer: 2,
    explanation: "Đáp án đúng là C.",
    image: null
  },
  {
    id: "q2",
    type: "mcq",
    question: "Tìm $m$ để đồ thị hàm số $(C)$ của hàm số : $y = \\frac{-x^3}{m} + 3mx^2 - 2$ có điểm uốn nằm trên đường parabol $(P): y = 2x^2 - 2$?",
    options: ["$m = 0$", "$m = 2$", "$m = 1$", "$m = -2$"],
    correctAnswer: 2,
    explanation: "Đáp án đúng là C.",
    image: null
  },
  {
    id: "q3",
    type: "mcq",
    question: "Tiệm cận xiên của đồ thị hàm số : $y = \\frac{x^3}{x^2 - 1}$ là?",
    options: ["$y = 2x$", "$y = 2x + 1$", "$y = x$", "$y = -x$"],
    correctAnswer: 2,
    explanation: "Đáp án đúng là C.",
    image: null
  },
  {
    id: "q4",
    type: "mcq",
    question: "Cho $x, y$ là các số thực dương thỏa mãn bất đẳng thức sau đây $\\log \\frac{x+1}{3y+1} \\leq 9y^4 + 6y^3 - x^2y^2 - 2y^2x$. Biết $y \\leq 1000$. Hỏi có bao nhiêu cặp số nguyên dương $(x; y)$ thỏa mãn bất đẳng thức trên?",
    options: ["1501100", "1501300", "1501400", "1501500"],
    correctAnswer: 3,
    explanation: "Đáp án đúng là D.",
    image: null
  },
  {
    id: "q5",
    type: "mcq",
    question: "Có bao nhiêu cặp số nguyên $(x, y)$ thỏa mãn điều kiện $0 \\leq y \\leq 100$ và $x^6 + 6x^4y + 12x^2y^2 - 19y^3 + 3x^2 - 3y = 0$?",
    options: ["10", "100", "20", "21"],
    correctAnswer: 3,
    explanation: "Đáp án đúng là D.",
    image: null
  },
  {
    id: "q6",
    type: "mcq",
    question: "Trong phòng giáo viên, giờ ra chơi có bốn cô giáo: An, Bình, Giang và Nhàn ngồi nói chuyện với nhau quanh 1 chiếc bàn hình tròn. Cô mặc áo dài xanh ( không phải là cô An và cô Bình) thì ngồi giữa cô mặc áo dài tím và cô Nhàn. Cô mặc áo dài trắng thì ngồi giữa cô mặc áo dài hồng và cô Bình. Vậy cô An mặc áo màu gì?",
    options: ["Hồng", "Tím", "Trắng", "Xanh"],
    correctAnswer: 2,
    explanation: "Đáp án đúng là C.",
    image: null
  },
  {
    id: "q7",
    type: "mcq",
    question: "Cho hình chóp $S.ABCD$ đáy là hình vuông cạnh $a$. Mặt bên $SAD$ là tam giác đều và nằm trong mặt phẳng vuông góc với đáy. Gọi $M, N, P$ lần lượt là trung điểm của các cạnh $SB, BC, CD$. Tính thể tích khối tứ diện $CMNP$.",
    options: ["$3a^3\\sqrt{3}$", "$\\frac{a^3\\sqrt{3}}{96}$", "$\\frac{a^3\\sqrt{2}}{96}$", "$a^3\\sqrt{96}$"],
    correctAnswer: 1,
    explanation: "Đáp án đúng là B.",
    image: null
  },
  {
    id: "q8",
    type: "mcq",
    question: "Cho hình chóp $S.ABCD$ có đáy $ABCD$ là hình thoi và $AB = BD = a, SA = a\\sqrt{3}, SA \\perp (ABCD)$. Gọi $M$ là điểm trên cạnh $SB$ sao cho $BM = \\frac{2}{3}SB$. Giả sử $N$ là điểm di động trên trên cạnh $AD$. Tìm vị trí điểm $N$ để $BN \\perp DM$?",
    options: ["$N$ nằm trên cạnh $AD$ sao cho $AN = \\frac{3}{5}AD$", "$N$ nằm trên cạnh $AD$ sao cho $AN = \\frac{2}{5}AD$", "$N$ nằm trên cạnh $AD$ sao cho $AN = \\frac{4}{5}AD$", "$N$ nằm trên cạnh $AD$ sao cho $AN = \\frac{3}{4}AD$"],
    correctAnswer: 1,
    explanation: "Đáp án đúng là B.",
    image: null
  },
  {
    id: "q9",
    type: "mcq",
    question: "Cho hàm số $y = f(x)$ có đạo hàm trên $\\mathbb{R}$ là $f'(x) = (x+3)(x-4)$. Tính tổng các giá trị nguyên của tham số $m \\in [-10;5]$ để hàm số: $y = f(x^2 - 3x + m)$ có nhiều điểm cực trị nhất",
    options: ["13", "15", "17", "19"],
    correctAnswer: 1,
    explanation: "Đáp án đúng là B.",
    image: null
  },
  {
    id: "q10",
    type: "mcq",
    question: "Có bao nhiêu giá trị nguyên của tham số $m$ trong đoạn $[-10;10]$ sao cho đồ thị hàm số $y = x^3$ cắt đường thẳng $y = 3mx - m^2$ tại ba điểm phân biệt?",
    options: ["4", "6", "3", "8"],
    correctAnswer: 1,
    explanation: "Đáp án đúng là B.",
    image: null
  },
  {
    id: "q11",
    type: "mcq",
    question: "Cho hàm số $y = f(x)$ có đồ thị như hình vẽ. Hỏi phương trình $f[f(x)] = 0$ có bao nhiêu nghiệm thực phân biệt?",
    options: ["3", "7", "5", "9"],
    correctAnswer: 3,
    explanation: "Đáp án đúng là D.",
    image: "cau_11.png"
  },
  {
    id: "q12",
    type: "mcq",
    question: "Tìm tất cả các giá trị của tham số $m$ để hàm số $y = \\frac{x^2 + m}{x^2 - 3x + 2}$ có đúng 1 tiệm cận đứng?",
    options: ["$m \\in \\{-1; -4\\}$", "$m = -1$", "$m = -4$", "$m \\in \\{1; 4\\}$"],
    correctAnswer: 0,
    explanation: "Đáp án đúng là A.",
    image: null
  },
  {
    id: "q13",
    type: "mcq",
    question: "Một công ty cần xây một cái kho chứa hàng dạng hình hộp chữ nhật có thể tích 2000m³ bằng vật liệu gạch và xi măng, đáy là hình chữ nhật có chiều dài bằng hai lần chiều rộng. Người ta cần tính toán sao cho chi phí xây dựng thấp nhất, biết giá vật liệu xây dựng là 500.000 đồng /m². Khi đó, chi phí thấp nhất gần với số nào nhất trong các số dưới đây?",
    options: ["495.969.987đồng", "495.288.088 đồng", "495.279.087 đồng", "495.289.087 đồng"],
    correctAnswer: 3,
    explanation: "Đáp án đúng là D.",
    image: null
  },
  {
    id: "q14",
    type: "mcq",
    question: "Cho hàm số $f(x) = \\cos^2 2x + 2(\\sin x + \\cos x)^3 - 3\\sin 2x + m$. Số các giá trị nguyên của $m$ để $f^2(x) \\leq 36 \\; \\forall x$ là?",
    options: ["10", "13", "11", "12"],
    correctAnswer: 3,
    explanation: "Đáp án đúng là D.",
    image: null
  },
  {
    id: "q15",
    type: "mcq",
    question: "Cho hàm số $y = f(x)$ có đạo hàm $\\forall x \\in \\mathbb{R}$, hàm số $f'(x) = x^3 + ax^2 + bx + c$ có đồ thị như hình vẽ.\\nSố điểm cực trị của hàm số: $y = f\\left[f'(x)\\right]$ là:",
    options: ["7", "11", "9", "8"],
    correctAnswer: 0,
    explanation: "Đáp án đúng là A.",
    image: "cau_15.png"
  },
  {
    id: "q16",
    type: "mcq",
    question: "Cho hàm số $y = f(x)$ liên tục trên $\\mathbb{R}$. Biết rằng hàm số $y = f'(x)$ có đồ thị như hình vẽ. Hàm số $y = f\\left(x^2 - 5\\right)$ nghịch biến trên khoảng nào sau đây ?",
    options: ["$(-1; 0)$", "$(-1; 1)$", "$(0; 1)$", "$(1; 2)$"],
    correctAnswer: 2,
    explanation: "Đáp án đúng là C.",
    image: "cau_16.png"
  },
  {
    id: "q17",
    type: "mcq",
    question: "Tìm tất cả các giá trị thực của tham số $m$ sao cho hàm số $y = \\frac{1}{3}x^3 - \\frac{1}{2}mx^2 + 2mx - 3m + 4$ nghịch biến trên đoạn có độ dài là 3?",
    options: ["$m \\in \\{-1; 9\\}$", "$m = -1$", "$m = 9$", "$m \\in \\{-9; 1\\}$"],
    correctAnswer: 0,
    explanation: "Đáp án đúng là A.",
    image: null
  },
  {
    id: "q18",
    type: "mcq",
    question: "Cho hàm số $y = \\frac{x+1}{1-x}$. Khẳng định nào sau đây là khẳng định đúng?",
    options: ["Hàm số nghịch biến trên khoảng $(-\\infty; 1) \\cup (1; +\\infty)$", "Hàm số đồng biến trên khoảng $(-\\infty; 1) \\cup (1; +\\infty)$", "Hàm số nghịch biến trên các khoảng $(-\\infty; 1), (1; +\\infty)$", "Hàm số đồng biến trên các khoảng $(-\\infty; 1), (1; +\\infty)$"],
    correctAnswer: 3,
    explanation: "Đáp án đúng là D.",
    image: null
  },
  {
    id: "q19",
    type: "fill",
    question: "Cho hàm số $y = f(x)$ có bảng biến thiên như hình vẽ:\\nĐồ thị hàm số $y = \\left|f(x - 2001) - 2019\\right|$ có bao nhiêu điểm cực trị?",
    correctAnswer: "3",
    explanation: "Đáp án đúng là 3.",
    image: "cau_19.png"
  },
  {
    id: "q20",
    type: "fill",
    question: "Tìm tất cả các giá trị thực của tham số $m$ để đồ thị hàm số $y = x^3 - 3mx^2 + 6mx - 8$ cắt trục hoành tại ba điểm phân biệt có hoành độ lập thành cấp số cộng?",
    correctAnswer: "-1",
    explanation: "Đáp án đúng là -1.",
    image: null
  },
  {
    id: "q21",
    type: "fill",
    question: "Một tạp chí bán được 25 nghìn đồng một cuốn tạp chí. Chi phí xuất bản $x$ cuốn tạp chí được cho bởi công thức: $C(x) = 0,0001x^2 - 0,2x + 11000$ vạn đồng ( bao gồm : lương cán bộ,công nhân viên,....). Chi phí phát hành cho mỗi cuốn là 6000 đồng. Các khoản thu chi bán tạp chí bao gồm tiền bán tạp chí và 100 triệu đồng nhận được từ quảng cáo. Giả sử số cuốn in ra được bán hết. Tính số tiền lãi lớn nhất có thể có được khi bán tạp chí (làm tròn đến chữ số hàng chục nghìn)",
    correctAnswer: "100250",
    explanation: "Đáp án đúng là 100250.",
    image: null
  },
  {
    id: "q22",
    type: "fill",
    question: "Giả sử chiều cao (tính bằng cm) của một giống cây trồng (trong vòng 1 số tháng nhất định) tuân theo quy luật logistic được mô hình hóa bằng hàm số: $f(t) = \\frac{200}{1 + 4e^{-t}}, t \\geq 0$. Trong đó, thời gian $t$ được tính bằng tháng kể từ khi hạt bắt đầu nảy mầm. Khi đó đạo hàm $f'(t)$ sẽ biểu thị tốc độ tăng chiều cao của giống cây đó. Hỏi sau khi hạt giống bắt đầu nảy mầm thì sau bao nhiêu tháng tốc độ tăng chiều cao của cây là lớn nhất? Kết quả lấy phần nguyên",
    correctAnswer: "1",
    explanation: "Đáp án đúng là 1.",
    image: null
  },
  {
    id: "q23",
    type: "fill",
    question: "Vào năm 2020, dân số của một quốc gia là khoảng 97 triệu người và tốc độ tăng trưởng dân số là 0,91%. Nếu tốc độ tăng trưởng dân số này được giữ nguyên hàng năm, hãy ước tính dân số quốc gia đó vào năm 2030 (Lấy phần nguyên)",
    correctAnswer: "106",
    explanation: "Đáp án đúng là 106.",
    image: null
  },
  {
    id: "q24",
    type: "mcq",
    question: "Trả lời các câu hỏi từ câu 24 - 25:\\nBiết rằng gia đình cô Xuân có hai người con\\nTính xác suất 2 người con đều là gái, biết rằng có ít nhất 1 người là con gái?",
    options: ["$\\frac{1}{2}$", "$\\frac{1}{4}$", "$\\frac{1}{3}$", "$\\frac{1}{5}$"],
    correctAnswer: 2,
    explanation: "Đáp án đúng là C.",
    image: null
  },
  {
    id: "q25",
    type: "mcq",
    question: "Xác suất hai người con đều là con gái biết rằng người con đầu là con gái là",
    options: ["$\\frac{1}{2}$", "$\\frac{2}{3}$", "$\\frac{3}{5}$", "$\\frac{1}{4}$"],
    correctAnswer: 0,
    explanation: "Đáp án đúng là A.",
    image: null
  },
  {
    id: "q26",
    type: "fill",
    question: "Cho hai số thực $x \\geq 0; 1 \\leq y \\leq 3$ thỏa mãn $2^{x-2y}.(2x+1) = 4y + 2x + 4$. Tìm giá trị nhỏ nhất của biểu thức $P = 2^{x-y-2} - x - y^2 + 2037$? (nhập đáp án vào ô trống).",
    correctAnswer: "2025",
    explanation: "Đáp án đúng là 2025.",
    image: null
  },
  {
    id: "q27",
    type: "mcq",
    question: "Một tòa nhà cao 50 m, vào những ngày trời nắng, độ dài bóng của tòa nhà được tính theo công thức $S(t) = 50\\left|\\cot \\frac{\\pi}{12}t\\right|$. Trong đó $S$ được tính bằng mét, $t$ là số giờ tính từ 6 giờ sáng. Trong một ngày có bao nhiêu thời điểm bóng có độ dài bằng chiều cao của tòa nhà?",
    options: ["0", "1", "2", "3"],
    correctAnswer: 2,
    explanation: "Đáp án đúng là C.",
    image: null
  },
  {
    id: "q28",
    type: "mcq",
    question: "Cho hai biến cố A và B, với $P(A) = \\frac{3}{8}, P(B) = \\frac{1}{2}, P(\\overline{A}B) = \\frac{1}{5}$. Giá trị của $P(AB)$ là?",
    options: ["$\\frac{3}{40}$", "$\\frac{4}{5}$", "$\\frac{5}{40}$", "$\\frac{3}{5}$"],
    correctAnswer: 0,
    explanation: "Đáp án đúng là A.",
    image: null
  },
  {
    id: "q29",
    type: "mcq",
    question: "Trên sườn đồi, với độ dốc 16% (Độ dốc của sườn đồi được tính bằng $\\tan$ của góc nhọn tạo bởi sườn đồi với phương nằm ngang ) có một vây cao thẳng đứng. Ở phía chân đồi, cách gốc cây 30m, người ta nhìn ngọn cây dưới một góc $45^\\circ$ so với phương nằm ngang. Tính chiều cao của cây đó (làm tròn đến hàng đơn vị, theo đơn vị mét).",
    options: ["25m", "26m", "27m", "28m"],
    correctAnswer: 1,
    explanation: "Đáp án đúng là B.",
    image: null
  },
  {
    id: "q30",
    type: "fill",
    question: "Tìm số nguyên dương $n$ bé nhất sao cho trong khai triển $(x+1)^n$ có hai hệ số liên tiếp nhau có tỷ số là $\\frac{7}{15}$ ( điền đáp án vào ô trống).",
    correctAnswer: "21",
    explanation: "Đáp án đúng là 21.",
    image: null
  },
  {
    id: "q31",
    type: "mcq",
    question: "Có bao nhiêu giá trị nguyên dương của tham số $m$ để phương trình $m^2 \\ln \\left(\\frac{x}{e}\\right) = (2 - m)\\ln x - 4$ có nghiệm thuộc vào đoạn $\\left[\\frac{1}{e}; 1\\right]$.",
    options: ["0", "1", "2", "3"],
    correctAnswer: 1,
    explanation: "Đáp án đúng là B.",
    image: null
  },
  {
    id: "q32",
    type: "mcq",
    question: "Tìm giá trị của tham số $m$ để hàm số liên tục tại $x = 0$.\\n$f(x) = \\begin{cases} \\frac{\\sqrt{1-x} - \\sqrt{1+x}}{x}, & x < 0 \\\\ m + \\frac{1-x}{1+x}, & x \\geq 0 \\end{cases}$",
    options: ["$m = 1$", "$m = -2$", "$m = 3$", "$m = -4$"],
    correctAnswer: 1,
    explanation: "Đáp án đúng là B.",
    image: null
  },
  {
    id: "q33",
    type: "mcq",
    question: "Cho hình chóp đều $S.ABCD$ có tất cả các cạnh bằng $2a$, điểm $M$ thuộc cạnh $SC$ sao cho $SM = 2MC$. Mặt phẳng $(P)$ chứa $AM$ và song song với $BD$. Tính diện tích thiết diện của hình chóp $S.ABCD$ cắt bởi $(P)$.",
    options: ["$\\frac{4\\sqrt{3}a^2}{5}$", "$\\frac{4\\sqrt{26}a^2}{15}$", "$\\frac{4\\sqrt{3}a^2}{15}$", "$\\frac{8\\sqrt{26}a^2}{15}$"],
    correctAnswer: 3,
    explanation: "Đáp án đúng là D.",
    image: null
  },
  {
    id: "q34",
    type: "fill",
    question: "Cho 8 bạn học sinh A, B, C, D, E, F, G, H hỏi có bao nhiêu cách xếp 8 bạn đó ngồi quanh một bàn tròn có 8 chiếc ghế?",
    correctAnswer: "5040",
    explanation: "Đáp án đúng là 5040.",
    image: null
  },
  {
    id: "q35",
    type: "mcq",
    question: "Gọi M, m lần lượt là giá trị lớn nhất và giá trị nhỏ nhất của hàm số $y = \\frac{2\\cos x + 1}{\\cos x - 2}$. Khẳng định nào sau đây đúng?",
    options: ["$M + 9m = 0$.", "$9M - m = 0$.", "$9M + m = 0$.", "$M + m = 0$."],
    correctAnswer: 2,
    explanation: "Đáp án đúng là C.",
    image: null
  },
  {
    id: "q36",
    type: "mcq",
    question: "Cho dãy số $(u_n)$ biết $\\begin{cases} u_1 = 1 \\\\ u_n = \\frac{1}{3}u_{n-1} + 2 \\end{cases}$. Mệnh đề nào sau đây đúng?",
    options: ["$(u_n)$ là dãy số tăng.", "$(u_n)$ là dãy số giảm.", "$(u_n)$ không là dãy tăng, không là dãy giảm.", "$u_5 = 2$"],
    correctAnswer: 0,
    explanation: "Đáp án đúng là A.",
    image: null
  },
  {
    id: "q37",
    type: "mcq",
    question: "Cho tứ diện $ABCD$. Trên các cạnh $AD$ và $BC$ lần lượt lấy các điểm $M, N$ sao cho $\\overrightarrow{AM} = 3\\overrightarrow{MD}, \\overrightarrow{NB} = -3\\overrightarrow{NC}$. Gọi $P, Q$ lần lượt là trung điểm của $AD, BC$. Khẳng định nào sau đây sai?",
    options: ["Các vecto $\\overrightarrow{AB}, \\overrightarrow{DC}, \\overrightarrow{MN}$ đồng phẳng.", "Các vecto $\\overrightarrow{AB}, \\overrightarrow{PQ}, \\overrightarrow{MN}$ đồng phẳng.", "Các vecto $\\overrightarrow{PQ}, \\overrightarrow{DC}, \\overrightarrow{MN}$ đồng phẳng.", "Các vecto $\\overrightarrow{BD}, \\overrightarrow{AC}, \\overrightarrow{MN}$ đồng phẳng."],
    correctAnswer: 3,
    explanation: "Đáp án đúng là D.",
    image: null
  },
  {
    id: "q38",
    type: "mcq",
    question: "Một vườn thú ghi lại tuổi thọ ( đơn vị: năm) của 20 con khỉ và ghi lại kết quả như sau:\\nNhóm chứa tứ phân vị thứ ba là:",
    options: ["[10;11)", "[11;12)", "[12;13)", "[14;15)"],
    correctAnswer: 2,
    explanation: "Đáp án đúng là C.",
    image: "cau_38.png"
  },
  {
    id: "q39",
    type: "mcq",
    question: "Cho tứ diện $ABCD$ có $AC = AD = BC = BD = a$ và hai mặt phẳng $(ACD), (BCD)$ vuông góc với nhau. Tính độ dài cạnh $CD$ sao cho hai mặt phẳng $(ABC), (ABD)$ vuông góc với nhau.",
    options: ["$\\frac{2}{\\sqrt{3}}a$.", "$\\frac{1}{\\sqrt{3}}a$.", "$\\frac{1}{2}a$.", "$\\sqrt{3}a$."],
    correctAnswer: 0,
    explanation: "Đáp án đúng là A.",
    image: null
  },
  {
    id: "q40",
    type: "fill",
    question: "Biết $\\lim \\frac{-3n^3 + 2n^2 - 4}{an^3 - 1} = \\frac{1}{2}$ với $a$ là tham số. Khi đó $a^3 + 3a$ bằng bao nhiêu?",
    correctAnswer: "18",
    explanation: "Đáp án đúng là 18.",
    image: null
  },
  {
    id: "q41",
    type: "mcq",
    question: "Tính đạo hàm của hàm số $f(x) = x(x-1)(x-2)\\dots(x-2024)$ tại điểm $x = 0$?",
    options: ["$f'(0) = 0$.", "$f'(0) = 2024!$.", "$f'(0) = 2024$", "$f'(0) = -2024!$"],
    correctAnswer: 1,
    explanation: "Đáp án đúng là B.",
    image: null
  },
  {
    id: "q42",
    type: "mcq",
    question: "Thời gian tập luyện cự ly 100m của hai vận động viên được cho trong bảng sau:\\nKhẳng định nào sau đây sai?",
    options: ["Thời gian chạy trung bình của A là $\\frac{2117}{200}$.", "Thời gian chạy trung bình của B là $\\frac{5333}{500}$.", "Vận động viên A có thành tích luyện tập ổn định hơn.", "Vận động viên B có thành tích luyện tập ổn định hơn."],
    correctAnswer: 3,
    explanation: "Đáp án đúng là D.",
    image: "cau_42.png"
  },
  {
    id: "q43",
    type: "fill",
    question: "Có bao nhiêu số nguyên $x$ sao cho tồn tại số thực $y$ thỏa mãn $\\log_3(x+y) = \\log_4(x^2+y^2)$. (nhập đáp án vào ô trống).",
    correctAnswer: "2",
    explanation: "Đáp án đúng là 2.",
    image: null
  },
  {
    id: "q44",
    type: "fill",
    question: "Anh An mua ô tô trả góp trị giá 400 triệu với lãi suất 1.2% một tháng. Hỏi hàng tháng anh An phải trả bao nhiêu triệu để sau 4 năm thì hết nợ.( làm tròn đến hàng đơn vị )",
    correctAnswer: "11",
    explanation: "Đáp án đúng là 11.",
    image: null
  },
  {
    id: "q45",
    type: "fill",
    question: "Trên bàn cờ 6x7 như hình vẽ, người chơi chỉ được di chuyển quân cờ theo các cạnh của hình vuông, mỗi bước đi được một cạnh. Có bao nhiêu cách di chuyển quân cờ từ điểm A đến điểm B bằng 13 bước? ( điền đáp án vào ô trống).",
    correctAnswer: "1716",
    explanation: "Đáp án đúng là 1716.",
    image: "cau_45.png"
  },
  {
    id: "q46",
    type: "mcq",
    question: "Cho hình chóp $S.ABC$ có đáy $ABC$ là tam giác vuông tại $B, SA \\perp (ABC), BC = 2SA = 2a, AB = 2\\sqrt{2}a$. Gọi $E$ là trung điểm $AC$. Khi đó, góc giữa hai đường thẳng $SE$ và $BC$ là:",
    options: ["$45^\\circ$.", "$90^\\circ$.", "$30^\\circ$.", "$60^\\circ$."],
    correctAnswer: 3,
    explanation: "Đáp án đúng là D.",
    image: null
  },
  {
    id: "q47",
    type: "mcq",
    question: "Trả lời câu hỏi từ câu 47 - 49:\\nTrong một khu rừng, người ta ước tính đang có 800 con hà mã, 1500 con cá sấu và 2100 con ngựa vằn. Tốc độ tăng trưởng của hà mã là 4% mỗi năm, trong khi đó số ngựa vằn lại giảm 3% mỗi năm. Số lượng cá sấu tăng 2% mỗi năm.\\nSố lượng hà mã tăng gấp đôi sau bao nhiêu năm?",
    options: ["16.", "17.", "18.", "19."],
    correctAnswer: 2,
    explanation: "Đáp án đúng là C.",
    image: null
  },
  {
    id: "q48",
    type: "mcq",
    question: "Sau 10 năm, số lượng ngựa vằn còn lại trong rừng gần nhất với giá trị nào sau đây?",
    options: ["1390", "1396", "1549", "1550"],
    correctAnswer: 2,
    explanation: "Đáp án đúng là C.",
    image: null
  },
  {
    id: "q49",
    type: "mcq",
    question: "Sau bao nhiêu năm số lượng cá sấu nhiều hơn số lượng ngựa vằn?",
    options: ["6.", "7.", "8.", "9."],
    correctAnswer: 1,
    explanation: "Đáp án đúng là B.",
    image: null
  },
  {
    id: "q50",
    type: "mcq",
    question: "Cho hình hộp $ABCD.A'B'C'D'$, trên cạnh $AA', BB', CC'$ lần lượt lấy ba điểm $M, N, P$ sao cho $\\frac{AM}{AA'} = \\frac{3}{4}, \\frac{BN}{BB'} = \\frac{1}{2}, \\frac{CP}{CC'} = \\frac{1}{3}$. Biết rằng $(MNP)$ cắt $D'D$ tại $Q$. Tính tỷ số $\\frac{D'Q}{D'D}$.",
    options: ["$\\frac{5}{6}$", "$\\frac{1}{6}$", "$\\frac{7}{12}$", "$\\frac{5}{12}$"],
    correctAnswer: 2,
    explanation: "Đáp án đúng là C.",
    image: null
  }
];

``

## File: firebase-config.js

``js
import { initializeApp } from "https://www.gstatic.com/firebasejs/10.8.1/firebase-app.js";
import {
  getDatabase, ref, push, set, update, serverTimestamp,
} from "https://www.gstatic.com/firebasejs/10.8.1/firebase-database.js";

const firebaseConfig = {
  apiKey: "AIzaSyC8AT2g3vS54-Qco3uU36xYsXN04trj0Yw",
  authDomain: "mtsedu-85ea3.firebaseapp.com",
  databaseURL: "https://mtsedu-85ea3-default-rtdb.asia-southeast1.firebasedatabase.app",
  projectId: "mtsedu-85ea3",
  storageBucket: "mtsedu-85ea3.firebasestorage.app",
  messagingSenderId: "73617729802",
  appId: "1:73617729802:web:e7fa3c3c3b9ded7522f2f3",
  measurementId: "G-JHQC9DSKY5"
};

const app = initializeApp(firebaseConfig);
const db = getDatabase(app);
export { db, ref, push, set, update, serverTimestamp };

``

## File: index.html

``html
<!doctype html>
<html lang="vi">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>ĐỀ THI ĐỊNH LƯỢNG HSA - ĐỀ SỐ 3</title>
    <link rel="stylesheet" href="style.css" />
    <script>
      MathJax = {
        tex: { inlineMath: [["$", "$"], ["\\(", "\\)"]] },
        svg: { fontCache: "global" },
      };
    </script>
    <script id="MathJax-script" async
      src="https://cdn.jsdelivr.net/npm/mathjax@3/es5/tex-mml-chtml.js">
    </script>
  </head>
  <body>
    <!-- Màn hình chờ / hướng dẫn -->
    <div id="login-screen" class="container">
      <div class="exam-header-block" style="margin-bottom: 20px">
        <div class="exam-header-top" style="border-radius: 8px; border-bottom: 1px solid var(--border-color);">
          <div class="meta-text">BÀI THI ĐÁNH GIÁ NĂNG LỰC HSA · TOÁN HỌC VÀ XỬ LÝ SỐ LIỆU</div>
          <h1 class="exam-title">ĐỀ THI ĐỊNH LƯỢNG HSA - ĐỀ SỐ 3</h1>
          <div class="meta-sub">50 câu hỏi · Trắc nghiệm &amp; Điền đáp án — thang điểm 50</div>
          <hr class="dashed-line" />
        </div>
      </div>
      <div class="card form-card">
        <div class="exam-instructions" style="text-align: left;">
          <h3 style="margin-top: 0; color: var(--navy); font-size: 16px; border-bottom: 2px solid #e2e8f0; padding-bottom: 8px; font-weight: bold;">📋 HƯỚNG DẪN &amp; QUY CHẾ THI</h3>
          <ul style="font-size: 14px; color: #334155; line-height: 1.8; padding-left: 20px; margin-bottom: 16px;">
            <li><strong>Tổng số câu hỏi:</strong> 50 câu (Bao gồm câu hỏi trắc nghiệm 4 lựa chọn và câu hỏi điền đáp án).</li>
            <li><strong>Thang điểm:</strong> Mỗi câu trả lời đúng được <strong>1 điểm</strong> (Tối đa 50 điểm).</li>
            <li><strong>Thời gian làm bài:</strong> 75 phút.</li>
            <li><span style="color: #d97706; font-weight: bold;">⚠️ Lưu ý (Với câu điền đáp án):</span> Dùng dấu chấm (<code>.</code>) để phân cách thập phân. VD: <code>1.25</code></li>
          </ul>
          <div style="background: #fef9c3; border: 1px solid #fde047; border-radius: 6px; padding: 10px 14px; font-size: 13px; color: #854d0e; margin-bottom: 16px;">
            ⚠️ <strong>Quy chế:</strong> Nếu bạn chuyển sang tab hoặc ứng dụng khác trong khi thi, hệ thống sẽ ghi nhận số lần vi phạm và báo cáo về giáo viên.
          </div>
          <button id="btn-start-exam" class="btn-primary" style="width: 100%; padding: 12px; font-size: 16px; font-weight: bold;">
            ✅ Tôi đã đọc hướng dẫn — Bắt đầu thi
          </button>
        </div>
      </div>
      <div class="page-footer">Toán và Xử lý số liệu · tự động chấm điểm theo đúng barem &amp; lưu kết quả</div>
    </div>

    <!-- Màn hình làm bài thi -->
    <div id="exam-screen" class="hidden container">
      <div id="board-container" class="board-card">
        <h3>Bảng Điều Hướng</h3>
        <div id="question-board" class="board-wrapper"></div>
      </div>
      <div class="exam-header-block">
        <div class="exam-header-top">
          <div class="meta-text">KIỂM TRA 75 PHÚT · Toán và Xử lý số liệu</div>
          <h1 class="exam-title">ĐỀ THI ĐỊNH LƯỢNG HSA - ĐỀ SỐ 3</h1>
          <div class="meta-sub">50 câu hỏi</div>
          <hr class="dashed-line" />
        </div>
        <div class="exam-info-bar sticky">
          <div class="student-info">
            Thí sinh: <strong id="display-name" style="color: white"></strong> ·
            Lớp <strong id="display-class" style="color: white"></strong>
          </div>
          <div class="progress-info"><span id="answered-count">0/50</span> câu đã làm</div>
          <div class="timer-pill">
            <span class="green-dot">●</span> <span id="countdown">75:00</span>
          </div>
          <div class="score-pill hidden" id="score-pill">
            <span class="green-dot">✓</span> Điểm: <span id="review-score">0</span>/50
          </div>
        </div>
      </div>
      <div id="questions-container"></div>
      <div class="submit-container">
        <button id="submit-btn" class="btn-primary">Nộp bài kiểm tra</button>
      </div>
    </div>

    <!-- Màn hình kết quả -->
    <div id="result-screen" class="hidden container">
      <div class="card result-card">
        <h2 style="font-family: var(--font-serif)">Kết Quả Bài Thi</h2>
        <div class="score-display mono-font">Điểm: <span id="final-score"></span>/50</div>
        <p>Số lần rời khỏi màn hình: <span id="cheat-display">0</span></p>
        <p id="firebase-status" style="font-size: 14px; margin-top: 8px; color: #666;">⏳ Đang kết nối hệ thống lưu...</p>
        <button id="review-btn" class="btn-primary">Xem lại bài làm</button>
      </div>
    </div>

    <script type="module" src="script.js"></script>
  </body>
</html>

``

## File: mtsedu-auth.js

``js
const SESSION_KEY = 'mtsedu_session';

export function getMTSeduSession() {
  const params = new URLSearchParams(window.location.search);
  const urlUsername = params.get('mtsedu_user');
  const urlName = params.get('mtsedu_name');
  const urlId = params.get('mtsedu_id');
  const returnUrl = params.get('mtsedu_return');

  if (urlUsername) {
    const session = {
      username: urlUsername,
      displayName: urlName || urlUsername,
      id: urlId || ('user_' + urlUsername),
      returnUrl: returnUrl || 'https://mtsedu.vercel.app'
    };
    try { localStorage.setItem(SESSION_KEY, JSON.stringify(session)); } catch {}
    return session;
  }

  try {
    const raw = localStorage.getItem(SESSION_KEY);
    if (!raw) return null;
    const user = JSON.parse(raw);
    return (user && user.username) ? user : null;
  } catch { return null; }
}

export function getReturnUrl() {
  const session = getMTSeduSession();
  return (session && session.returnUrl) ? session.returnUrl : 'https://mtsedu.vercel.app';
}

export function isLoggedIn() { return getMTSeduSession() !== null; }

export function getStudentName() {
  const s = getMTSeduSession();
  return s ? (s.displayName || s.username) : '';
}

export function clearSession() {
  try { localStorage.removeItem(SESSION_KEY); } catch {}
}

export function showLoginRequired(container, returnHash = '') {
  const mtseduUrl = 'https://mtsedu.vercel.app/' + returnHash;
  container.innerHTML = `
    <div style="max-width:480px;margin:0 auto;padding:36px;background:white;border-radius:16px;
      box-shadow:0 4px 24px rgba(0,0,0,0.08);text-align:center;
      font-family:-apple-system,BlinkMacSystemFont,'Segoe UI',sans-serif;">
      <div style="font-size:48px;margin-bottom:16px;">🔒</div>
      <h2 style="font-size:22px;font-weight:700;margin:0 0 8px;color:#111;">Vui lòng đăng nhập</h2>
      <p style="color:#666;font-size:15px;margin:0 0 28px;line-height:1.6;">
        Bạn cần đăng nhập vào hệ thống <strong>MTS Education</strong> để làm bài thi này.
      </p>
      <a href="${mtseduUrl}" style="display:inline-block;background:#000;color:#fff;
        text-decoration:none;padding:14px 32px;border-radius:10px;font-size:15px;font-weight:600;">
        Đăng nhập tại MTS Education →
      </a>
      <p style="margin-top:20px;font-size:13px;color:#999;">Tài khoản được cung cấp bởi giáo viên</p>
    </div>
  `;
}

export function insertBackButton() {
  const session = getMTSeduSession();
  const returnUrl = (session && session.returnUrl) ? session.returnUrl : 'https://mtsedu.vercel.app';
  const btn = document.createElement('div');
  btn.id = 'mtsedu-back-btn';
  btn.innerHTML = `
    <a href="${returnUrl}" style="display:inline-flex;align-items:center;gap:8px;
      position:fixed;top:14px;left:14px;z-index:9999;background:rgba(0,0,0,0.85);
      color:white;text-decoration:none;padding:9px 18px;border-radius:50px;
      font-size:14px;font-weight:600;font-family:-apple-system,sans-serif;
      backdrop-filter:blur(8px);box-shadow:0 2px 12px rgba(0,0,0,0.3);"
      onmouseover="this.style.background='rgba(0,0,0,1)'"
      onmouseout="this.style.background='rgba(0,0,0,0.85)'">
      ← Trang chủ
    </a>
  `;
  document.body.appendChild(btn);
}

``

## File: script.js

``js
import { examData } from "./data.js";
import { db, ref, push, set, update, serverTimestamp } from "./firebase-config.js";
import { getMTSeduSession, showLoginRequired, insertBackButton } from "./mtsedu-auth.js";

const loginScreen = document.getElementById("login-screen");
const examScreen = document.getElementById("exam-screen");
const resultScreen = document.getElementById("result-screen");
const questionsContainer = document.getElementById("questions-container");
const questionBoard = document.getElementById("question-board");
const submitBtn = document.getElementById("submit-btn");

// ===== CHỈ THAY DÒNG NÀY =====
const MA_DE       = "HSA_DINHLUONG_DE3";               // mã đề Firebase (không dấu, không cách)
const DRAFT_KEY   = "examDraft_HSA_DINHLUONG_DE3";     // key localStorage
const EXAM_MINUTES = 75;                               // thời gian làm bài (phút)
const RETURN_HASH = "#math";                           // hash trang MTSedu
// ================================

let timeRemaining = EXAM_MINUTES * 60;
let timerInterval;
let userAnswers = {};
let flaggedQuestions = {};
let isFinished = false;
let cheatCount = 0;
let studentName = "";
let studentClass = "";

window.addEventListener("DOMContentLoaded", () => {
  const session = getMTSeduSession();
  const btnStart = document.getElementById("btn-start-exam");
  if (btnStart) {
    btnStart.addEventListener("click", () => {
      if (!session) {
        const loginCard = loginScreen.querySelector(".form-card") || loginScreen.querySelector(".card");
        if (loginCard) showLoginRequired(loginCard, RETURN_HASH);
        return;
      }
      const draft = JSON.parse(localStorage.getItem(DRAFT_KEY));
      if (draft && !draft.isFinished && draft.studentName === studentName) {
        loadDraftAndContinue(draft);
      } else {
        startExamDirectly();
      }
    });
  }

  if (!session) return;
  studentName = session.displayName || session.username;
  studentClass = session.username;
  insertBackButton();
});

function startExamDirectly() {
  userAnswers = {}; flaggedQuestions = {}; cheatCount = 0; isFinished = false;
  localStorage.removeItem(DRAFT_KEY);
  timeRemaining = EXAM_MINUTES * 60;
  document.getElementById("display-name").innerText = studentName;
  document.getElementById("display-class").innerText = studentClass;
  loginScreen.classList.add("hidden");
  examScreen.classList.remove("hidden");
  renderExam(); restoreDOMState(); renderBoard(); startTimer(); setupAntiCheat();
}

function loadDraftAndContinue(draft) {
  studentName = draft.studentName || studentName;
  studentClass = draft.studentClass || studentClass;
  timeRemaining = draft.timeRemaining;
  userAnswers = draft.userAnswers || {};
  flaggedQuestions = draft.flaggedQuestions || {};
  cheatCount = draft.cheatCount || 0;
  document.getElementById("display-name").innerText = studentName;
  document.getElementById("display-class").innerText = studentClass;
  loginScreen.classList.add("hidden");
  examScreen.classList.remove("hidden");
  renderExam(); restoreDOMState(); renderBoard(); startTimer(); setupAntiCheat();
}

function renderExam() {
  questionsContainer.innerHTML = "";
  
  const header = document.createElement("div");
  header.className = "section-header";
  header.innerHTML = `
    <div class="section-title">Phần thi: Toán học và Xử lí số liệu <span class="badge">50 điểm</span></div>
    <div class="section-subtitle">Mỗi câu đúng được 1 điểm. Gồm trắc nghiệm 4 lựa chọn và điền đáp án.</div>`;
  questionsContainer.appendChild(header);

  let qCounter = 1;

  examData.forEach((q) => {
    const card = document.createElement("div");
    card.className = "question-card";
    card.id = `q-card-${q.id}`;

    let html = `<div class="q-layout"><div class="q-header"><div class="q-num-flag">
      <div class="q-num">Câu ${qCounter}</div>
      <button class="btn-flag ${flaggedQuestions[q.id] ? "active" : ""}" data-id="${q.id}" title="Đánh dấu">
        ${flaggedQuestions[q.id] ? "★" : "☆"}</button>
    </div></div><div class="q-content">
    <div class="q-text">${q.question}</div>
    ${q.image ? `<div class="q-image"><img src="${q.image}" alt="Hình câu ${qCounter}"></div>` : ""}`;

    if (q.type === "mcq") {
      html += `<div class="options-list">`;
      q.options.forEach((opt, idx) => {
        html += `<label class="option-label" id="lbl-${q.id}-${idx}">
          <input type="radio" name="ans-${q.id}" value="${idx}">
          <span class="opt-letter">${["A","B","C","D"][idx]}.</span> ${opt}</label>`;
      });
      html += `</div>`;
    } else if (q.type === "fill") {
      html += `<input type="text" class="short-ans-input" name="ans-${q.id}" placeholder="Nhập đáp án...">`;
    }

    html += `<div class="explanation hidden" id="exp-${q.id}"><strong>Hướng dẫn giải:</strong> ${q.explanation}</div></div></div>`;
    card.innerHTML = html;
    questionsContainer.appendChild(card);
    qCounter++;
  });

  document.querySelectorAll(".btn-flag").forEach((btn) => {
    btn.addEventListener("click", (e) => {
      e.preventDefault();
      const qid = e.target.closest(".btn-flag").getAttribute("data-id");
      flaggedQuestions[qid] = !flaggedQuestions[qid];
      e.target.closest(".btn-flag").classList.toggle("active");
      e.target.closest(".btn-flag").innerText = flaggedQuestions[qid] ? "★" : "☆";
      updateBoard(); saveDraft();
    });
  });

  document.querySelectorAll("input").forEach((input) => {
    input.addEventListener("change", (e) => {
      const name = e.target.name;
      if (name.startsWith("ans-") && e.target.type === "radio") {
        const qid = name.replace("ans-", "");
        document.querySelectorAll(`input[name="${name}"]`).forEach((r) =>
          r.closest(".option-label").classList.remove("selected"));
        e.target.closest(".option-label").classList.add("selected");
        userAnswers[qid] = parseInt(e.target.value);
      } else if (e.target.type === "text") {
        const qid = name.replace("ans-", "");
        userAnswers[qid] = e.target.value;
      }
      updateBoard(); saveDraft();
    });
  });

  if (window.MathJax) MathJax.typesetPromise();
}

function renderBoard() {
  if (!questionBoard) return;
  const legend = document.createElement("div");
  legend.className = "board-legend";
  legend.innerHTML = `
    <span class="box"></span><span class="box-label">Chưa làm</span>
    <span class="box done"></span><span class="box-label">Đã làm</span>
    <span class="box flagged"></span><span class="box-label">Đánh dấu</span>`;
  questionBoard.appendChild(legend);

  const grid = document.createElement("div");
  grid.className = "q-grid";
  grid.id = "q-grid-inner";
  questionBoard.appendChild(grid);

  examData.forEach((q, index) => {
    const box = document.createElement("button");
    box.className = "q-box"; box.id = `box-${q.id}`; box.innerText = index + 1; box.type = "button";
    box.addEventListener("click", (e) => {
      e.preventDefault();
      document.getElementById(`q-card-${q.id}`).scrollIntoView({ behavior: "smooth", block: "center" });
    });
    grid.appendChild(box);
  });
  updateBoard();
}

function updateBoard() {
  let answeredCount = 0;
  examData.forEach((q) => {
    let answered = false;
    if (q.type === "mcq" && userAnswers[q.id] !== undefined) answered = true;
    if (q.type === "fill" && userAnswers[q.id] && userAnswers[q.id].trim() !== "") answered = true;
    
    if (answered) answeredCount++;
    if (questionBoard) {
      const box = document.getElementById(`box-${q.id}`);
      if (box) {
        box.className = "q-box";
        if (flaggedQuestions[q.id]) box.classList.add("flagged");
        else if (answered) box.classList.add("done");
      }
    }
  });
  const countEl = document.getElementById("answered-count");
  if (countEl) countEl.innerText = `${answeredCount}/${examData.length}`;
}

function saveDraft() {
  localStorage.setItem(DRAFT_KEY, JSON.stringify({
    studentName, studentClass, timeRemaining,
    userAnswers, flaggedQuestions, cheatCount, isFinished,
    lastSaved: new Date().toISOString(),
  }));
}

function restoreDOMState() {
  document.querySelectorAll("input").forEach((input) => {
    const name = input.name;
    if (!name) return;
    if (input.type === "radio" && name.startsWith("ans-")) {
      const qid = name.replace("ans-", "");
      if (userAnswers[qid] == input.value) {
        input.checked = true;
        input.closest(".option-label").classList.add("selected");
      }
    } else if (input.type === "text") {
      const qid = name.replace("ans-", "");
      input.value = userAnswers[qid] || "";
    }
  });
}

function startTimer() {
  timerInterval = setInterval(() => {
    timeRemaining--; saveDraft();
    const m = Math.floor(timeRemaining / 60).toString().padStart(2, "0");
    const s = (timeRemaining % 60).toString().padStart(2, "0");
    document.getElementById("countdown").innerText = `${m}:${s}`;
    if (timeRemaining === 30) {
      alert("⚠️ Cảnh báo: Chỉ còn 30 giây!");
      document.querySelector(".timer-pill").classList.add("timer-danger");
    }
    if (timeRemaining <= 0) { clearInterval(timerInterval); submitExam(); }
  }, 1000);
}

function setupAntiCheat() {
  window.addEventListener("beforeunload", (e) => {
    if (!isFinished) { e.preventDefault(); e.returnValue = "Bạn chưa nộp bài!"; }
  });
  window.addEventListener("pagehide", () => { if (!isFinished) saveDraft(); });
  document.addEventListener("visibilitychange", () => {
    if (document.hidden && !isFinished) { cheatCount++; saveDraft(); }
  });
}

submitBtn.addEventListener("click", () => {
  if (confirm("Bạn có chắc muốn nộp bài?")) submitExam();
});

function submitExam() {
  isFinished = true; clearInterval(timerInterval);
  document.querySelectorAll("input, .btn-flag").forEach((el) => (el.disabled = true));
  submitBtn.style.display = "none";
  const timerPill = document.querySelector(".timer-pill");
  if (timerPill) timerPill.classList.remove("timer-danger");

  let totalScore = 0;

  examData.forEach((q) => {
    document.getElementById(`exp-${q.id}`).classList.remove("hidden");
    
    if (q.type === "mcq") {
      const selected = userAnswers[q.id];
      document.getElementById(`lbl-${q.id}-${q.correctAnswer}`).classList.add("correct-ans");
      if (selected === q.correctAnswer) { 
        totalScore += 1; 
      } else if (selected !== undefined) {
        document.getElementById(`lbl-${q.id}-${selected}`).classList.add("wrong-ans");
      }
    } else if (q.type === "fill") {
      const input = document.querySelector(`input[name="ans-${q.id}"]`);
      const userVal = (userAnswers[q.id] || "").trim().toLowerCase();
      const correct = q.correctAnswer.toLowerCase();
      if (userVal === correct || userVal === correct.replace(".", ",")) {
        totalScore += 1; 
        input.classList.add("correct-ans");
      } else { 
        input.classList.add("wrong-ans"); 
      }
    }
  });

  const scorePill = document.getElementById("score-pill");
  document.querySelector(".timer-pill")?.classList.add("hidden");
  if (scorePill) { 
    scorePill.classList.remove("hidden"); 
    document.getElementById("review-score").innerText = totalScore.toFixed(0); 
  }

  saveExamResultToFirebase(totalScore, cheatCount);
  document.getElementById("final-score").innerText = totalScore.toFixed(0);
  document.getElementById("cheat-display").innerText = cheatCount;
  examScreen.classList.add("hidden"); 
  resultScreen.classList.remove("hidden");
  localStorage.removeItem(DRAFT_KEY);
}

async function saveExamResultToFirebase(tongDiem, soLanThoat) {
  const statusEl = document.getElementById("firebase-status");
  if (statusEl) statusEl.innerText = "⏳ Đang đồng bộ kết quả lên MTSedu...";
  try {
    const session = getMTSeduSession();
    const userId = session ? session.id : null;
    const resultData = {
      hoTen: studentName, lop: studentClass, maDe: MA_DE,
      tongDiem, soLanThoat,
      userId: userId || "unknown",
      thoiGianNop: new Date().toISOString(),
      serverTimestamp: serverTimestamp(),
    };
    const updates = {};
    const newResultId = push(ref(db, `testResults/${MA_DE}`)).key;
    updates[`testResults/${MA_DE}/${newResultId}`] = resultData;
    if (userId) updates[`users/${userId}/results/${newResultId}`] = resultData;
    await update(ref(db), updates);
    if (statusEl) { statusEl.style.color = "green"; statusEl.innerText = "✅ Kết quả đã được đồng bộ thành công!"; }
  } catch (error) {
    if (statusEl) { statusEl.style.color = "red"; statusEl.innerText = "❌ Lỗi: " + error.message; }
  }
}

document.getElementById("review-btn").addEventListener("click", () => {
  resultScreen.classList.add("hidden");
  examScreen.classList.remove("hidden");
  window.scrollTo({ top: 0, behavior: "smooth" });
});

``

## File: style.css

``css
:root {
  --bg-color: #f8fafc;
  --grid-color: #e2e8f0;
  --ink: #1e293b;
  --navy: #1e3a8a;
  --blue-text: #2563eb;
  --gray-text: #64748b;
  --border-color: #e2e8f0;
  --font-sans:
    system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-serif: "Times New Roman", Times, serif;
}

* {
  box-sizing: border-box;
  margin: 0;
  padding: 0;
}

body {
  background-color: var(--bg-color);
  background-image:
    linear-gradient(var(--grid-color) 1px, transparent 1px),
    linear-gradient(90deg, var(--grid-color) 1px, transparent 1px);
  background-size: 25px 25px;
  font-family: var(--font-sans);
  color: var(--ink);
  line-height: 1.6;
}

.hidden {
  display: none !important;
}

.container {
  max-width: 900px;
  margin: 40px auto;
  padding: 0 20px;
}

/* BẢNG ĐIỀU HƯỚNG STICKY NHỎ */
#board-container {
  position: fixed;
  bottom: 30px;
  right: 30px;
  width: 280px;
  max-height: 400px;
  background: #fff;
  border: 1px solid var(--border-color);
  border-radius: 12px;
  padding: 12px;
  box-shadow: 0 4px 12px rgba(0, 0, 0, 0.15);
  z-index: 500;
  overflow-y: auto;
}

#board-container h3 {
  font-size: 13px;
  font-weight: bold;
  color: var(--navy);
  margin-bottom: 8px;
  text-transform: uppercase;
  letter-spacing: 1px;
}

.board-legend {
  font-size: 11px;
  display: flex;
  flex-wrap: wrap;
  gap: 6px;
  margin-bottom: 10px;
  padding: 8px;
  background: #f8fafc;
  border-radius: 6px;
}

.box {
  width: 18px;
  height: 18px;
  border: 1px solid #ccc;
  border-radius: 4px;
  display: inline-block;
  background: #fff;
}

.box.done {
  background-color: #007bff;
  border-color: #007bff;
}

.box.flagged {
  background-color: #ffc107;
  border-color: #ffc107;
}

.box-label {
  font-size: 11px;
  color: var(--gray-text);
  line-height: 18px;
}

.board-wrapper {
  display: flex;
  flex-direction: column;
  gap: 0;
}

.q-grid {
  display: grid;
  grid-template-columns: repeat(4, 1fr);
  gap: 6px;
}

.q-box {
  padding: 8px;
  text-align: center;
  border: 1px solid #ccc;
  border-radius: 4px;
  cursor: pointer;
  font-weight: bold;
  font-size: 12px;
  background: #fff;
  transition: all 0.2s;
}

.q-box:hover {
  background: #f0f0f0;
  transform: scale(1.05);
}

.q-box.done {
  background-color: #007bff;
  color: white;
  border-color: #007bff;
}

.q-box.flagged {
  background-color: #ffc107;
  color: #333;
  border-color: #ffc107;
  font-weight: bold;
}

/* CARD CHUNG */
.card {
  background: #fff;
  border-radius: 8px;
  padding: 30px;
  box-shadow: 0 1px 3px rgba(0, 0, 0, 0.1);
  border: 1px solid var(--border-color);
}

.login-card,
.result-card {
  text-align: center;
  max-width: 500px;
  margin: 80px auto;
}

.form-group input {
  width: 100%;
  padding: 12px;
  border: 1px solid #ccc;
  border-radius: 6px;
  font-size: 16px;
  margin-bottom: 15px;
}

.btn-primary {
  background-color: var(--navy);
  color: #fff;
  border: none;
  padding: 12px 24px;
  font-size: 16px;
  border-radius: 6px;
  cursor: pointer;
  font-weight: bold;
  transition: 0.2s;
}

.btn-primary:hover {
  background-color: #1e3a8a;
  transform: translateY(-2px);
}

.submit-container {
  text-align: center;
  margin: 40px 0 80px 0;
}

/* HEADER BÀI THI */
.exam-header-block {
  margin-bottom: 30px;
}

.exam-header-top {
  background: #fff;
  padding: 25px 30px;
  border: 1px solid var(--border-color);
  border-radius: 12px 12px 0 0;
  border-bottom: none;
}

.meta-text {
  font-family: var(--font-sans);
  font-size: 12px;
  color: var(--gray-text);
  letter-spacing: 2px;
  text-transform: uppercase;
  margin-bottom: 10px;
}

.exam-title {
  font-family: var(--font-serif);
  font-size: 28px;
  color: var(--navy);
  margin-bottom: 10px;
}

.meta-sub {
  font-size: 14px;
  color: var(--gray-text);
}

.dashed-line {
  border: none;
  border-top: 1px dashed #cbd5e1;
  margin-top: 20px;
  position: relative;
}

.dashed-line::after {
  content: "";
  position: absolute;
  right: -5px;
  top: -5px;
  width: 8px;
  height: 8px;
  border: 1px solid #cbd5e1;
  border-radius: 50%;
  background: #fff;
}

/* THANH THÔNG TIN & TIMER */
.exam-info-bar {
  background-color: var(--navy);
  color: #94a3b8;
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 12px 30px;
  border-radius: 0 0 12px 12px;
  font-size: 14px;
}

.exam-info-bar.sticky {
  position: sticky;
  top: 0;
  z-index: 100;
  box-shadow: 0 4px 6px -1px rgba(0, 0, 0, 0.1);
}

.timer-pill {
  background-color: #334155;
  color: #fff;
  padding: 4px 12px;
  border-radius: 20px;
  font-weight: bold;
  font-family: monospace;
  font-size: 16px;
  display: flex;
  align-items: center;
  gap: 6px;
}

.green-dot {
  color: #4ade80;
  font-size: 12px;
}

.timer-danger {
  background-color: #ef4444 !important;
  animation: pulse 1s infinite;
}

@keyframes pulse {
  0%,
  100% {
    opacity: 1;
  }
  50% {
    opacity: 0.7;
  }
}

/* TIÊU ĐỀ PHẦN */
.section-header {
  margin: 40px 0 20px 0;
  border-bottom: 1px solid var(--border-color);
  padding-bottom: 10px;
}

.section-title {
  font-family: var(--font-serif);
  font-size: 22px;
  font-weight: bold;
  color: var(--navy);
  display: flex;
  align-items: center;
  gap: 10px;
}

.badge {
  font-family: var(--font-sans);
  background-color: #e0e7ff;
  color: var(--blue-text);
  font-size: 12px;
  padding: 3px 8px;
  border-radius: 12px;
  font-weight: bold;
}

.section-subtitle {
  font-size: 14px;
  color: var(--gray-text);
  margin-top: 5px;
}

/* CÂU HỎI */
.question-card {
  background: #fff;
  border: 1px solid var(--border-color);
  border-radius: 8px;
  padding: 20px 25px;
  margin-bottom: 15px;
}

.q-layout {
  display: flex;
  flex-direction: column;
  gap: 15px;
}

.q-header {
  display: flex;
  justify-content: flex-start;
  align-items: center;
  gap: 12px;
}

.q-num-flag {
  display: flex;
  align-items: center;
  gap: 10px;
  flex-wrap: nowrap;
}

.q-num {
  background: var(--navy);
  color: #fff;
  width: 60px;
  height: 28px;
  display: flex;
  justify-content: center;
  align-items: center;
  border-radius: 6px;
  font-weight: bold;
  font-size: 14px;
  flex-shrink: 0;
}

.btn-flag {
  margin-bottom: 10px;
  cursor: pointer;
  padding: 4px 8px;
  width: 70px;
  height: 30px;
  background: #f0f0f0;
  border: 1px solid #ccc;
  border-radius: 5px;
}

.btn-flag:hover {
  border-color: #ffc107;
  color: #ffc107;
  background: #fffbf0;
}

.btn-flag.active {
  background: #ffc107;
  border-color: #ffc107;
  color: #333;
}

.q-content {
  flex: 1;
}

.q-text {
  font-size: 16px;
  margin-bottom: 15px;
  margin-top: 2px;
  line-height: 1.6;
}

.q-image {
  margin: 15px 0;
  display: flex;
  justify-content: center;
}

.q-image img {
  max-width: 100%;
  height: auto;
  border: 1px solid var(--border-color);
  border-radius: 8px;
  box-shadow: 0 2px 8px rgba(0, 0, 0, 0.1);
}

/* ĐÁP ÁN TRẮC NGHIỆM */
.options-list {
  display: flex;
  flex-direction: column;
  gap: 10px;
}

.option-label {
  display: block;
  border: 1px solid var(--border-color);
  border-radius: 8px;
  padding: 12px 15px;
  cursor: pointer;
  transition: 0.2s;
}

.option-label:hover {
  border-color: #93c5fd;
  background: #f8fafc;
}

.option-label input {
  display: none;
}

.option-label.selected {
  border-color: var(--blue-text);
  background: #eff6ff;
}

.opt-letter {
  color: var(--blue-text);
  font-weight: bold;
  margin-right: 10px;
  font-family: var(--font-serif);
}

/* ĐÚNG SAI */
.tf-row {
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 12px 15px;
  border: 1px solid var(--border-color);
  border-radius: 8px;
  margin-bottom: 10px;
}

.tf-controls {
  display: flex;
  gap: 15px;
  flex-shrink: 0;
}

.tf-controls label {
  cursor: pointer;
  font-size: 14px;
}

.short-ans-input {
  width: 100%;
  max-width: 300px;
  padding: 10px;
  border: 1px solid var(--border-color);
  border-radius: 6px;
  font-size: 14px;
}

/* CHẤM ĐIỂM */
.correct-ans {
  background-color: #dcfce7 !important;
  border-color: #22c55e !important;
}

.wrong-ans {
  background-color: #fee2e2 !important;
  border-color: #ef4444 !important;
}

.explanation {
  margin-top: 15px;
  padding: 15px;
  background: #f8fafc;
  border-left: 3px solid var(--navy);
  font-size: 14px;
  border-radius: 4px;
}

.image-placeholder {
  background: #f1f5f9;
  border: 2px dashed #cbd5e1;
  padding: 30px;
  text-align: center;
  color: #64748b;
  margin: 15px 0;
  border-radius: 8px;
}

.page-footer {
  text-align: center;
  font-size: 12px;
  color: var(--gray-text);
  margin-top: 40px;
  padding-top: 20px;
  border-top: 1px solid var(--border-color);
}

.form-note {
  font-size: 13px;
  color: var(--gray-text);
  margin-top: 15px;
  font-style: italic;
}

/* RESPONSIVE */
@media (max-width: 768px) {
  #board-container {
    width: 240px;
    bottom: 20px;
    right: 20px;
  }

  .q-grid {
    grid-template-columns: repeat(3, 1fr);
  }

  .exam-title {
    font-size: 22px;
  }

  .container {
    margin: 20px auto;
  }
}

@media (max-width: 480px) {
  #board-container {
    width: 200px;
    bottom: 10px;
    right: 10px;
    max-height: 300px;
  }

  .q-grid {
    grid-template-columns: repeat(2, 1fr);
  }

  .q-num-flag {
    flex-direction: column;
    align-items: flex-start;
  }

  .exam-info-bar {
    flex-direction: column;
    gap: 10px;
    padding: 10px 15px;
  }

  .tf-row {
    flex-direction: column;
    align-items: flex-start;
    gap: 10px;
  }

  .tf-controls {
    width: 100%;
    justify-content: space-around;
  }
}
.score-pill {
  background-color: #16a34a;
  color: #fff;
  padding: 4px 12px;
  border-radius: 20px;
  font-weight: bold;
  font-family: monospace;
  font-size: 16px;
  display: flex;
  align-items: center;
  gap: 6px;
}

.score-pill .green-dot {
  color: #fff;
}


#toast {
  position: fixed;
  top: 70px;
  left: 50%;
  transform: translateX(-50%) translateY(-20px);
  background: #b91c1c;
  color: #fff;
  padding: 10px 20px;
  border-radius: 8px;
  font-size: 14px;
  font-weight: 600;
  box-shadow: 0 4px 16px rgba(0, 0, 0, 0.25);
  opacity: 0;
  pointer-events: none;
  transition: opacity 0.25s, transform 0.25s;
  z-index: 10000;
}
#toast.show {
  opacity: 1;
  transform: translateX(-50%) translateY(0);
}

``

