# Price Section Redesign Proposal

## Current Problems

### Flow Issues:
1. Section opens with abstract "price sensitivity meter" before establishing context
2. Jumps between concepts (sensitivity → pricing → affordability) without logical progression
3. Key data (59% can only afford <$1k) comes AFTER the pricing comparison, weakening impact

### Visual Issues:
- Gradient "Sweet Spot" bar is confusing - doesn't clearly show what the price points mean
- Relationship between $157, $306, $706, $1,512 and consumer perception unclear
- Abstract visualization doesn't connect to real-world implications

---

## Proposed New Flow

**Narrative Arc: "Start with reality, then reveal the gap"**

### 1. Opening (Current intro is good, keep it)
> "The gap between what consumers can afford and what licensed services cost appears stark."

### 2. What Consumers Can Actually Afford (MOVE THIS UP)
- Start with the bar chart showing payment constraints
  - 59% can only pay if under $1,000
  - 53% need sliding-scale
  - 35% must have insurance
- **Why this first:** Establishes the baseline reality before showing the gap

### 3. Price Sensitivity: Where Consumers Find Value (REDESIGNED)
Replace current gradient with clearer visualization showing:
- 4 price points as distinct zones
- Clear labels: "Too Cheap" → "Good Value" → "Getting Expensive" → "Too Expensive"
- Highlight the "acceptable range" ($306-$706)
- Key stat: "Only 22% can pay upfront if services ≥$1k"

**Visual concept:**
```
Price Perception Zones (n=18)

|  Too Cheap  |    ACCEPTABLE RANGE     |  Too Expensive  |
|    $157     |   $306   →   $706      |     $1,512      |
|-------------|-------------------------|-----------------|
               Most consumers find value here
               But 78% still need payment help
```

### 4. The Reality: What Services Actually Cost (KEEP, but add connector)
Add transition text:
> "Here's the problem: the range consumers find acceptable ($306-$706) doesn't align with what services actually cost."

Then show the pricing comparison charts

### 5. The Gap Becomes Clear (NEW connecting paragraph)
Add explicit text showing the mismatch:
> "Licensed individual sessions average $3,500—nearly 5× the high end of the acceptable range. Even underground options at $1,200 exceed what most consumers report they can afford."

### 6. Key Takeaway (KEEP, slight revision)
Current takeaway is good but strengthen the structural nature

---

## New Price Sensitivity Visual Design

### Option A: Price Zones with Vertical Markers
```
┌─────────────────────────────────────────────────┐
│  Price Perception: What Consumers Report (n=18) │
├─────────────────────────────────────────────────┤
│                                                  │
│   $157        $306              $706    $1,512  │
│    │           │─────────────────│        │     │
│    │           │   Acceptable    │        │     │
│    │           │     Range       │        │     │
│  "Too        "Good             "Getting  "Too   │
│  Cheap"      Value"            Expensive" Exp"  │
│                                                  │
│  ⚠️ But only 22% can pay ≥$1k upfront          │
│     78% need insurance, sliding scale, or       │
│     payment plans                               │
└─────────────────────────────────────────────────┘
```

### Option B: Four Columns Showing Perceptions
- 4 distinct boxes, one for each price point
- Each labeled with the perception
- Middle two highlighted as "acceptable range"
- More visual separation than gradient

### Option C: Simple Range Bar
```
Too Cheap ────[====ACCEPTABLE====]──── Too Expensive
         $157  $306            $706   $1,512

         Most consumers find value between $306-$706
         But 59% can only afford <$1,000 total
```

---

## Recommended Approach

**Option A (Price Zones with Vertical Markers)** because:
- Clearly shows the 4 data points from the Van Westendorp analysis
- Visually highlights the acceptable range
- Includes the critical context (only 22% can pay upfront)
- Less abstract than current gradient
- Easier to understand at a glance

---

## Implementation Notes

**What to keep:**
- Bar charts for affordability data (they're clear and effective)
- Pricing comparison visualization (works well)
- Key takeaway box
- Interactive calculator button

**What to change:**
- Move affordability data BEFORE price sensitivity
- Replace gradient meter with clearer price zones visual
- Add connecting text between sections
- Strengthen the narrative arc

**New section order:**
1. Intro
2. What Consumers Can Afford (bar charts)
3. Price Sensitivity (redesigned visual)
4. What Services Cost (pricing comparison)
5. The Gap (connecting paragraph)
6. Key Takeaway
7. Interactive calculator

This creates a clear story: "Here's what people can afford → Here's where they find value → Here's what it actually costs → Here's the gap"
