# Two Piles
Educational mobile-first prototype: separate contributions from hypothetical growth or loss. No real investing, payments, account connectors, performance data or backend.

Open index.html in a browser. No build dependencies. Flow: Home > Goal > Amount > Baseline > What-if > Time > Bad-year comparison > Fund examples > Practice confirmation > Saved > Goal detail.

Arithmetic: monthly rate = (1 + annual rate)^(1/12) - 1. Contributions arrive at month-end. No inflation, fees, exit load or tax. At 1000 rupees monthly: 5y/+8% = 72945; 5y/-10% = 46846; 10y/+8% = 180124. Corrects supplied 180100 approximate fixture. Bad-year scenario: -20% annualised for 12 months then +10% for 24 months; 10856 at year1, 39471 continuing, 13135 stopping contributions but remaining invested. This recovery is made up, not a forecast. More contributions do not by themselves prove a better return.

State: resumable draft is separate from practice goal saved on confirmation. Local browser only, no sync. Storage errors fall back to session memory. Delete clears both.

Fund examples are alphabetical by type, no ranking or returns. Selection is optional learning interest, unrelated to arithmetic.
- PPFAS: https://amc.ppfas.com/schemes/parag-parikh-flexi-cap-fund/ . Current risk label not verified; UI uses fallback. Older KIM inspected but not treated as current: https://amc.ppfas.com/downloads/parag-parikh-flexi-cap-fund/KIM_PPFCF.pdf?14082025=
- UTI: https://www.utimf.com/mutual-funds/uti-nifty-50-index-fund . Current risk label not verified from readable AMC source, UI uses fallback. Type description: https://doc.utimf.com/uticontainer/UTI%20Nifty%2050%20Index%20Fund-12820220918-220021.pdf
- SBI: https://www.sbimf.com/sbimf-scheme-details/sbi-liquid-fund-19 . Current risk label not verified from readable AMC source, UI uses fallback. Type description: https://www.sbimf.com/liquid-mutual-fund

No target amount solving, success probability or fund recommendation. Market/account tabs are disabled prototype chrome. No telemetry. Dark mode and reduced motion supported.
