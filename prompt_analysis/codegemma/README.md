
codegemma:

1. prompt1 go problematic output: " ## Hindi Code Summary" : sample_68262  ------ prompt 0 did produce output in Arabic, prompt1 just didn't!!

"summary_hindi": "## Hindi Code Summary\n\n**फंक्शन का नाम:** Use\n\n**कुल मिला:** यह फंक्शन एक नया रोटर हेंडलर को हस्तक्षेप में जोड़ता है।\n\n**आरेग़ुमेंट:**\n\n* `h`: यह एक `RouterHandler` प्रकार का मान लेता है।\n\n**मुख्य लॉजिक:**\n\n1. यह फंक्शन `hs.Handlers` नामक एक मैमेंडल स्टैक् में एक नया मान जोड़ता है।\n2. यह मान `h` नामक आरेग़ुमेंट से लेता है।\n3. यह मान `hs.Handlers` में जोड़ा जाता है।\n\n**उदाहरण:**\n\n```go\n// एक नया रोटर हेंडलर बनाना\nmyHandler := MyCustomHandler{}\n\n// हस्तक्षेप में हेंडलर जोड़ना\nhandlers.Use(myHandler)\n```\n\nइसके बाद, जब कोई HTTP अनुरोध मिलता है, तो हस्तक्षेप में जोड़े गए सभी हेंडलर एक-एक करके इसका xửली करते हैं।<eos>"
  },
"summary_arabic": "This function, named `Use`, is part of a stack of handlers, which are responsible for routing requests. It takes a handler of type `RouterHandler` as an argument and adds it to the stack. The handlers are executed in the order they are added, so adding a handler at the beginning of the stack will execute it before any other handlers. The main logic involves appending the new handler to the existing list of handlers.<eos>",

2. 
