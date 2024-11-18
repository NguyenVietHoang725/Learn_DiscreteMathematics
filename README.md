# Toán Rời Rạc

---

#### Mục lục

---

# Chương 4: Quan hệ

## 1. Quan hệ hai ngôi - Binary Relations

Giả sử `A`, `B` là các tập bất kỳ. **Quan hệ hai ngôi R** từ `A` vào `B`, viết dạng `R:AxB`, hoặc `R:A,B` là **tập con** của tập `AxB`.

- Ký hiệu: `aRb` có nghĩa là (a, b) $\in$ **R**.
- Nếu `aRb` ta nói "`a` có quan hệ với `b` (qua quan hệ **R**)"

## 2. Quan hệ bù - Complementary Relations

Giả sử R:A,B là quan hệ hai ngôi bất kỳ. Khi đó, $\not$R:AxB (phần bù của R) là quan hệ hai ngôi xác định như sau:

$\not$R:$\equiv$ {(a,b) | (a,b) $\notin$ R} = (AxB) - R

- Ký hiệu phần bù của R là $\not$R.

## 3. Quan hệ ngược - Inverse Relations

Quan hệ hai ngôi bất kỳ R:AxB có quan hệ ngược $R^{-1}$:BxA, xác định bởi:

$R^{-1}$:$\equiv$ {(b, a) | (a,b) $\in$ R}

## 4. Tính phản xạ và phi phản xạ

Quan hệ R trên A là phản xạ nếu $\forall$a$\in$A, aRa.

Quan hệ R trên A là phi phản xạ khi và chỉ khi quan hệ bù của nó $\not$R là phản xạ.

## 5. Tính đối xứng và phản đối xứng

Quan hệ hai ngôi R trên A là đối xứng khi và chỉ khi $R$ = $R^{-1}$, tức là nếu (a,b) $\in$ R $\leftrightarrow$ (b,a) $\in$ R.

Quan hệ hai ngôi R là phản xứng nếu $\forall$a$\ne$b, (a,b) $\in$ R $\rightarrow$ (b,a) $\notin$ R.

## 6. Tính bắc cầu

Quan hệ R là bắc cầu khi và chỉ khi $\forall$(a, b, c) ta có:

(a,b) $\in$ R $\wedge$ (b,c) $\in$ R $\rightarrow$ (c,a) $\in$ R.

## 7. Tích quan hệ - Composite Relations

Cho R:AxB và S:BxC. Khi đó, phép hợp S$\circ$R (composite) của R và S được định nghĩa như sau:

S $\circ$ R = {(a,c) | $\exists$b: aRb $\wedge$ bSC}

Luỹ thừa bậc n của R trên tập A được định nghĩa đệ qui như sau:

$R^0$ :$\equiv$ $I_{A}$ (Quan hệ đồng nhất trên A)

$R^{n+1}$ :$\equiv$ $R^n$$\circ$$R$ với mọi n $\geq$ 0.

Luỹ thừa âm của R có thể định nghĩa bởi $R^{-1}$ :$\equiv$ $(R^{-1})^n$

## 8. Biểu diễn quan hệ bằng Ma trận 0 - 1

Biểu diễn quan hệ hai ngôi $R:A$$\times$$B$ bằng ma trận 0 - 1 (cỡ |$A$|$\times$|$B$|) $M_R$ = [$m_{ij}$], với $m_{ij}$ = 1 khi và chỉ khi ($a_i$, $b_j$) $\in$ $R$

Thực hiện các phép toán trên quan hệ nhờ Ma trận 0 - 1

- Cho $R:A$$\times$$B$, $S:A$$\times$$B$, khi đó
  - $M_{R \cup S}$ = $M_{R}$ $\vee$ $M_S$
  - $M_{R \cap S}$ = $M_{R}$ $\wedge$ $M_S$
  - $M_{\overline R}$ = $\overline M_R$
- Cho $R:A$$\times$$B$, $S:B$$\times$$C$, khi đó $M_{S \circ R}$ = $M_R$ $\otimes$ $M_S$

## 9. Bao đóng của quan hệ
