#IntelliJ Tricks, original by Victor Rentea, spinOff by Carlos Sánchez

#### Mother of all commands
⌘ + shift + a (some already use double shift)
&&
opt + enter

### Navigating 
- Recent Files (CTRL-E :: ⌘E)
- Recent Places/Changes (CTRL-SHIFT-E)
+ Recent Projects (⌘ + opt + e) vs ⌘ + Tab With fullScreen included
- Go to declaration / impl ⌘ + B, ⌘ + opt + B
- See file in project opt + F1
- move to next/prev change (ctr + opt + shift scrollbar colors)
- Clipboard history (⌘ + shift + v)
- Open File vs Class, write only capital letters (⌘ + o or ⌘ + shift + o)

### Typing 
- Autocompletion: person.firstName > person.fn > p.fn
- Boilerplate: toString
- Type-aware / snake-completion: MaritalStatus  
- Postfix Completion: .sout .log .assertThat
- Live Templates: boot, logs
- TAB completion
- Statics (CTRL-SPACE x 2): ctm

### Wrapping
- Finish Statement (CTRL-SHIFT-ENTER :: ⇧⌘Enter) 
  - if, method, class
  - method call: ofNullable(
  - Wrap generics: Optional<
- Surround with (CTRL-ALT-T :: ⌥⌘T): if, try
- Embrace Selection: while text is selected, press any of: {"'`<([

### Smart Selecting
- Multi-cursor
  - Token-based❤️ (ALT-J :: ^G) -- MovieType .html 
  - ALT-drag -- .feature
  - ALT-SHIFT + click, click
- Expand/Contract selection

### 👑 Quick Fix (aka Inspections) 
(ALT-ENTER :: ⌥ ⏎):
- Define Variable for expression
- Define new type/method
- Delete dead code
- Syntax-Tree analysis: see Boolean Logic
- Run inspection on entire project -- String.valueOf
- and 500+ more 😊=> almost all are disabled by default
    
### FP Support
- ALT-Enter on .stream <-> for
- Skip writing ".stream()"
- Autocomplete after directly after ::  
- Collecting: ctl, cs, cj

### Code inspection / Surviving Legacy
- Quick Definition (Ctrl-Shift-I :: ⌥ Space)
- Current Parameter (Ctrl-P)
- Type of current expression (Ctrl-Shift-P)
- Call hierarchy (CTRL-ALT-H :: ^⌥H)
- Bookmark (F11 :: F3)
- Collapse / Fold (CTRL-. :: ⌘.)

### Refactoring
- Introduce Parameter, Functional Parameter, and Parameter Object -- Parameters.java
- Add param from inside / from outside w/ ALT-ENTER 

- Extract Method (+ Auto-Parameterize) -- ExtractMethod.java
- Combo: Extract over & Inline inner
- Combo: Extract & Move/Convert to Instance

- Extract / Inline / Encapsulate Field -- Fields.java 
- Extract explanatory variable (w or w/o preselecting)
- Extract / Inline Interface

## EXTRAS
### HTML client
show a demo GET request, see eps-promo-api
https://www.jetbrains.com/help/idea/http-client-in-product-code-editor.html#composing-http-requests

### Know my debugger + Tests executions
f7, f8, alt f8, ⌘ alt f8, f9, run till here, reset frame, eval in place

### Navigate intellij Tool windows
⌘ + #'s

### Next Steps
- Become a Shortcuts Ninja 🥷: install "Key Promoter X" plugin
- Practice all the moves yourself
  