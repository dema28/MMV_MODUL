## BUG_MMSRO_006 | No Hover Effect on Buttons

### Issue Description

Buttons do not provide any visual feedback on hover. Users can’t tell if the button is interactive or not.

---

### Priority

**Level:** Medium

> UX issue affecting the perceived interactivity and polish of the interface.

---

### Environment

| Parameter        | Value                                                                                 |
| ---------------- | ------------------------------------------------------------------------------------- |
| Device           | PC                                                                                    |
| Operating System | Windows 11 Pro                                                                        |
| Browsers         | Chrome 134.0.6998.166 (64-bit), Firefox 136.0.2 (64-bit), Edge 134.0.3124.85 (64-bit) |
| System Version   | 64-bit                                                                                |

---

### Steps to Reproduce

1. Open https://modultest1.framer.website
2. Hover the mouse over any active button (e.g., "O nas")

---

### Expected Behavior

The button reacts visually on hover: background or shadow changes, cursor switches to pointer.

---

### Actual Behavior

No visual feedback — the button remains static and looks inactive.

---

### Attachments

_(none)_

---

### Suggested Fix

Add `:hover` CSS styling — background color, shadow, and pointer cursor changes.

---

### Additional Information

The issue is consistently reproducible in all tested browsers and environments.
