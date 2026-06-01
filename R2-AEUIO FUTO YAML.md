Here is the code for two versions of the Vowel Vortex R2-AEUIO Layout, the layout that I prefer after all the research and tests. The first one, "square", has the function keys set to the same size as the alphabet keys. The second one function keys are closer to the standard size. 

<img width="1080" height="964" alt="1000113691" src="https://github.com/user-attachments/assets/27af2d61-5a4c-46d3-ad9c-59be28bfa32e" />


```
name: Vowel Vortex R2 square

bottomRowHeightMode: Flexible

description: Vowel Vortex layout

overrideWidths:
  Custom1: 0.143        # Consonants
  Custom2: 0.11         # ',.
  Custom3: 0.08         # not used
  Custom4: 0.143        # Vowels
  FunctionalKey: 0.143  # function key

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
      $shift,
      
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
      
      {type: base, spec: 'o', 
      hint: " ", 
      attributes: { width: Custom4 }, 
      moreKeys: [
      "0", "⁰","₀", 
      "°", "ⁿ", "•", "∅", "Ω"]},
      
      $delete
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
            
      - $action
      
      - {type: base, spec: ",", 
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
      "!icon/action_undo|!code/action_undo"]}
      
      - $space
      
      - {type: base, spec: "'", 
      attributes: { width: Custom2 }, 
      moreKeys: [
      "!icon/action_text_edit|!code/action_text_edit", 
      "!icon/action_voice_input|!code/action_voice_input", 
      "!icon/action_clipboard_history|!code/action_clipboard_history", 
      "!icon/numpad|!code/key_to_number_layout", 
      "!icon/action_select_all|!code/action_select_all", 
      "!icon/action_cut|!code/action_cut", 
      "!icon/action_copy|!code/action_copy", 
      "!icon/action_paste|!code/action_paste", 
      "!icon/action_redo|!code/action_redo", 
      "!icon/action_undo|!code/action_undo"]}

      - {type: base, spec: '.', 
      attributes: { width: Custom2 }, 
      moreKeys: ["\u0022", "?", "!", "!icon/numpad|!code/key_to_number_layout", ":", ";", "-", "—", "–", "/", "\\", "|", "#", "@", "&", "()", "[]", "{}", ">", "<", "$", "%|%", "*", "…", "°", "```", "~", "+", "=", "÷", "(", ")", "'", ",", "]", "["]}
      
      - $enter
```

<img width="1080" height="974" alt="1000113692" src="https://github.com/user-attachments/assets/8f9d558e-9438-4a39-94de-bf4948355fa5" />


```
name: Vowel Vortex R2 Big

bottomRowHeightMode: Flexible

description: Vowel Vortex layout

overrideWidths:
  Custom1: 0.143        # Consonants
  Custom2: 0.08        # '
  Custom3: 0.08         # gaps
  Custom4: 0.128        # Vowels
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
      $shift,
      
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
      
      {type: base, spec: 'o', 
      hint: " ", 
      attributes: { width: Custom4 }, 
      moreKeys: [
      "0", "⁰","₀", 
      "°", "ⁿ", "•", "∅", "Ω"]},
      
      $delete
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
      
      - {type: base, spec: "'", 
      attributes: { width: Custom2 }}
      
      - $action
      
      - {type: base, spec: ",", 
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
      "!icon/action_undo|!code/action_undo"]}
      
      - $space
      
      - {type: base, spec: '.', 
      moreKeys: ["\u0022", "?", "!", "!icon/numpad|!code/key_to_number_layout", ":", ";", "-", "—", "–", "/", "\\", "|", "#", "@", "&", "()", "[]", "{}", ">", "<", "$", "%|%", "*", "…", "°", "```", "~", "+", "=", "÷", "(", ")", "'", ",", "]", "["]}
      
      - $enter
```




