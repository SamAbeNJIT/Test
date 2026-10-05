# 6. Custom Shapes: The Margin Driver

Custom-shape signs cost Postline almost nothing extra to make. A CNC router or flatbed cutter follows a vector path whatever its shape, so a contour cut takes about the same machine time as a straight cut. Customers see a shaped sign as a premium, branded product, though. That gap between cost and perceived value is where the margin is.

The UX job is to **make shapes easy to discover, easy to understand, and easy to say yes to**, without hiding the price.

## 6.1 What we added

| Where | What | Why |
|---|---|---|
| Home: product grid + category row | **Custom shape signs** listed **first** | Order = priority. The first item gets the most clicks. |
| Home: dedicated band | "Your logo, cut to its own shape." with custom / circle / arrow examples and a **Design a custom shape** button | Shows the value visually; rectangles look plain next to it |
| Product page: configurator | **Select a shape** tiles above size, each with an icon and its price premium (+10% … +45%) | Shape is the first decision, so it frames everything after it |
| "Most popular" badge on Custom shape | Social-proof nudge toward the highest-margin option |
| Custom shape product | Defaults to **Custom shape** selected | Default effect: most people keep the default |
| Other products (yard, aluminum, acrylic, decals) | Same shape picker, default **Rectangle** | Upsell where it makes sense, without forcing it |
| Live preview | Sign redraws in the chosen shape with a **pink dashed cut line** | Removes "what will it look like?" doubt |
| Upload preview + proof | Same cut line, plus a checklist row: "Cut path: custom shape, 1/8 in white border" | Reassurance at the moment of commitment |
| Copy | "No setup fee, no die charge." | Competitors often charge setup/die fees. Saying there's none removes the biggest objection to custom shapes. |

## 6.2 Pricing model

Shape is a **percentage premium on the unit price**, applied before quantity discounts. The premium grows with quantity, while the cost difference stays near zero.

| Shape | Premium | Example: 10 × 18 × 18 in |
|---|---|---|
| Rectangle | — | (not offered on the shaped product) |
| Rounded corners | +10% | $454.30 |
| Circle / oval | +20% | $495.60 |
| Arrow | +25% | $516.25 |
| **Custom shape** | **+45%** | **$598.85** |

*Base for 18 × 18 in: $59/sign; ×0.70 at 10 signs = $41.30/sign before the shape premium.*

**Why a percentage and not a flat fee:**
- It scales with order size, so revenue grows with the order.
- The price is shown inside every quantity row, so there's **no surprise** at checkout. This keeps Sticker Mule's core rule of transparent pricing.
- "+45%" on the tile is honest. People see the premium before they choose it.

## 6.3 Flow

```mermaid
flowchart LR
  H[Home] -->|"Design a custom shape" / grid card| P[Custom shape signs<br/>Custom shape preselected]
  H -->|Yard / Aluminum / Acrylic / Decals| Q[Product page<br/>Rectangle preselected]
  Q -->|Pick a shape tile| Q2[Preview redraws<br/>+ cut line, prices update]
  P --> U[Upload: preview shows art inside the cut line]
  Q2 --> U
  U --> C[Cart: "24 × 18 in · Custom shape"] --> K[Checkout] --> R[Proof: cut path checklist row]
  R -->|"Make the border thinner"| R
```

## 6.4 Persuasion vs. manipulation (for your ethics section)

| Technique used | Fair? | Why |
|---|---|---|
| Default selection on the custom-shape product | ✅ | The user came for custom shapes; the default matches their intent |
| "Most popular" badge | ⚠️ | Fair **only if true**. In a real store, back it with order data. |
| Premium shown on every tile | ✅ | Full transparency, no hidden fees |
| Rectangle stays the default on standard products | ✅ | We don't push an upsell on someone who picked "Yard signs" |
| Preview with cut line | ✅ | Helps people decide; doesn't pressure them |

What we deliberately **didn't** do: pre-check custom shape on standard products, hide the premium until checkout, or add a fake countdown timer.

## 6.5 Test ideas
1. **A/B:** shape picker above size (current) vs. below quantity. Measure % of orders with a non-rectangle shape and average order value.
2. **Usability task:** "Your client wants a sign shaped like their coffee cup logo. Order 10." Success = finds Custom shape and reaches the cart in under 90 seconds.
3. **Comprehension:** after seeing the preview, ask "What does the pink dashed line mean?" Target ≥ 80% correct.
