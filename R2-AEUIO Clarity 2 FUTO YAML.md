This is a modified version of the Clarity layout. 

For those that want the large vowels but don't want the bottom consonant keys crammed together. 


![Vowel Vortex](https://raw.githubusercontent.com/cinnabar777/Vowel-Vortex-Keyboard-Layouts/refs/heads/main/images/VV_R2-AEUIO_Clarity2.png)


```
name: Vowel Vortex Clarity 2

bottomRowHeightMode: Flexible

description: Vowel Vortex layout

overrideWidths:
  Custom1: 0.143        # Consonants
  Custom2: 0.08        # '
  Custom3: 0.08         # gaps
  Custom4: 0.169        # Vowels
  FunctionalKey: 0.18  # function key

rows:

  - letters: [
      {type: base, spec: 'q', 
      hint: " ", 
      attributes: { width: Custom1 }, 
      moreKeys: [
      "~", "\u0022", "?", "¿"]},
      
      {type: base, spec: 'w', 
      hint: " ", 
      attributes: { width: Custom1 }, 
      moreKeys: [
      "1", "¹", "₁", "½", "⅓", 
      "`", "¼", "⅕", "⅙", "⅐", 
      "⅛", "⅑", "⅒"]},
      
      {type: base, spec: 'r', 
      hint: " ", 
      attributes: { width: Custom1 }, 
      moreKeys: [
      "2", "²", "₂", 
      "⅔", •, "⅖"]},
      
      {type: base, spec: 't', 
      hint: " ", 
      attributes: { width: Custom1 }, 
      moreKeys: [
      "3", "`", "~", "×", "¾", 
      "³", "₃", "⅗", "⅜"]},
      
      {type: base, spec: 'y', 
      hint: " ", 
      attributes: { width: Custom1 }, 
      moreKeys: [
      "!icon/action_redo|!code/action_redo", 
      "4", "π", 
      "⁴", "₄", "⅘"]},
      
      {type: base, spec: 'p', 
      hint: " ", 
      attributes: { width: Custom1 }, 
      moreKeys: [
      "5", 
      "!icon/numpad|!code/key_to_number_layout", 
      "⁵", "₅", "⅚", 
      "=", "⅝", "|", "%|%", "‰", 
      "π", "Π", "+", "±", "#", 
      "₊", "⁺"]},
      
      {type: base, spec: 'l', 
      hint: " ", 
      attributes: { width: Custom1 }, 
      moreKeys: [
      ")", "]", "⟩", "}", "\\", 
      "|", ">", "≥", "›", "»"]}
    ]
  
  - letters: [
      {type: base, spec: 'a', 
      hint: " ", 
      attributes: { width: Custom4 }, 
      moreKeys: [
      "!icon/action_select_all|!code/action_select_all", 
      "6", 
      "!icon/tab_key|!code/key_tab", 
      "⁶", "₆", 
      "@", "~", "'", "*", "&",
      "→", "←", "↑", "↓"]},
      
      {type: base, spec: ",", 
      attributes: { width: Custom2 }, 
      moreKeys: [
      "'",
      "!icon/action_voice_input|!code/action_voice_input", 
      "!icon/action_clipboard_history|!code/action_clipboard_history", 
      "!icon/action_text_edit|!code/action_text_edit", 
      "!icon/numpad|!code/key_to_number_layout", 
      "!icon/action_select_all|!code/action_select_all", 
      "!icon/action_cut|!code/action_cut", 
      "!icon/action_copy|!code/action_copy", 
      "!icon/action_paste|!code/action_paste", 
      "!icon/action_redo|!code/action_redo", 
      "!icon/action_undo|!code/action_undo"]},
      
      {type: base, spec: 'e', 
      hint: " ", 
      attributes: { width: Custom4 }, 
      moreKeys: [
      "!icon/action_text_edit|!code/action_text_edit", 
      "7", "⁷", "₇", "⅞", 
      "—", "–", "!", "¡", 
      "=", "≠", "≈", "…", "![[]]"]},
      
      {type: base, spec: 'u', 
      hint: " ", 
      attributes: { width: Custom4 }, 
      moreKeys: [
      "8", "_", "÷", "⁸", "₈"]},
      
      {type: base, spec: 'i', 
      hint: " ", 
      attributes: { width: Custom4 },
      moreKeys: [
      "!icon/action_voice_input|!code/action_voice_input", 
      "⁹", "9", "₉", 
      "×", "∞", "[[]]"]},
      
      {type: base, spec: "'", 
      attributes: { width: Custom2 }, 
      moreKeys: [".", "\u0022", "?", "!", "!icon/numpad|!code/key_to_number_layout", ":", ";", "-", "—", "–", "/", "\\", "|", "#", "@", "&", "()", "[]", "{}", ">", "<", "$", "%|%", "*", "…", "°", "```", "~", "+", "=", "÷", "(", ")", "'", ",", "]", "["]},
      
      {type: base, spec: 'o', 
      hint: " ", 
      attributes: { width: Custom4 }, 
      moreKeys: [
      "0", "⁰","₀", 
      "°", "ⁿ", "•", "∅", "Ω"]}
    ]
  
  - letters: [
      {type: base, spec: 's', 
      hint: " ", 
      attributes: { width: Custom1 }, 
      moreKeys: [
      "#", ";", "№", 
      "§", "★", "¶"]},
      
      {type: base, spec: 'd', 
      hint: " ", 
      attributes: { width: Custom1 }, 
      moreKeys: [
      "$", "€", "£", "¢", 
      "¥", "₱", "₹", "°", 
      "÷", "∆", "†", "‡"]},
      
      {type: base, spec: 'f', 
      hint: " ", 
      attributes: { width: Custom1 }, 
      moreKeys: [
      "_", "%|%"]},
      
      {type: base, spec: 'g', 
      hint: " ", 
      attributes: { width: Custom1 }, 
      moreKeys: [
      "&", "^", ">", "<", 
      "←", "↑", "↓", "→"]},
      
      {type: base, spec: 'h', 
      hint: " ", 
      attributes: { width: Custom1 }, 
      moreKeys: [
      "!icon/action_clipboard_history|!code/action_clipboard_history", 
      "—", "-", "–"]},
      
      {type: base, spec: 'j', 
      hint: " ", 
      attributes: { width: Custom1 }, 
      moreKeys: [
      "+", "±", "=", "≠", "≈", 
      "∞", "×", "÷", "°", "·"]},
      
      {type: base, spec: 'k', 
      hint: " ", 
      attributes: { width: Custom1 }, 
      moreKeys: [
      "(", "[", "⟨", "{", "/", 
      "|", "<", "≤", "‹", "«"]}
    ]
  
  - letters: [
      {type: base, spec: 'z', 
      hint: " ", 
      moreKeys: [
      "!icon/action_undo|!code/action_undo", 
      "*", "%|%", 
      "★", "†", "‡"]},
      
      {type: base, spec: 'x', 
      hint: " ", 
      moreKeys: [
      "!icon/action_cut|!code/action_cut", 
      "\u0022", "×"]},
      
      {type: base, spec: 'c', 
      hint: " ", 
      moreKeys: [      
      "!icon/action_copy|!code/action_copy", 
      "'", ",", ":", 
      "```", "√", "^"]},
      
      {type: base, spec: 'v', 
      hint: " ", 
      moreKeys: [
      "!icon/action_paste|!code/action_paste", 
      ":", "©", "®", "™"]},
      
      {type: base, spec: 'b', 
      hint: " ", 
      moreKeys: [
      ";", "✓", "•", "·", "\u0022"]},
      
      {type: base, spec: 'n', 
      hint: " ", 
      moreKeys: [
      "!", "¡", "ⁿ", "№"]},
      
      {type: base, spec: 'm', 
      hint: " ", 
      moreKeys: [
      "?", "¿", "‽", "×", 
      "μ", "♪", "[]()"]}
    ]
  
  - bottom: 
      - $symbols
      
      - $shift
      
      - $action
      
      - $space
      
      - $delete
      
      - $enter
```

This is a slightly different version where the comma and apostrophe keys are slightly larger, delete is smaller and moved to the outer edge, enter is larger, and the numbers are 1-7 on the top row with 8, 9, and 0 centered on the second row e, u, and i. 


![Vowel Vortex](https://raw.githubusercontent.com/cinnabar777/Vowel-Vortex-Keyboard-Layouts/refs/heads/main/images/VV_Clarity_2.0.png)


```
name: Clarity

bottomRowHeightMode: Flexible

description: Vowel Vortex layout

overrideWidths:
  Custom1: 0.143        # Consonants
  Custom2: 0.09         # ' and ,
  Custom3: 0.08         # not used
  Custom4: 0.164        # Vowels
  FunctionalKey: 0.20  # function key

rows:

  - letters: [
  
      {type: base, spec: 'q', 
      hint: " ", 
      attributes: { width: Custom1 }, 
      moreKeys: [
      1, "~", "\u0022", "?", 
      ‽, ¹, ₁, ½, 
      ⅓, ¼, ⅕, ⅙, 
      ⅐, ⅛, ⅑, ⅒, "¿"]},
      
      {type: base, spec: 'w', 
      hint: " ", 
      attributes: { width: Custom1 }, 
      moreKeys: [
      2, ², ₂, 
      "`", ⅔, ⅖]},
      
      {type: base, spec: 'r', 
      hint: " ", 
      attributes: { width: Custom1 }, 
      moreKeys: [
      3, "•", ³, ₃, 
      ¾, ⅗, ⅜]},
      
      {type: base, spec: 't', 
      hint: " ", 
      attributes: { width: Custom1 }, 
      moreKeys: [
      4, ⁴, ₄, 
      "`", "~", "×"]},
      
      {type: base, spec: 'y', 
      hint: " ", 
      attributes: { width: Custom1 }, 
      moreKeys: [
      5,
      "!icon/action_redo|!code/action_redo", 
      ⁵, ₅, 
      ⅚, ⅝, "π"]},
      
      {type: base, spec: 'p', 
      hint: " ", 
      attributes: { width: Custom1 }, 
      moreKeys: [
      6,
      "!icon/numpad|!code/key_to_number_layout", 
      "=", "|", "%|%", "‰", 
      "π", "Π", "+", "±", "#", 
      "₊", "⁺", ⁶, ₆]},
      
      {type: base, spec: 'l', 
      hint: " ", 
      attributes: { width: Custom1 }, 
      moreKeys: [
      7, 
      ")", "]", "⟩", "}", "\\", 
      "|", ">", "≥", "›", "»", 
      ⁷, ₇, ⅞,]}
    ]
  
  - letters: [
  
      {type: base, spec: 'a', 
      hint: " ", 
      attributes: { width: Custom4 }, 
      moreKeys: [
      "!icon/action_select_all|!code/action_select_all", 
      "!icon/tab_key|!code/key_tab", 
      "@", "~", "'", "*", "&",
      "→", "←", "↑", "↓"]},
      
      {type: base, spec: "'", 
      attributes: { width: Custom2 }, 
      moreKeys: [
      "!icon/action_voice_input|!code/action_voice_input", 
      "!icon/action_clipboard_history|!code/action_clipboard_history", 
      "!icon/action_text_edit|!code/action_text_edit", 
      "!icon/numpad|!code/key_to_number_layout", 
      "!icon/action_select_all|!code/action_select_all", 
      "!icon/action_cut|!code/action_cut", 
      "!icon/action_copy|!code/action_copy", 
      "!icon/action_paste|!code/action_paste", 
      "!icon/action_redo|!code/action_redo", 
      "!icon/action_undo|!code/action_undo"]},
      
      {type: base, spec: 'e', 
      hint: " ", 
      attributes: { width: Custom4 }, 
      moreKeys: [
      8, 
      "!icon/action_text_edit|!code/action_text_edit", 
      "—", "–", "!", "¡", 
      "=", "≠", "≈", "…", "![[]]", 
      ⁸, ₈]},
      
      {type: base, spec: 'u', 
      hint: " ", 
      attributes: { width: Custom4 }, 
      moreKeys: [
      9, "_", "÷", 
      ⁹, ₉]},
      
      {type: base, spec: 'i', 
      hint: " ", 
      attributes: { width: Custom4 },
      moreKeys: [
      0, 
      "!icon/action_voice_input|!code/action_voice_input", 
      ⁰, ₀, 
      "×", "∞", "[[]]"]},
      
      {type: base, spec: ",", 
      attributes: { width: Custom2 }, 
      moreKeys: [".", "\u0022", "?", "!", "!icon/numpad|!code/key_to_number_layout", ":", ";", "-", "—", "–", "/", "\\", "|", "#", "@", "&", "()", "[]", "{}", ">", "<", "$", "%|%", "*", "…", "°", "```", "~", "+", "=", "÷", "(", ")", "'", ",", "]", "["]},
      
      {type: base, spec: 'o', 
      hint: " ", 
      attributes: { width: Custom4 }, 
      moreKeys: [
      "°", "ⁿ", "•", "∅", "Ω"]}
    ]
  
  - letters: [
  
      {type: base, spec: 's', 
      hint: " ", 
      attributes: { width: Custom1 }, 
      moreKeys: [
      "#", ";", "№", 
      "§", "★", "¶"]},
      
      {type: base, spec: 'd', 
      hint: " ", 
      attributes: { width: Custom1 }, 
      moreKeys: [
      "$", "€", "£", "¢", 
      "¥", "₱", "₹", "°", 
      "÷", "∆", "†", "‡"]},
      
      {type: base, spec: 'f', 
      hint: " ", 
      attributes: { width: Custom1 }, 
      moreKeys: [
      "_", "%|%"]},
      
      {type: base, spec: 'g', 
      hint: " ", 
      attributes: { width: Custom1 }, 
      moreKeys: [
      "&", "^", ">", "<", 
      "←", "↑", "↓", "→"]},
      
      {type: base, spec: 'h', 
      hint: " ", 
      attributes: { width: Custom1 }, 
      moreKeys: [
      "-", 
      "!icon/action_clipboard_history|!code/action_clipboard_history", 
      "—", "–"]},
      
      {type: base, spec: 'j', 
      hint: " ", 
      attributes: { width: Custom1 }, 
      moreKeys: [
      "+", "±", "=", "≠", "≈", 
      "∞", "×", "÷", "°", "·"]},
      
      {type: base, spec: 'k', 
      hint: " ", 
      attributes: { width: Custom1 }, 
      moreKeys: [
      "(", "[", "⟨", "{", "/", 
      "|", "<", "≤", "‹", "«"]}
    ]
  
  - letters: [
  
      {type: base, spec: 'z', 
      attributes: { width: Custom1 },
      hint: " ", 
      moreKeys: [
      "*", 
      "!icon/action_undo|!code/action_undo", 
      "%|%", 
      "★", "†", "‡"]},
      
      {type: base, spec: 'x', 
      attributes: { width: Custom1 },
      hint: " ", 
      moreKeys: [
      "\u0022", 
      "!icon/action_cut|!code/action_cut", 
      "×"]},
      
      {type: base, spec: 'c', 
      attributes: { width: Custom1 },
      hint: " ", 
      moreKeys: [
      "'",
      "!icon/action_copy|!code/action_copy", 
      ",", ":", 
      "```", "√", "^"]},
      
      {type: base, spec: 'v', 
      attributes: { width: Custom1 },
      hint: " ", 
      moreKeys: [
      ":", 
      "!icon/action_paste|!code/action_paste", 
      "©", "®", "™"]},
      
      {type: base, spec: 'b', 
      attributes: { width: Custom1 },
      hint: " ", 
      moreKeys: [
      ";", "✓", "•", "·", "\u0022"]},
      
      {type: base, spec: 'n', 
      attributes: { width: Custom1 },
      hint: " ", 
      moreKeys: [
      "!", "¡", "ⁿ", "№"]},
      
      {type: base, spec: 'm', 
      attributes: { width: Custom1 },
      hint: " ", 
      moreKeys: [
      "?", "¿", "‽",  
      "μ", "♪", "[]()", 
      =, ≠, ≈, ∞, 
      +, ±, ×, ÷]}
    ]
  
  - bottom: 
      
      - { type: symbols, 
      attributes: { width: Custom1 }}
      
      - { type: shift, 
      attributes: { width: Custom1 }}
      
      - $action
      
      - $space
      
      - $enter
      
      - { type: delete, 
      attributes: { width: Custom1 }}
```
