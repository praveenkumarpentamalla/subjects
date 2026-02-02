# ELEMENTARY STATISTICS: Complete Mastery Guide for Government Exams

## 1. FOUNDATION TO ADVANCED COVERAGE

### **BASIC CONCEPTS (Foundation Level)**

#### **A. What is Statistics?**

**Definition:** Statistics is the science of collecting, organizing, analyzing, and interpreting numerical data.

**Real-world Example:** 
- **Average score** of a class (mean)
- **Most common shoe size** in a store (mode)
- **Middle salary** in a company (median)

---

#### **B. Types of Data**

**1. Ungrouped Data:** Individual values listed separately
```
Example: Marks of 5 students: 60, 70, 80, 90, 100
```

**2. Grouped Data:** Data organized in class intervals
```
Example: 
Marks Range    Frequency
0-20           5
20-40          10
40-60          15
```

---

### **MEASURES OF CENTRAL TENDENCY**

#### **1. MEAN (Average)**

**Definition:** Sum of all values divided by number of values

**Formula for Ungrouped Data:**
```
Mean (x̄) = Sum of all values / Number of values
         = Σx / n
```

**Example:** Marks: 60, 70, 80, 90, 100
```
Mean = (60+70+80+90+100) / 5 = 400 / 5 = 80
```

**Real-world:** Average temperature, average salary, average score

---

**Formula for Grouped Data (Direct Method):**
```
Mean = Σ(f × x) / Σf
```
Where:
- f = frequency
- x = class mark (mid-value)
- Class mark = (Upper limit + Lower limit) / 2

**Example:**

| Marks | Frequency (f) | Class Mark (x) | f × x |
|-------|---------------|----------------|-------|
| 0-10  | 5             | 5              | 25    |
| 10-20 | 10            | 15             | 150   |
| 20-30 | 15            | 25             | 375   |

```
Mean = Σ(f×x) / Σf = (25+150+375) / (5+10+15) = 550 / 30 = 18.33
```

---

**Assumed Mean Method (Shortcut for large numbers):**
```
Mean = A + [Σ(f × d) / Σf]
```
Where:
- A = Assumed mean (any class mark, preferably middle one)
- d = x - A (deviation from assumed mean)

**Why useful?** Simplifies calculation when dealing with large numbers!

---

**Step Deviation Method (Best for equal class intervals):**
```
Mean = A + [Σ(f × u) / Σf] × h
```
Where:
- u = (x - A) / h (coded deviation)
- h = class width (interval)

**Most efficient for exams!**

---

#### **2. MEDIAN (Middle Value)**

**Definition:** The middle value when data is arranged in order

**For Ungrouped Data:**

**Step 1:** Arrange in ascending/descending order
**Step 2:** Find middle position

**If n is odd:**
```
Median = Value at position (n+1)/2
```

**If n is even:**
```
Median = Average of values at positions n/2 and (n/2)+1
```

**Example 1:** Data: 3, 7, 9, 12, 15 (n=5, odd)
```
Median = 3rd value = 9
```

**Example 2:** Data: 3, 7, 9, 12, 15, 18 (n=6, even)
```
Median = (9+12)/2 = 10.5
```

---

**For Grouped Data:**
```
Median = L + [(n/2 - cf) / f] × h
```
Where:
- L = Lower boundary of median class
- n = Total frequency (Σf)
- cf = Cumulative frequency of class before median class
- f = Frequency of median class
- h = Class width

**Steps:**
1. Find n/2
2. Locate median class (where cumulative frequency ≥ n/2)
3. Apply formula

**Example:**

| Class | Frequency | Cumulative Frequency |
|-------|-----------|---------------------|
| 0-10  | 5         | 5                   |
| 10-20 | 10        | 15                  |
| 20-30 | 15        | 30                  |
| 30-40 | 10        | 40                  |

```
n = 40, n/2 = 20
Median class = 20-30 (cf = 15 < 20, next cf = 30 ≥ 20)
L = 20, cf = 15, f = 15, h = 10

Median = 20 + [(20-15)/15] × 10
       = 20 + (5/15) × 10
       = 20 + 3.33 = 23.33
```

---

#### **3. MODE (Most Frequent Value)**

**Definition:** The value that appears most frequently

**For Ungrouped Data:**
Simply identify the most repeated value

**Example:** Data: 3, 5, 5, 7, 9, 5, 12
```
Mode = 5 (appears 3 times)
```

---

**For Grouped Data:**
```
Mode = L + [(f₁ - f₀) / (2f₁ - f₀ - f₂)] × h
```
Where:
- L = Lower boundary of modal class (class with highest frequency)
- f₁ = Frequency of modal class
- f₀ = Frequency of class before modal class
- f₂ = Frequency of class after modal class
- h = Class width

**Example:**

| Class | Frequency |
|-------|-----------|
| 0-10  | 5         |
| 10-20 | 10        |
| 20-30 | 15        | ← Modal class (highest frequency)
| 30-40 | 10        |

```
L = 20, f₁ = 15, f₀ = 10, f₂ = 10, h = 10

Mode = 20 + [(15-10) / (30-10-10)] × 10
     = 20 + [5/10] × 10
     = 20 + 5 = 25
```

---

### **RELATIONSHIP BETWEEN MEAN, MEDIAN, MODE**

**Empirical Formula (for moderately skewed distribution):**
```
Mode = 3 Median - 2 Mean
```

**Or:**
```
Mean - Mode = 3(Mean - Median)
```

**Pattern Recognition:**
- **Symmetrical distribution:** Mean = Median = Mode
- **Positively skewed:** Mean > Median > Mode
- **Negatively skewed:** Mean < Median < Mode

---

### **INTERMEDIATE LEVEL TECHNIQUES**

#### **A. RANGE**

**Definition:** Difference between highest and lowest values

```
Range = Highest value - Lowest value
```

**Example:** Data: 20, 30, 40, 50, 60
```
Range = 60 - 20 = 40
```

**Real-world:** Temperature range (max - min), price range

---

#### **B. VARIANCE and STANDARD DEVIATION**

**Variance (σ²):** Measures spread of data around mean

**Standard Deviation (σ):** Square root of variance

**For Ungrouped Data:**
```
Variance (σ²) = Σ(x - x̄)² / n
Standard Deviation (σ) = √[Σ(x - x̄)² / n]
```

**Shortcut Formula:**
```
σ² = [Σx² / n] - (x̄)²
σ = √{[Σx² / n] - (x̄)²}
```

**Example:** Data: 2, 4, 6, 8, 10
```
Mean = 6
Σx² = 4 + 16 + 36 + 64 + 100 = 220
σ² = (220/5) - 36 = 44 - 36 = 8
σ = √8 ≈ 2.83
```

---

**For Grouped Data:**
```
σ² = [Σf(x - x̄)² / Σf]

Or (Shortcut):
σ² = [Σf·x² / Σf] - (x̄)²
```

**Step Deviation Method (Best for exams):**
```
σ = h × √{[Σf·u² / Σf] - ([Σf·u / Σf])²}
```
Where u = (x - A) / h

---

#### **C. COEFFICIENT OF VARIATION (CV)**

**Definition:** Measures relative variation (for comparing two datasets)

```
CV = (σ / x̄) × 100%
```

**Use:** To compare consistency of two different datasets

**Example:** 
- Team A: Mean = 50, SD = 10 → CV = (10/50) × 100 = 20%
- Team B: Mean = 100, SD = 15 → CV = (15/100) × 100 = 15%

**Team B is more consistent** (lower CV)

---

### **ADVANCED PROBLEM-SOLVING STRATEGIES**

#### **A. Combined Mean**

**When two groups are combined:**
```
Combined Mean = (n₁x̄₁ + n₂x̄₂) / (n₁ + n₂)
```

**Example:** 
- Class A: 30 students, mean = 60
- Class B: 20 students, mean = 70

```
Combined mean = (30×60 + 20×70) / (30+20)
              = (1800 + 1400) / 50
              = 3200 / 50 = 64
```

---

#### **B. Effect of Change on Mean**

**If constant k is:**
- **Added to all values:** New mean = Old mean + k
- **Subtracted:** New mean = Old mean - k
- **Multiplied:** New mean = Old mean × k
- **Divided:** New mean = Old mean / k

**Example:** Mean = 50, each value increased by 10
```
New mean = 50 + 10 = 60
```

---

#### **C. Weighted Mean**

**When values have different importance (weights):**
```
Weighted Mean = Σ(w × x) / Σw
```

**Example:** Exam weights
- Theory (weight 3): 70 marks
- Practical (weight 2): 80 marks

```
Weighted mean = (3×70 + 2×80) / (3+2)
              = (210 + 160) / 5 = 74
```

---

## 2. FORMULAS & SHORTCUTS

### **MASTER FORMULA LIST**

#### **A. Central Tendency**

**1. Mean (Ungrouped):**
```
x̄ = Σx / n
```

**2. Mean (Grouped - Direct):**
```
x̄ = Σ(f × x) / Σf
```

**3. Mean (Assumed Mean Method):**
```
x̄ = A + [Σ(f × d) / Σf]
```

**4. Mean (Step Deviation):**
```
x̄ = A + [Σ(f × u) / Σf] × h
```

**5. Median (Ungrouped, odd n):**
```
Median = Value at (n+1)/2 position
```

**6. Median (Ungrouped, even n):**
```
Median = Average of n/2 and (n/2+1) positions
```

**7. Median (Grouped):**
```
Median = L + [(n/2 - cf) / f] × h
```

**8. Mode (Grouped):**
```
Mode = L + [(f₁ - f₀) / (2f₁ - f₀ - f₂)] × h
```

**9. Empirical Relation:**
```
Mode = 3 Median - 2 Mean
```

---

#### **B. Dispersion**

**10. Range:**
```
Range = Max - Min
```

**11. Variance:**
```
σ² = Σ(x - x̄)² / n
Or: σ² = [Σx² / n] - (x̄)²
```

**12. Standard Deviation:**
```
σ = √[Σ(x - x̄)² / n]
Or: σ = √{[Σx² / n] - (x̄)²}
```

**13. Coefficient of Variation:**
```
CV = (σ / x̄) × 100%
```

---

#### **C. Combined/Weighted**

**14. Combined Mean:**
```
x̄ = (n₁x̄₁ + n₂x̄₂) / (n₁ + n₂)
```

**15. Weighted Mean:**
```
x̄w = Σ(w × x) / Σw
```

---

### **TIME-SAVING SHORTCUTS**

#### **Shortcut 1: Quick Mean (Ungrouped)**

**For evenly spaced values:**
```
Mean = (First + Last) / 2
```

**Example:** 10, 20, 30, 40, 50
```
Mean = (10 + 50) / 2 = 30
```

**Works only for arithmetic progression!**

---

#### **Shortcut 2: Median Position**

**Quick formula for finding median position:**
- **Odd n:** Middle = (n+1)/2
- **Even n:** Two middles = n/2 and (n/2)+1

**Example:** 7 values → Median at position 4
**Example:** 8 values → Median = average of positions 4 and 5

---

#### **Shortcut 3: Mode Recognition**

**In grouped data, modal class is simply:**
- The class with **highest frequency**

**Then apply formula only to that class!**

---

#### **Shortcut 4: Step Deviation (Coded Values)**

**Instead of working with large numbers like 1005, 1015, 1025:**
- Choose A = 1015 (middle value)
- h = 10
- Convert to u = (x - 1015) / 10 = -1, 0, 1

**Work with small numbers -1, 0, 1 instead!**

---

#### **Shortcut 5: Variance from Mean**

**If mean is given, use shortcut formula:**
```
σ² = [Σx² / n] - (Mean)²
```

**Don't calculate (x - mean)² for each value!**

---

#### **Shortcut 6: Combined Mean (Quick)**

**When n₁ = n₂ (equal groups):**
```
Combined mean = (x̄₁ + x̄₂) / 2
```

**Example:** Two groups of 20 each, means 60 and 70
```
Combined = (60 + 70) / 2 = 65
```

---

#### **Shortcut 7: Effect of Transformation**

**Remember the pattern:**
- Add/Subtract k → Mean changes, SD unchanged
- Multiply/Divide k → Both mean and SD change

**Example:** All values ×2
- New mean = 2 × old mean
- New SD = 2 × old SD

---

#### **Shortcut 8: Coefficient of Variation**

**Quick mental calculation:**
```
CV = (SD / Mean) × 100
```

**If SD = 10, Mean = 50:**
```
CV = (10/50) × 100 = 20%
```

**Mental: 10 is 1/5 of 50, so 20%**

---

#### **Shortcut 9: Cumulative Frequency**

**For median class:**
- Don't recalculate cf each time
- Mark it while making the table
- Median class = First cf ≥ n/2

---

#### **Shortcut 10: Checking Answers (Reasonableness)**

**Mean should be:**
- Between min and max values
- Close to middle values

**If mean = 80 but all values are around 20-30 → ERROR!**

---

### **ALTERNATIVE METHODS COMPARISON**

**Problem:** Find mean of grouped data

**Method 1: Direct Method (30s)**
```
Calculate f×x for each class
Sum them all
Divide by Σf
```

**Method 2: Assumed Mean (25s)**
```
Choose middle class mark as A
Calculate d = x - A
Calculate f×d
Mean = A + Σ(f×d)/Σf
```

**Method 3: Step Deviation (20s)**
```
Choose A, note h
Calculate u = (x-A)/h
Calculate f×u
Mean = A + [Σ(f×u)/Σf] × h
```

**Best for Exam:** Step Deviation (smallest numbers to work with!)

---

### **WHEN TO USE WHICH METHOD**

| Problem Type | Best Method | Time |
|--------------|-------------|------|
| Mean (5-6 values) | Direct sum/n | 10s |
| Mean (evenly spaced) | (First+Last)/2 | 5s |
| Mean (grouped, small numbers) | Direct f×x | 25s |
| Mean (grouped, large numbers) | Step deviation | 20s |
| Median (ungrouped) | Arrange & find middle | 15s |
| Median (grouped) | Formula with cf | 30s |
| Mode (ungrouped) | Count frequency | 10s |
| Mode (grouped) | Formula | 25s |
| Range | Max - Min | 3s |
| SD (given mean) | Shortcut formula | 30s |
| Combined mean (equal n) | Average of means | 10s |
| Combined mean (unequal n) | Weighted formula | 20s |

---

## 3. MEMORY TECHNIQUES

### **MNEMONICS FOR FORMULAS**

#### **A. "Some Fractions Need" (Mean)**

**S**um (**Σ**)
**F**requency times (**f ×**)
**N**umber (**n** or **Σf**)

```
Mean = Σ(f×x) / Σf
```

---

#### **B. "Lazy Cat Fishers" (Median Formula)**

**L**ower limit +
**C**alculate (n/2 - cf) /
**F**requency times
**H**eight (class width)

```
Median = L + [(n/2 - cf) / f] × h
```

---

#### **C. "Left Fish Right" (Mode Formula)**

**L**ower +
**F**₁ minus f₀ (left fish)
**R**ight calculation: 2f₁ - f₀ - f₂

```
Mode = L + [(f₁-f₀) / (2f₁-f₀-f₂)] × h
```

---

#### **D. "3-2 Relation" (Empirical)**

**3** Median - **2** Mean

```
Mode = 3 Median - 2 Mean
```

**Memory:** "Three med minus two mean gives mode clean!"

---

#### **E. "Sigma Squared Sum" (Variance)**

**Σ**um of squares (**Σx²**)
**S**quared mean (**x̄²**)

```
σ² = [Σx² / n] - (x̄)²
```

---

#### **F. "n₁x₁ + n₂x₂ over n₁+n₂" (Combined Mean)**

Chant it like a rhythm!

```
Combined = (n₁x̄₁ + n₂x̄₂) / (n₁+n₂)
```

---

### **VISUALIZATION TECHNIQUES**

#### **A. The Number Line (Median)**

Visualize data arranged on a number line:

```
2  4  6  [8]  10  12  14
         ↑
      Median (middle)
```

**For even count, median is between two middles**

---

#### **B. The Frequency Bar Chart (Mode)**

Mode is the **tallest bar** (highest frequency)!

```
    ___
   |   |
   | 15| ← Modal class
___|___|___
| 10| 15| 10|
|___|___|___|
```

---

#### **C. The Balance Point (Mean)**

Mean is the **balance point** of data:

```
2  3  4  [5]  6  7  8
         ↑
    Mean (balance)
```

---

#### **D. The Spread Visual (Standard Deviation)**

SD shows how **spread out** data is:

```
Low SD:  • • •|• • •  (clustered around mean)
High SD: •   • |   •  (spread out)
                ↑
              Mean
```

---

### **PATTERN RECOGNITION TIPS**

#### **Pattern 1: Symmetrical Data**

```
If data is symmetrical:
Mean = Median = Mode
```

**Example:** 10, 20, 30, 40, 50
- All three = 30

---

#### **Pattern 2: Skewed Data**

```
Positively skewed (tail on right):
Mean > Median > Mode

Negatively skewed (tail on left):
Mean < Median < Mode
```

---

#### **Pattern 3: Equal Class Intervals**

```
If all class widths are equal:
Use Step Deviation Method!
h is constant
```

---

#### **Pattern 4: Consecutive Numbers**

```
Mean of 1,2,3,...,n = (n+1)/2
```

**Example:** 1 to 10
```
Mean = 11/2 = 5.5
```

---

#### **Pattern 5: Effect of Outliers**

```
Outliers affect: Mean (yes), Median (less), Mode (no)
```

**Data:** 10, 12, 14, 16, 100
- Mean = 30.4 (affected by 100)
- Median = 14 (not much affected)

---

### **MEMORY HOOKS THAT LAST**

#### **Hook 1: "Mean is Mean to Outliers"**

> Mean gets pulled by extreme values (outliers)
> Median is more robust!

---

#### **Hook 2: "Mode is Most"**

> Mode = **Most** frequently occurring value

---

#### **Hook 3: "Median is Middle"**

> Median = **Middle** value when arranged

---

#### **Hook 4: "Add Frequencies, Find Products"**

For grouped mean:
> Add all **f**, multiply each **f × x**, divide!

---

#### **Hook 5: "n/2 Finds Median Class"**

> Calculate **n/2**, find cf that exceeds it!

---

#### **Hook 6: "Standard Deviation Never Negative"**

> SD = √(something) → Always positive or zero!

---

## 4. GOVERNMENT EXAM QUESTIONS (15-20)

### **BASIC LEVEL (Questions 1-5)**

---

**Q1. [SSC CGL 2019]**
Find the mean of 10, 20, 30, 40, 50.

**Solution:**
```
Mean = (10+20+30+40+50) / 5 = 150 / 5 = 30
```

**Shortcut (Evenly spaced):**
```
Mean = (First + Last) / 2 = (10+50) / 2 = 30
```

**Answer:** 30
**Time:** 5 seconds

---

**Q2. [Railway Group D 2018]**
Find the median of 3, 7, 9, 12, 15.

**Solution:**
```
Already arranged, n = 5 (odd)
Median position = (5+1)/2 = 3rd value
Median = 9
```

**Answer:** 9
**Time:** 8 seconds

---

**Q3. [SBI PO 2020]**
Find the mode of 3, 5, 7, 5, 9, 5, 11.

**Solution:**
```
5 appears 3 times (most frequent)
Mode = 5
```

**Answer:** 5
**Time:** 5 seconds

---

**Q4. [SSC CHSL 2019]**
The mean of 5 numbers is 20. If one number 25 is replaced by 30, what is the new mean?

**Solution:**
```
Sum of 5 numbers = 5 × 20 = 100
New sum = 100 - 25 + 30 = 105
New mean = 105 / 5 = 21
```

**Answer:** 21
**Time:** 15 seconds

---

**Q5. [IBPS Clerk 2018]**
Find the range of 12, 18, 25, 30, 45.

**Solution:**
```
Range = Max - Min = 45 - 12 = 33
```

**Answer:** 33
**Time:** 5 seconds

---

### **INTERMEDIATE LEVEL (Questions 6-12)**

---

**Q6. [SSC CGL 2020]**
The mean of 6, 8, 10, 12, x, 16 is 11. Find x.

**Solution:**
```
Mean = Sum / n
11 = (6+8+10+12+x+16) / 6
66 = 52 + x
x = 14
```

**Answer:** 14
**Time:** 20 seconds

---

**Q7. [Railway NTPC 2021]**
Find the median of 4, 2, 8, 6, 10, 12.

**Solution:**
```
Arrange: 2, 4, 6, 8, 10, 12
n = 6 (even)
Median = (6+8) / 2 = 14/2 = 7
```

**Answer:** 7
**Time:** 15 seconds

---

**Q8. [SBI Clerk 2019]**
Class marks of a distribution are 5, 15, 25, 35 with frequencies 4, 6, 8, 2. Find the mean.

**Solution (Direct Method):**

| x  | f | f×x |
|----|---|-----|
| 5  | 4 | 20  |
| 15 | 6 | 90  |
| 25 | 8 | 200 |
| 35 | 2 | 70  |

```
Mean = Σ(f×x) / Σf = 380 / 20 = 19
```

**Answer:** 19
**Time:** 30 seconds

---

**Q9. [IBPS PO 2020]**
Two groups of 30 and 20 students have mean marks 60 and 70 respectively. Find the combined mean.

**Solution:**
```
Combined mean = (n₁x̄₁ + n₂x̄₂) / (n₁+n₂)
               = (30×60 + 20×70) / (30+20)
               = (1800 + 1400) / 50
               = 3200 / 50 = 64
```

**Answer:** 64
**Time:** 25 seconds

---

**Q10. [SSC CGL 2018]**
If each value in a dataset is increased by 10, how does the mean change?

**Solution:**
```
When constant k is added to all values:
New mean = Old mean + k
New mean = Old mean + 10
```

**Answer:** Increases by 10
**Time:** 5 seconds

---

**Q11. [Railway Group D 2019]**
The mean and mode of a distribution are 24 and 12 respectively. Find the median.

**Solution (Empirical Relation):**
```
Mode = 3 Median - 2 Mean
12 = 3 Median - 2(24)
12 = 3 Median - 48
3 Median = 60
Median = 20
```

**Answer:** 20
**Time:** 20 seconds

---

**Q12. [SBI PO 2018]**
The mean of 10 numbers is 15. If each number is multiplied by 3, what is the new mean?

**Solution:**
```
When all values are multiplied by k:
New mean = k × Old mean
New mean = 3 × 15 = 45
```

**Answer:** 45
**Time:** 10 seconds

---

### **ADVANCED LEVEL (Questions 13-20)**

---

**Q13. [SSC CGL 2021]**
Find the median of the following distribution:

| Class | Frequency |
|-------|-----------|
| 0-10  | 5         |
| 10-20 | 8         |
| 20-30 | 12        |
| 30-40 | 7         |
| 40-50 | 3         |

**Solution:**

| Class | f  | cf |
|-------|----|----|
| 0-10  | 5  | 5  |
| 10-20 | 8  | 13 |
| 20-30 | 12 | 25 | ← Median class
| 30-40 | 7  | 32 |
| 40-50 | 3  | 35 |

```
n = 35, n/2 = 17.5
Median class = 20-30 (cf=13 < 17.5, next cf=25 > 17.5)
L = 20, cf = 13, f = 12, h = 10

Median = 20 + [(17.5-13)/12] × 10
       = 20 + (4.5/12) × 10
       = 20 + 3.75 = 23.75
```

**Answer:** 23.75
**Time:** 45 seconds

---

**Q14. [IBPS PO 2019]**
The variance of 5 values is 10 and their sum is 50. Find the sum of their squares.

**Solution:**
```
Mean = 50/5 = 10
σ² = [Σx²/n] - (Mean)²
10 = [Σx²/5] - 100
Σx²/5 = 110
Σx² = 550
```

**Answer:** 550
**Time:** 30 seconds

---

**Q15. [SSC CGL 2017]**
Find the mode of the following:

| Class  | Frequency |
|--------|-----------|
| 10-20  | 8         |
| 20-30  | 12        |
| 30-40  | 15        | ← Modal class
| 40-50  | 10        |
| 50-60  | 5         |

**Solution:**
```
Modal class = 30-40 (highest frequency = 15)
L = 30, f₁ = 15, f₀ = 12, f₂ = 10, h = 10

Mode = 30 + [(15-12)/(30-12-10)] × 10
     = 30 + [3/8] × 10
     = 30 + 3.75 = 33.75
```

**Answer:** 33.75
**Time:** 35 seconds

---

**Q16. [Railway NTPC 2020]**
The mean of 20 observations is 18. Later it was found that an observation 16 was misread as 61. Find the correct mean.

**Solution:**
```
Original sum = 20 × 18 = 360
Incorrect value = 61, Correct value = 16
Difference = 61 - 16 = 45

Correct sum = 360 - 45 = 315
Correct mean = 315 / 20 = 15.75
```

**Answer:** 15.75
**Time:** 25 seconds

---

**Q17. [SBI PO 2021]**
The coefficient of variation of a distribution is 40% and its mean is
25. Find the standard deviation.

**Solution:**
```
CV = (σ/x̄) × 100
40 = (σ/25) × 100
σ = 40 × 25 / 100 = 10
```

**Answer:** 10
**Time:** 15 seconds

---

**Q18. [IBPS Clerk 2020]**
The mean of 15 values is 12 and the mean of another 25 values is 16. Find the combined mean.

**Solution:**
```
Combined mean = (n₁x̄₁ + n₂x̄₂) / (n₁+n₂)
               = (15×12 + 25×16) / (15+25)
               = (180 + 400) / 40
               = 580 / 40 = 14.5
```

**Answer:** 14.5
**Time:** 25 seconds

---

**Q19. [SSC CHSL 2020]**
The mean deviation of the data 3, 10, 10, 4, 7, 10, 5 from the mean is:

**Solution:**
```
Mean = (3+10+10+4+7+10+5) / 7 = 49/7 = 7

|x-7|: |3-7|=4, |10-7|=3, |10-7|=3, |4-7|=3, |7-7|=0, |10-7|=3, |5-7|=2

Sum of deviations = 4+3+3+3+0+3+2 = 18
Mean deviation = 18/7 ≈ 2.57
```

**Answer:** 2.57
**Time:** 45 seconds

---

**Q20. [Railway Group D 2022]**
If the mean of x, x+3, x+6, x+9, x+12 is 10, find x.

**Solution:**
```
Mean = (x + x+3 + x+6 + x+9 + x+12) / 5
10 = (5x + 30) / 5
50 = 5x + 30
5x = 20
x = 4
```

**Alternative (Pattern Recognition):**
```
Evenly spaced values
Mean = Middle value = x+6
x+6 = 10
x = 4
```

**Answer:** 4
**Time:** 20 seconds

---

## 5. COMMON MISTAKES & TRAPS

### **FREQUENT ERRORS STUDENTS MAKE**

#### **Error 1: Not Arranging Data for Median**

❌ **Wrong:** Finding median of 5,2,9,3,7 directly

✅ **Correct:** First arrange: 2,3,5,7,9, then find median = 5

---

#### **Error 2: Confusing n/2 with (n+1)/2**

❌ **Wrong:** Using n/2 for odd numbers

✅ **Correct:**
- Odd n → Position = (n+1)/2
- Even n → Positions = n/2 and (n/2)+1

---

#### **Error 3: Using f instead of Σf in denominator**

❌ **Wrong:** Mean = Σ(f×x) / f

✅ **Correct:** Mean = Σ(f×x) / **Σf** (sum of ALL frequencies)

---

#### **Error 4: Wrong Class Mark Calculation**

❌ **Wrong:** Class 10-20, class mark = 10 or 20

✅ **Correct:** Class mark = (10+20)/2 = 15

---

#### **Error 5: Forgetting Square Root in SD**

❌ **Wrong:** SD = Variance

✅ **Correct:** SD = √Variance

---

#### **Error 6: Mode in Grouped Data**

❌ **Wrong:** Mode = Class mark of modal class

✅ **Correct:** Use formula with f₀, f₁, f₂

---

#### **Error 7: Effect of Transformation**

❌ **Wrong:** Adding 10 to all values changes SD

✅ **Correct:** Adding constant doesn't change SD!
- Only multiplication/division changes SD

---

### **TRICK QUESTIONS COMMONLY ASKED**

#### **Trick 1: The Zero Trap**

**Question:** Mean of 0, 5, 10, 15, 20 = ?

**Trap:** Ignoring zero

**Correct:** Include zero! Mean = 50/5 = 10

---

#### **Trick 2: The Rearrangement Trap**

**Question:** Median of 15, 3, 9, 21, 7 = ?

**Trap:** Taking middle value directly (9)

**Correct:** Arrange first: 3,7,9,15,21 → Median = 9 (it's same here, but method matters!)

---

#### **Trick 3: The Combined Mean Trap**

**Question:** Mean of two groups (30 students each) is 60 and 70. Combined mean?

**Trap:** (60+70)/2 = 65... wait, this is correct when n₁=n₂!

**Be careful:** This shortcut works ONLY when groups are equal!

---

#### **Trick 4: The Cumulative Frequency Confusion**

**Question:** In median formula, what is cf?

**Trap:** Using cf of median class

**Correct:** cf of class **BEFORE** median class!

---

#### **Trick 5: The Mode Multiple Values**

**Question:** Data: 2,3,3,4,4,5. Mode = ?

**Trap:** Saying "no mode" or choosing randomly

**Correct:** Bimodal - both 3 and 4 are modes!

---

### **HOW TO AVOID CALCULATION MISTAKES**

#### **Strategy 1: Always Write Steps**

Don't do complex calculations mentally:
```
Wrong: Mean = ... thinking... 23.5
Right: Write: Σx = 235, n = 10, Mean = 235/10 = 23.5
```

---

#### **Strategy 2: Check Reasonableness**

Mean should be:
- Between minimum and maximum values
- Close to middle values

**If all values are 20-30 but mean = 50 → ERROR!**

---

#### **Strategy 3: Verify with Pattern**

For symmetrical data:
```
Check: Mean ≈ Median ≈ Mode
```

If very different → Recheck!

---

#### **Strategy 4: Use Cumulative Frequency Table**

For grouped data, ALWAYS make cf column:
```
| Class | f | cf |
```

Prevents errors in median calculation!

---

#### **Strategy 5: Double-Check n and Σf**

```
n (total count) = Σf (sum of frequencies)
```

If not equal → ERROR in table!

---

## 6. PRACTICE STRATEGY

### **LEARNING SEQUENCE (3-Week Plan)**

#### **Week 1: Foundation**

**Days 1-2:** Ungrouped data basics
- Memorize: Mean, Median, Mode definitions
- Practice: 30 problems on ungrouped data
- Master: Quick mental calculations

**Days 3-4:** Grouped data - mean
- Practice: 20 direct method problems
- Practice: 15 assumed mean problems
- Master: Step deviation method

**Days 5-7:** Grouped data - median & mode
- Practice: 20 median problems
- Practice: 15 mode problems
- Master: Cumulative frequency technique

**Goal:** Identify measure needed and calculate in under 45 seconds

---

#### **Week 2: Intermediate**

**Days 8-10:** Dispersion measures
- Practice: 20 range problems
- Practice: 15 variance/SD problems
- Master: Shortcut SD formula

**Days 11-12:** Combined means & transformations
- Practice: 15 combined mean problems
- Practice: 15 effect of change problems
- Master: Pattern recognition

**Days 13-14:** Empirical relations
- Practice: 20 problems using Mode = 3Med - 2Mean
- Practice: 15 CV problems
- Master: Quick formula application

**Goal:** Solve any intermediate problem in under 60 seconds

---

#### **Week 3: Advanced & Speed**

**Days 15-17:** Complex problems
- Practice: 20 multi-step problems
- Practice: 15 word problems
- Master: Breaking complex into simple

**Days 18-19:** Previous year papers
- Solve: 100 government exam questions
- Time: Maximum 45 seconds each
- Review: All errors thoroughly

**Days 20-21:** Speed drills
- Redo all problems at 60% time
- Take 3 mock tests
- Focus on weak areas

**Goal:** Any statistics problem in under 60 seconds

---

### **TIPS FOR SPEED AND ACCURACY**

#### **Speed Tips:**

**1. Memorize Common Patterns**
```
1+2+3+...+n = n(n+1)/2
Mean of 1 to n = (n+1)/2
```

**2. Use Mental Math**
- For symmetrical data: Mean = (First+Last)/2
- For equal groups: Combined mean = (x̄₁+x̄₂)/2

**3. Quick Median Position**
- Odd: Middle = (n+1)/2
- Even: Two middles = n/2 and next

**4. Step Deviation Always**
- For grouped data with large numbers
- Work with -2,-1,0,1,2 instead of 1005,1015...

**5. Recognize Mode Instantly**
- Highest frequency = Modal class
- Then apply formula

**6. Skip Unnecessary Calculations**
- If asked for median, don't calculate mean!
- If given mean, use shortcut for SD

**7. Use Formula Card**
- Write all formulas on scratch paper first
- Reference quickly without thinking

---

#### **Accuracy Tips:**

**1. Always Arrange for Median**
- Never skip this step
- Even if data looks arranged

**2. Make Frequency Table**
- For grouped data, organize systematically
- Include cf column for median

**3. Check Which cf to Use**
- Median formula: cf of class **BEFORE** median class
- Not the median class itself!

**4. Verify n = Σf**
- Total count should equal sum of frequencies
- If not, error in table

**5. Be Careful with Parentheses**
- (n+1)/2 ≠ n+1/2
- [(n/2 - cf)/f] - order matters!

**6. Remember Square Root**
- SD = √(Variance)
- Don't forget the root!

**7. Check Units in Word Problems**
- Mean salary in thousands? Answer in thousands!

---

### **QUICK REVISION CHECKLIST (Day Before Exam)**

#### **☑️ Central Tendency Formulas (5 minutes)**

**Mean:**
- Ungrouped: Σx/n ✓
- Grouped: Σ(f×x)/Σf ✓
- Step deviation: A + [Σ(f×u)/Σf]×h ✓

**Median:**
- Odd n: (n+1)/2 position ✓
- Even n: Average of n/2 and (n/2+1) ✓
- Grouped: L + [(n/2-cf)/f]×h ✓

**Mode:**
- Ungrouped: Most frequent ✓
- Grouped: L + [(f₁-f₀)/(2f₁-f₀-f₂)]×h ✓

---

#### **☑️ Dispersion Formulas (3 minutes)**

- Range = Max - Min ✓
- Variance = [Σx²/n] - (Mean)² ✓
- SD = √Variance ✓
- CV = (SD/Mean) × 100% ✓

---

#### **☑️ Other Formulas (2 minutes)**

- Combined mean = (n₁x̄₁+n₂x̄₂)/(n₁+n₂) ✓
- Empirical: Mode = 3Med - 2Mean ✓
- Effect of +k: Mean changes, SD doesn't ✓
- Effect of ×k: Both change ✓

---

#### **☑️ Common Traps (2 minutes)**

- ❌ Arrange data before finding median
- ❌ Use Σf in denominator, not just f
- ❌ Class mark = (Lower+Upper)/2
- ❌ For median: cf of previous class
- ❌ SD = √Variance (don't forget root!)
- ✓ Mode = highest frequency class
- ✓ Check n = Σf always

---

#### **☑️ Quick Patterns (2 minutes)**

- Symmetrical: Mean = Med = Mode ✓
- Evenly spaced: Mean = (First+Last)/2 ✓
- Equal groups: Combined = (x̄₁+x̄₂)/2 ✓
- Add constant: Mean changes, SD doesn't ✓
- Multiply constant: Both change ✓

---

### **FINAL EXAM DAY STRATEGY**

**For each Statistics problem:**

**Step 1 (5 seconds): Identify What's Asked**
- Mean/Median/Mode/SD/Range?
- Ungrouped or grouped?
- Any special pattern?

**Step 2 (5 seconds): Check for Shortcuts**
- Evenly spaced values?
- Equal groups?
- Given relationships?
- Can use empirical formula?

**Step 3 (10 seconds): Choose Method**
- Ungrouped → Direct calculation
- Grouped → Step deviation if large numbers
- Median → Make cf table first
- Mode → Find highest frequency

**Step 4 (30 seconds): Calculate**
- Write formula clearly
- Substitute values
- Calculate step by step
- Don't skip steps!

**Step 5 (10 seconds): Verify**
- Answer reasonable?
- Between min and max?
- Matches an option?

**Total: 60 seconds maximum**

---

### **CONFIDENCE BUILDERS**

✅ **Master these 10, you're 90% ready:**

1. Mean of 10,20,30,40,50 = ? → 30 [5s]
2. Median of 3,7,9,12,15 = ? → 9 [8s]
3. Mode of 2,3,3,4,5,3 = ? → 3 [5s]
4. Range of 10,15,20,25 = ? → 15 [3s]
5. Mean of 5 values is 20, sum = ? → 100 [5s]
6. Combined mean (30 at 60, 20 at 70) = ? → 64 [20s]
7. All values +10, mean changes by? → +10 [5s]
8. Mode = 12, Mean = 24, Median = ? → 20 [15s]
9. CV = 20%, Mean = 50, SD = ? → 10 [10s]
10. Median of 2,4,6,8 = ? → 5 [10s]

**If you solved all in under 2 minutes, YOU'RE READY!** 🎯

---

## FINAL MOTIVATION

🎯 **Mastery Formula:** Memorize 15 key formulas + Practice 300 problems = Statistics Champion!

**Remember:**
- **Mean = Average (affected by outliers)**
- **Median = Middle (robust measure)**
- **Mode = Most frequent**
- Range, SD, Variance measure spread
- Always arrange for median!
- Step deviation saves time!

**Statistics is about patterns!** Once you recognize the type of problem, choosing the right formula becomes automatic! 💪

**You've mastered all the concepts - now GO ACE that exam!** 🚀

---

**ONE LAST POWER TIP:**

Create a **"Statistics Formula Card":**
- Front side: All mean formulas
- Back side: Median, mode, SD formulas

Review it 5 minutes before exam for instant recall!

**Your Statistics mastery journey ends in TRIUMPH!** 🏆
