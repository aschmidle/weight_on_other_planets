
# 🌍 Planet Weight Calculator

This is a simple Python program that calculates what your weight would be on another planet in our solar system. Just enter your weight on Earth and choose a planet number — the script will take care of the rest!

## 🚀 How It Works

1. The user is prompted to enter their Earth weight (in pounds).
2. The user selects a planet from a numbered list (1–6).
3. The script multiplies the Earth weight by the gravity factor of the selected planet.
4. The adjusted weight is displayed, formatted to two decimal places.

## 🪐 Planet Gravity Reference

| Number | Planet   | Gravity Multiplier |
|--------|----------|--------------------|
| 1      | Venus    | 0.91               |
| 2      | Mars     | 0.38               |
| 3      | Jupiter  | 2.34               |
| 4      | Saturn   | 1.06               |
| 5      | Uranus   | 0.92               |
| 6      | Neptune  | 1.19               |

These multipliers represent how much gravity each planet exerts compared to Earth.

## 📂 File Info

- **Filename:** `planet_weight.py`
- **Dependencies:** None — runs with base Python 3.
- **Function:** `planet_weight(weight, gravity)` — returns the adjusted weight on another planet.

## ✨ Sample Output

```
I have information for the following planets:

   1. Venus   2. Mars    3. Jupiter
   4. Saturn  5. Uranus  6. Neptune

Enter your weight in pounds: 185
Enter the number of your planet: 3
Your weight on Jupiter is:  432.90 pounds.
```

## 🔧 Possible Enhancements

- Allow planet name input (e.g., "Mars") in addition to numbers.
- Add Earth to the list as a baseline.
- Let users run multiple comparisons in a loop.

---

Want me to convert that into a docstring block at the top of your script or turn it into a Markdown file for GitHub?
