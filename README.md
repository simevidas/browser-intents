This is my selection of relevant Chromium and Firefox intents (from [blink-dev](https://groups.google.com/a/chromium.org/forum/#!forum/blink-dev) and [dev-platform@mozilla.org](https://groups.google.com/a/mozilla.org/g/dev-platform), respectively); updated weekly (:new: marks latest additions).

[Atom feed](https://github.com/simevidas/browser-intents/commits/master.atom).

---

Jump to section: [Chromium](#chromium) | [Firefox](#firefox)

---

### Chromium

July 2021

- :new: [Ship](https://groups.google.com/a/chromium.org/g/blink-dev/c/EF9fJTfqoGI/m/K2-QWCNxAgAJ) Virtual Keyboard API
- :new: [Experiment](https://groups.google.com/a/chromium.org/g/blink-dev/c/GtR3POPyefM/m/gCfjcSNYAgAJ) HTTP `Service-Worker-Subresource-Filter` header
- :new: [Ship](https://groups.google.com/a/chromium.org/g/blink-dev/c/YoefXLTQsw0/m/NVoV6NcIAgAJ) `preferCurrentTab` option for the `getDisplayMedia` method (Screen Capture)
- :new: [Ship](https://groups.google.com/a/chromium.org/g/blink-dev/c/pNPotQY92UY/m/thZ3h-zQAQAJ) `display-capture` permission
- :new: [Experiment](https://groups.google.com/a/chromium.org/g/blink-dev/c/WitVII_BzyU/m/mI8lZY4NAgAJ) `URLPattern` API
- :new: [Prototype](https://groups.google.com/a/chromium.org/g/blink-dev/c/9e9q5WAepGk/m/uw_XP5zuFAAJ) `speak-as` descriptor for CSS `@counter-style` rule
- :new: [Ship](https://groups.google.com/a/chromium.org/g/blink-dev/c/ruFLLkjvzwg/m/9aGteUUlAgAJ) CSS `@counter-style` rules in shadow trees
- [Experiment](https://groups.google.com/a/chromium.org/g/blink-dev/c/HNHbpxvrECA) Window Controls Overlay for Installed Desktop Web Apps
- [Experiment](https://groups.google.com/a/chromium.org/g/blink-dev/c/dJQgwZ_1jk0) Device Attributes API
- [Ship](https://groups.google.com/a/chromium.org/g/blink-dev/c/71vtc_Xv7jk) CSS `scrollbar-gutter` property
- [Ship](https://groups.google.com/a/chromium.org/g/blink-dev/c/tZqSbhmxiGM) Web App Manifest `"note_taking"` field
- [Experiment](https://groups.google.com/a/chromium.org/g/blink-dev/c/xCWP1ltlAgw) Conversion Measurement API (cont.)
- [Experiment](https://groups.google.com/a/chromium.org/g/blink-dev/c/R0xKm1B7qoQ) reduced `User-Agent` string
- [Experiment](https://groups.google.com/a/chromium.org/g/blink-dev/c/RGlyGO-3Az8) Progressive Web Apps as URL Handlers
- [Ship](https://groups.google.com/a/chromium.org/g/blink-dev/c/snsxQeTSFHo) Prioritized Task Scheduling (`scheduler.postTask` method)
- [Prototype](https://groups.google.com/a/chromium.org/g/blink-dev/c/hvMJ33kqHRo) Cookies Having Independent Partitioned State (CHIPS)
- [Prototype](https://groups.google.com/a/chromium.org/g/blink-dev/c/_quChIvPzT8) Shared Storage API

June 2021

- [Experiment](https://groups.google.com/a/chromium.org/g/blink-dev/c/jznxQK1U8ZQ/m/BsDTdhK4AgAJ) Multi-Screen Window Placement
- [Experiment](https://groups.google.com/a/chromium.org/g/blink-dev/c/NZLnzSY3wIQ/m/TbVKL-cyAAAJ) Virtual Keyboard API
- [Ship](https://groups.google.com/a/chromium.org/g/blink-dev/c/Yy86jN-TjOE/m/tuZim9iCAAAJ) cross-device support for Web OTP API
- [Ship](https://groups.google.com/a/chromium.org/g/blink-dev/c/bCA9H3eaO3s/m/gDrJ0Mx-AAAJ) `supports <font-technology>` for the CSS `src` descriptor
- [Ship](https://groups.google.com/a/chromium.org/g/blink-dev/c/7UlTzFMbTFs/m/Rib4ca4-BQAJ) WebCodecs
- [Prototype nad ship](https://groups.google.com/a/chromium.org/g/blink-dev/c/6I-I3lZWy5k/m/kjqDF1ARBQAJ) `<meta name="theme-color" media>` attribute
- [Prototype](https://groups.google.com/a/chromium.org/g/blink-dev/c/hlxPHfg9GRc/m/M1jbEffUBQAJ) Web App Manifest `"id"` field
- [Ship](https://groups.google.com/a/chromium.org/g/blink-dev/c/tEZ4RVsP1ms/m/9h-yQpmJAgAJ) HTTP `Sec-CH-Prefers-Color-Scheme` header (Client Hints)
- [Ship](https://groups.google.com/a/chromium.org/g/blink-dev/c/epSTNPYkLIs/m/xamWYETxAgAJ) Canvas color management (`colorSpace` option for canvas context)
- [Ship](https://groups.google.com/a/chromium.org/g/blink-dev/c/WwYkLjbGhoA/m/EUw_33z_AgAJ) CSS `accent-color` property
- [Ship](https://groups.google.com/a/chromium.org/g/blink-dev/c/iT0bQjzD04k/m/VkHPoOFLBAAJ) CSS module scripts
- [Experiment](https://groups.google.com/a/chromium.org/g/blink-dev/c/AuKUdqTkUAs/m/qZ3V4_YEBAAJ) URL Protocol Handler Registration for PWAs
- [Prototype and ship](https://groups.google.com/a/chromium.org/g/blink-dev/c/OpiUjfRR4WQ/m/jKdB_mxpAQAJ) `AbortSignal` `abort` static method
- [Experiment](https://groups.google.com/a/chromium.org/g/blink-dev/c/oisKIPVdLQw/m/KAikvxDQAQAJ) WebCodecs (cont.)
- [Implement and ship](https://groups.google.com/a/chromium.org/g/blink-dev/c/saobtpGibyA/m/eDN52Gj9BQAJ) CSS `:autofill` pseudo-class

May 2021

- [Experiment](https://groups.google.com/a/chromium.org/g/blink-dev/c/Cw-hOjT47qI/m/EObn9-4MAgAJ) Speculation Rules (`<script type="speculationrules">`)
- [Prototype and ship](https://groups.google.com/a/chromium.org/g/blink-dev/c/u9jsiarDEOg/m/lpPUQH9VAgAJ) `noplaybackrate` token for the HTML media element `controlslist` attribute
- [Experiment](https://groups.google.com/a/chromium.org/g/blink-dev/c/w6OKsf4e9-Y/m/OUhROQ9JAAAJ) HTML `aria-touchpassthrough` attribute
- [Prototype](https://groups.google.com/a/chromium.org/g/blink-dev/c/CjrLTguZuO4/m/kEO65RvCAAAJ) anonymous iframes
- [Experiment](https://groups.google.com/a/chromium.org/g/blink-dev/c/xb_NHDS3twY/m/Ha1c7Ly9AQAJ) HTTP status code `103 Early Hints` on navigation responses
- [Prototype](https://groups.google.com/a/chromium.org/g/blink-dev/c/ejTbFoJF3sQ/m/wRAxkc54AQAJ) HTTP `Sec-CH-Prefers-Color-Scheme` header (Client Hints)
- [Experiment](https://groups.google.com/a/chromium.org/g/blink-dev/c/bw7Nh5bfsYE/m/ArLjJ1D7AwAJ) `fetch()` upload streaming (cont.)
- [Prototype](https://groups.google.com/a/chromium.org/g/blink-dev/c/Lo7WBM_v_LY/m/LncCKkXeAwAJ) Pickling for Async Clipboard API
- [Prototype](https://groups.google.com/a/chromium.org/g/blink-dev/c/hqkcKdDrhXE/m/qzEVzxbfAwAJ) CSS `:has()` pseudo-class
- [Experiment](https://groups.google.com/a/chromium.org/g/blink-dev/c/POsYbrXbL6I/m/Yfk5la0fBAAJ) Storage Foundation API (cont.)
- [Experiment](https://groups.google.com/a/chromium.org/g/blink-dev/c/RKONugfoGwM/m/ZInY8UtXBAAJ) Capture Handle
- [Prototype](https://groups.google.com/a/chromium.org/g/blink-dev/c/yLTykllpNmI/m/bnzA4mASBAAJ) Capture Handle
- [Experiment](https://groups.google.com/a/chromium.org/g/blink-dev/c/UgZAAElUWzU/m/sBc82Fb2AgAJ) Shared Element Transitions
- [Ship](https://groups.google.com/a/chromium.org/g/blink-dev/c/1PVr94hZHjU/m/J0xT8-rlAQAJ) CSS `size-adjust` descriptor
- [Experiment](https://groups.google.com/a/chromium.org/g/blink-dev/c/uoTx_cRuL5o/m/X3U0GpmRAgAJ) Digital Goods API (cont.)
- [Ship](https://groups.google.com/a/chromium.org/g/blink-dev/c/RqDYSPYE4lI/m/sxXCWw5dAgAJ) EXIF-based intrinsic image sizing
- [Ship](https://groups.google.com/a/chromium.org/g/blink-dev/c/zvFUdYCvZew/m/dzH8rJhVAgAJ) `crypto.randomUUID` method
- [Experiment](https://groups.google.com/a/chromium.org/g/blink-dev/c/oJE9_77rZZ4/m/5jLDB0PCAQAJ) Idle Detection API (cont.)
- [Experiment](https://groups.google.com/a/chromium.org/g/blink-dev/c/HzVV-sM97T0/m/yHcpZWRQAgAJ) Compute Pressure API
- [Experiment](https://groups.google.com/a/chromium.org/g/blink-dev/c/K4_egTNAvTs/m/ApS804L_AQAJ) WebGPU

April 2021

- [Prototype](https://groups.google.com/a/chromium.org/g/blink-dev/c/Ko9UXQYPgUE/m/URRsB-qvAAAJ) Fenced Frames (for ads)
- [Experiment](https://groups.google.com/a/chromium.org/g/blink-dev/c/nNdY-qOScBc/m/A5H3mcf5BQAJ) First-Party Sets and `SameParty` cookie attribute (cont.)
- [Experiment](https://groups.google.com/a/chromium.org/g/blink-dev/c/GJsdwulsGiI/m/7OauT6SjBQAJ) back-forward cache on desktop
- [Experiment](https://groups.google.com/a/chromium.org/g/blink-dev/c/-W90wVkS0Ks/m/HyICZtuuBAAJ) Trust Token API (cont.)
- [Experiment](https://groups.google.com/a/chromium.org/g/blink-dev/c/bEgFQrTsDso/m/9wD9tqxQBAAJ) updated Canvas 2D API
- [Prototype](https://groups.google.com/a/chromium.org/g/blink-dev/c/uEcgVgTJ5qA/m/bemJBwikBAAJ) HTTP `Service-Worker-Subresource-Filter` header
- [Implement and ship](https://groups.google.com/a/chromium.org/g/blink-dev/c/V5jFCsw8J2M/m/VBg0oh2_AwAJ) tainted origin flag for fetch requests
- [Experiment](https://groups.google.com/a/chromium.org/g/blink-dev/c/sLC_W6B8big/m/5sk787RQBAAJ) Network State Partitioning
- [Implement and ship](https://groups.google.com/a/chromium.org/g/blink-dev/c/kz3w-yOMDks/m/Ue71o4xYAAAJ) CSS `:playing` and `:paused` pseudo-classes
- [Experiment](https://groups.google.com/a/chromium.org/g/blink-dev/c/aaLFxzw5zL4/m/H3V_l-qlAgAJ) WebTransport over HTTP/3
- [Prototype](https://groups.google.com/a/chromium.org/g/blink-dev/c/loqGn7N9hzU/m/mRDdLA_cAgAJ) CSS `contain-intrinsic-size: auto` value
- [Ship](https://groups.google.com/a/chromium.org/g/blink-dev/c/6U78F3KWJ78/m/hcEoYVx8AgAJ) imperative slot distribution API (Shadow DOM)

March 2021

- [Ship](https://groups.google.com/a/chromium.org/g/blink-dev/c/xPQYlcf-N-0/m/se6xRssBCAAJ) Managed Configuration API
- [Prototype](https://groups.google.com/a/chromium.org/g/blink-dev/c/LTIRZ24C5Os/m/BPSeJ8y0BwAJ) Compute Pressure
- [Prototype](https://groups.google.com/a/chromium.org/g/blink-dev/c/WjCKcBw219k/m/BK9qXyz1BwAJ) JPEG XL image format
- [Ship](https://groups.google.com/a/chromium.org/g/blink-dev/c/_P5bxPTo6XE/m/1tqu3dzCBwAJ) HTML `inert` attribute
- [Ship](https://groups.google.com/a/chromium.org/g/blink-dev/c/clPEmywkX4w/m/LbIZZv-fBQAJ) cross-origin iframe support in Web OTP API
- [Experiment](https://groups.google.com/a/chromium.org/g/blink-dev/c/Fb-NdCvbgmU/m/68nHOaFPBQAJ) File Handling API
- [Prototype](https://groups.google.com/a/chromium.org/g/blink-dev/c/uJ1tuT7HTd8/m/gP8ixHXiBQAJ) Web App Manifest `"note_taking"` and `"new_note_url"` fields
- [Prototype](https://groups.google.com/a/chromium.org/g/blink-dev/c/006tkVwj1yw/m/7i4d1XXiBQAJ) Lock Screen API
- [Experiment](https://groups.google.com/a/chromium.org/g/blink-dev/c/OrWQnXVQJ0A/m/TbF-0Dw3BQAJ) Sanitizer API
- [Ship](https://groups.google.com/a/chromium.org/g/blink-dev/c/uV1gwoX2fMY/m/vWrj0BA6AwAJ) `GravitySensor` API
- [Experiment](https://groups.google.com/a/chromium.org/g/blink-dev/c/o8RqlFwZItQ/m/zDlYHEhYBAAJ) Handwriting Recognition API
- [Experiment](https://groups.google.com/a/chromium.org/g/blink-dev/c/55QViQdz5Rc/m/UxytBsZ5AgAJ) WebCodecs (cont.)
- [Prototype and ship](https://groups.google.com/a/chromium.org/g/blink-dev/c/iJaPCv9HOrE/m/MRJDqCRvAgAJ) standard JavaScript modules in service workers
- [Experiment](https://groups.google.com/a/chromium.org/g/blink-dev/c/9CwkzaF_eQ4/m/kuR07FTTCAAJ) subresource loading with Web Bundles
- [Ship](https://groups.google.com/a/chromium.org/g/blink-dev/c/V3Yo20_ZZLc/m/rUT-qELKBwAJ) HTTP `Critical-CH` response header
- [Implement and ship](https://groups.google.com/a/chromium.org/g/blink-dev/c/OwUSsHWokpA/m/DyH99LahBwAJ) HTML `<link rel="icon" media>` attribute
- [Experiment](https://groups.google.com/a/chromium.org/g/blink-dev/c/MmijXrmwrJs/m/uDBQ5-tJAAAJ) Federated Learning of Cohorts (FLoC)
- [Prototype](https://groups.google.com/a/chromium.org/g/blink-dev/c/R1D5xYccqb0/m/8ukfzdVSAgAJ) App History API
- [Prototype](https://groups.google.com/a/chromium.org/g/blink-dev/c/8R6kvHjiqdw/m/9JwSNAP7AQAJ) `document.prerendering` property

February 2021

- [Ship](https://groups.google.com/a/chromium.org/g/blink-dev/c/_BO41rwrrtI/m/TjPsQnC2AwAJ) CSS `advance-override` descriptor
- [Ship](https://groups.google.com/a/chromium.org/g/blink-dev/c/kC8b-dZ8uBQ/m/Ngopo8S2AgAJ) CSS `@counter-style` at-rule
- [Prototype](https://groups.google.com/a/chromium.org/g/blink-dev/c/DAgWIczGtG0/m/gSXvjYn-AwAJ) HTTP status code `103 Early Hints` on navigation responses
- [Ship](https://groups.google.com/a/chromium.org/g/blink-dev/c/7sZ52cP8HMg/m/ciep5kv-AwAJ) Declarative Shadow DOM
- [Prototype](https://groups.google.com/a/chromium.org/g/blink-dev/c/1q7Fp3zpjgQ/m/5jbNkmRfAwAJ) Speculation Rules
- [Ship](https://groups.google.com/a/chromium.org/g/blink-dev/c/MRDuNaR4Zd0/m/n7J2g6qNAQAJ) files on the clipboard
- [Prototype](https://groups.google.com/a/chromium.org/g/blink-dev/c/Ix2u8NHG5Po/m/sNguLXOsAQAJ) Custom Highlight API
- [Experiment](https://groups.google.com/a/chromium.org/g/blink-dev/c/Jhirhnq3WbY/m/GnhrTQAnAQAJ) Storage Foundation API
- [Experiment](https://groups.google.com/a/chromium.org/g/blink-dev/c/XkWbQKrBzMg/m/dIQckPbZAAAJ) First-Party Sets and `SameParty` cookie attribute
- [Prototype](https://groups.google.com/a/chromium.org/g/blink-dev/c/q9zf-frdewo/m/zxw2HuzGAQAJ) CSS `accent-color` property
- [Experimenrt](https://groups.google.com/a/chromium.org/g/blink-dev/c/YD_fiUqNggo/m/LyyvJWTFAAAJ) QuicTransport (cont.)
- [Ship](https://groups.google.com/a/chromium.org/g/blink-dev/c/nrpl_ewkmaQ/m/aVI8C8NeAwAJ) stricter mixed content check for `blob:` and `filesystem:` URLs
- [Prototype](https://groups.google.com/a/chromium.org/g/blink-dev/c/8sNTXCoggcQ/m/sFr7FOteBAAJ) MulticastReceiver API
- [Experiment](https://groups.google.com/a/chromium.org/g/blink-dev/c/q6ivDcvAJwQ/m/UWFuY2E9BAAJ) Declarative Link Capturing for PWAs (`"capture_links"` member for web app manifest)

January 2021

- [Ship](https://groups.google.com/a/chromium.org/g/blink-dev/c/gv69rSngHDY/m/B_p8K21kAgAJ) CSS `:focus-visible` in the user-agent style sheet
- [Ship](https://groups.google.com/a/chromium.org/g/blink-dev/c/8_86NDuVdRk/m/Q7KXPPJAAwAJ) `signal` option for `addEventListener` method (AbortSignal)
- [Prototype](https://groups.google.com/a/chromium.org/g/blink-dev/c/X6rEbWvU7cI/m/IJqgEI-HAwAJ) Multi-Screen Window Placement
- [Prototype](https://groups.google.com/a/chromium.org/g/blink-dev/c/XeELlWkuCgQ/m/jNKb15bEAwAJ) Multi Apps
- [Prototype](https://groups.google.com/a/chromium.org/g/blink-dev/c/etQ-LVhY6S4/m/JfKi-o6HAwAJ) ARIA Virtual Content
- [Prototype](https://groups.google.com/a/chromium.org/g/blink-dev/c/HVO2p0V5OW8/m/9lU8Ns1zAwAJ) `GravitySensor` API
- [Prototype](https://groups.google.com/a/chromium.org/g/blink-dev/c/XIXudwZdr44/m/emDJRTFoAwAJ) COLRv1 Color Gradient Vector Fonts
- [Implement and ship](https://groups.google.com/a/chromium.org/g/blink-dev/c/bqRpC58mtKE/m/rb36zgABAgAJ) `StaticRange` constructor
- [Experiment](https://groups.google.com/a/chromium.org/g/blink-dev/c/tkdwZYCI4EE/m/L6-Gw2-kCAAJ) Idle Detection API (cont.)
- [Prototype](https://groups.google.com/a/chromium.org/g/blink-dev/c/9y-Thg9UCxY/m/_4gShWjQAAAJ) HTML `<popup>` element
- [Implement and ship](https://groups.google.com/a/chromium.org/g/blink-dev/c/NNm3FnMvyZc/m/9wtFLdrDAAAJ) smooth interpolation when animating the CSS `aspect-ratio` property
- [Experiment](https://groups.google.com/a/chromium.org/g/blink-dev/c/QMQz7rWADO0/m/UYYZJMMOAQAJ) `scheduler.postTask` method for main-thread scheduling (cont.)
- [Prototype](https://groups.google.com/a/chromium.org/g/blink-dev/c/-unZxHbw8Pc/m/_23CsOkHAQAJ) `SameParty` cookie attribute
- [Experiment](https://groups.google.com/a/chromium.org/g/blink-dev/c/mNVaRrvBZG0/m/lOezCQV_CwAJ) `fetch()` upload streaming
- [Experiment](https://groups.google.com/a/chromium.org/g/blink-dev/c/A1kOJydFI3I/m/V88Gfe3MAAAJ) Declarative Shadow DOM (cont.)
- [Experiment](https://groups.google.com/a/chromium.org/g/blink-dev/c/C0P7ePjITJQ/m/ZYFmn30SDQAJ) Conversion Measurement API (cont.)
- [Prototype](https://groups.google.com/a/chromium.org/g/blink-dev/c/8UEcRJViPEU/m/YZml0HGxCQAJ) CSS `::spelling-error` and `::grammar-error` pseudo-elements, and `spelling-error` and `grammar-error` values for `text-decoration-line`
- [Ship](https://groups.google.com/a/chromium.org/g/blink-dev/c/RExJ9a3SmQw/m/7mbQ4RELCgAJ) `performance.measureMemory` method
- [Spec, implement and ship](https://groups.google.com/a/chromium.org/g/blink-dev/c/0xrbzYe_vxU/m/52xVJHTICQAJ) persistent guaranteed-invalid CSS variables
- [Implement](https://groups.google.com/a/chromium.org/g/blink-dev/c/GfVrt1CwxK8/m/i9Rv8Jp5BwAJ) Web Share API on macOS

December 2020

- [Ship](https://groups.google.com/a/chromium.org/g/blink-dev/c/ZdJgwttxnQM/m/zA6ddWonAgAJ) CSS `filter` property for SVG elements (filter functions)
- [Implement and ship](https://groups.google.com/a/chromium.org/g/blink-dev/c/l3Qw9cWYPUA/m/Yl9siP_8AQAJ) CSS `:link`, `:visited`, and `:any-link` pseudo selectors for `<link>` elements
- [Prototype](https://groups.google.com/a/chromium.org/g/blink-dev/c/2ZnA1IrSpS8/m/7wx6dENTAwAJ) Declarative Link Capturing for PWAs (`"capture_links"` member for web app manifest)
- [Prototype](https://groups.google.com/a/chromium.org/g/blink-dev/c/cPTMI1i6d7I/m/28mjGLIjBAAJ) EyeDropper API
- [Ship](https://groups.google.com/a/chromium.org/g/blink-dev/c/aoj06_plqPc/m/D-6ahhfuAwAJ) Web NFC
- [Prototype](https://groups.google.com/a/chromium.org/g/blink-dev/c/4oKgdB26p6g/m/4M2fIR_aAwAJ) well-specified prerendering
- [Prototype](https://groups.google.com/a/chromium.org/g/blink-dev/c/4cT9dMkzVXE/m/aCT8B6PDAwAJ) `infinity` and `NaN` values in CSS `calc()`
- [Prototype and ship](https://groups.google.com/a/chromium.org/g/blink-dev/c/d4UdwpPDXJM/m/J-o_C_kqAwAJ) CSS `::file-selector-button` pseudo-element
- [Ship](https://groups.google.com/a/chromium.org/g/blink-dev/c/rVX_dJAJ-eI/m/17r-6-eiAgAJ) Import Maps
- [Ship](https://groups.google.com/a/chromium.org/g/blink-dev/c/AQip4hjqt5U/m/OwPgs9NmAgAJ) Byte Streams (Streams API)
- [Ship](https://groups.google.com/a/chromium.org/g/blink-dev/c/RCtZPCQLLOQ/m/pnMErtbFAAAJ) Web Serial API
- [Prototype](https://groups.google.com/a/chromium.org/g/blink-dev/c/CURnzae5yOE/m/yggKMxjGAAAJ) Canvas Formatted Text
- [prototype and ship](https://groups.google.com/a/chromium.org/g/blink-dev/c/YmWSODSTPS4/m/qx1uXvYxAgAJ) CSS `border-start-start-radius`, `border-start-end-radius`, `border-end-start-radius`, and `border-end-end-radius` properties
- [Ship](https://groups.google.com/a/chromium.org/g/blink-dev/c/Hb1-VLwq54Y/m/TYsK4EzlCAAJ) potentially trustworthy `data:` URLs
- [Ship](https://groups.google.com/a/chromium.org/g/blink-dev/c/MZgYJgS4Lcs/m/NnUxG2_mAAAJ) Web App Manifest `"display_override"` field
- [Ship](https://groups.google.com/a/chromium.org/g/blink-dev/c/xGofL-IMAb4/m/t03fbbg3CQAJ) CSS `overflow: clip` value and `overflow-clip-margin` property
- [Ship](https://groups.google.com/a/chromium.org/g/blink-dev/c/rL1csFYD1Ms/m/3qgPuZACCQAJ) WebHID
- [Ship](https://groups.google.com/a/chromium.org/g/blink-dev/c/Czc_36BS2dA/m/_yHDeFwQCQAJ) `disclosure-open` and `disclosure-closed` keywords for the CSS `list-style-type` property
- [Ship](https://groups.google.com/a/chromium.org/g/blink-dev/c/ihZFdCHuiTA/m/e1SEN6IQCQAJ) CSS `list-style-type` and `::marker` support on `<summary>` element

November 2020

- [Prototype](https://groups.google.com/a/chromium.org/g/blink-dev/c/prHGPxF62i4/m/SjBiLZ7ZBgAJ) Screen Fold API
- [Prototype](https://groups.google.com/a/chromium.org/g/blink-dev/c/VXUq1UY4m7Y/m/T2apH2ZeBQAJ) Handwriting Recognition API
- [Prototype](https://groups.google.com/a/chromium.org/g/blink-dev/c/gBpWuawy-Ms/m/a2qg7cFcBQAJ) `"display-capture"` permission
- [Experiment](https://groups.google.com/a/chromium.org/g/blink-dev/c/a76WF3Dfl3E/m/IwSS51VqBQAJ) `beforematch` event and CSS `content-visibility: hidden-matchable` value (cont.)
- [Ship](https://groups.google.com/a/chromium.org/g/blink-dev/c/yN2lrq67a1c/m/_Giqh2g_AwAJ) CSS `::target-text` pseudo-element
- [Experiment](https://groups.google.com/a/chromium.org/g/blink-dev/c/3MNyU3OAacI/m/sj8IdIMRAwAJ) WebCodecs (cont.)
- [Prototype](https://groups.google.com/a/chromium.org/g/blink-dev/c/7SMI3IklO4g/m/JS-JojxNAwAJ) Shared Element Transitions
- [Ship](https://groups.google.com/a/chromium.org/g/blink-dev/c/WW4fGjvroWI/m/H6edWbOgAQAJ) Origin Isolation
- [Prototype](https://groups.google.com/a/chromium.org/g/blink-dev/c/9396JedBBOM/m/OfeJ4z1OAQAJ) `signal` option for `addEventListener` method (AbortSignal)
- [Prototype](https://groups.google.com/a/chromium.org/g/blink-dev/c/vSPTU15iL9Y/m/jNYWijNmAgAJ) CSS `@counter-style` at-rule
- [Experiment](https://groups.google.com/a/chromium.org/g/blink-dev/c/TESchpNIjr4/m/rJq1GqEcCQAJ) HTML `<meta name="battery-savings">` tag (cont.)
- [Prototype](https://groups.google.com/a/chromium.org/g/blink-dev/c/u1AKdrXhPGI/m/wrJb-unhAgAJ) Container Queries
- [Ship](https://groups.google.com/a/chromium.org/g/blink-dev/c/bta50W_Hg24/m/R6GE8BxHCQAJ) `click`, `contextmenu`, and `auxlick` as instances of `PointerEvent`

October 2020

- [Prototype](https://groups.google.com/a/chromium.org/g/blink-dev/c/gh0gTHO18YQ/m/6ZulUK96AAAJ) NativeIO storage API
- [Prototype](https://groups.google.com/a/chromium.org/g/blink-dev/c/-cdYnhNAtmo/m/U2_boIg9AAAJ) WebXR Hand Input module
- [Ship](https://groups.google.com/a/chromium.org/g/blink-dev/c/FFX6VkvladY/m/QgaWHK6ZBAAJ) implicit `rel="noopener"` for `<a target="_blank">` elements
- [Prototype](https://groups.google.com/a/chromium.org/g/blink-dev/c/9CeLYndESPE/m/AhEttheMBQAJ) Capability Delegation
- [Prototype](https://groups.google.com/a/chromium.org/g/blink-dev/c/Q8Qgu1ZdJ44/m/m36Nlar_BAAJ) byte streams for Streams API
- [Implement and ship](https://groups.google.com/a/chromium.org/g/blink-dev/c/0alTkXvDCL8/m/-ClOGvOJBAAJ) selector lists in CSS `:not()` pseudo-class
- [Experiment](https://groups.google.com/a/chromium.org/g/blink-dev/c/eXQq11lrAGU/m/gMObweAxBQAJ) Trust Token API (cont.)
- [Prototype](https://groups.google.com/a/chromium.org/g/blink-dev/c/jBMvUEkyBq8/m/IwYIZmhEBQAJ) URL pattern matching for service worker scope
- [Prototype](https://groups.google.com/a/chromium.org/g/blink-dev/c/nZVd7iiy3dc/m/udaY1Mo6BQAJ) HTTP `Supports-Loading-Mode` response header (prerendering opt-in)
- [Prototype and ship](https://groups.google.com/a/chromium.org/g/blink-dev/c/p0Wc66rbVOc/m/khHJ0dSsAwAJ) CSS `:dir()` pseudo-class
- [Experiment](https://groups.google.com/a/chromium.org/g/blink-dev/c/3MW3ngOsUOk/m/iE0Bvg-6AwAJ) Local Font Access
- [Ship](https://groups.google.com/a/chromium.org/g/blink-dev/c/sIRXYKA4jGE/m/OfZMzveCAAAJ) CSS `hyphens: auto` value on Windows
- [Ship](https://groups.google.com/a/chromium.org/g/blink-dev/c/Wodp9dSSdL8/m/OZo2vJqTAwAJ) CSS `:is()` and `:where()` pseudo-classes
- [Prototype](https://groups.google.com/a/chromium.org/g/blink-dev/c/zwG2m_KG0RY/m/8nEx9wCWAwAJ) CSS `scrollbar-color` and `scrollbar-width` properties
- [Prototype](https://groups.google.com/a/chromium.org/g/blink-dev/c/YEo4LqB7nWI/m/t1IkW35rAwAJ) TLS Encrypted Client Hello (ECH)
- [Ship](https://groups.google.com/a/chromium.org/g/blink-dev/c/E0bpVCaWPEg/m/anYk3vFfAwAJ) CSS `clip-path: path()` values
- [Prototype](https://groups.google.com/a/chromium.org/g/blink-dev/c/I0e2_nAwW7E/m/Fpb7hrZdAwAJ) CSS `prefers-contrast` media feature
- [Prototype](https://groups.google.com/a/chromium.org/g/blink-dev/c/5zkY3e9cpoo/m/xWNtvgyFAAAJ) CSS `::target-text` pseudo-element
- [Prototype](https://groups.google.com/a/chromium.org/g/blink-dev/c/NYVbRRBlABI/m/T5nWjE0rCAAJ) `getCurrentBrowsingContextMedia` method
- [Prototype](https://groups.google.com/a/chromium.org/g/blink-dev/c/2B4TJ7j2U4M/m/1X5T3OszCAAJ) WebID
- [Ship](https://groups.google.com/a/chromium.org/g/blink-dev/c/TF41VMfLhMI/m/py4LZcfwAQAJ) CSS `aspect-ratio` property
- [Prototype](https://groups.google.com/a/chromium.org/g/blink-dev/c/LZsMi8heTu0/m/bh0my7vpBwAJ) Storage Buckets API
- [Experiment](https://groups.google.com/a/chromium.org/g/blink-dev/c/DjucMDeR-og/m/6yLpNN4wAAAJ) WebXR Depth API
- [Experiment](https://groups.google.com/a/chromium.org/g/blink-dev/c/_yZ54YV5Gis/m/0Dcw3Jt6AAAJ) Declarative Shadow DOM (cont.)
- [Ship](https://groups.google.com/a/chromium.org/g/blink-dev/c/NUR-gpWxSZ4/m/zLYNL-hwAAAJ) “Partition the HTTP cache”

September 2020

- [Ship](https://groups.google.com/a/chromium.org/g/blink-dev/c/gTPNGMPgDBk/m/kKXmazEXCgAJ) HTTP `Permissions-Policy` header
- [Experiment](https://groups.google.com/a/chromium.org/g/blink-dev/c/6KrwUguadyE/m/GK5C8KbWCQAJ) `scheduler.postTask` method for main-thread scheduling (cont.)
- [Ship](https://groups.google.com/a/chromium.org/g/blink-dev/c/ZzngHwf2qyQ/m/cp9jcX6_CQAJ) Cross-Origin Isolation
- [Prototype](https://groups.google.com/a/chromium.org/g/blink-dev/c/SlLdc64lvpM/m/G_FqIcLWCAAJ) platform-issued trust tokens
- [Experiment](https://groups.google.com/a/chromium.org/g/blink-dev/c/W7GGHz9vecg/m/BwJuNhDBCAAJ) QuicTransport (cont.)
- [Ship](https://groups.google.com/a/chromium.org/g/blink-dev/c/9OzS90KISXI/m/q5KYyyWBCAAJ) CSS `text-decoration-thickness` and `text-underline-offset` properties, and `text-underline-position: from-font` value
- [Experiment](https://groups.google.com/a/chromium.org/g/blink-dev/c/tkdwZYCI4EE/m/L6-Gw2-kCAAJ) Idle Detection API (cont.)
- [Experiment](https://groups.google.com/a/chromium.org/g/blink-dev/c/xOTmlUxPj7A/m/X7E-BmYwCQAJ) Notification Triggers (cont.)
- [Experiment](https://groups.google.com/a/chromium.org/g/blink-dev/c/uI3DP5v-s34/m/0us1sPDmCAAJ) Origin Isolation (cont.)
- [Experiment](https://groups.google.com/a/chromium.org/g/blink-dev/c/WPQCslQMRWY/m/8Wo4QtEZCQAJ) `performance.measureMemory` method (cont.)
- [Ship](https://groups.google.com/a/chromium.org/g/blink-dev/c/8Vt2atMrNNs/m/1DGx9DKsBwAJ) `navigator.scheduling.isInputPending` method
- [Ship](https://groups.google.com/a/chromium.org/g/blink-dev/c/ApR03h3CGfo/m/K_Fw3bAPBwAJ) CSS `ascent-override`, `descent-override`, and `line-gap-override` font descriptors
- [Ship](https://groups.google.com/a/chromium.org/g/blink-dev/c/zOsGZGMGiM4/m/zdJGMq5iBwAJ) Cookie Store API
- [Experiment](https://groups.google.com/a/chromium.org/g/blink-dev/c/Ib9-tDFitns/m/Sm9RXTNaBwAJ) Conversion Measurement API
- [Ship](https://groups.google.com/a/chromium.org/g/blink-dev/c/fJ8n9kTbna4/m/i8mMlc0jAgAJ) Web Share API on Windows and Chrome OS
- [Prototype](https://groups.google.com/a/chromium.org/g/blink-dev/c/zPYGbULXn7o/m/j92zXBvYAwAJ) HTTP `Critical-CH` response header
- [Prototype and ship](https://groups.google.com/a/chromium.org/g/blink-dev/c/1V6Ss1VABko/m/Y3Nl0vHIAQAJ) Screen Wake Lock `released` property

August 2020

- [Experiment](https://groups.google.com/a/chromium.org/g/blink-dev/c/syI9_M9dANY/m/3eMd0n15AAAJ) Digital Goods API
- [Experiment](https://groups.google.com/a/chromium.org/g/blink-dev/c/7OdxQf5HnlQ/m/oyb3oFVaAAAJ) WebCodecs
- [Prototype](https://groups.google.com/a/chromium.org/g/blink-dev/c/XcGGi4jAwfE/m/QSIQThtmAAAJ) CSS `overflow: clip` value and `overflow-clip-margin` property
- [Ship](https://groups.google.com/a/chromium.org/g/blink-dev/c/E7f_WZOcTgQ/m/pbudXZNaAAAJ) CSS flow-relative box model properties
- [Prototype](https://groups.google.com/a/chromium.org/g/blink-dev/c/9TcfjaOs5zg/m/Tuk80aIeAAAJ) customizable `<select>` element
- [Prototype](https://groups.google.com/a/chromium.org/g/blink-dev/c/2Sv3fCWEi_Q/m/yrSoJP8mAAAJ) Progressive Web Apps as URL Handlers
- [Ship](https://groups.google.com/a/chromium.org/g/blink-dev/c/9Fcpl2KVfbk/m/d9VN0Fz8BwAJ) Native File System API
- [Prototype](https://groups.google.com/a/chromium.org/g/blink-dev/c/ARtkaw4e9T4/m/npjeMssPCAAJ) Raw Sockets API
- [Prototype](https://groups.google.com/a/chromium.org/g/blink-dev/c/As1ABvc2QdA/m/yZSpPXY4CAAJ) HTTP `Permissions-Policy` header
- [Ship](https://groups.google.com/a/chromium.org/g/blink-dev/c/iqihcxi-CzY/m/U_0GkEoqCAAJ) CSS `quotes: auto` value
- [Ship](https://groups.google.com/a/chromium.org/g/blink-dev/c/1LStSgBt6AM/m/sJaTciPKBwAJ) Transferable Streams
- [Experiment](https://groups.google.com/a/chromium.org/g/blink-dev/c/C6xw8i1ZIdE/m/TJsr0zXxBwAJ) Multi-Screen Window Placement
- [Prototype](https://groups.google.com/a/chromium.org/g/blink-dev/c/U5Iy4LrcwoI/m/dIlbC2OhAwAJ) WebXR Depth API
- [Prototype](https://groups.google.com/a/chromium.org/g/blink-dev/c/0EMGi-xbI-8/m/d_UxAJeiBwAJ) First-Party Sets
- [Experiment](https://groups.google.com/a/chromium.org/g/blink-dev/c/aTrk7__Eiq4/m/BOGSzGHeAwAJ) `beforematch` event and CSS `content-visibility: hidden-matchable` value
- [Experiment](https://groups.google.com/a/chromium.org/g/blink-dev/c/vVtAi2evarQ/m/VSFDPeCPAwAJ) HTML `<meta name="battery-savings">` tag
- [Ship](https://groups.google.com/a/chromium.org/g/blink-dev/c/Jdw3VWbKvLY/m/qnoA5DlPAwAJ) Imperative Shadow DOM Distribution API
- [Experiment](https://groups.google.com/a/chromium.org/g/blink-dev/c/NGgprfPEbG0/m/nhNCiN0ZBgAJ) Serial API (cont.)
- [Ship](https://groups.google.com/a/chromium.org/g/blink-dev/c/h6my3rcC628/m/RBGKm4aXAgAJ) opt-out for Scroll To Text Fragment (`force-load-at-top` document policy)
- [Prototype](https://groups.google.com/a/chromium.org/g/blink-dev/c/uZIHh4zMS94/m/pP__46dlAgAJ) SVG image support for the Async Clipboard API
- [Prototype](https://groups.google.com/a/chromium.org/g/blink-dev/c/PQ9aDeWGUE0/m/qf07C9FDAgAJ) HTML `<meta name="battery-savings">` tag
- [Prototype](https://groups.google.com/a/chromium.org/g/blink-dev/c/xtyi6D52DkM/m/xU7r3sPoAQAJ) re-enabled `SharedArrayBuffer` gated behind COOP/COEP (on Android)

July 2020

- [Prototype](https://groups.google.com/a/chromium.org/g/blink-dev/c/4hFGYxBRIBU/m/dUgy9SUVAgAJ) HTTP `Content-Encoding: jxl` value (JPEG XL)
- [Ship](https://groups.google.com/a/chromium.org/g/blink-dev/c/lqFuqwZDDR8/m/nKPRTc7DAQAJ) `strict-origin-when-cross-origin` as default referrer policy
- [Implement](https://groups.google.com/a/chromium.org/g/blink-dev/c/PZkIB8wBTwQ/m/qfX1At8UAgAJ) Web Share API on Windows and Chrome OS
- [Ship](https://groups.google.com/a/chromium.org/g/blink-dev/c/Za159T1QOek/m/lewQUFlBCQAJ) HTTP `Document-Policy` header
- [Ship](https://groups.google.com/a/chromium.org/g/blink-dev/c/ZRI-7X_4GwM/m/WOtmGnlACQAJ) altitude and azimuth angles for Pointer Events
- [Prototype](https://groups.google.com/a/chromium.org/g/blink-dev/c/h21QrfPrkl4/m/ff_dZxYcCQAJ) `@font-face` descriptors for overriding font metrics (e.g., `ascent-override`)
- [Experiment](https://groups.google.com/a/chromium.org/g/blink-dev/c/yG0JzbEUoX4/m/eFfQJwRzBAAJ) opt-out for Scroll To Text Fragment
- [Implement and ship](https://groups.google.com/a/chromium.org/g/blink-dev/c/BXxS2U5EaN0/m/cSVmzxSmDQAJ) WebXR AR Module
- [Ship](https://groups.google.com/a/chromium.org/g/blink-dev/c/fgme9KOd8CU/m/TCYPKQAXAwAJ) Permission Policty `web-share` permission
- [Experiment](https://groups.google.com/a/chromium.org/d/msg/blink-dev/DuvhXyYo7Pc/_zcDVQmCAAAJ) Declarative Shadow DOM
- [Implement and ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/PwIp0J5FJBY/LvWWFrSFBQAJ) DOM `replaceChildren` method
- [Ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/80j6AEWI-_s/1hLY7RP5BQAJ) CSS `::marker` pseudo-element
- [Prototype](https://groups.google.com/a/chromium.org/d/msg/blink-dev/0rW4Q_NtL20/h1C2C0rLAAAJ) `'visibility-state'` performance entries
- [Prototype and ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/P0dGbK3ThT0/H84DQKPZBQAJ) `FetchEvent` `handled` property (promise)
- [Prototype](https://groups.google.com/a/chromium.org/d/msg/blink-dev/t_9QdJ7hcls/CAAOGBIVBgAJ) WebAuthn Level 2 and CTAP2.1
- [Prototype](https://groups.google.com/a/chromium.org/d/msg/blink-dev/MMba4E0bAeo/IwWQV1bIBQAJ) `quotachange` event (storage pressure)
- [Prototype](https://groups.google.com/a/chromium.org/d/msg/blink-dev/MJxVZs1H5SY/6q0QxEFtBAAJ) Sanitizer API

June 2020

- [Ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/lqCQ63CTKEQ/cYTNFETPAwAJ) Web Bluetooth `getDevices` and `watchAdvertisements` methods
- [Ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/MlTJyKGGtks/rTfshC2SBAAJ) AVIF (image format)
- [Prototype and ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/IDAapW6w4to/iSH1MXRFCgAJ) Feature Policy `clipboard-read` and `clipboard-write` policies
- [Ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/OXZLwImwdbc/ai77f5puBAAJ) Media Feeds (`<link rel="media-feed">`)
- [Implement and ship](https://groups.google.com/a/chromium.org/g/blink-dev/c/XVCt0EXVplQ/m/sDyHmylZAgAJ) `HTMLMediaElement` `preservesPitch` property
- [Implement and ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/gwaEnJjtfKw/rEf_uw92AgAJ) `PictureInPictureEvent` `pictureInPictureWindow` property
- [Prototype](https://groups.google.com/a/chromium.org/d/msg/blink-dev/U51-KZ51vNY/gdA2ZYt6AQAJ) Cross-Origin Isolation
- [Prototype](https://groups.google.com/a/chromium.org/d/msg/blink-dev/GErJ9WbxJrU/F8N2xl1kBgAJ) CSS `scrollbar-gutter` property
- [Prototype](https://groups.google.com/a/chromium.org/d/msg/blink-dev/uASqamKZILY/DYm_UuokBQAJ) CSS `color-mix()` function
- [Implement and ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/LpHjBZZSPB0/QpafCJheBQAJ) CSS `counter-set` property
- [Experiment](https://groups.google.com/a/chromium.org/d/msg/blink-dev/LoyzK8xTRME/yLR-K-siBQAJ) WebHID (Human Interface Device)
- [Ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/Ay1bG_e9m00/kpJVUINhBQAJ) WebXR Anchors
- [Prototype](https://groups.google.com/a/chromium.org/d/msg/blink-dev/WvIeZT8uSzw/al7sVZjVBAAJ) Web Manifest `"display-override"` field
- [Implement and ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/8En_5DqV_fU/fKD_sQRiAwAJ) Intensive JavaScript Timer Throttling
- [Ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/uElH0-Ys8Cs/bJXV-Ky5BAAJ) CSS `content-visibility` property
- [Prototype](https://groups.google.com/a/chromium.org/d/msg/blink-dev/4kMGCyCUIao/5vjPk4tuAQAJ) WebXR Raw Camera Access

May 2020

- [Prototype](https://groups.google.com/a/chromium.org/d/msg/blink-dev/viBACPfSsEM/URCnDl81AAAJ) CSS `attr()` function Level 4 extension
- [Implement and ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/3RhZFvZE1LM/2n93K-kPAwAJ) updated CSS `color-scheme` property
- [Prototype](https://groups.google.com/a/chromium.org/d/msg/blink-dev/3eac-HVygFY/N_OXaOs7AAAJ) MediaBlob (improved client side video editing)
- [Prototype](https://groups.google.com/a/chromium.org/d/msg/blink-dev/wYn13HabRN0/L4y4iY1-AgAJ) subresource loading with Web Bundles
- [Experiment](https://groups.google.com/a/chromium.org/d/msg/blink-dev/LuoryMqT7wQ/DEiG_IpAAgAJ) `performance.measureMemory` method (cont.)
- [Prototype](https://groups.google.com/a/chromium.org/d/msg/blink-dev/JVKSTHFiDzo/XlduZcFWAgAJ) MulticastReceiver API
- [Ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/1UQqjz1CR-k/Rdl-wVPkBwAJ) Event Timing
- [Implement and ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/FGCgsKmylhw/BSUrk2roCQAJ) CSS `attr()` function Level 4 extension
- [Experiment](https://groups.google.com/a/chromium.org/d/msg/blink-dev/mHV_ZALf07Q/d7J9W0a1CQAJ) QuicTransport
- [Ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/FgzYX7AFbUQ/f2i0-f-BAQAJ) App Icon Shortcuts Menu
- [Experiment](https://groups.google.com/a/chromium.org/d/msg/blink-dev/bBdx2xIB7OQ/k2fMXf-WAAAJ) Cookie Store API
- [Ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/HYDQLFPAHC0/BsF9T0wGAAAJ) CSS `row-gap` and `column-gap` properties in Flexbox Layout
- [Experiment](https://groups.google.com/a/chromium.org/d/msg/blink-dev/G0h3PFPeclA/Lqt872UCAAAJ) Origin Isolation
- [Experiment](https://groups.google.com/a/chromium.org/d/msg/blink-dev/UIvia1WwIhk/DuXLKdF7AgAJ) Trust Token API
- [Prototype](https://groups.google.com/a/chromium.org/d/msg/blink-dev/QKUZ_ALJdM8/d0Qu1wJcAQAJ) `beforematch` event

April 2020

- [Ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/hkjRPJ1-Ruk/AS6HBVfCAAAJ) Forced Colors Mode (CSS `forced-color-adjust` property)
- [Experiment](https://groups.google.com/a/chromium.org/d/msg/blink-dev/9OwINXHzbUE/0EhqVz2CAAAJ) Idle Detection API
- [Prototype](https://groups.google.com/a/chromium.org/d/msg/blink-dev/Bkn7wCAsKbs/reJTn3uuBQAJ) Web Bluetooth `watchAdvertisements` method
- [Ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/Wu4yPMznUw0/-LrirfTJBAAJ) Web Animations API
- [Ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/3ygpsew53a0/T7acB6sRBQAJ) CSS `@property` at-rule
- [Experiment](https://groups.google.com/a/chromium.org/d/msg/blink-dev/sBGPdqQRQfo/cam3wY2jAwAJ) HTML `rendersubtree` attribute (cont.)
- [Ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/cMlaiFqdkYQ/ANy6Ad2DAwAJ) Content Index API
- [Prototype](https://groups.google.com/a/chromium.org/d/msg/blink-dev/q80uCrMgiTM/nF3mo-7zBAAJ) Virtual Keyboard API
- [Prototype](https://groups.google.com/a/chromium.org/d/msg/blink-dev/_1_ljYsaqrU/qOoHJ7MhAgAJ) Window Segments Enumeration API
- [Experiment](https://groups.google.com/a/chromium.org/d/msg/blink-dev/tFFemLT2xgQ/V35iIDJHAwAJ) Portals (same-origin, Android only)
- [Prototype](https://groups.google.com/a/chromium.org/d/msg/blink-dev/_aMJlxE8Jrw/UgoQSGZZAwAJ) altitude and azimuth angles for Pointer Events
- [Prototype](https://groups.google.com/a/chromium.org/d/msg/blink-dev/gK4XF2vbvf0/NeA28SQDBgAJ) App Icon Shortcuts Menu
- [Ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/aq1Zxc8D_uI/R_uNpPCWBQAJ) `navigator.getInstalledRelatedApps` API on Windows
- [Prototype](https://groups.google.com/a/chromium.org/d/msg/blink-dev/cper6nNLFRQ/hU91kfCWBQAJ) Window Controls Overlay for Installed Desktop Web Apps
- [Prototype](https://groups.google.com/a/chromium.org/d/msg/blink-dev/D6S8JRPYtDA/yZ7fYcQUBQAJ) CSS `text-decoration-thickness` and `text-underline-offset` properties, and `text-underline-position: from-font` value

March 2020

- [Ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/tOHolEkBeY8/jX0jvQqkBAAJ) CSS `revert` keyword
- [Ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/4QercWhVKP8/FnM5NkpnCgAJ) Web OTP API (requesting one-time-passwords)
- [Prototype](https://groups.google.com/a/chromium.org/d/msg/blink-dev/iwsT-jkCQcI/Rpt_hBFUBQAJ) CSS `lch()` and `lab()` functions (CIE LAB color functions)
- [Prototype](https://groups.google.com/a/chromium.org/d/msg/blink-dev/ByWuVBk1lFE/vAfiloyPBAAJ) CSS `page` property (named pages) and `page-orientation` descriptor
- [Prototype](https://groups.google.com/a/chromium.org/d/msg/blink-dev/pD4UW52y8Uk/CPWozoVmBAAJ) CSS `aspect-ratio` property
- [Experiment](https://groups.google.com/a/chromium.org/d/msg/blink-dev/FvRHynL2uwE/_jbRY6xkAgAJ) Native File System API (cont.)
- [Prototype](https://groups.google.com/a/chromium.org/d/msg/blink-dev/pb8sjXyFFg4/oH_XpCMxAQAJ) Font Access API (enumerate installed fonts and obtain table data)
- [Ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/uDn6a9fquCM/QmBxasoLAgAJ) Wake Lock API
- [Implement and ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/C5afPWCPXp8/5-uxJaSBAQAJ) (unprefixed) CSS `appearance` property
- [Implement and ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/2NKgeWa_kuQ/HACnp5OBAQAJ) CSS `-webkit-appearance: auto` value
- [Ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/Q0D5Lz6HwMU/7vBD4fM5AAAJ) WebXR DOM Overlay
- [Ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/qBQCKhzbIRc/RsfZQmf3AQAJ) `off` and `noscroll` values for the `<iframe scrolling>` attribute
- [Experiment](https://groups.google.com/a/chromium.org/d/msg/blink-dev/zxCKzulX424/Ac3zzMqqAQAJ) `performance.measureMemory` method

February 2020

- [Ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/cJ5dXIcQCsc/eGgi0gkcAAAJ) Cross-Origin Opener Policy (COOP)
- [Prototype](https://groups.google.com/a/chromium.org/d/msg/blink-dev/TNYIAu5E_M4/1i7LME9WCwAJ) Imperative Shadow DOM Distribution API
- [Ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/XBKAGb2_7uA/TDg_AkQbAAAJ) Cross-Origin Embedder Policy (COEP)
- [Prototype](https://groups.google.com/a/chromium.org/d/msg/blink-dev/x4Ev_l9Oj2U/6bGPs7MVCwAJ) URL Protocol Handler Registration for PWAs
- [Prototype](https://groups.google.com/a/chromium.org/d/msg/blink-dev/UHRmDD20FWE/sCmwI9oxGgAJ) Web Bluetooth `getDevices` method
- [Ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/dJibhmzE73o/jzB1zkJeCQAJ) CSS `:state()` pseudo-class
- [Prototype](https://groups.google.com/a/chromium.org/d/msg/blink-dev/D1sGl6UkCzs/bSiEw3rlCAAJ) Media Feeds API
- [Ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/P7Jpm9JW6q8/bhl3sT5bBgAJ) `durability` property for IndexedDB transactions (durability hint)
- [Ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/TzuPAx9ZOk0/HYOf3FFFBgAJ) `<iframe disallowdocumentaccess>` attribute
- [Ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/2uume_z0n8M/dUFRWmVNBgAJ) ARIA `suggestion`, `mark`, and `comment` roles and `aria-description` attribute (ARIA annotations)
- [Ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/Dbpth-n7LZo/vtyZAmMIBgAJ) CSS `contain-intrinsic-size` property
- [Prototype](https://groups.google.com/a/chromium.org/d/msg/blink-dev/oNJTem41LBs/CA4Nx05aAwAJ) CSS `prefers-reduced-data` media feature
- [Prototype](https://groups.google.com/a/chromium.org/d/msg/blink-dev/nJDc-1s3R9U/uCJKsEqpAwAJ) Declarative Shadow DOM
- [Prototype](https://groups.google.com/a/chromium.org/d/msg/blink-dev/KsPRO3hkOGw/md4jgIAaAgAJ) CSS `spanning` media feature and `fold-top`/`fold-left`/`fold-width`/`fold-height` environment variables
- [Implement and ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/QsgMjIyO8qA/RWWWukoaAgAJ) CSS `font-display: optional` without relayout
- [Prototype](https://groups.google.com/a/chromium.org/d/msg/blink-dev/FMPV2LCc0Ho/X4minYyAAQAJ) `rawValue` property for `<input>` elements
- [Experiment](https://groups.google.com/a/chromium.org/d/msg/blink-dev/31qZ-bMToM8/bLhpSdXhEgAJ) `scheduler.postTask` method for main-thread scheduling

January 2020

- [Implement and ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/GTPDv_MQbR0/fMjKxd5iDgAJ) `<input type="time">` with a reversed range (`min` > `max`)
- [Ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/DcuNrnEQo4k/etmmN3pYDgAJ) `requestAnimationFrame` method for `<video>` elements
- [Prototype](https://groups.google.com/a/chromium.org/d/msg/blink-dev/VU1zkDOL3bc/AU9FjKl2DQAJ) CSS `row-gap` and `column-gap` properties in Flexbox Layout
- [Ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/QyIz793UdGs/PgWUPO1PDQAJ) WebXR Hit Testing
- [Prototype](https://groups.google.com/a/chromium.org/d/msg/blink-dev/T6d2zqF_jpw/-ZmHBqlKDgAJ) mechanism for running PWAs on startup
- [Implement and ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/BXxS2U5EaN0/cSVmzxSmDQAJ) WebXR Augmented Reality (AR) Module
- [Prototype](https://groups.google.com/a/chromium.org/d/msg/blink-dev/0vuiPTvBGvQ/4faGCaqnDQAJ) Origin Isolation
- [Prototype](https://groups.google.com/a/chromium.org/d/msg/blink-dev/phH1_G6qI0o/2O4YR8RkCgAJ) Origin Policy
- [Ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/-_0REgUR-yY/f2ezL1tSCgAJ) CSS `color-scheme` property and `"color-scheme"` `<meta>` value
- [Ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/A4wxFpvqUfA/g7iccl9ICgAJ) HTTP `Sec-CH-UA-*` headers (Client Hints)
- [Deprecate and freeze](https://groups.google.com/a/chromium.org/d/msg/blink-dev/-2JIRNMWJ7s/yHe4tQNLCgAJ) HTTP `User-Agent` header value
- [Experiment](https://groups.google.com/a/chromium.org/d/msg/blink-dev/8bsAd-PsdbA/ZTcgiwf7CQAJ) Web NFC
- [Ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/fHc49JNFTAU/bJD25Yr7CAAJ) Badging API
- [Prototype](https://groups.google.com/a/chromium.org/d/msg/blink-dev/4BUSE2aTQEc/bNQv4jyTCQAJ) `timezonechange` event
- [Experiment](https://groups.google.com/a/chromium.org/d/msg/blink-dev/7HasvKUZm5c/7k3QehJBCAAJ) Native File System API (cont.)

December 2019

- [Prototype](https://groups.google.com/a/chromium.org/d/msg/blink-dev/rSavaKsqd0o/mqos8JyEAwAJ) Service Worker Scope Pattern Matching
- [Ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/KSJViFp3hMc/e-Yzd3_-AwAJ) Periodic Background Sync
- [Implement and ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/cX5ahS7nCFw/WHmxn8-uAwAJ) `buffered` option for Performance Observer
- [Implement and ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/AZO9T-eHy4E/nv4aQN9oAwAJ) `submitter` property for `submit` events
- [Ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/JmwpHPTu3XM/lel6vSEvBAAJ) Compression Streams

November 2019

- [Prototype and ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/_j6K_xSxWj0/fbn4kzx9AgAJ) Resize Observer `contentBoxSize`, `borderBoxSize`, and `devicePixelContentBoxSize` properties
- [Ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/gDLl4fKCr8Y/35aaeQ0fAgAJ) HTML `<a hreftranslate>` attribute
- [Ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/g_SYa13ZDPQ/gFZQVBTIAQAJ) HTTP `Sec-Fetch-Dest` request header
- [Ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/fgE0Ua9ZSU8/3XM9bU1LAgAJ) Media Playback Quality (`getVideoPlaybackQuality` method)
- [Ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/zv6k2X7Wr1M/AvQ76fYWAgAJ) CSS `ActiveText`, `Field`, and `FieldText` values (system color keywords)
- [Implement and ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/jPgnRoivOis/AmQfHDtEBgAJ) CSS `image-orientation` property
- [Experiment](https://groups.google.com/a/chromium.org/d/msg/blink-dev/AJpqos6iG5Y/7pGU2RRcBAAJ) Content Index API
- [Implement](https://groups.google.com/a/chromium.org/d/msg/blink-dev/Mjm4FzfxekY/YR8d2FdfBwAJ) `spatialNavigationSearch` method (part of CSS Spatial Navigation)
- [Experiment](https://groups.google.com/a/chromium.org/d/msg/blink-dev/F8fT0EhW9XA/v0ol03HPBgAJ) Contact Picker API (cont.)
- [Ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/wB7mDJqrUZ8/Ga2LMxdfBwAJ) `navigator.getInstalledRelatedApps` API
- [Ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/XKNtAVyO4AY/ujOrvaYsBwAJ) CSS `:focus-visible` pseudo-class
- [Implement](https://groups.google.com/a/chromium.org/d/msg/blink-dev/SFyBx9MrGRo/ucdX5HGWBQAJ) Window Placement
- [Ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/CQVTVOYx1XI/zSEBfVhKBQAJ) CSS `intrinsic-size` property

October 2019

- [Ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/BcWAX13du9w/wlp9E1YGEAAJ) default semantics for custom elements via the `ElementInternals` object
- [Ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/882iPcdnNQs/UP-PI8H2DwAJ) ARIA attribute reflection
- [Implement](https://groups.google.com/a/chromium.org/d/msg/blink-dev/_j4TT0laYRs/QorCYE3TDQAJ) `latencyHint` attribute for HTML media elements
- [Experiment](https://groups.google.com/a/chromium.org/d/msg/blink-dev/hxV0yjyS8_4/Fz4t4WseEQAJ) ARIA `annotation-attribution`, `annotation-commentary`, `annotation-presence`, `annotation-revision`, `annotation-suggestion` roles
- [Implement](https://groups.google.com/a/chromium.org/d/msg/blink-dev/3oVuczJ5Ty4/b8VLNNvyEAAJ) WebCodecs (access to built-in media encoders/decoders)
- [Ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/-apVTp8jBi0/x7kSszjUEAAJ) CSS `Canvas` and `Text` system color keywords
- [Implement](https://groups.google.com/a/chromium.org/d/msg/blink-dev/aBtuQUga1Tk/n4BLwof4DgAJ) `strict-origin-when-cross-origin` as new default for Referrer Policy
- [Implement](https://groups.google.com/a/chromium.org/d/msg/blink-dev/7B0ldtZR_68/GjLBu0n4DgAJ) Conversion Measurement API
- [Implement](https://groups.google.com/a/chromium.org/d/msg/blink-dev/OOZIrtSPLeM/QsTCnouFDgAJ) MathML Core
- [Experiment](https://groups.google.com/a/chromium.org/d/msg/blink-dev/AiGJihoCbl4/OmA24108DwAJ) Serial API
- [Implement](https://groups.google.com/a/chromium.org/d/msg/blink-dev/X9sF2uLe9rA/1aUxs8mnDgAJ) Trust Token API
- [Implement](https://groups.google.com/a/chromium.org/d/msg/blink-dev/CApU9QIu3TM/jCR5dyZFDAAJ) CSS `:state()` pseudo-class
- [Ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/zlLSxQ9BA8Y/uw9HcwIVDQAJ) Scroll To Text Fragment
- [Implement](https://groups.google.com/a/chromium.org/d/msg/blink-dev/rkGWbui8B9A/KLDR1ASCDAAJ) Raw Clipboard Access
- [Experiment](https://groups.google.com/a/chromium.org/d/msg/blink-dev/-6Cp2osHn50/VZhPCrXHDAAJ) HTML `rendersubtree` attribute and CSS `content-size` property
- [Ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/Il-wfnw9TAw/JRt5MTXHDAAJ) Trusted Types
- [Implement](https://groups.google.com/a/chromium.org/d/msg/blink-dev/LGPUCOCVQxs/IKVPne8wDQAJ) `requestAnimationFrame` method for `<video>` elements
- [Implement and ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/MVXTnyC_4bQ/ytY3XJq7CwAJ) CSS `@supports selector()` function
- [Ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/GePU9T8UpEc/bET6Mi60CgAJ) image/video aspect ratios from HTML `width` and `height` attributes
- [Implement](https://groups.google.com/a/chromium.org/d/msg/blink-dev/I6MS2kOKcx0/NAdg7Sc-CwAJ) QuicTransport API (part of the WebTransport framework)
- [Ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/CHCM_xALBG4/JeQQYkONBwAJ) WebXR Device API
- [Ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/Nvll21RaKwM/fTn8qUaNBwAJ) WebXR Gamepads Module
- [Implement and ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/GojYpoeDbqc/Ly-gpSrxCgAJ) string values for the CSS `list-style-type` property
- [Ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/8qesjfh0a80/xrruWrixBwAJ) CSS `line-break: anywhere` value
- [Implement and ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/CeGWh7l1Jq4/NeQXxZ4UCAAJ) CSS `overflow-wrap: anywhere` value

September 2019

- [Implement](https://groups.google.com/a/chromium.org/d/msg/blink-dev/U3kH6_98BuY/uiaeS3D2AwAJ) percent-based scrolling
- [Implement](https://groups.google.com/a/chromium.org/d/msg/blink-dev/pZq73q_Mc-c/chp8ssUKBgAJ) “heavy ad” intervention
- [Implement](https://groups.google.com/a/chromium.org/d/msg/blink-dev/wdWtyA1gyvI/37hqCDu5BgAJ) ARIA roles for annotation purposes
- [Implement and ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/Y3lhEykjfV0/FKa0H8zwDQAJ) CSS `font-optical-sizing` property
- [Implement](https://groups.google.com/a/chromium.org/d/msg/blink-dev/Bh0bSdkQlbk/7n6b50N6AwAJ) HTML `rendersubtree` attribute
- [Implement](https://groups.google.com/a/chromium.org/d/msg/blink-dev/LDymWZeV7jo/DCcYyBYtAwAJ) Screen Enumeration (`navigator.screen.requestDisplays` method)
- [Ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/XI1otbsuvMw/X_65dN7qAgAJ) auto-upgrade mixed audio and video content (`http:` to `https:`)
- [Implement](https://groups.google.com/a/chromium.org/d/msg/blink-dev/XQEO617FMhA/LShCefAgAgAJ) navigation to Bundled HTTP Exchanges (Web Packaging)
- [Implement](https://groups.google.com/a/chromium.org/d/msg/blink-dev/b5vXvm1bP3s/BDBx92QxAwAJ) CSS `navigation-controls` media feature
- [Experiment](https://groups.google.com/a/chromium.org/d/msg/blink-dev/nrDKOvVl_I4/N9T_Mpu9AgAJ) Wake Lock API
- [Experiment](https://groups.google.com/a/chromium.org/d/msg/blink-dev/-bdqHhCyBwM/yFoKtQQRAQAJ) SMS Receiver API
- [Implement](https://groups.google.com/a/chromium.org/d/msg/blink-dev/OHqvPx9mFww/ikcYp9K_DwAJ) `EditContext` API
- [Implement](https://groups.google.com/a/chromium.org/d/msg/blink-dev/hbhKRuBzZ4o/pmehGGHKAAAJ) image/video aspect ratios from HTML `width` and `height` attributes
- [Experiment](https://groups.google.com/a/chromium.org/d/msg/blink-dev/5dCim99q5hM/-qGaZpUEAQAJ) Notification Triggers (show notifications when certain conditions are met)
- [Implement and ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/g8MP8KUf96w/360rLewrDwAJ) `autofocus` attribute on any focusable HTML/SVG element
- [Experiment](https://groups.google.com/a/chromium.org/d/msg/blink-dev/noan0cgEBGQ/t8DuK8_hDwAJ) Native File System API
- [Implement](https://groups.google.com/a/chromium.org/d/msg/blink-dev/aDDJXM8TZnk/xdhSlY-ZDwAJ) `relaxedDurability` option for the IndexedDB `transaction` method (controls flushing to disk)

August 2019

- [Implement](https://groups.google.com/a/chromium.org/d/msg/blink-dev/brAJpwPoix8/FDmDG9VfDgAJ) `navigator.scheduling.isFramePending` method
- [Implement](https://groups.google.com/a/chromium.org/d/msg/blink-dev/9gaUKa3QmmE/z_Ef9Xr_DQAJ) `CompressStream` and `DecompressStream` APIs
- [Experiment](https://groups.google.com/a/chromium.org/d/msg/blink-dev/_NfpCRzST-k/XVYPHCxPAwAJ) WebXR Device API (cont.)
- [Implement](https://groups.google.com/a/chromium.org/d/msg/blink-dev/RMCpsWaqds0/_H9hTQ5tAgAJ) CSS `content-size` property
- [Implement and ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/rebS5clSnIg/U0Nze97LAQAJ) inline styles in WebVTT files
- [Implement](https://groups.google.com/a/chromium.org/d/msg/blink-dev/XfkSdpMWNik/IX67fOTLAQAJ) Font Enumeration API
- [Experiment](https://groups.google.com/a/chromium.org/d/msg/blink-dev/TGe5hYfJZU4/1mFm4a5AAgAJ) Badging API V2 (different badges depending on URL scope)
- [Experiment](https://groups.google.com/a/chromium.org/d/msg/blink-dev/GP0OlwtC1EQ/7Q8P3v8nAgAJ) JS Self-Profiling API
- [Implement](https://groups.google.com/a/chromium.org/d/msg/blink-dev/pWxNRxNcxFE/cjjqFse5AQAJ) Element Reflection (“allow specifying semantic relationships between elements without the need to assign globally unique ID attributes”)
- [Implement](https://groups.google.com/a/chromium.org/d/msg/blink-dev/-8wPGNpuV2Y/C5wdLebLAQAJ) API for accessing TrueType/OpenType font tables
- [Implement](https://groups.google.com/a/chromium.org/d/msg/blink-dev/Biu2XfAls5A/tJFlkdE0AgAJ) Document Policy
- [Deprecate and remove](https://groups.google.com/a/chromium.org/d/msg/blink-dev/6KhRNH3PrvU/Xz6YyNXbAQAJ) non-`Secure` cookies in third-party contexts
- [Implement and ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/NB6BMfcyKok/26LODCniAQAJ) WebAuthn in cross-origin iframes
- [Implement](https://groups.google.com/a/chromium.org/d/msg/blink-dev/vCrJCQxNnzo/OAYI9cPWAQAJ) CSS Modules V1
- [Implement](https://groups.google.com/a/chromium.org/d/msg/blink-dev/EAj0HR-jIWI/wiZx2NmqBwAJ) WebXR Anchors
- [Implement](https://groups.google.com/a/chromium.org/d/msg/blink-dev/b-cGz9c67pM/0zvBzjhrAAAJ) default accessibility semantics for custom elements
- [Experiment](https://groups.google.com/a/chromium.org/d/msg/blink-dev/aHdERJoKYh8/o3IysK5PFQAJ) Periodic Background Sync
- [Deprecate and remove](https://groups.google.com/a/chromium.org/d/msg/blink-dev/PoC7ShITSJI/-mrg7qQRBQAJ) Shadow DOM v0, Custom Elements v0, and HTML Imports (cont.)s

July 2019

- [Implement](https://groups.google.com/a/chromium.org/d/msg/blink-dev/HvqbB7TGJKU/xda9kTXGBAAJ) `scheduler.postTask` method for main-thread scheduling
- [Implement](https://groups.google.com/a/chromium.org/d/msg/blink-dev/Cibo-GNPs7Y/RznlX7WKDAAJ) Feature Policy `document-access` policy
- [Experiment](https://groups.google.com/a/chromium.org/d/msg/blink-dev/0Bw-JW1POdw/ru7xMH2vCwAJ) `navigator.scheduling.isInputPending` method (early detection of input events)
- [Implement](https://groups.google.com/a/chromium.org/d/msg/blink-dev/e5fu5Q06ntA/UUqPuA8hEQAJ) Storage Access API
- [Ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/j-PLtssE5fo/budv_U6fCwAJ) Barcode Detection API (part of Shape Detection API)
- [Ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/bI7qfrSQBZY/RgzD9zMrBAAJ) Layout Instability API
- [Implement](https://groups.google.com/a/chromium.org/d/msg/blink-dev/ojwkySW-bpQ/ecR5pnocAgAJ) JSON Modules
- [Implement and ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/YMrf4l2DqtM/B8FB2axQAQAJ) `buffered` option for `PerformanceObserver` `observe` method
- [Experiment](https://groups.google.com/a/chromium.org/d/msg/blink-dev/JVQ34vvuApE/RC2wl0hOAgAJ) Trusted Types (cont.)
- [Experiment](https://groups.google.com/a/chromium.org/d/msg/blink-dev/M3ZMGLo362Y/oCUiqQrAAQAJ) `navigator.getInstalledRelatedApps` API (cont.)
- [Ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/DXSoS7dMmok/30ColVMUAQAJ) Element Timing
- [Ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/S36p6Y16u5c/tCz9124UAQAJ) Largest Contentful Paint (LCP) page-load metric

June 2019

- [Implement and ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/V86fOkIaEQA/7bbQ4rP8AgAJ) CSS `overscroll-behavior-inline` and `overscroll-behavior-block` properties
- [Experiment](https://groups.google.com/a/chromium.org/d/msg/blink-dev/NySZyk6UMEs/XGquAepZAwAJ) Scroll To Text Fragment
- [Ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/nC5p6W8nM3g/Bk6GOoaYAwAJ) alternative text for the CSS `content` property
- [Implement and ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/7FaMtRBfTBU/-Sm3s-gFAwAJ) CSS `min()`, `max()` and `clamp()` functions
- [Ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/aRKT0BkrF-8/G-KuTnMBBgAJ) Animation Worklet
- [Experiment](https://groups.google.com/a/chromium.org/d/msg/blink-dev/PyYXyqBI3fk/2SBwjUPkBgAJ) Feature Policy Reporting (cont.)
- [Implement and ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/F0IiHq9EHyc/F4qC3QCQCwAJ) `integrity` attribute on `<link rel="preload">` elements
- [Implement and ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/ucEUTqoi4Nc/wx3q-B7tAQAJ) CSS `font-size: xxx-large` value
- [Implement](https://groups.google.com/a/chromium.org/d/msg/blink-dev/Gl7FIKM5IFw/tA70X9ZIBQAJ) `<std-toast>` element (toast notification)
- [Implement](https://groups.google.com/a/chromium.org/d/msg/blink-dev/qERxZjYu6SE/JGd_lkyXBQAJ) Content Indexing
- [Implement](https://groups.google.com/a/chromium.org/d/msg/blink-dev/qoJkuLOMKqI/I3DGDTCRBQAJ) CSS `@property` at-rule
- [Implement](https://groups.google.com/a/chromium.org/d/msg/blink-dev/cdUOyBAtWzo/MRmGAURjBQAJ) JavaScript Memory API (`performance.measureMemory` method)
- [Implement](https://groups.google.com/a/chromium.org/d/msg/blink-dev/kP556piqDR8/XHuly9HMAwAJ) `<std-switch>` element (toggle switch control)
- [Implement and ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/093IZbeZ6RA/PdhQFP6NAgAJ) Web Bluetooth `getAvailability` method

May 2019

- [Implement](https://groups.google.com/a/chromium.org/d/msg/blink-dev/u65DesVOzmY/htUnPfFcBgAJ) `jump-start`, `jump-end`, `jump-none`, and `jump-both` keywords for the CSS `steps()` easing function
- [Implement](https://groups.google.com/a/chromium.org/d/msg/blink-dev/RN0PfhoxdHI/ASzdxxoMBgAJ) HTTP `Cross-Origin-Opener-Policy` response header
- [Implement](https://groups.google.com/a/chromium.org/d/msg/blink-dev/WVqgYtyaGJk/q-TGbeExBgAJ) Largest Contentful Paint (LCP) metric
- [Implement and ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/AknSSyQTGYs/SSB1rTEkBgAJ) changes to cookies (add `SameSite=Lax` by default)
- [Ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/pnUiTrLHHmw/CDN1s3F1BQAJ) Feature Policy `focus-without-user-activation` policy
- [Experiment](https://groups.google.com/a/chromium.org/d/msg/blink-dev/hqhrB2BIIr0/q7TfR2I1BgAJ) `lowLatency` option for `'2d'` and `'webgl'` canvas contexts (cont.)
- [Implement](https://groups.google.com/a/chromium.org/d/msg/blink-dev/xXVJlqlDL_k/pxwluzwSAwAJ) CSS `color-scheme` property
- [Implement and ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/Hfe5xktjSV8/Re-SMF3wAwAJ) `enterkeyhint` attribute
- [Ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/ufFQ4OvtqxQ/Ib0n6M5nAwAJ) `ImageBitmap` rendering context for `OffscreenCanvas`
- [Ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/0w_Z-9_kSNs/QV6ChIapAwAJ) form-associated custom elements
- [Ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/ONvzLM5fPvk/FZDswIOpAwAJ) `'formdata'` event type
- [Implement and ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/CxelaeahNho/aC6Zp8KvAwAJ) `HTMLFormElement` `requestSubmit` method
- [Experiment](https://groups.google.com/a/chromium.org/d/msg/blink-dev/nlMUxXEqMgg/fmiVVcKqAwAJ) WebXR Device API (cont.)
- [Implement and ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/bkUwigYHJDM/Bzvm8tkHAgAJ) CSS `scroll-snap-stop` property
- [Implement](https://groups.google.com/a/chromium.org/d/msg/blink-dev/hVszlf4l2_E/1K_ZgQ4lBQAJ) Bundled HTTP Exchanges
- [Ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/mUW58VMIrTM/gIotA4HwBAAJ) `pointerrawmove` event type
- [Experiment](https://groups.google.com/a/chromium.org/d/msg/blink-dev/VqoLPVSXE4g/7N5veAaeBAAJ) Badging API (cont.)
- [Implement and ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/Gstf0GA7cbg/711ymCKKAAAJ) `Animation` `pending` property
- [Ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/sLK1cLgvieg/8bvIdznFAAAJ) CSS `prefers-color-scheme` media feature

April 2019

- [Ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/_-WBHYZ-rBk/yltzslk4DQAJ) `IDBTransaction` `commit` method
- [Implement](https://groups.google.com/a/chromium.org/d/msg/blink-dev/VytOh5dHdDo/THj8cgZeDQAJ) Feature Policy `execution-while-out-of-viewport` and `execution-while-not-rendered` features (enables freezing hidden iframes)
- [Implement](https://groups.google.com/a/chromium.org/d/msg/blink-dev/61yC4_xbZRA/mpB5rMBTDwAJ) Periodic Background Sync
- [Implement](https://groups.google.com/a/chromium.org/d/msg/blink-dev/cl_WCx9OEcg/9b-6_7DPDAAJ) JS Self-Profiling API
- [Implement](https://groups.google.com/a/chromium.org/d/msg/blink-dev/uK0hyACy_fg/XXFsm_4kDAAJ) Picture-in-Picture for arbitrary content
- [Experiment](https://groups.google.com/a/chromium.org/d/msg/blink-dev/LpE_bzcSv5Y/mLEg7wMLDAAJ) `<a hrefTranslate>` attribute (cont.)
- [Experiment](https://groups.google.com/a/chromium.org/d/msg/blink-dev/WwszZpavn6U/x9pyllbZCQAJ) Event Timing API (cont.)
- [Ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/66BSOtd7jYc/md5JrQsSCgAJ) CSS `white-space: break-spaces` value
- [Experiment](https://groups.google.com/a/chromium.org/d/msg/blink-dev/oRp0lYze0oA/nsB1TGUaCwAJ) HTML `importance` attribute (Priority Hints) (cont.)
- [Ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/lq83adC8QRo/Vcr9NfGpCgAJ) Storage Quota Usage Details
- [Implement](https://groups.google.com/a/chromium.org/d/msg/blink-dev/Drmmb_t4eE8/z_k9l09gCgAJ) SMS OTP Retriever API
- [Ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/TssvWe8TzBc/ewO5G9TCCAAJ) image support for the Async Clipboard API
- [Implement and ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/-lgbwMK0O5M/P7kABDjeCAAJ) `Blob` `text`, `arrayBuffer`, and `stream` methods
- [Implement](https://groups.google.com/a/chromium.org/d/msg/blink-dev/GzllP8DToqw/evfBnu58BQAJ) Gamepad light indicator extension
- [Ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/yQgJlq5PEOQ/erexYRWHBgAJ) HTTP `Sec-Fetch-Mode`, `Sec-Fetch-Site`, and `Sec-Fetch-User` request headers
- [Ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/CWN34Qo8icI/cpHrV7GPBgAJ) arbitrary timestamps and metadata in User Timing
- [Ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/UMxgGkxhdCo/CHZ2H9DsBgAJ) `Animation` constructor (Web Animations)

March 2019

- [Ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/gETVpeiayNE/H7_YDB61BQAJ) Web Share Target Level 2 (adds support for files)
- [Implement](https://groups.google.com/a/chromium.org/d/msg/blink-dev/ZEEwLuKlmcw/Nrj2wFkJAwAJ) Native Caret Browsing
- [Implement and ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/X-qPSmdSR_g/Yd0xweofBgAJ) CSS `:picture-in-picture` pseudo-class
- [Implement and ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/IKe_SAgdNAA/NCTyawqYAwAJ) SVG favicons (`<link rel="icon">`)
- [Ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/nxjWgMIeC1Q/LyC1sle2BQAJ) `desynchronized` option for 2D canvas context (was `lowLatency`)
- [Implement](https://groups.google.com/a/chromium.org/d/msg/blink-dev/9B7OHgwwEzs/jnmdgx_7DAAJ) Element Timing for text
- [Ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/rZOaOONFCNI/4IZTJBYMCAAJ) Feature Policy `document-domain` feature
- [Implement and ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/0TJyePKiegs/24w8YsCQCAAJ) HTML `<video playsinline>` attribute
- [Implement](https://groups.google.com/a/chromium.org/d/msg/blink-dev/p0nHeY_ZSEg/-leLPafWCQAJ) CSS `outline-color: invert` value
- [Implement and ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/GRl1_Qy97jM/h7v1qIDsBwAJ) CSS `backdrop-filter` property
- [Implement](https://groups.google.com/a/chromium.org/d/msg/blink-dev/xnoMlEorXxw/mZisL9zqBwAJ) alternative text for the CSS `content` property
- [Experiment](https://groups.google.com/a/chromium.org/d/msg/blink-dev/sEwWEF80T4s/Nss9VxM3BAAJ) KV Storage + import maps
- [Ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/-iAATJCpcNY/o6Kb_ktrBQAJ) Background Fetch
- [Implement](https://groups.google.com/a/chromium.org/d/msg/blink-dev/r7PkIqQDvlU/X0aocVo9BQAJ) CSS `line-break: anywhere` value

February 2019

- [Implement](https://groups.google.com/a/chromium.org/d/msg/blink-dev/NcLn2-BpBd0/ItPPTEZPBAAJ) image support for the Async Clipboard API
- [Implement and experiment](https://groups.google.com/a/chromium.org/d/msg/blink-dev/d5f7djVL5H0/7HX9Dl5ABAAJ) Feature Policy `unoptimized-images` and `oversized-images` features
- [Ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/bHo6cy9qKuw/6xqZt_1LAAAJ) Signed Exchange Reporting for distributors
- [Ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/emvtXAXtqWs/ohZ_ZkYSEAAJ) `PointerEvent` `getPredictedEvents` method
- [Implement](https://groups.google.com/a/chromium.org/d/msg/blink-dev/sFb2H2pwEug/rKue2Dy_DwAJ) Notification Triggers (show notifications when certain conditions are met)
- [Implement](https://groups.google.com/a/chromium.org/d/msg/blink-dev/qYeQFqgFOyA/rXJapjMaEAAJ) import maps (`<script type="importmap">`)
- [Implement](https://groups.google.com/a/chromium.org/d/msg/blink-dev/ZcJNEfRFbj0/kl42H12-GAAJ) Signed Exchange Reporting for distributors
- [Experiment](https://groups.google.com/a/chromium.org/d/msg/blink-dev/1Tqsa-0I04E/wXKUtUiqGAAJ) Event Timing API (cont.)

January 2019

- [Implement and ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/L5J1DUzfQIw/3SSWuKkaDAAJ) CSS transition events (`transitionrun`, `transitionstart`, and `transitioncancel`)
- [Experiment](https://groups.google.com/a/chromium.org/d/msg/blink-dev/eFZ3h_A3VTY/NuXabBbQDQAJ) HTML `<video autoPictureInPicture>` attribute
- [Implement](https://groups.google.com/a/chromium.org/d/msg/blink-dev/8NsJruvDJIw/xgtAfWJoDAAJ) HTML `<meta name="supported-color-schemes">` element
- [Ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/g-pdQdSR0HI/LY6lcGKOCgAJ) Intersection Observer V2
- [Implement and ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/TBNHorRPhZk/4_gfRjfzDgAJ) HTTP `Cross-Origin-Resource-Policy` header
- [Implement](https://groups.google.com/a/chromium.org/d/msg/blink-dev/WQ0eC_Gf8bw/dhWMhCYYDwAJ) HTTP `Sec-CH-UA-*` headers (Client Hints)
- [Experiment](https://groups.google.com/a/chromium.org/d/msg/blink-dev/jpeSdM897Xw/CY6tothSDgAJ) HTML `importance` attribute (Priority Hints)
- [Experiment](https://groups.google.com/a/chromium.org/d/msg/blink-dev/GBgoS_eCmzM/Ot7ePqCbCgAJ) Web Contact API
- [Implement](https://groups.google.com/a/chromium.org/d/msg/blink-dev/vN-5SjwHPus/saJY6qwXDwAJ) HTTP `Sec-CH-Lang` header (Client Hints)
- [Experiment](https://groups.google.com/a/chromium.org/d/msg/blink-dev/hi1RKJcdplo/T_BvnpHhDgAJ) `navigator.getInstalledRelatedApps` API
- [Implement and ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/Y3lhEykjfV0/FKa0H8zwDQAJ) CSS `font-optical-sizing` property
- [Ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/gPH_BcOBEtc/Z41GR0mwEQAJ) Signed HTTP Exchanges (SXG)
- [Implement](https://groups.google.com/a/chromium.org/d/msg/blink-dev/AiKgWvv3cq0/xAsjfSfMDQAJ) file sharing in Web Share API
- [Implement](https://groups.google.com/a/chromium.org/d/msg/blink-dev/ewfRSdqcOd8/w_Fr6rJ3DQAJ) HTML Modules
- [Experiment](https://groups.google.com/a/chromium.org/d/msg/blink-dev/9LV2L8sDgPY/5-PSyCOkBwAJ) `<img elementtiming>` attribute
- [Experiment](https://groups.google.com/a/chromium.org/d/msg/blink-dev/2aHJE8YNXE0/9oo5x3s2EQAJ) Feature Policy Reporting
- [Experiment](https://groups.google.com/a/chromium.org/d/msg/blink-dev/QRK6RbAwsb4/L6s-XUAvEQAJ) `'layoutjank'` performance entries
- [Experiment](https://groups.google.com/a/chromium.org/d/msg/blink-dev/sJ4lxamz2V0/YSRPP3SwBgAJ) Event Timing API (cont.)
- [Experiment](https://groups.google.com/a/chromium.org/d/msg/blink-dev/I9To21DXcLo/NrU9P0M4EAAJ) Trusted Types for DOM Manipulation
- [Ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/07CbItWfA4M/CG1qF8IoEAAJ) `imagesrcset` and `imagesizes` attributes for the `<link>` element (selectively preloading images)
- [Implement and ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/NZ3c9d4ivA8/BIHFbOj6DAAJ) CSS `prefers-reduced-motion` media feature
- [Implement](https://groups.google.com/a/chromium.org/d/msg/blink-dev/Muw0N43ntSw/WZZZI7w7DQAJ) CSS `prefers-color-scheme` media feature

December 2018

- [Implement and ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/qwLRSNFsfUQ/ZhxYYusjCAAJ) `document.featurePolicy` API (for policy introspection)
- [Implement](https://groups.google.com/a/chromium.org/d/msg/blink-dev/aVxGkVQ2xRk/iYw0yIB4CQAJ) Web Bluetooth Scanning
- [Implement](https://groups.google.com/a/chromium.org/d/msg/blink-dev/8V4ixKVmNY4/vJQdo9GCBgAJ) scroll-linked animations (only JavaScript part)
- [Ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/rspPrQHfFkI/rrhGyO4DBwAJ) `stale-while-revalidate` `Cache-control` extension
- [Ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/DAmfw08GGis/-0OyBbTmBgAJ) CSS `::part` pseudo-element (CSS Shadow Parts)
- [Ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/gL2EVBzO5og/YfId9-vqBAAJ) Constructable Stylesheet Objects
- [Experiment](https://groups.google.com/a/chromium.org/forum/#!topic/blink-dev/gJB_mlA6joQ) Signed HTTP Exchanges (cont.)
- [Experiment](https://groups.google.com/a/chromium.org/d/msg/blink-dev/9yCtIXtw_Qw/PA2bXNQOBwAJ) `lowLatency` option for `'2d'` and `'webgl'` canvas contexts (cont.)
- [Ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/pc5Jx9qcEJo/JyFBJTbXBQAJ) `GamepadButton` `touched` property
- [Experiment](https://groups.google.com/a/chromium.org/d/msg/blink-dev/KEUnHsvulEU/tMzKbzHxBQAJ) Badging API
- [Implement and ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/XZU_DhQ9ZGs/whPNC357BQAJ) `PerformanceObserver.supportedEntryTypes` property

November 2018

- [Experiment](https://groups.google.com/a/chromium.org/d/msg/blink-dev/vWg9cs2t648/QaGw3B3cAAAJ) Web XR Device API (cont.)
- [Ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/LN92hkaKCzw/Y-ryVxu5AgAJ) First Input Timing
- [Implement](https://groups.google.com/a/chromium.org/d/msg/blink-dev/CwAwSbTUmeg/27O5K12iBgAJ) Storage Quota Usage Details
- [Experiment](https://groups.google.com/a/chromium.org/d/msg/blink-dev/4DZIDt9o1ME/L4878LGOBwAJ) `<a hrefTranslate>` attribute
- [Implement](https://groups.google.com/a/chromium.org/d/msg/blink-dev/OuwzBmH02M4/5ChXdXZQBwAJ) User Idle Detection
- [Implement](https://groups.google.com/a/chromium.org/d/msg/blink-dev/HW8j_JLLiPo/V_SmVZkwBgAJ) form-associated custom elements
- [Implement](https://groups.google.com/a/chromium.org/d/msg/blink-dev/brKChSa9_d0/GmzVbvYcAAAJ) Contacts API
- [Implement](https://groups.google.com/a/chromium.org/d/msg/blink-dev/Ff6Ywg5vnh4/VbDH4X6wBQAJ) Feature Policy `document-domain` feature
- [Ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/_TllF9146H0/PgI3cqEMBAAJ) `Intl.ListFormat` API
- [Ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/ryK8SHcBzZw/2cjTF_OCBwAJ) crash reports (Reporting API)
- [Ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/Fku6784p0wI/3MyOMTk7BwAJ) keyboard-focusable scroll containers
- [Ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/xSf7B0aVxnI/0E05ZEB6DAAJ) an API for enumerating IndexedDB databases
- [Ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/QjcyhPZ_sNI/SuB-GuNPDAAJ) CSS Properties and Values API Level 1 (subset)

October 2018

- [Implement](https://groups.google.com/a/chromium.org/d/msg/blink-dev/WS17dXHV6xQ/rOnUbU4CCgAJ) `FetchEvent` Worker Timing (measuring the performance of service workers)
- [Implement](https://groups.google.com/a/chromium.org/d/msg/blink-dev/ulyuFI9aMig/zCegnl22CQAJ) an explicit API for commiting IndexedDB transactions
- [Ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/QILBb4Oqb-k/tvdXEy7dBwAJ) `colorSpace` and `pixelFormat` options for canvas contexts (canvas color management)
- [Implement](https://groups.google.com/a/chromium.org/d/msg/blink-dev/C6taiCkYayU/hlKC-v0GCQAJ) CSS `font-display` descriptor for `@font-feature-values` (setting the default `font-display` value for a font family)
- [Experiment](https://groups.google.com/a/chromium.org/d/msg/blink-dev/jWBA5ooXNIU/TQ7ULG8cBwAJ) `lowLatency` option for `'2d'` and `'webgl'` canvas contexts
- [Experiment](https://groups.google.com/a/chromium.org/d/msg/blink-dev/mGkwLYpHOxM/rvpxhsYUBAAJ) Event Timing API (cont.)
- [Implement](https://groups.google.com/a/chromium.org/d/msg/blink-dev/jF1-M8KWAMU/ubGV4Fx2BgAJ) `'layoutjank'` performance entry (Performance API)
- [Ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/eKS6bOz9a_o/bSAKi3RdBAAJ) `navigator.getDisplayMedia` method (Screen Capture)
- [Ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/gYrR2nR6quI/gngoL0HLAwAJ) spec-compliant specificity for CSS Scoping selectors (`:host()`, etc.)
- [Experiment](https://groups.google.com/a/chromium.org/d/msg/blink-dev/z5WX-2RMulo/JQqeF3XZAgAJ) Background Fetch

September 2018

- [Implement](https://groups.google.com/a/chromium.org/d/msg/blink-dev/OaDCpCaEe_4/3taK3m75DAAJ) WebHID
- [Experiment](https://groups.google.com/a/chromium.org/d/msg/blink-dev/MKHe54W996c/1E51GLbvAQAJ) Signed HTTP Exchanges
- [Implement](https://groups.google.com/a/chromium.org/d/msg/blink-dev/cMoPvrdcF0E/bt2Uwsn8BgAJ) Gamepad API touchpad extension
- [Implement](https://groups.google.com/a/chromium.org/d/msg/blink-dev/rbqI2wiszyY/RzIx7aIFCQAJ) crash reports (Reporting API)
- [Implement](https://groups.google.com/a/chromium.org/d/msg/blink-dev/CgFyxYikn6A/viBXhqRSBgAJ) `PointerEvent` `getPredictedEvents` method
- [Implement](https://groups.google.com/a/chromium.org/d/msg/blink-dev/qKjn0tLMezI/TCix0GI0CgAJ) IndexedDB database enumeration API
- [Implement](https://groups.google.com/a/chromium.org/d/msg/blink-dev/GcqEnSW5yHs/r7G3iMmDCQAJ) Serial API
- [Implement](https://groups.google.com/a/chromium.org/d/msg/blink-dev/ljkPttdvVuc/atNE2qYSCAAJ) `navigator.isProtocolHandlerRegistered` method
- [Ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/eYCm_qnf9BA/zZvhlGXXBwAJ) CSP `report-to` directive
- [Implement](https://groups.google.com/a/chromium.org/d/msg/blink-dev/2Yo590-USNo/7Da9scWwBwAJ) Display Locking
- [Implement](https://groups.google.com/a/chromium.org/d/msg/blink-dev/2twP4Xdd1VI/yFE1pbwVBgAJ) Element Timing for images (incl. `<img elementtiming>` attribute)
- [Ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/vTnSjFcPwNc/kkTX92hpBgAJ) User Activation API
- [Ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/jx2joIL5SbU/pGuwgvi7EAAJ) `TextEncoderStream` and `TextDecoderStream` APIs
- [Implement and ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/uauMQQQ7fAI/UAY5FX9UBgAJ) CSP `script-src-attr`, `script-src-elem`, `style-src-attr`, and `style-src-elem` directives
- [Implement and ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/LGCEO53Mb6A/9oc4olniBQAJ) `queueMicrotask` function
- [Experiment](https://groups.google.com/a/chromium.org/d/msg/blink-dev/QdjD9onSDFU/TPL9NPPrEAAJ) WebXR Device API (cont.)

August 2018

- [Ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/ODzbWn-xRrQ/dhkJzD8-CgAJ) `prefersNavigationBar` option for Fullscreen API
- [Ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/PPuewynNpaE/4rP9YAMPCgAJ) Permission Delegation
- [Implement](https://groups.google.com/a/chromium.org/d/msg/blink-dev/84RGJvm_PMM/bYh0Ehv1DgAJ) `pointerrawmove` event type
- [Implement](https://groups.google.com/a/chromium.org/d/msg/blink-dev/-xagQ4UJawY/6NonQwt_CAAJ) an API to measure the memory footprint of the website
- [Implement](https://groups.google.com/a/chromium.org/d/msg/blink-dev/mAwFEMP6JDQ/sTobLh4HDQAJ) HTML `intrinsicsize` attribute (for images and videos)
- [Remove](https://groups.google.com/a/chromium.org/d/msg/blink-dev/18r3whCBv0I/b8qrtFTsDAAJ) Budget API
- [Implement](https://groups.google.com/a/chromium.org/d/msg/blink-dev/nRNPNwlRS6E/iLB-b5H6DAAJ) Feature Policy `animations` feature
- [Implement](https://groups.google.com/a/chromium.org/d/msg/blink-dev/5-3woY4Y1Qg/xHDTmUFAEAAJ) Feature Policy violation reports (`'feature-policy-violation'` report type)
- [Implement](https://groups.google.com/a/chromium.org/d/msg/blink-dev/Icw_sU6PqVA/8hwXw0jTDwAJ) searchable invisible DOM
- [Implement and ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/HgDaX3qW0IY/AYg6t_oaDwAJ) TLS 1.3
- [Implement](https://groups.google.com/a/chromium.org/d/msg/blink-dev/hmASm1yhi5s/7vqmt7CwDgAJ) HTML `<a hreftranslate>` attribute
- [Implement](https://groups.google.com/a/chromium.org/d/msg/blink-dev/U4rXcm5CE4Y/3XmVtoAPDwAJ) Writable Files
- [Implement](https://groups.google.com/a/chromium.org/d/msg/blink-dev/yCGhf7EA1Zs/70_NL0AEDwAJ) Feature Policy `lazyload` feature
- [Implement](https://groups.google.com/a/chromium.org/d/msg/blink-dev/IVjeSC9tk64/u1kIxBFiBQAJ) Shadow DOM imperative distributed API
- [Ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/7MCjXU3zmCQ/ZSDsTaMuBQAJ) WebSockets over HTTP/2
- [Deprecate and remove](https://groups.google.com/a/chromium.org/d/msg/blink-dev/h-JwMiPUnuU/sl79aLoLBQAJ) Shadow DOM v0, Custom Elements v0, and HTML Imports

July 2018

- [Implement](https://groups.google.com/a/chromium.org/d/msg/blink-dev/WLuXgLp2WWY/WvzMRIjdAgAJ) iframe sandboxing features as Feature Policy features
- [Implement](https://groups.google.com/a/chromium.org/d/msg/blink-dev/Fw764MVF5nI/FNlBi815AwAJ) Badging API
- [Implement](https://groups.google.com/a/chromium.org/d/msg/blink-dev/SgsbpO08AeI/ZyDL6r5FBgAJ) HTML `<portal>` element for seamless navigations between sites or pages
- [Experiment](https://groups.google.com/a/chromium.org/d/msg/blink-dev/pQZopKWaQIk/Z-XD1hvwBQAJ) Feature Policy API (`document.policy`)
- [Implement and ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/-CYu9jVflMw/-_IVvtODBQAJ) `queueMicrotask` function
- [Implement](https://groups.google.com/a/chromium.org/d/msg/blink-dev/xACYBou4f9A/Ft0-QlFMAQAJ) options argument for the `postMessage` method
- [Experiment](https://groups.google.com/a/chromium.org/d/msg/blink-dev/dgmf_goI_S0/YyVOB2lQAQAJ) Web Locks API (cont.)
- [Implement](https://groups.google.com/a/chromium.org/d/msg/blink-dev/b7f_K30MBYo/T9iXfP4fBgAJ) Feature Policy `sync-script` feature (for disabling parser-blocking script execution)
- [Ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/sQrAZpTA8WI/EWC7W6GOCwAJ) intervention reports
- [Experiment](https://groups.google.com/a/chromium.org/d/msg/blink-dev/k0jK4JIhiYk/tKePgtllBgAJ) `stale-while-revalidate` directive for HTTP `Cache-Control` header
- [Implement and ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/gXXMY1grZ-o/b0y3ENIaCQAJ) `left` and `right` values for the CSS `text-underline-position` property

June 2018

- [Implement](https://groups.google.com/a/chromium.org/d/msg/blink-dev/9cfRxXx5Cis/XRm0wHaNCAAJ) `gamepadbuttondown`, `gamepadbuttonup`, `gamepadbuttonchange`, and `gamepadaxismove` events
- [Ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/e2fg_-Ha-AE/nheenHnXBgAJ) Web Locks API
- [Implement and ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/mAWBTaANvmE/OgaCRH04BAAJ) DOM `Element` `toggleAttribute` method
- [Experiment](https://groups.google.com/a/chromium.org/d/msg/blink-dev/pdxkBoURmaA/vOTkwUBCBAAJ) Cookie Store API
- [Ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/PNTQCliD2oA/daIyhTskCQAJ) Notification Inline Replies
- [Implement](https://groups.google.com/a/chromium.org/d/msg/blink-dev/P8bZxeA84Z4/gGWF1_4JBAAJ) `stale-while-revalidate` directive for HTTP `Cache-Control` header
- [Ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/Fim-KmT08PE/LIHNNXALBAAJ) CSS environment variables and `viewport-fit` descriptor for `<meta name="viewport">`
- [Implement](https://groups.google.com/a/chromium.org/d/msg/blink-dev/4dohVXDfEI4/tO6rhuv4AwAJ) CSP `'unsafe-hashes'` source expression
- [Ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/V2xR7cucnOA/slvSxt-KAQAJ) Keyboard Map (`navigator.keyboard` and `keyboardchange` event)
- [Implement and ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/hnIOyxASKFU/nBkzXbvuAQAJ) module workers (`type: 'module'` option for `Worker` constructor)
- [Implement](https://groups.google.com/a/chromium.org/d/msg/blink-dev/j7k2nI_9nng/OE6IvgJyAQAJ) `navigator.getDisplayMedia` method (Screen Capture)
- [Ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/ibVPbqBQapU/rUZIrPPLAQAJ) Picture-in-Picture (`requestPictureInPicture` method)
- [Experiment](https://groups.google.com/a/chromium.org/d/msg/blink-dev/wybNlFUskig/l04GcYwVAgAJ) Event Timing API
- [Ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/5MSY_oNVEjo/pCeXIZLEAgAJ) `Request` `isHistoryNavigation` property
- [Implement](https://groups.google.com/a/chromium.org/d/msg/blink-dev/peRlfsYaDIw/bw2CJHrvAgAJ) an API for querying the user activation state
- [Ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/z4CWYor4UpQ/CVS65qLrAgAJ) deprecation reports and the `ReportingObserver` API
- [Implement and ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/KZx0i3e5nZM/I7txb1mmAgAJ) nested, dedicated workers

May 2018

- [Implement](https://groups.google.com/a/chromium.org/d/msg/blink-dev/dxqWTSvyhDg/1UDaFD17AQAJ) WebGPU API
- [Implement and ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/48OwfwZrbvI/yIElvmbkCQAJ) CSS Logical Properties
- [Implement](https://groups.google.com/a/chromium.org/d/msg/blink-dev/tNwA_l_o9lc/5wug6BcmCQAJ) HTTP `Sec-Metadata` request header
- [Ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/Na7aTFJOpWs/_tpdtav8CAAJ) Web Lifecycle
- [Implement](https://groups.google.com/a/chromium.org/d/msg/blink-dev/Va5xWNoBOeE/1pQGezNpCAAJ) `TextEncoderStream` and `TextDecoderStream` APIs
- [Implement](https://groups.google.com/a/chromium.org/d/msg/blink-dev/aKI6doxffgQ/7dzrVvo4CAAJ) scroll target based on CSS selector in URL fragment
- [Ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/nNji_u7BRxo/Zh8Y9hRlBAAJ) Reporting API and Network Error Logging
- [Implement](https://groups.google.com/a/chromium.org/d/msg/blink-dev/PqEt_hXm9us/cG_LT9ZHAwAJ) Gamepad API touchpad extension
- [Ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/jfd4knvCiio/qcf5uaspBQAJ) `<script referrerpolicy>` attribute
- [Ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/K4m85YRD1II/4NsXBn-pBAAJ) CSS Scroll Snap
- [Experiment](https://groups.google.com/a/chromium.org/d/msg/blink-dev/xQiDYZEnwaA/MNGbYJnaBwAJ) Picture-in-Picture (`requestPictureInPicture` method)
- [Ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/isXS3f3Tqo8/GPIQi_8oCAAJ) Keyboard Lock API (second intent)
- [Implement](https://groups.google.com/a/chromium.org/d/msg/blink-dev/tudxAHN9-AY/vz91o_aNDwAJ) element visibility reporting for Intersection Observer API (`trackVisibility` and `isVisible` properties)
- [Implement](https://groups.google.com/a/chromium.org/d/msg/blink-dev/suT7pB2M9L0/ZuA8AQz6DgAJ) Async Local Storage API (layered API)
- [Implement](https://groups.google.com/a/chromium.org/d/msg/blink-dev/5411pauM9e8/aX4K4wz6DgAJ) HTML `<virtual-list>` element (layered API)
- [Implement and ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/TNeeH17Y26c/YmWpxPBrBAAJ) `AnimationEvent` `pseudoElement` property (CSS Animations)

April 2018

- [Implement](https://groups.google.com/a/chromium.org/d/msg/blink-dev/MFbJuzA5tH4/t6Q-LZHpAgAJ) infrastructure for Layered APIs
- [Ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/WOAtshyL2As/wITX3abkAQAJ) `'same-origin'` as the default credentials mode for `fetch()` (the previous default was `'omit'`)
- [Ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/G_rkd0yo2A) HTTP `Network-RTT` and `Network-BW` request headers (network quality estimates)
- [Implement](https://groups.google.com/a/chromium.org/d/msg/blink-dev/65lfM2f0eeM/-1ttGbZmCQAJ) Priority Hints API (`importance` attribute)
- [Implement and ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/4qF8XPQ1z2s/q2MFDxHxCAAJ) CSS `overflow` shorthand (accepts two values)
- [Implement](https://groups.google.com/a/chromium.org/d/msg/blink-dev/T-DgYf79sFU/Kuu6Ltt6CAAJ) User Timing Level 3 extensions
- [Implement](https://groups.google.com/a/chromium.org/d/msg/blink-dev/KMNZmMF1_H4/U6EGekDrBwAJ) Wake Lock API
- [Implement](https://groups.google.com/a/chromium.org/d/msg/blink-dev/XdRp1DXmUFs/5vda0YM6CAAJ) `prefersNavigationBar` option for Fullscreen API
- [Implement and ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/hnAWBzq1qys/DhyRSDKKBQAJ) Cross-Origin Read Blocking (CORB)
- [Implement](https://groups.google.com/a/chromium.org/d/msg/blink-dev/m0OOlPJGNTY/Mofa0PzxBwAJ) Keyboard Map (`navigator.keyboard` and `keyboardchange` event)
- [Implement](https://groups.google.com/a/chromium.org/d/msg/blink-dev/QNE6TVQve-0/y3KfnxOaBAAJ) Event Timing API (`'event'` performance entries)
- [Implement](https://groups.google.com/a/chromium.org/d/msg/blink-dev/zCQe7UkR07w/8In0oinBAgAJ) `customElements.upgrade` method

March 2018

- [Ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/MrKpBV26ik4/D_zmoAJrAQAJ) events for back/forward mouse buttons (`button` property values `3` and `4`)
- [Implement](https://groups.google.com/a/chromium.org/d/msg/blink-dev/RQVKGUjDz9U/ltwrLQ1HAQAJ) `style` option for `customElements.define` method (for providing a custom element’s default styles)
- [Implement](https://groups.google.com/a/chromium.org/d/msg/blink-dev/IIV1MfaPHYc/l0lsJ-agBQAJ) `formdata` event type (Form Participation API)
- [Ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/l5PCVakcOCE/g0wnSg_jBAAJ) unified touch adjustment
- [Ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/r8iKkTXftm4/8iBn0c2UAAAJ) Motion Sensors (based on Generic Sensor API)
- [Ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/o9RU6Vv0xeM/EGnQOExbAAAJ) Web Authentication API (with FIDO U2F support)
- [Ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/YEHinDOBaBw/JhMNfDiNAgAJ) `TransformStream` constructor
- [Ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/ySuNvyaB8jY/CtcfGxoCAgAJ) CSS `conic-gradient()` function
- [Ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/S3naD9vIcM4/7tKyfvi0AgAJ) customized built-in elements
- [Implement and ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/EJ4xF_DwZyk/i6qz7FSnBQAJ) CSP `navigate-to` directive
- [Ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/8RBFue7RMXQ/c_Nf_XJ4AAAJ) HTTP `Accept-CH-Lifetime` response header
- [Implement](https://groups.google.com/a/chromium.org/d/msg/blink-dev/9BB64XIznsE/s_I4QTM0DgAJ) CSS Shadow Parts (`::part()` and `::theme()` pseudo-elements)
- [Experiment](https://groups.google.com/a/chromium.org/d/msg/blink-dev/C5ouVl8q3rU/WZLU1iM4DQAJ) AudioWorklet

February 2018

- [Implement](https://groups.google.com/a/chromium.org/d/msg/blink-dev/-wN72ESFsyo/leH6DuuhAwAJ) CSS `:focus-visible` pseudo-class
- [Ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/aXYvQ01tMhw/SqA09gD7AgAJ) Media Capabilities API (getting information about decoding capabilities)
- [Ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/6UNwnk97lrE/LmW0ni0NCwAJ) `<slot>` elements in the flat tree
- [Implement](https://groups.google.com/a/chromium.org/d/msg/blink-dev/TQN4jWHydTk/52JwsCJ8CgAJ) WebSockets over HTTP/2
- [Implement](https://groups.google.com/a/chromium.org/d/msg/blink-dev/8tVgAyS47y0/e9L-NbatBwAJ) `srcset` and `imgsizes` attributes on `<link rel="preload" as="image">` elements
- [Ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/T-OkMDASYfk/Mp7VsfDGBQAJ) `modulepreload` link relation
- [Experiment](https://groups.google.com/a/chromium.org/d/msg/blink-dev/AZ-PYPMS7EA/DEqbe2u5BQAJ) CSS Animation Worklet API
- [Ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/dEsseBBMbs4/rvdT2wK4BQAJ) AudioWorklet
- [Ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/MAHQkH4vvUQ/i0yCobrMCQAJ) HTML `inputmode` attribute
- [Experiment](https://groups.google.com/a/chromium.org/d/msg/blink-dev/apdn-NbyZJg/RqHUfq3aCQAJ) Web Locks API
- [Implement and ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/GzDmvZO7IjU/syvJp9QjCAAJ): Expand list of properties that can apply to CSS `::first-letter` pseudo-elements
- [Ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/fVxkGlKpDbU/GJD6RgkbCAAJ) Payment Handler API
- [Implement](https://groups.google.com/a/chromium.org/d/msg/blink-dev/irhrlr6n5YQ/LOS8xSGsBwAJ) constructable style sheet objects (`CSSStyleSheet` constructor)
- [Implement](https://groups.google.com/a/chromium.org/d/msg/blink-dev/BLBHKKG90DM/MxokOGuaBwAJ) CSS `:is()` pseudo-class

January 2018

- [Implement and ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/FsD97U77tss/n3m_yvyoAAAJ) CSS `x` unit (synonym for `dppx`)
- [Implement](https://groups.google.com/a/chromium.org/d/msg/blink-dev/czmmZUd4Vww/1-H6j-zdAwAJ) “Lazily load below-the-fold iframes and images”
- [Ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/wP4NWLgbIpA/P1rebd9ZAgAJ) CSS `justify-items: legacy` value
- [Implement](https://groups.google.com/a/chromium.org/d/msg/blink-dev/QDhDKXJqKVE/SVeKgDw4AgAJ) CSS `justify-items: legacy` value
- [Experiment](https://groups.google.com/a/chromium.org/d/msg/blink-dev/sWa31BxDO0g/fHNukicyAgAJ) “Extend Subresource Integrity (`<script integrity>`) to support validating a resource’s signature”
- [Implement](https://groups.google.com/a/chromium.org/d/msg/blink-dev/U8Apo-WLBm4/03sO4ITYAQAJ) Picture-in-Picture (`video.requestPictureInPicture()`)
- [Deprecate and remove](https://groups.google.com/a/chromium.org/d/msg/blink-dev/_g_HnAHkMPo/1DrejG5mAgAJ) `#` in data URL body (the first `#` will be treated as the start of the fragment)
- [Implement and ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/UViBfJuuIq8/w7_2W7lLAgAJ) CSS `row-gap`, `column-gap`, and `gap` properties (`grid-row-gap`/etc. become aliases)
- [Implement and ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/Hudukgo_fB4/6FPRvvBtBQAJ) CSS `calc()` in media queries
- [Ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/6ai8np0DSOA/XJak-Nw0AgAJ) CSS Typed OM
- [Implement and ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/o9Pnen-jNcI/8thpmgMHAwAJ) “Fire an `input` event when a `range` or `file` `<input>` element is activated”
- [Implement and ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/xEXD9C48c1k/HRCCs311CgAJ) Performance Observer `takeRecords` method
- [Implement](https://groups.google.com/a/chromium.org/d/msg/blink-dev/irAY53rSXIE/p0oZ5j4mAgAJ) Permission Delegation (through `<iframe allow>` attribute)
- [Implement and ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/RWWG6ZJYDhc/VBKxlCuVAgAJ) Feature Policy `sync-xhr` feature
- [Experiment](https://groups.google.com/a/chromium.org/d/msg/blink-dev/Dpw4IJ0hQdg/BAPNQsJgAQAJ) Media Capabilities API (cont.)
- [Implement and ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/Qc-bOSyU0FQ/tczXROBoCQAJ) “Fire an `input` event when a (mutable) checkbox is clicked”
- [Implement](https://groups.google.com/a/chromium.org/d/msg/blink-dev/gVvtbIjE2J4/0KWy4Ew2CQAJ) (a subset of the) CSS Layout API
- [Ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/epeaao7l13M/b8ewAH5uBwAJ) Async Clipboard API
- [Implement and ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/lgA_loKD_XU/DlJ_LppLBwAJ) `HTMLAnchorElement` `relList` property
- [Experiment](https://groups.google.com/a/chromium.org/d/msg/blink-dev/-s4pWwshKhI/md53uVDRBgAJ) WebVR 1.1
- [Ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/8vqcABTnDF4/2kZzScnzBgAJ) Fetch API `keepalive` option

December 2017

- [Ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/XzdNrEvn4Qk/650SpqXTBAAJ) CSS `display: contents` value
- [Implement](https://groups.google.com/a/chromium.org/d/msg/blink-dev/kqD_G4sxfZE/6CJM01X2BwAJ) CSS `:matches()` pseudo-class
- [Implement and ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/RX0GN4PyCF8/6XVhJ_oTCgAJ) Feature Policy `accelerometer`, `gyroscope`, `magnetometer` features
- [Implement and ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/9vNZh4fhV2U/ZVxD2iQACgAJ) Abortable fetch (`AbortController` and `AbortSignal`)
- [Implement](https://groups.google.com/a/chromium.org/d/msg/blink-dev/VjFBlOBwkmY/rDS04njmCAAJ) unified touch adjustment
- [Ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/sufZCxRTvXk/HvSyv8yOAgAJ) Feature Policy `autoplay` feature
- [Ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/RNHfILQBYic/6PeEeAstDwAJ) CSS `:any-link` pseudo-class
- [Ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/ySf8YHR6MpA/nxOmaP4oAwAJ) TLS 1.3 draft-22 in 1-RTT mode
- [Ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/MbXp16hQclY/bQjegyrbAgAJ) `<img decoding>` attribute
- [Ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/AgonJunvfIE/O7Gb0fzXAgAJ) Network Information `saveData` property

November 2017

- [Implement](https://groups.google.com/a/chromium.org/d/msg/blink-dev/dJkNHglu1Z0/eodHxUDdAgAJ) CSS `:any-link` pseudo-class
- [Implement and ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/KeQ2s0z6ZkM/GhGv3vhlBgAJ) HTTP 425 (Too Early) status code
- [Implement](https://groups.google.com/a/chromium.org/d/msg/blink-dev/KTLndMOFLLA/VykZ7bg8BgAJ) Feature Policy `autoplay` feature
- [Implement and ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/TgoXNRtA3Zs/-MzmGA_UBAAJ) delayed dispatch of performance entries
- [Implement and ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/KRAyvMD4QZs/ABBp-5aLBAAJ) WebVTT `positionAlign` and `lineAlign` properties
- [Implement](https://groups.google.com/a/chromium.org/d/msg/blink-dev/3DjSQKQzKz8/FI9qbxHhAwAJ) events for back/forward mouse buttons (`button` property values `3` and `4`)
- [Experiment](https://groups.google.com/a/chromium.org/d/msg/blink-dev/oeBf3websgM/Smi7gQxjAQAJ) Web Audio API `AudioWorklet` interface
- [Implement](https://groups.google.com/a/chromium.org/d/msg/blink-dev/DpODIjdpUMg/hVQkjqeIAAAJ) Web Locks API
- [Implement and ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/n5Ch_N1tqN0/zwFttOx9AAAJ) `autocapitalize` attribute on `<form>` and `contenteditable` elements
- [Ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/7aZGnBIlG5o/zkt8FPJPAAAJ) Fetch API `cache` option (also a property on `Request` objects)
- [Experiment](https://groups.google.com/a/chromium.org/d/msg/blink-dev/rDbHXbrowN0/DVwqDZ14AQAJ) CSS `line-height-step` property
- [Implement](https://groups.google.com/a/chromium.org/d/msg/blink-dev/ynkrM70KDD4/g6W39QpsBQAJ) `modulepreload` link relation
- [Implement and ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/fKk4d_Vj080/Pu73nu90BQAJ) (subclassable) `EventTarget` constructor
- [Implement](https://groups.google.com/a/chromium.org/d/msg/blink-dev/qrnnwQOGxTk/CthGq40SBQAJ) transform streams
- [Implement and ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/55sC81ciQgY/7jAt5YpgBAAJ) `preventScroll` option for focus APIs

October 2017

- [Ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/F4h7sdBdiBM/oVnhPTV5BAAJ) HTML `<iframe delegatestickyuseractivation>` attibute
- [Ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/4ZWHz8tCONI/XBTvQtw2BAAJ) CSS `transform-box` property
- [Ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/47BHtmz0jVY/itAC_xpwBgAJ) CSS `text-decoration-skip-ink` property (and remove `text-decoration-skip: ink` value)
- [Implement](https://groups.google.com/a/chromium.org/d/msg/blink-dev/5s1nbytTL68/SnnummScBAAJ) stylable `<slot>` elements (assigned nodes inherit style)
- [Implement](https://groups.google.com/a/chromium.org/d/msg/blink-dev/AUAIHVF63SM/naGVAnoBAwAJ) Fetch API `keepalive` option
- [Implement](https://groups.google.com/a/chromium.org/d/msg/blink-dev/1WFVPbRL640/TPPG9gs5AwAJ) Web Lifecycle
- [Implement](https://groups.google.com/a/chromium.org/d/msg/blink-dev/IrIwAdMWhAE/B0A23MQhBQAJ) Network Information `saveData` property
- [Implement](https://groups.google.com/a/chromium.org/d/msg/blink-dev/9i6wgXv7c7c/0kiqdQkhBQAJ) `<img async>` attribute
- [Implement and ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/bUAhkdsrmqE/nimnFDG3BAAJ) CSP `'unsafe-hashed-attributes'` source expression

September 2017

- [Ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/z6ienONUb5A/GlHRa9S2AAAJ) Resize Observer API
- [Implement and ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/2tutRHmhwTE/X0UX8G5eBgAJ) `<textarea autocomplete>` and `<select autocomplete>` attributes
- [Implement](https://groups.google.com/a/chromium.org/d/msg/blink-dev/fP1jDcQu68g/qSjd8EI8BQAJ) CSS `overflow-wrap: break-spaces` value
- [Ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/ut-Mr0jt5X8/Q8B4F3wxBQAJ) JavaScript `import()` syntax for dynamic imports
- [Implement](https://groups.google.com/a/chromium.org/d/msg/blink-dev/e7I1tZAfavU/wjgW9s0EBAAJ) Gesture Delegation (HTMLIframeElement `allowedActivationDelegation` property)
- [Implement](https://groups.google.com/a/chromium.org/d/msg/blink-dev/qbOrXp9g3B8/hziymUnHAQAJ) trusted types for DOM manipulation
- [Implement](https://groups.google.com/a/chromium.org/d/msg/blink-dev/e-kQSgkoXpc/nkW5cETqAwAJ) PauseFrame API
- [Ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/KHXNJINUrj0/OAAh-sWuAwAJ) “Send mouse events (excluding `click`) to disabled form controls”
- [Implement and ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/D2va-gTcmvA/haBswl-lAwAJ) MediaStreamTrack `applyConstraints` method
- [Experiment](https://groups.google.com/a/chromium.org/d/msg/blink-dev/dsdTLv33r4w/-SUKCfGkAwAJ) Media Capabilities API
- [Ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/Jex3idOld48/dDOK4U5lAwAJ) CSS Paint API
- [Implement](https://groups.google.com/a/chromium.org/d/msg/blink-dev/7CiC3CaPHek/Cy0CN0R6AwAJ) CSS Animation Worklet API
- [Ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/zDbxwYpwTCM/NtLBzCQzAwAJ) Intl NumberFormat `formatToParts` method
- [Implement](https://groups.google.com/a/chromium.org/d/msg/blink-dev/XMLgC_SR0dw/H5UUANxOAgAJ) revised WebVR API
- [Ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/2C0oACCHt_w/lZljNqg9AgAJ) Promise `finally` method
- [Ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/OqBNF2efmFA/3ByBUKyaCgAJ) CSS `scroll-boundary-behavior` property
- [Ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/XdIsb1IFGrI/C6AJvk1PCgAJ) Keyboard Lock API (`navigator.requestKeyboardLock` method)
- [Implement](https://groups.google.com/a/chromium.org/d/msg/blink-dev/QeiK3lAXcmI/MQpErASnAwAJ) options argument for Element `focus` method

August 2017

- [Ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/MFBsNZCkotU/heK7JapxAgAJ) `navigator.deviceMemory` property
- [Implement and ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/DZHASdj7kQc/tpy5mEbrCgAJ) `history.index` property
- [Implement and ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/RC9dSw-O3fE/E3_0XaT0BAAJ) “Treat `http://localhost` as a secure context”
- [Implement and ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/RRUYxYvsRCk/7VillBFrCAAJ) CSS `q` unit
- [Implement](https://groups.google.com/a/chromium.org/d/msg/blink-dev/Mmd02M8rTDE/4-R5glsvBQAJ) Gamepad API haptics extension
- [Ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/ivub1L2UQzQ/e_dreSHfBAAJ) Server Timing
- [Ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/3AISwpQNoNs/9XZxdKRYBgAJ) Performance `timeOrigin` property
- [Experiment](https://groups.google.com/a/chromium.org/d/msg/blink-dev/2zPZt3watBk/M4qcI8wlBwAJ) Generic Sensor API
- [Experiment](https://groups.google.com/a/chromium.org/d/msg/blink-dev/6bfORfa0ajY/wZHKqV3qBAAJ) WebVR (cont.)
- [Ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/xK_P_Rl7zVg/Hrbo1p6NBAAJ) “Dispatch mouse transition events after layout”
- [Ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/312urSSJVXU/Q-fXQAoLAgAJ) collapsable table rows (via CSS `visibility: collapse`)
- [Implement](https://groups.google.com/a/chromium.org/d/msg/blink-dev/mdkHs4jybG4/QQCJJQSsAgAJ) Origin Policy

July 2017

- [Ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/0uSHjqvgAwQ/CqmFd6KNAwAJ) `s` flag for JavaScript regular expressions
- [Implement](https://groups.google.com/a/chromium.org/d/msg/blink-dev/ck9M6Ev21lo/0wf6sg6ZBwAJ) `performance.timeOrigin` property
- [Ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/Su9wM-T6NHc/om3tojbSBgAJ) HTMLImageElement `decode` method
- [Ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/8qlTjzRY9Mc/BYCuqWJXBwAJ) HTTP `Device-Memory` header
- [Ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/7_EgKuWAXjE/QJCzbBscBQAJ) HTTP `Expect-CT` header
- [Implement](https://groups.google.com/a/chromium.org/d/msg/blink-dev/wRLMM5-kpCY/Y0be_ASaAwAJ) JavaScript `import()` syntax for dynamic imports

June 2017

- [Experiment](https://groups.google.com/a/chromium.org/d/msg/blink-dev/eJnB-5Sg-mQ/uvdWnO2OBQAJ) Shape Detection API
- [Ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/AzphlHk8orw/0fiWYuVLAQAJ) OpenType variable fonts
- [Implement and ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/3B0I0EDKfpk/leSOUkN0AQAJ) `beforeprint` and `afterprint` events
- [Implement and ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/e52E3t3ijHo/eyEaNDt1AQAJ) HTML `<time>` element
- [Implement and ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/IjFvnq8yzy8/n_vYt5oUBQAJ) HTML `<data>` element
- [Implement and ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/U0p_jFYpgss/st46sTGjAAAJ) URLSearchParams `sort` method
- [Implement](https://groups.google.com/a/chromium.org/d/msg/blink-dev/EcCNqd1InOs/mBuma3TnBAAJ) collapsable table rows (via CSS `visibility: collapse`)
- [Ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/sFeoDft_cV8/saPiVx5gBAAJ) `<script type="module">`
- [Ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/kbcFPnvDwUc/P2PLzcGhBAAJ) inert visual viewport and Visual Viewport API
- [Ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/rXxzsXLuZEc/HM17-B75BQAJ) HTTP `Clear-Site-Data` header
- [Ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/EZruVTchex8/bauqezVDBAAJ) ImageCapture `getPhotoSettings` method
- [Ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/nwmTLZKFFIA/8bslfL3JAwAJ) Web Share API
- [Implement](https://groups.google.com/a/chromium.org/d/msg/blink-dev/B1oztuLlzxg/tuFtADi0AgAJ) deprecation reports and the `ReportingObserver` API
- [Implement and ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/X64Sg16RhT4/6ZiW7Dt8CAAJ) “Move the role of the scrolling element from `<body>` to `<html>`”
- [Implement and ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/TgtPUowSWuU/Y-Sn2oRsCAAJ) Referrer Policy `'same-origin'`, `'strict-origin'`, and `'strict-origin-when-cross-origin'` values

May 2017

- [Implement and ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/waIh70rrNKM/YzfvTGLvBgAJ) “Exit fullscreen mode if a JavaScript dialog is shown”
- [Implement and ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/s0pPWgyGexg/HQa8IErlBgAJ) Element `getAttributeNames` method
- [Ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/KuXx_k2KIis/-g-75FScBgAJ) WebUSB
- [Ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/DdzeM55D87Y/kwMlfu-DBgAJ) CSP Embedded Enforcement (`<iframe csp>` attribute)
- [Implement and ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/0P4_WvNr1xY/ttehiRR5BgAJ) DOMTokenList `replace` method
- [Implement and ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/mKkVXwMhOLc/1X2m8u7HBQAJ) mandatory `as` value for `preload` links
- [Implement and ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/6GysDZCWwB8/rXbGoRohBgAJ) `navigator.webdriver` property
- [Implement](https://groups.google.com/a/chromium.org/d/msg/blink-dev/Xro1jnasnY0/rUbiEtbDBQAJ) CSP `report-to` directive
- [Ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/UVfNMH50aaQ/4Hy5h-wzEQAJ) Network Information API `downlink`, `rtt`, and `effectiveType` properties
- [Ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/frMdM1H8jJ8/GB9OnD3OBAAJ) Storage API `navigator.storage.estimate` method
- [Implement and ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/_4wD-NXS6Ik/W51KNjTzAAAJ) CSS Box Alignment for Flexbox Layout
- [Ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/fsDaKFqvU20/6swtcHVrAQAJ) stricter `X-Frame-Options: SAMEORIGIN` (check all ancestor frames)
- [Ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/7BZrqCfZ-OQ/R1H6vikdBQAJ) First Paint Timing API (`PerformancePaintTiming` interface)
- [Implement and ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/nT51eE7fWn4/8HBF1NtqBAAJ) Credential Management API `password` property
- [Implement and ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/Z_XzejHJTrs/dQc-XV_lAwAJ) `messageerror` event
- [Ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/DxYtgt49OjA/dH7-4knVAgAJ) Fetch API `formData` method

April 2017

- [Implement](https://groups.google.com/a/chromium.org/d/msg/blink-dev/CvheM4B71Ws/P1c1Hf6xBAAJ) HTTP `Device-Ram` header and `navigator.deviceRam` API
- [Ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/gQCGIrnMxFU/Fz0UDLNeBAAJ) Web Payment Manifest
- [Ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/d8KxOilsS2g/9M1igHrpDgAJ) Navigation Preload for Service Worker
- [Implement](https://groups.google.com/a/chromium.org/d/msg/blink-dev/kphhS7AnFig/uaJ3kjHfDgAJ) Memory Pressure API
- [Implement and ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/zz7AqKAfVTY/N9YQ9BSiDQAJ) CSS `scroll-behavior` property and `behavior` option for scroll APIs (enables smooth scrolling)
- [Ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/yBtmc-4xl_o/GE0vneAVDQAJ) Budget API `reserve` method
- [Experiment](https://groups.google.com/a/chromium.org/d/msg/blink-dev/_l_fxUTWCHs/BQNBSuAVDQAJ) Budget API `getCost` and `getBudget` methods

March 2017

- [Implement](https://groups.google.com/a/chromium.org/d/msg/blink-dev/LMV9dBG_1-I/Bx5VsRWLCgAJ) HTMLImageElement `decode` method
- [Ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/0EW0_vT_MOU/rY-0w8efCwAJ) ReadableStream `pipeTo` and `pipeThrough` methods
- [Ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/qpY1dj_ND-Q/L5a2M3OaCwAJ) writable streams
- [Ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/xEOyu8QFCr0/3oqSlHBxCwAJ) APNG
- [Implement](https://groups.google.com/a/chromium.org/d/msg/blink-dev/v8g3QF8pRF8/Wptgd-sQCwAJ) CSS `transform-box` property
- [Implement and ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/t2ai4lsHhWI/MndrZyEWCwAJ) “CSP hash expressions matching external scripts” (`<script integrity>`)
- [Implement and ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/NY8OPSzHGuE/cbQzsEowCwAJ) `DataTransfer` constructor
- [Experiment](https://groups.google.com/a/chromium.org/d/msg/blink-dev/j-e8iI-WWg8/OjoJbm_zCgAJ) `navigator.getInstalledRelatedApps` API
- [Ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/W-Q1yWW-zas/dO0znwAjCwAJ) InputEvent
- [Ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/Y1hsOyT-vkk/n-8DDvKeCgAJ) Image Capture
- [Implement](https://groups.google.com/a/chromium.org/d/msg/blink-dev/YlMpaO-E2mE/-_GgiMiRCgAJ) Web Payment Manifest
- [Implement and ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/j7l8_DjMsVE/OiOo5zNwCQAJ) CSS `frames()` timing function
- [Implement and ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/V3RNBhQelSg/twVPZYOACQAJ) CSS `:focus-within` pseudo-class
- [Ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/uKO1CwiY3ts/62vV7xmaCQAJ) Feature Policy v1
- [Ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/XlcpobBfJOI/8WYpiyk0CQAJ) `script-sample` property in CSP violation reports
- [Implement](https://groups.google.com/a/chromium.org/d/msg/blink-dev/-z66SwKdklc/5t-NBchECQAJ) CSS `conic-gradient()` notation
- [Implement](https://groups.google.com/a/chromium.org/d/msg/blink-dev/hlRQU77Wq0o/Apbt1WNQBwAJ) Accessibility Object Model
- [Implement](https://groups.google.com/a/chromium.org/d/msg/blink-dev/y3qwr490Fc4/boGoo41-BwAJ) Server Timing
- [Implement and ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/c-b866DUg10/MxS1WTWfBgAJ) HDR display detection via `screen.colorDepth`, `screen.pixelDepth`, and the CSS `color` media feature
- [Ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/cAiTOdSGyes/Su7dlx32EQAJ) Geometry Interfaces
- [Ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/Tr43oT4DQoY/XRxLWmrrEQAJ) “Android on-screen keyboard doesn’t resize layout”
- [Implement](https://groups.google.com/a/chromium.org/d/msg/blink-dev/6W9r_sX3zTQ/5XCSBUQBEAAJ) `sample` property for CSP reports

February 2017

- [Ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/_DPl-JG6bV8/y2_GUwFVDwAJ) animations/transitions on the CSS `offset-path` property
- [Implement and ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/fHl9GNxPPpA/VwhB6h5cDwAJ) “Temporarily stop permission requests after 3 dismissals”
- [Implement and ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/tFuQd3AcsIQ/c-sUR-AxDwAJ) HTMLMediaElement `controlsList` property (for customizing native media controls)
- [Implement and ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/qCfsZJhGtOQ/sC5n92IwDgAJ) CSS Box Alignment `place-*` (shorthand) properties
- [Ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/El0ueyoNgRE/N-6u2SdNDgAJ) `allow-top-navigation-by-user-activation` keyword for `<iframe sandbox>`
- [Ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/bmQjmh0-YB8/iG-7lrqvCgAJ) IndexedDB 2.0 APIs
- [Implement](https://groups.google.com/a/chromium.org/d/msg/blink-dev/N--HhuYFJQI/bmwhhHDZCQAJ) HTML `inert` attribute
- [Implement](https://groups.google.com/a/chromium.org/d/msg/blink-dev/EAqWCAdw1lI/zk3MvsBbCQAJ) Media Capabilities API (getting information about decoding capabilities)
- [Implement and ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/UtFM-kndhaI/19dqA4klCAAJ) “Pause `<video muted autoplay>` when invisible (on Android)
- [Implement and ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/oPGdc9lqpg8/gSjBah0YCAAJ) global `origin` property (`self.origin`)
- [Implement and ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/6otx9aZlwEo/ddfnO5gTCAAJ) construcing workers with `data:` URLs
- [Implement](https://groups.google.com/a/chromium.org/d/msg/blink-dev/TS9zT_u2M4k/ydZK5WpTBwAJ) HTTP `Network-RTT` and `Network-BW` headers (Network Information API extension)
- [Ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/Mx9q5WXunSE/TOAXeHFZBgAJ) Long Task API

January 2017

- [Implement and ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/36CcloDrB3E/1wMSNMl9BQAJ) CSS `color-gamut` media feature
- [Implement](https://groups.google.com/a/chromium.org/d/msg/blink-dev/Ia9_-CVrl1U/oW0riJbHBAAJ) Background Fetch API
- [Implement](https://groups.google.com/a/chromium.org/d/msg/blink-dev/CGeXqTudllA/3t72vfXOBAAJ) uncancellable touch events when the main thread is busy (intervention)
- [Remove](https://groups.google.com/a/chromium.org/d/msg/blink-dev/0nSxuuv9bBw/EMfaclV-AwAJ) prerendering in Chrome
- [Ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/tSEKFwM_WuU/d1UOoJAJAwAJ) CSS `font-display` property
- [Implement and ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/wlRDnLbyVlk/uuByF-a1AgAJ) “Send all keys (except ESC/F11) to the web app when the browser is in fullscreen mode”
- [Ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/5OBK4Uew2Js/VlYpo_JcAgAJ) PointerEvent `getCoalescedEvents` method
- [Ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/z0RI8seNuCs/ATwON9v3FwAJ) CSS `line-height-step` property
- [Ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/C-iuVJeDGkk/IfIam8_rFgAJ) Token Binding
- [Experiment](https://groups.google.com/a/chromium.org/d/msg/blink-dev/0-6bmy1cOnw/E_IQ3l23FgAJ) “navigation preload for service workers”
- [Implement](https://groups.google.com/a/chromium.org/d/msg/blink-dev/T4HsGFfxbGw/_Ld_WgBjFgAJ) CSS Logical Properties (`margin-*` properties)
- [Experiment](https://groups.google.com/a/chromium.org/d/msg/blink-dev/LI7O__FjIJk/6dlwUmGhFgAJ) WebUSB (another Origin Trial)
- [Implement and ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/-NmHZqP4cQg/tAaPqI1GFgAJ) PointerEvent `tangentialPressure` and `twist` properties
- [Ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/6iqiskBdDQE/hBrnmzssFgAJ) WebAssembly
- [Implement and ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/k9WOAVA5Ewc/v7DPYeWhFQAJ) CSS `display: flow-root` value
- [Ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/xIpJ_303phw/6PoGcPIGFQAJ) Media Session API
- [Implement](https://groups.google.com/a/chromium.org/d/msg/blink-dev/tgn5R-58iek/Q6YCnu0RFQAJ) `Expect-CT` header
- [Experiment](https://groups.google.com/a/chromium.org/d/msg/blink-dev/COF0YKkjZVQ/at24EPkRFQAJ) `document.rootScroller` property
- [Implement](https://groups.google.com/a/chromium.org/d/msg/blink-dev/qu73qpdGunE/FoOgPZ6-FAAJ) Canvas color management (`colorSpace` property)

December 2016

- [Implement and ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/8Zo2HiNEs94/h8mDVkx0EwAJ) `rel="prefetch"` in `Link` header
- [Implement](https://groups.google.com/a/chromium.org/d/msg/blink-dev/pFI8AMdDChM/GEWPKoGzEgAJ) asynchronous Clipboard API
- [Implement and ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/2XJ51Apy5XY/9wh9z2zSDwAJ) ARIA 1.1
- [Implement](https://groups.google.com/a/chromium.org/d/msg/blink-dev/V38Q47CxTIY/vIEsirLTDwAJ) Reporting API
- [Ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/5zb6MESKRog/ax6EObiJDgAJ) `ClipboardEvent` constructor
- [Implement and ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/4qEXWptfVHs/vhgeXGNzDgAJ) CSS Logical Properties (`*-size` properties)
- [Implement](https://groups.google.com/a/chromium.org/d/msg/blink-dev/9pauQUAvrcw/lfbG7eunCAAJ) System Keyboard Lock
- [Implement](https://groups.google.com/a/chromium.org/d/msg/blink-dev/txdySyr-mb0/tPQJZvJiBwAJ) CSS `scroll-boundary-behavior` property
- [Implement and ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/1ebMBNhqRew/_6hAQKAfBwAJ) Web App Manifest `purpose` field (for icons)
- [Implement](https://groups.google.com/a/chromium.org/d/msg/blink-dev/_oUskZTzQxg/TwReQ2npBgAJ) Web Share Target API
- [Implement and ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/I0hKADppnoU/y7E08rh4BgAJ) SVG transform presentation attributes
- [Implement](https://groups.google.com/a/chromium.org/d/msg/blink-dev/gWp3xcyEDJM/JKOu68Y2BQAJ) MediaStreamTrack Content Hints
- [Implement and ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/HZ_ZHEE9oDo/jXunplrqBAAJ) Presentation API 1-UA mode
- [Implement](https://groups.google.com/a/chromium.org/d/msg/blink-dev/sa5Tvr4QyWI/Pk_ohqbpBAAJ) Phone number API (a.k.a. Sign up API)

November 2016

- [Implement](https://groups.google.com/a/chromium.org/d/msg/blink-dev/5AgbvQwEEdM/bLQcXkF7BAAJ) ReadableStream `pipeTo` and `pipeThrough` methods
- [Implement](https://groups.google.com/a/chromium.org/d/msg/blink-dev/kyll3WFKTig/gMNvZ66eBAAJ) PerformancePaintTiming interface (incl. time to first paint)
- [Implement and ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/npKDoKVOUAs/ogtlIFmLBAAJ) changes to CSP’s model for workers
- [Implement](https://groups.google.com/a/chromium.org/d/msg/blink-dev/GAhY5gl8bIs/8eVDOUA8BAAJ) OpenType variable fonts
- [Implement and ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/vM3RM1OQNFU/ao3wqCM6AgAJ) `<iframe allowpaymentrequest>` attribute
- [Implement](https://groups.google.com/a/chromium.org/d/msg/blink-dev/OTbGJtwRmXg/RCYzioMlAgAJ) PointerEvent `getCoalescedEvents` method
- [Ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/d2mbqJ0ADXk/MLrTZq1xAwAJ) CSS `text-decoration-*` properties
- [Implement and ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/Qm_q-LzwnHs/bTh_T0T1AgAJ) CSS `::placeholder` pseudo-element
- [Ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/kJLzOeS-l4w/Dco5FIcpAwAJ) Remote Playback API
- [Implement and ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/6jK81erL87E/i6t4G9AaAwAJ) CSS `caret-color` property
- [Ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/hBx1ffTS9CQ/TMTigaDIAgAJ) CSS Grid Layout
- [Implement](https://groups.google.com/a/chromium.org/d/msg/blink-dev/qCJhuuZH5p0/le6l1t37AQAJ) Web Authentication API
- [Implement and ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/IoIxRpn6l9g/ux1C1Cj7AQAJ) Payment Request API `canMakeActivePayment` method
- [Ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/sTJ0OL9QJx8/DAXDOrIqAQAJ) “Fire `visibilitychange` event on document unloading”
- [Implement and ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/AT7aqhPcNdw/10jQ2B0HAQAJ) Navigation Timing Level 2
- [Implement and ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/Hs5-wPpCPZc/7BVwLbfMAAAJ) Resource Timing `nextHopProtocol` property
- [Implement and ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/1UkZE-vOROc/gEj7psewAAAJ) CSP's `worker-src` directive
- [Implement](https://groups.google.com/a/chromium.org/d/msg/blink-dev/2ojnMk_T9_c/h7QfIhTeCAAJ) Payment App API
- [Implement](https://groups.google.com/a/chromium.org/d/msg/blink-dev/PI3FG54L1ZU/B4jNSzhyCAAJ) navigation preload for service workers
- [Ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/VJmxBRYGVIE/CogbbYWXCAAJ) scroll anchoring

October 2016

- [Implement and ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/LukPJ86fcs8/RX_dsbUiCAAJ) `<link referrerpolicy>` attribute
- [Ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/X_vBQp60kp8/v43CLS89CAAJ) CSS `position: sticky` value
- [Implement](https://groups.google.com/a/chromium.org/d/msg/blink-dev/wfIVkXvQ7kQ/VfuOr_FhBwAJ) FIDO U2F API
- [Implement and ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/1kroHAnh3BU/uYZb6uZRBwAJ) Fractional MouseEvent coordinates
- [Implement and ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/6o1W8mVUDsA/JOKZ-aRfBwAJ) KeyboardEvent `isComposing` property
- [Implement](https://groups.google.com/a/chromium.org/d/msg/blink-dev/f1zzIHtRomQ/foZ6f5dKBwAJ) WritableStream (part of Streams API)
- [Implement](https://groups.google.com/a/chromium.org/d/msg/blink-dev/vNNQ50QRNuY/u6n62FlqBgAJ) CSS `shape` media feature
- [Ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/VAEv-MUFGC8/n7gz63UfBgAJ) WebGL 2.0
- [Ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/___gftRPAvg/TsANSIDHBQAJ) TLS 1.3 1-RTT (field trial)
- [Implement and ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/toKFfP_oOac/jde6w6xuBQAJ) ImageBitmap rendering context for `<canvas>`
- [Remove](https://groups.google.com/a/chromium.org/d/msg/blink-dev/JqUlPA-HFfU/l77tAggtBQAJ) CSP `'referrer'` directive
- [Implement and ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/nAUxrvJeNLQ/-e1zF6YkBAAJ) CSS `display: contents` value
- [Intervene](https://groups.google.com/a/chromium.org/d/msg/blink-dev/BW3qrkisqIs/v5Au-HVTAwAJ) “Treat touch Scroll-blocking event listeners as passive”
- [Implement and ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/jkHEX_9eOjE/hmlv6sJMBAAJ) `PresentationConnection.url` property
- [Ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/Ono3RWkejAA/2skvuBhSCQAJ) Web Bluetooth
- [Ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/j7NzKZKdSyc/HISQnGJXCQAJ) “Render Unicode control characters”
- [Implement and ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/hvN9YVvIb5c/5DrcunKSCAAJ) CSS `system-ui` generic font family
- [Ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/y6U-3IGIduM/VxCRbkntBgAJ) Notification API `image` property (“a large image as part of the content of a notification”)
- [Ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/nAM3o4NSMsI/3gRKsOuYBgAJ) durable (persistent) storage
- [Implement](https://groups.google.com/a/chromium.org/d/msg/blink-dev/j7Oo9JSPY8c/DMNbU2qdBgAJ) customized built-in elements
- [Ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/y4a1OWfMzN0/XFBIp_GIBgAJ) HTTP `Referrer-Policy` header

September 2016

- [Ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/ip4dmVNr15Y/jyE0Gc8jBQAJ) CSP violation event `disposition` property
- [Experiment](https://groups.google.com/a/chromium.org/d/msg/blink-dev/3tViQmRF2l8/0hRE9EBUBQAJ) Long Task API
- [Implement](https://groups.google.com/a/chromium.org/d/msg/blink-dev/Uzit4zDQ1ps/pD_3k2rqBAAJ) CSS `overscroll-action` property
- [Ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/EVN4Y8NVtNM/VanLZ_1hBAAJ) `pinch-zoom` value for CSS `touch-action` property
- [Implement](https://groups.google.com/a/chromium.org/d/msg/blink-dev/bck8mCc-HOQ/HUeob0z8AwAJ) Content Security Policy: Embedded Enforcement
- [Experiment](https://groups.google.com/a/chromium.org/d/msg/blink-dev/iAIKruoq5QM/Ht0eD081AwAJ) MediaStream Image Capture
- [Ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/9WIVyDz1T34/5Nmj46UXAwAJ) `MediaStream` constructor
- [Implement and ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/hdBMDg5Nmok/ZAd7NTgfAwAJ) CSS `text-decoration-skip` property (and default to `ink` value)
- [Ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/UY1EfjaGF_E/OU7W_s3PAgAJ) Pointer Events
- [Ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/SUF73nqP1P4/2fK1GjVFAgAJ) ECMAScript async functions
- [Implement and ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/IxyBdzkSU98/LJ12LwjKAAAJ) constructible document with `new Document()`
- [Experiment](https://groups.google.com/a/chromium.org/d/msg/blink-dev/zGAzqfi0e00/atXaz8UCAQAJ) WebVR
- [Ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/s-w44wOMzqs/tEd_YNjkAAAJ) MediaDevices `devicechange` event
- [Ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/LsnvY7FFrY0/iVl1FcAFAgAJ) CSS `hyphens` property
- [Implement](https://groups.google.com/a/chromium.org/d/msg/blink-dev/GxTBfZjzqFw/dw63GhkrAgAJ) “Process continuous events just before `requestAnimationFrame` occurs”
- [Implement](https://groups.google.com/a/chromium.org/d/msg/blink-dev/JkdoxpINjxQ/CUWOBwc0AgAJ) Shape Detection API
- [Implement](https://groups.google.com/a/chromium.org/d/msg/blink-dev/fBfWECEGZa8/Jr_3UDsCAQAJ) AudioWorklets for Web Audio API

August 2016

- [Implement](https://groups.google.com/a/chromium.org/d/msg/blink-dev/_IReUkNKF6o/S1GCeqxMAAAJ) Accelerometer, Gyroscope and Magnetometer Sensor APIs
- [Implement](https://groups.google.com/a/chromium.org/d/msg/blink-dev/b6UBgAZt1kQ/nZTYfu0AAgAJ) CSS Properties and Values API
- [Experiment](https://groups.google.com/a/chromium.org/d/msg/blink-dev/zuqQaLp3js8/5V9wpRWhBgAJ) Web Share API on Android
- [Ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/R8OehqGJzt0/x95pHclCBgAJ) `auxclick` event type
- [Implement](https://groups.google.com/a/chromium.org/d/msg/blink-dev/UpS11lcUkYg/NBFTJMQPBgAJ) IndexedDB object store and index renaming (during version change transactions)
- [Implement](https://groups.google.com/a/chromium.org/d/msg/blink-dev/FQxPB5GEQjo/oUJb_54BBgAJ) Notifications API `image` property
- [Experiment](https://groups.google.com/a/chromium.org/d/msg/blink-dev/lLX_NIuTpkM/-iP0Kq23BQAJ) WebUSB (updated)
- [Ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/P2UKXfsFWWE/Nii0d7snBQAJ) custom elements v1
- [Implement](https://groups.google.com/a/chromium.org/d/msg/blink-dev/uMC1NQP4kpY/Rh8LYedWBAAJ) `once` option for `addEventListener` method
- [Ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/Yk8u329AmIs/eXTS5WeaAwAJ) media tracks (limited to 1 audio/video track)
- [Implement and ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/zXlpFPXhyvE/PPbUFRAvAgAJ) `dataset` API on SVG elements
- [Experiment](https://groups.google.com/a/chromium.org/d/msg/blink-dev/sIzHpZVhmBE/fF0Qf15qAQAJ) foreign fetch and `serviceworker` link relation
- [Implement and ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/Tf5TwA45W8Q/eycERiHpAAAJ) unprefixed CSS `-webkit-image-set` function
- [Implement](https://groups.google.com/a/chromium.org/d/msg/blink-dev/A_sM-fu6u50/ao9mnO8SAQAJ) “long task” notifications in Performance Observer
- [Ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/A12B1S4eGxY/TECSVggtAAAJ) visual viewport
- [Implement](https://groups.google.com/a/chromium.org/d/msg/blink-dev/I3FhKqtui_k/YY4AvQq6AAAJ) Budget API

July 2016

- [Ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/fH5bzd0_lRI/58_8fyxIBwAJ) ParentNode/ChildNode `prepend`/`append`/`before`/`after`/`replaceWith` methods
- [Ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/bcD93CiIJHE/2a9_ibfbDQAJ) `pan-up`/`pan-down`/`pan-left`/`pan-right` values for CSS `touch-action` property (follow up)
- [Implement and ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/Z2fllXoSjcU/P-kHtCVJBQAJ) “Allow web pages to request fullscreen while an orientation change event handler is running”
- [Implement and ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/MjeLmhOZKXw/zvlyAsvNBAAJ) `Node.getRootNode` method (was `Node.rootNode`)
- [Implement](https://groups.google.com/a/chromium.org/forum/#!topic/blink-dev/N0HybdIpKBs) Content Size Policy
- [Implement and ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/IHrxKj4zGjg/LTzEZ2iuAgAJ) Gamepad API extensions (`touched` and `pose` properties)
- [Ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/kJ3FGlUaWHU/BTg1AXx7AQAJ) `BroadcastChannel` API
- [Implement](https://groups.google.com/a/chromium.org/forum/#!topic/blink-dev/jyCdW1dHyYA) CSP `require-sri-for` directive
- [Implement and ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/ysEXU21Dn1Y/2UZUHve_BQAJ) Push API `PushSubscription.options` property
- [Implement](https://groups.google.com/a/chromium.org/d/msg/blink-dev/nsmmXIAOil4/Hc1th-x-BQAJ) `"auxclick"` event type (non-primary button click)
- [Implement and ship]() “Block `navigator.vibrate` in cross-origin iframes”
- [Ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/VhYxkRlfQng/EXRHD7A5BQAJ) `pan-up`/`pan-down`/`pan-left`/`pan-right` values for CSS `touch-action` property

June 2016

- [Ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/p1DYoxHlkKg/qxS32AaCAgAJ) PaymentRequest API
- [Implement and ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/hWT6i_qXcjo/7uN5KoiJAgAJ) `"install"` event for Web App Manifest
- [Implement and ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/_Lhz8THHk2Q/f8j8E49rAgAJ) timer throttling for hidden, cross-origin frames
- [Implement](https://groups.google.com/a/chromium.org/d/msg/blink-dev/rBYR3Xd6Skw/oddIWad6AgAJ) Feature Policy
- [Implement and ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/-vHFK4g93jA/JW9wAJyKAQAJ) CSS `the text-size-adjust` property
- [Ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/zrZRD2ls5tw/ibbjD3cQAQAJ) Shadow DOM v1
- [Ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/SKLhE1LhjOg/-oIudYzfAAAJ) Media Capture from `<audio>`/`<video>` (“WebRTC streaming of prerecorded content”)
- [Implement](https://groups.google.com/a/chromium.org/d/msg/blink-dev/1BOhy5av8MQ/OPPt76oZCQAJ) Web Share API
- [Implement](https://groups.google.com/a/chromium.org/d/msg/blink-dev/Umj9iVRJM70/6CG49IswBwAJ) `Referrer-Policy` HTTP header
- [Ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/WEMnlVIbe70/i2MJcEtNBgAJ) “Do not perform default action on un-trusted events”
- [Implement](https://groups.google.com/a/chromium.org/d/msg/blink-dev/vuYEHSeqonM/JpeLkiJABgAJ) “Web Audio requires user gesture on Android”
- [Implement and ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/Q1cnzNI2GpI/AL_eyUNABgAJ) “Autoplay muted videos on Android” (`<video autoplay muted>`)
- [Implement and ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/1bdP80f0GVs/U7qIckr-BQAJ) Resource Timing `transferSize`/`encodedBodySize`/`decodedBodySize` properties
- [Implement](https://groups.google.com/a/chromium.org/d/msg/blink-dev/HGh92uMX_kE/zt2TLWgNAgAJ) “Block cross-origin scripts inserted via document.write” (for users on slow connections)
- [Implement](https://groups.google.com/a/chromium.org/d/msg/blink-dev/ezyGy6JE7hs/lz5TuPcbGwAJ) Media Capture Depth Stream Extensions (media stream from depth camera)

May 2016

- [Ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/L-BRotfWD8U/YiYj6aGCAgAJ) HTTP Alternative Services
- [Implement and ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/QC5iefctcag/kkoBNliBAgAJ) “External stylesheets in `<body>` do not block paint”
- [Implement and ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/g09B730nI80/tWiUWVWFAQAJ) CSS `nav-up`, `nav-down`, `nav-left`, `nav-right` properties
- [Implement and ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/XUNMtri0tI4/qIsHgTWNAQAJ) “Apply `u` flag to `<input pattern>` attribute”
- [Implement and ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/KoasIWagGsk/ayj7mTF5AAAJ) `allow-presentation` token for `<iframe sandbox>` attribute
- [Implement](https://groups.google.com/a/chromium.org/d/msg/blink-dev/iHXS9S66bAw/BM1mV5BQAAAJ) Resize Observer API
- [Ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/0S-jPuCy8ws/QMUrHFQdBwAJ) “Specifying a `ReadableStream` response body in the `Response` constructor”
- [Implement](https://groups.google.com/a/chromium.org/d/msg/blink-dev/SMlcunoqHl0/-1XtMsPPBgAJ) permission delegation for `<iframe>`s
- [Ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/0mBO8Q5FhTo/2OagzgagBgAJ) (read-only) `action`/`vibrate` attributes on `Notification` instances
- [Ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/OzHI2c2vkEo/9Bz-j4PhBAAJ) “Do not perform default action on untrusted events”
- [Implement](https://groups.google.com/a/chromium.org/d/msg/blink-dev/jlSoAmWa1i4/7xowBIOSBAAJ) ECMAScript async functions (`async` and `await`)
- [Implement](https://groups.google.com/a/chromium.org/d/msg/blink-dev/alcPcPKzzkg/QDDrbz2hAwAJ) IndexedDB Observers
- [Ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/Y6Q69fwcexo/xq5YCjiRAwAJ) 8 and 4-digit hex color notation (`#RRGGBBAA` and `#RGBA`)
- [Deprecate and remove](https://groups.google.com/a/chromium.org/d/msg/blink-dev/O9_XnDQh3Yk/SI9yuUpjAwAJ) `requestAutocomplete` method
- [Implement and ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/osZzOCF-ONM/RU3h7wiMAwAJ) CSS `font-variant-numeric` property
- [Experiment](https://groups.google.com/a/chromium.org/d/msg/blink-dev/5Sihi1iAXYc/SISKuRppAwA) durable storage (`navigator.storage.persist` and `.persisted` methods)
- [Ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/zLL_d4DLAno/paH269ijAwAJ) Performance Observer API

April 2016

- [Ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/Wo7fimlUUjc/sN34ExpqAQAJ) Web Push protocol and subscription restrictions
- [Implement](https://groups.google.com/a/chromium.org/d/msg/blink-dev/NHkG8FXFEWU/KLPutppmAQAJ) `Clear-Site-Data` HTTP header
- [Implement](https://groups.google.com/a/chromium.org/d/msg/blink-dev/TkfdVqYAYiE/xLGN2b1-AAAJ) Generic Sensor and Ambient Light Sensor APIs
- [Ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/r4zE8RKB6l4/wg7xJM5HAAAJ) Token Binding
- [Ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/MgponsgdJcg/1rFgBswaAAAJ) CSS Containment (`contain` property)
- [Implement](https://groups.google.com/a/chromium.org/d/msg/blink-dev/QDHX73bCAZc/XKqR4xaKBwAJ) CSS `hyphens` property
- [Implement and ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/5GDO3nt_oDI/n6D838dYBwAJ) `ImageBitmap.close` method
- [Implement and ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/g3qEQkTv5dU/V4Ppp1xuBgAJ) `unsafe-dynamic` CSP source expression
- [Implement and ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/NDHMUjbHywI/WOJfYG1NBQAJ) `IDBKeyRange.includes` method
- [Implement](https://groups.google.com/a/chromium.org/d/msg/blink-dev/P6eY26vB91c/Ri4ohXOPBQAJ) Storage Quota Estimation API (`navigator.storage.estimate()`)
- [Ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/W6rKEsdQHXE/neTBKQomCAAJ) ECMAScript 2016 exponentiation operator
- [Ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/PoHJp1mu4fE/fWlRRIN0BQAJ) `ImageBitmapOptions`
- [Implement](https://groups.google.com/a/chromium.org/d/msg/blink-dev/WYTiG9h8Xbs/fxbpfZEBBQAJ) Mediastream Image Capture (e.g. taking pictures from a webcam)
- [Implement and ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/HZ_SDWrDTHo/QV6rBTjIBAAJ) `-webkit-appearance: none` for `<meter>` and `<progress>` elements
- [Ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/Et8xbBUxrHs/HwdzVp36AgAJ) `HTMLMediaElement.srcObject` for MediaStreams
- [Implement and ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/2VWDU83_VzQ/Dw9l33nyAgAJ) CSS `user-select: none` (unprefixed)
- [Experiment](https://groups.google.com/a/chromium.org/d/msg/blink-dev/i6wQ7PNuMyc/eGfTKYsiAwAJ) WebUSB
- [Ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/Jhwj8QAYaFY/breWmVLNAgAJ) filters in 2D canvas (`CanvasRenderingContext2D.filter` property)
- [Implement and ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/0b5Jgk47uMU/ldEJNx94CAAJ) `Node.isConnected` property

March 2016

- [Implement and ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/7GYNDnQHRCs/BXHM0jn8BgAJ) Fetch API `Request.referrerPolicy` property
- [Ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/KhRce4bmnb0/h--WcEzKBgAJ) DOM `KeyboardEvent.key` property
- [Implement](https://groups.google.com/a/chromium.org/d/msg/blink-dev/7ZWqizEIK1E/D3rDr_HEAwAJ) multiple audio and video tracks
- [Ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/csCtW3M3-wg/H5gEqBVNAwAJ) `SameSite` attribute for cookies
- [Implement](https://groups.google.com/a/chromium.org/d/msg/blink-dev/9s8Zamqbv34/JngoiqKeAwAJ) inline replies in web notifications
- [Implement](https://groups.google.com/a/chromium.org/d/msg/blink-dev/LqQXLx93mEo/C50y8EiLAQAJ) Visual Viewport API
- [Implement and ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/pqUfi_z57OY/8STCiGOCAQAJ) notification badges
- [Implement](https://groups.google.com/a/chromium.org/d/msg/blink-dev/29oXhN4RJlQ/N5IrEHGCAQAJ) multiple image definitions for notifications
- [Implement](https://groups.google.com/a/chromium.org/d/msg/blink-dev/D20_5X-2nCk/E7Gd0G8pAQAJ) `HTMLMediaElement.srcObject` for MediaStreams
- [Ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/FWu2lHOCbNg/eI-cQCqGBQAJ) iterable array-like interfaces
- [Ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/FcxvG5Jq4w0/wLWtyndoBAAJ) Intersection Observer
- [Implement and ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/cPcOuNxebX0/IEgKQMxvBAAJ) “Disallow `document.open` and `document.write` during unload”
- [Implement](https://groups.google.com/a/chromium.org/d/msg/blink-dev/sBHPRkLbF-E/yWJ4dJ6CBAAJ) “Fire `"visibilitychange"` event on document unloading”
- [Implement](https://groups.google.com/a/chromium.org/d/msg/blink-dev/uba6pMr-jec/tXdg6YYPBAAJ) `<script type="module">`
- [Ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/LpXX7Svx8IY/Hu54zinaAwAJ) DOM `.rootNode` property
- [Implement and ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/ntyWX1GW4gQ/xaNY_s0yAgAJ) “Correct handling of percentages in children of flex items”
- [Implement](https://groups.google.com/a/chromium.org/d/msg/blink-dev/kX6a99C1FGw/MQSorHYwAQAJ) CORS restrictions on internet-to-intranet connections

February 2016

- [Implement](https://groups.google.com/a/chromium.org/d/msg/blink-dev/Sf1C6blXmUo/bFNlBk1MDwAJ) Remote Playback API
- [Implement and experiment](https://groups.google.com/a/chromium.org/d/msg/blink-dev/0xXsJYdkaWg/2NwHKmZBEAAJ) AppInstalled API
- [Ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/gDokxXYyeSo/uCS1Gq8oDwAJ) `referrerpolicy` attribute
- [Ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/yEdXn35VwVw/H9BSdwYhDgAJ) Experimental Framework
- [Implement](https://groups.google.com/a/chromium.org/d/msg/blink-dev/wdSV0zUuvJQ/Jd7p_mAIDgAJ) `MediaDevices` `'devicechange'` event
- [Implement and ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/YIH8CoYVGSg/Di7TsljXDQAJ) “Do not use web page-provided strings for `'beforeunload'` dialogs”
- [Implement](https://groups.google.com/a/chromium.org/d/msg/blink-dev/Wc71ungGdn4/3Ix2IjnkDQAJ) CSS `@apply` rule
- [Ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/8hsz3bOFBpY/kUHDGmTPDQAJ) `EventListenerOptions.passive`
- [Implement](https://groups.google.com/a/chromium.org/d/msg/blink-dev/gbSs15ZSWtA/JFU3H7fTDQAJ) Payment Request API
- [Ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/7ouLjWzcjb0/E7YWD1KrDQAJ) Credential Management API
- [Ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/mOWCmoEFfS8/VHYbbaohDQAJ) Media capture from `<canvas>` (`captureStream` method )
- [Implement and ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/LIqrS6y7AiU/tkcDvyMdDQAJ) CSS `font-variant-caps` property
- [Implement](https://groups.google.com/a/chromium.org/forum/#!msg/blink-dev/_-RlGYnb5W8/bfFbSGDKCwAJ) CSS Snap Size
- [Implement and ship](https://groups.google.com/a/chromium.org/forum/#!msg/blink-dev/RrnitB0OElc/rirueVekCwAJ) Basic `InputEvent` interface
- [Implement and ship](https://groups.google.com/a/chromium.org/forum/#!msg/blink-dev/77188XZG5Lg/OXNW-f51CwAJ) CSS `:dir()` pseudo-class
- [Ship](https://groups.google.com/a/chromium.org/forum/#!msg/blink-dev/U55OzGb0bQo/bFMINnduCwAJ) Web Animations Level 1, interop with Firefox
- [Implement](https://groups.google.com/a/chromium.org/forum/#!msg/blink-dev/fv84jWFFovQ/DhjrNXpHCwAJ) `ImageBitmap` options
- [Implement](https://groups.google.com/a/chromium.org/forum/#!msg/blink-dev/ejLQ0y8IVPM/e8X5j6hSCwAJ) Non-document root scrollers
- [Implement](https://groups.google.com/a/chromium.org/forum/#!msg/blink-dev/HwDRVyP505Q/tgEJY5kYCwAJ) `"serviceworker"` link relationship
- [Implement and ship](https://groups.google.com/a/chromium.org/forum/#!msg/blink-dev/IM0HxOP7HOA/y8tu6iq1CgAJ) Optional icon URL for notification actions
- [Implement and ship](https://groups.google.com/a/chromium.org/forum/#!msg/blink-dev/sXT-rWAd0kk/P11TJQKuCQAJ) “Merge `DOMSettableTokenList` into `DOMTokenList`”
- [Experiment](https://groups.google.com/a/chromium.org/forum/#!msg/blink-dev/coyvHj1u2Z8/aqjyAUuICQAJ) Web Bluetooth API
- [Implement and ship](https://groups.google.com/a/chromium.org/forum/#!msg/blink-dev/k5n129-lM1A/02Qqlq0SCQAJ) Notification renotify flag
- [Implement](https://groups.google.com/a/chromium.org/forum/#!msg/blink-dev/ghf2Wq4qQ_w/kzVB_nIvCQAJ) Push subscription restrictions and the Web Push protocol
- [Implement](https://groups.google.com/a/chromium.org/forum/#!msg/blink-dev/E6kHXWv4sJA/7fKGaApzCAAJ) CSS `break-after`, `break-before`, `break-inside` (generic breaking control)
- [Implement and ship](https://groups.google.com/a/chromium.org/forum/#!msg/blink-dev/bvs8ledF4tU/qC__g3yICAAJ) “`HTMLMediaElement.play()` retuns a promise”

January 2016

- [Implement and ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/fePanzKy6ec/fscI5AOoBgAJ) `"notificationclose"` event
- [Ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/_nu6HlbNQfo/XzaLNb1bBgAJ) `"preload"` link relationship
- [Implement](https://groups.google.com/a/chromium.org/forum/#!msg/blink-dev/A4PZz_mXOTg/D9sNjsGWBQAJ) CSS Paint API
- [Ship](https://groups.google.com/a/chromium.org/forum/#!msg/blink-dev/JufzX024oy0/WEOGbN43AwAJ) Brotli (`Accept-encoding: br` on HTTPS connection)
- [Ship](https://groups.google.com/a/chromium.org/forum/#!msg/blink-dev/8P5RWP_nRTk/7QNvJVrmAgAJ) Unprefixed CSS Multi-column Layout
- [Ship](https://groups.google.com/a/chromium.org/forum/#!msg/blink-dev/jRzvehX9U1U/RReEdlqpAgAJ) `ImageBitmap` and `createImageBitmap` method
- [Implement](https://groups.google.com/a/chromium.org/forum/#!msg/blink-dev/ZuseXCSZY2U/p1gLNcCMAgAJ) Media Capture from `HTMLMediaElement`
- [Implement and ship](https://groups.google.com/a/chromium.org/forum/#!msg/blink-dev/WUUEUWha5cI/lnw0T_5XAgAJ) CSS `column-fill` property
- [Implement and ship](https://groups.google.com/a/chromium.org/forum/#!msg/blink-dev/XlBHOIOCjUk/1ZidsQfzAQAJ) `FetchEvent.clientId` and `Clients.get(id)` for Service Worker
- [Implement](https://groups.google.com/a/chromium.org/forum/#!msg/blink-dev/CuOrg2TrnDw/gTgLL59PAQAJ) `EventListenerOptions.passive`
- [Ship](https://groups.google.com/a/chromium.org/forum/#!msg/blink-dev/64DG7iR5Qjs/HHX2unspAQAJ) “Modify `{add,remove}EventListener` to accept `EventListenerOptions`”
- [Ship](https://groups.google.com/a/chromium.org/forum/#!msg/blink-dev/QnBcTm29mJU/3fMvH0XuAAAJ) Canvas Hit Regions

December 2015

- [Implement and ship](https://groups.google.com/a/chromium.org/forum/#!msg/blink-dev/N9a8eAT6Jug/c5LwnvEiBQAJ) CSS `inverted-colors` media feature
- [Ship](https://groups.google.com/a/chromium.org/forum/#!msg/blink-dev/Vga32co0YMQ/4i6qXvfeAwAJ) Push messaging payloads (`PushEvent.data` property)
- [Ship](https://groups.google.com/a/chromium.org/forum/#!msg/blink-dev/iJ_enKAj9gE/swGKdCAlAwAJ) CSS Custom Properties Level 1
- [Ship](https://groups.google.com/a/chromium.org/forum/#!msg/blink-dev/vAWK0ldpyrc/3I_RKXblAgAJ) `i` modifier for attribute selectors
- [Implement](https://groups.google.com/a/chromium.org/forum/#!msg/blink-dev/ckHvzFXn5zQ/ZkzPC--gAgAJ) OffscreenCanvas
- [Implement and ship](https://groups.google.com/a/chromium.org/forum/#!msg/blink-dev/g_igIzSue40/hpQoZ2oRAgAJ) Cookie prefixes and Strict Secure Cookies
- [Implement](https://groups.google.com/a/chromium.org/forum/#!msg/blink-dev/kl8ct3ub3a8/-WfzBTkCAgAJ) Worklets
- [Ship](https://groups.google.com/a/chromium.org/forum/#!msg/blink-dev/FnZBCN4t46w/qn3CtGa5BwAJ) Canvas `toBlob` method
- [Ship](https://groups.google.com/a/chromium.org/forum/#!msg/blink-dev/AmChp_uVpXU/SNEykhRLBwAJ) Promise rejection tracking events

November 2015

- [Implement and ship](https://groups.google.com/a/chromium.org/forum/#!msg/blink-dev/sWoR3JJpowc/WCd9GofQBQAJ) `HTMLMediaElement.disableRemotePlayback`
- [Ship](https://groups.google.com/a/chromium.org/forum/#!msg/blink-dev/76HB0BIxk_o/RTel6y2IBQAJ) Media Stream Recording API
- [Ship](https://groups.google.com/a/chromium.org/forum/#!msg/blink-dev/t9apD7cQb6I/NlTgcjt_BQAJ) Background Sync (one-shot)
- [Implement](https://groups.google.com/a/chromium.org/forum/#!msg/blink-dev/9W80Kw-z3ss/7CLbeeqGBQAJ) CSS Containment
- [Implement and ship](https://groups.google.com/a/chromium.org/forum/#!msg/blink-dev/3rsQQJvhY8k/P2cAFq3hAwAJ) `addEventListener`/`removeEventListener` non-optional arguments
- [Implement and ship](https://groups.google.com/a/chromium.org/forum/#!msg/blink-dev/xEoWkGEd_g4/Pkn_o92EAwAJ) DOMTokenList-based feature detection for `<link>` and `<iframe>`
- [Implement and ship](https://groups.google.com/a/chromium.org/forum/#!msg/blink-dev/grHZDbldP04/JdsoQ169AQAJ) `URLSearchParams`
- [Implement](https://groups.google.com/a/chromium.org/forum/#!msg/blink-dev/gDR7v8QBooU/pnA-5jSNAQAJ) suborigins
- [Implement and ship](https://groups.google.com/a/chromium.org/forum/#!msg/blink-dev/hqW3RGDV8WI/bGe64uK-AQAJ) `"noopener"` link relation

October 2015

- [Ship](https://groups.google.com/a/chromium.org/forum/#!msg/blink-dev/8iSlPpwokbY/LWMJ8IffDQAJ) notification action buttons
- [Implement and ship](https://groups.google.com/a/chromium.org/forum/#!msg/blink-dev/el1cAmGOrvY/0tnBa3bvDAAJ) `"navigate"` mode in `fetch` requests
- [Ship](https://groups.google.com/a/chromium.org/forum/#!msg/blink-dev/ELz4SxMwa0U/CWsWMGjfCwAJ) Audio Output Devices API
- [Implement](https://groups.google.com/a/chromium.org/d/msg/blink-dev/KpCcUTv1UQ8/aAoXs3UTCwAJ) CSS Typed OM
- [Implement](https://groups.google.com/a/chromium.org/forum/#!msg/blink-dev/nyo08pwJcfQ/meb49q1yCQAJ) “modify `addEventListener` to accept `EventListenerOptions`”
- [Ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/21YdGHt2ogM/pkNLbZftCAAJ) `WindowClient.navigate` method for service workers

September 2015

- [Ship](https://groups.google.com/a/chromium.org/forum/#!msg/blink-dev/G-hC66MRTso/uVrmHV0NAwAJ) Local Font Access API
- [Ship](https://groups.google.com/a/chromium.org/forum/#!msg/blink-dev/Md2SYtNazVU/QbN4NGgTAwAJ) durable storage
- [Implement](https://groups.google.com/a/chromium.org/forum/#!msg/blink-dev/VscIPcVtKrc/VfJHxeGUAgAJ) iterable `NodeList`
- [Implement](https://groups.google.com/a/chromium.org/forum/#!msg/blink-dev/TZ79t_huYcg/X00beRJmAgAJ) CSS `position: sticky`
- [Implement and ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/uajNnbH8UPU/YBmO4w-yAAAJ) “Allow `data:` and `blob:` schemes in Fetch API”
- [Implement](https://groups.google.com/a/chromium.org/forum/#!msg/blink-dev/7s4-eQTAxqs/SoahsGpMAQAJ) CSS `font-display`
- [Ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/iBX_2xfX6jc/Uc0D6jr3AgAJ) `stale-while-revalidate` Cache-control extension

### Firefox

July 2021

- :new: [Prototype and ship](https://groups.google.com/a/mozilla.org/g/dev-platform/c/wMKRWjyXGfU/m/biUon_ttAgAJ) CSS `accent-color` property
- :new: [Ship](https://groups.google.com/a/mozilla.org/g/dev-platform/c/u1DpLJyYbSw/m/6WCkr0QAAgAJ) `assign` method for `<slot>` element
- [Ship](https://groups.google.com/a/mozilla.org/g/dev-platform/c/RLqcyCotcdo) CSS `size-adjust` descriptor and
  extended syntax of the `font-size-adjust` property

June 2021

- [Ship](https://groups.google.com/a/mozilla.org/g/dev-platform/c/qNG2YLxbmFs/m/C9izptohAQAJ) CSS `font-synthesis: small-caps` value
- [Ship](https://groups.google.com/a/mozilla.org/g/dev-platform/c/oWc1K4Uur2Y/m/WooPE24fAQAJ) CSS `content: none` on elements
- [Ship](https://groups.google.com/a/mozilla.org/g/dev-platform/c/CJ6ZRmOMkao/m/TN0u8WAfAQAJ) CSS `content: none` on `::marker` pseudo-elements
- [Ship](https://groups.google.com/a/mozilla.org/g/dev-platform/c/4gjD-sC_AcQ/m/C7cd3D0XCQAJ) CSS `tab-size` property
- [Ship](https://groups.google.com/a/mozilla.org/g/dev-platform/c/9BVbcv_ddzA/m/JT5rewM3BgAJ) Implicit Pointer Capture

May 2021

- [Ship](https://groups.google.com/a/mozilla.org/g/dev-platform/c/ThYEXTiQc9g/m/P_AhpZliBAAJ) Visual Viewport API on desktop platforms
- [Ship](https://groups.google.com/a/mozilla.org/g/dev-platform/c/5Ny2u1YmAfQ/m/xnbLSA8fBgAJ) HTTP `Ship Sec-Fetch-*` headers (Fetch Metadata Request Headers)
- [Prototype](https://groups.google.com/a/mozilla.org/g/dev-platform/c/BTXw4pOfnR4/m/d6xtQXmsBQAJ) CSS `d` property on SVG `<path>` elements
- [Prototype](https://groups.google.com/a/mozilla.org/g/dev-platform/c/wdB1v7sKcdo/m/eLXlFIVLCgAJ) JPEG XL image format (limited support)

April 2021

- [Prototype and ship](https://groups.google.com/a/mozilla.org/g/dev-platform/c/IiuvO7eHBME/m/P0f9lDMiAwAJ) relaxed cache re-validation on soft reload
- [Prototype and ship](https://groups.google.com/a/mozilla.org/g/dev-platform/c/w-KLmQ2PQOM/m/YlGiJd5fAgAJ) EXIF image density correction
- [Ship](https://groups.google.com/a/mozilla.org/g/dev-platform/c/eeo02Z1x7NU/m/GK1L8WMIAAAJ) CSS `ascent-override`, `descent-override`, and `line-gap-override` font descriptors
- [Ship](https://groups.google.com/g/mozilla.dev.platform/c/zwDaj0JMYjs/m/roFqKU9HAQAJ) CSS `forced-colors` media feature (née `prefers-contrast`)

March 2021

- [Prototype and ship](https://groups.google.com/g/mozilla.dev.platform/c/Y7aZiULRVjg/m/uiEbMj99BgAJ) inferred `aspect-ratio` from `width`/`height` attributes for `<video>`, `<canvas>` and `<input type=image>`
- [Prototype](https://groups.google.com/g/mozilla.dev.platform/c/zk_-KRtKJr0/m/KcAhTOqcAwAJ) CSS `ascent-override`, `descent-override`, and `line-gap-override` font descriptors
- [Prototype](https://groups.google.com/g/mozilla.dev.platform/c/joBc4SoTOPc/m/Mwjr06tcAgAJ) CSS `glyph-scale-factor`/`size-adjust` descriptor
- [Ship](https://groups.google.com/g/mozilla.dev.platform/c/23hnabutNlA/m/VV6OTp12AgAJ) `AbortSignal.abort()` for creating an aborted `AbortSignal`
- [Ship](https://groups.google.com/g/mozilla.dev.platform/c/eWIa9XXxHsc/m/Wzs20e0kAAAJ) AV1 Image File Format (AVIF)
- [Ship](https://groups.google.com/g/mozilla.dev.platform/c/selXOOzcRkU/m/GKxYv-0kAAAJ) CSS `aspect-ratio` property
- [Prototype](https://groups.google.com/g/mozilla.dev.platform/c/K10xFE4xF58/m/sFhSXf2WAQAJ) CSS `fit-content()` function

February 2021

- [Ship](https://groups.google.com/g/mozilla.dev.platform/c/VJhM6SSQd-4/m/x3B45oatCAAJ) outlines that follow `border-radius`
- [Prototype](https://groups.google.com/g/mozilla.dev.platform/c/1MdyhPwaInw/m/2Fi4vWGXAQAJ) CSS `color-mix()` function
- [Prototype and ship](https://groups.google.com/g/mozilla.dev.platform/c/rEYMl79krS8/m/UI_kwzatCAAJ) CSS `:user-valid` and `:user-invalid` pseudo-classes
- [Prototype](https://groups.google.com/g/mozilla.dev.platform/c/4Tzs6hF4heA/m/3Bw57D9TAwAJ) outlines that follow `border-radius`

January 2021

- [Ship](https://groups.google.com/g/mozilla.dev.platform/c/C_92-abaiuw/m/GzXYMPe7AgAJ) `beforeinput` event and its `getTargetRanges` method
- [Ship](https://groups.google.com/g/mozilla.dev.platform/c/ARLg8hqDj2k/m/6hOqQYVzBwAJ) CSS `:autofill` pseudo-class

December 2020

- [Ship](https://groups.google.com/g/mozilla.dev.platform/c/uDYrtq1Ne3A/m/QCckV5y-AwAJ) Network Partitioning (incl. storage and HTTP cache partitioning)
- [Ship](https://groups.google.com/g/mozilla.dev.platform/c/K7Dq-0CyT_Q/m/l04RxJinAwAJ) `strict-origin-when-cross-origin` as default referrer policy
- [Prototype](https://groups.google.com/g/mozilla.dev.platform/c/1BUXJV3iCTM/m/r8APBo_FAAAJ) CSS `:autofill` pseudo-class
- [Unship](https://groups.google.com/g/mozilla.dev.platform/c/tc11BCenm2c/m/I1BtyaNmAAAJ) `<menu type=context>`, `<menuitem>`, and `contextMenu` property (HTML context menus)
- [Prototype and ship](https://groups.google.com/g/mozilla.dev.platform/c/KdR8-eJplCs/m/a0pVUNiTBAAJ) `signal` option for `addEventListener` method (AbortSignal)

November 2020

- [Implement and ship](https://groups.google.com/g/mozilla.dev.platform/c/DYc-4vO0D5Q/m/VJHGCUFhAQAJ) CSS `touch-action: pinch-zoom` value
- [Ship](https://groups.google.com/g/mozilla.dev.platform/c/yA2rL_2keTE/m/V0ZRCykZAAAJ) CSS `:focus-visible` pseudo-class

October 2020

- [Prototype and ship](https://groups.google.com/g/mozilla.dev.platform/c/sZdEYTiEBdE/m/PbGpLjcqAQAJ) `localhost` addresses as secure contexts (“potentially trustworthy”)
- [Ship](https://groups.google.com/g/mozilla.dev.platform/c/B3fPnRFM_yY/m/kPsyVeWzBAAJ) CSS `conic-gradient()` notation

September 2020

- [Ship](https://groups.google.com/g/mozilla.dev.platform/c/CPjGRm78JLI/m/aQTd4ulWAAAJ) Media Session API
- [Prototype](https://groups.google.com/g/mozilla.dev.platform/c/1hQQ7ISudGo/m/_yLEckEeBQAJ) CSS `math-style` property
- [Ship](https://groups.google.com/g/mozilla.dev.platform/c/LCTfPNZMWKU/m/E5mr4TmnBAAJ) `beforeinput` event and its `getTargetRanges` method
- [Prototype](https://groups.google.com/g/mozilla.dev.platform/c/p7XvnLTPRps/m/bjs_KjvQBAAJ) better error recovery for CSS `:is()` and `:where()` pseudo-classes
- [Prototype](https://groups.google.com/g/mozilla.dev.platform/c/28UyT7aO2YU/m/nAQwIFkkBAAJ) TLS Encrypted Client Hello
- [Prototype](https://groups.google.com/g/mozilla.dev.platform/c/xDj-uQVVCxc/m/GLek4FiYAQAJ) HTML `autocapitalize` attribute
- [Ship](https://groups.google.com/g/mozilla.dev.platform/c/gyrM1spEek8/m/Tp5rLtamCQAJ) `allow-downloads` keyword for the `<iframe sandbox>` attribute
- [Ship](https://groups.google.com/g/mozilla.dev.platform/c/RN-Hhmf_DyA/m/NMw4iLygAgAJ) CSS `::file-selector-button` pseudo-element

August 2020

- [Ship](https://groups.google.com/g/mozilla.dev.platform/c/zS9vCw9GMsg/m/Zd3_STiTAgAJ) `selectionchange` event for `<input>` and `<textarea>` elements
- [Prototype](https://groups.google.com/g/mozilla.dev.platform/c/O0CmHS8meNw/m/qH6cQF1uCwAJ) WebXR Layers
- [Ship](https://groups.google.com/g/mozilla.dev.platform/c/KUVVAroUv_Y/m/vKULscO_CQAJ) Redirect Tracking Protection

July 2020

- [Ship](https://groups.google.com/g/mozilla.dev.platform/c/7oQm8PC0aU0/m/9tIt7ld9BwAJ) CSS `overflow: clip` value
- [Unship](https://groups.google.com/g/mozilla.dev.platform/c/Pyvav7xbw9Y/m/MB3DXCK2BgAJ) CSS `::-moz-focus-outer` pseudo-element
- [Ship](https://groups.google.com/g/mozilla.dev.platform/c/WilU9G_vzxA/m/qiFp-oP-BgAJ) composite modes for animations
- [Prototype](https://groups.google.com/g/mozilla.dev.platform/c/gBQp1URD1lE/m/Fswh-5-ZBgAJ) Payment Handler API
- [Prototype](https://groups.google.com/g/mozilla.dev.platform/c/C4EHeQlaMbU/m/C8hNg9ehBwAJ) Sanitizer API
- [Ship](https://groups.google.com/g/mozilla.dev.platform/c/x8njjxKySKY/m/rPsQNU45BwAJ) CSS `appearance` property (unprefixed)
- [Prototype](https://groups.google.com/g/mozilla.dev.platform/c/uJfdlv1qKtQ/m/2W7PwA8uBwAJ) CSS `cross-fade()` function
- [Prototype](https://groups.google.com/g/mozilla.dev.platform/c/bTEmQxffGvA/m/_foj0Q8uBwAJ) CSS `prefers-contrast` media feature
- [Prototype](https://groups.google.com/d/msg/mozilla.dev.platform/nlun5QV63Bo/xUXCmySGAgAJ) unprefixed CSS `appearance` property

June 2020

- [Ship in Nightly](https://groups.google.com/d/msg/mozilla.dev.platform/gqi4MDQDwX8/eXCcIZNWAwAJ) HTML `<dialog>` element
- [Prototype](https://groups.google.com/d/msg/mozilla.dev.platform/DS9qGnqc_3Q/BbSSogcEAwAJ) HTML `inert` attribute
- [Prototype](https://groups.google.com/d/msg/mozilla.dev.platform/T97NRJWS8Qs/YhTfpSS_AQAJ) `enterkeyhint` attribute

May 2020

- [Ship](https://groups.google.com/d/msg/mozilla.dev.platform/eZ-UZT6rT5g/Jt82qvL5AQAJ) DOM `replaceChildren` method
- [Ship](https://groups.google.com/d/msg/mozilla.dev.platform/MShUZ4VTa6s/E4XFYfL5AQAJ) `<link rel=preload>`
- [Prototype](https://groups.google.com/d/msg/mozilla.dev.platform/mWViuwFw8b8/HVHJ8yAnAAAJ) CSS `aspect-ratio` property
- [Prototype](https://groups.google.com/d/msg/mozilla.dev.platform/70ODk1Gqrzs/CBLgePEkAAAJ) CSS `::file-chooser-button` pseudo-element
- [Prototype](https://groups.google.com/d/msg/mozilla.dev.platform/8EjoeN7NXrc/TlxdZcSpAgAJ) Schemeful Same-Site (http://example.com and https://example.com considered cross-site)
- [Ship](https://groups.google.com/d/msg/mozilla.dev.platform/3CguC7Mp3yQ/dQIFGug8AQAJ) CSS `:read-only` and `:read-write` pseudo-classes

April 2020

- [Prototype](https://groups.google.com/d/msg/mozilla.dev.platform/f2_hLdfsbq4/ZhuWE4ZAAgAJ) Dynamic First-Party Isolation
- [Prototype and ship](https://groups.google.com/d/msg/mozilla.dev.platform/_f8gYPevIQw/9X-A-2R5AQAJ) CSS `:is()` and `:where()` pseudo-classes
- [Ship](https://groups.google.com/d/msg/mozilla.dev.platform/_i1mSzhaDkQ/HCQ8CZwsAQAJ) AudioWorklet
- [Prototype](https://groups.google.com/d/msg/mozilla.dev.platform/FWdTtWSFzE0/Rsoy0cVGAgAJ) ARIA reflection

March 2020

- [Prototype and ship](https://groups.google.com/d/msg/mozilla.dev.platform/VXlDBa3SvWA/q7BZjj5iBAAJ) “Defer `<script defer>` execution until all script-blocking stylesheets are loaded”
- [Unship](https://groups.google.com/d/msg/mozilla.dev.platform/FqCZUT9ay_o/jt4DLRDjAwAJ) FTP protocol
- [Ship](https://groups.google.com/d/msg/mozilla.dev.platform/gie9ExD2-mU/7aTCCslyAAAJ) `getAnimations` method for the _Element_ and _Document_ interfaces

February 2020

- [Prototype and ship](https://groups.google.com/d/msg/mozilla.dev.platform/eh_O7G4H26Q/mFy5IambGQAJ) ARIA `suggestion`, `mark`, and `comment` roles and `aria-description` attribute (ARIA annotations)
- [Prototype](https://groups.google.com/d/msg/mozilla.dev.platform/QzmcYfffVQ4/gk8iCALCCAAJ) CSS `:focus-visible` pseudo-class
- [Prototype and ship](https://groups.google.com/d/msg/mozilla.dev.platform/i6V9W5XJjpA/DoxHJkiqBwAJ) CSS `min()`, `max()`, and `clamp()` functions
- [Implement](https://groups.google.com/d/msg/mozilla.dev.platform/CSbRi8-MrMM/wtFU1ZNcBwAJ) CSS `conic-gradient()` notation
- [Prototype and ship](https://groups.google.com/d/msg/mozilla.dev.platform/3CH2pXxTWl4/xXc4_7QJBQAJ) `<img loading>` attribute (for lazy-loading images)
- [Ship](https://groups.google.com/d/msg/mozilla.dev.platform/ZyUPHkyLun8/XvYEqPncBgAJ) `submit` event (contains `submitter` property)
- [Ship](https://groups.google.com/d/msg/mozilla.dev.platform/NB0Ht1UGoSw/KiPRi_ncBgAJ) `<form>` `requestSubmit` method

January 2020

- [Prototype](https://groups.google.com/d/msg/mozilla.dev.platform/iBKhDXB89OA/3NZ_7UGjAAAJ) masonry layout in CSS Grid
- [Ship](https://groups.google.com/d/msg/mozilla.dev.platform/acQMQCHXKZY/kIWdZ4koCwAJ) CSS `outline-style: auto` value
- [Implement](https://groups.google.com/d/msg/mozilla.dev.platform/bIM8ZaFS-d8/VwbG7okoCwAJ) AVIF image format (based on the AV1 video codec)
- [Ship](https://groups.google.com/d/msg/mozilla.dev.platform/dy72fIaeTtM/E1W3lIsoCwAJ) HTTP `Cross-Origin-Resource-Policy` header
- [Prototype](https://groups.google.com/d/msg/mozilla.dev.platform/qZ66aK0hZOY/ecdNMp5jDQAJ) `beforeinput` event
- [Ship](https://groups.google.com/d/msg/mozilla.dev.platform/FgKLdwRhCyA/RTSY3a-QDAAJ) CSS `text-underline-position` property

December 2019

- [Implement and ship](https://groups.google.com/d/msg/mozilla.dev.platform/Vd8kd41Zoew/bXgiKIViBwAJ) CSS `overscroll-behavior-inline` and `overscroll-behavior-block` properties
- [Prototype and ship](https://groups.google.com/d/msg/mozilla.dev.platform/FFUkDL33g0s/FO61jTnkBAAJ) `IDBTransaction` `commit` method
- [Prototype](https://groups.google.com/d/msg/mozilla.dev.platform/zKsl5XCB8LM/y9KgzrOcBAAJ) CSS `text-underline-position` property
- [Prototype](https://groups.google.com/d/msg/mozilla.dev.platform/wZwIB-QFugs/mLPLKbfhBAAJ) Navigation Preload for Service Worker
- [Prototype](https://groups.google.com/d/msg/mozilla.dev.platform/d4jO-DUBTE8/JDxCM7nhBAAJ) Constructable Stylesheet Objects

November 2019

- [Prototype](https://groups.google.com/d/msg/mozilla.dev.platform/BdFOMAuCGW8/-fqk-MWIAQAJ) delegated permissions for third-party iframes via the `allow` attribute
- [Ship](https://groups.google.com/d/msg/mozilla.dev.platform/dWnXJtFKY0I/WiwbWH8MAAAJ) CSS Shadow Parts
- [Ship](https://groups.google.com/d/msg/mozilla.dev.platform/4oyeCHOqt4I/ebrHWT8iBwAJ) CSS `translate`, `scale`, and `rotate` properties (individual transforms)
- [Ship](https://groups.google.com/d/msg/mozilla.dev.platform/nOOIRsuxvuc/spfjWTwiBwAJ) CSS Motion Paths
- [Ship](https://groups.google.com/d/msg/mozilla.dev.platform/Mezd5pLjnJU/jaqcJyngAgAJ) user interaction requirement for notification permission prompts

October 2019

- [Ship](https://groups.google.com/d/msg/mozilla.dev.platform/IKzfuoD77yE/-DiLKfkNDwAJ) CSS subgrid layout
- [Experiment](https://groups.google.com/d/msg/mozilla.dev.platform/SdnMKYwWxzU/a1FcX-nnCgAJ) heading level based on outline depth
- [Ship](https://groups.google.com/d/msg/mozilla.dev.platform/p80ptKoqVvk/uKJwoK6JDAAJ) CSS `column-span` property
- [Experiment](https://groups.google.com/d/msg/mozilla.dev.platform/x-ZWH5sodNk/jlipsa4EDAAJ) Web Speech API
- [Experiment](https://groups.google.com/d/msg/mozilla.dev.platform/CZ3IDkObpCs/3EdCuMwaCwAJ) Web Share Target
- [Ship](https://groups.google.com/d/msg/mozilla.dev.platform/H9j3aJ20IgE/fs9Df3loCQAJ): Infer `aspect-ratio` from image `width`/`height` attributes

September 2019

- [Ship](https://groups.google.com/d/msg/mozilla.dev.platform/2h1Nlx4_WIU/URQBNSN_BAAJ) CSS `text-decoration-skip-ink`, `text-decoration-thickness`, and `text-underline-offset` properties
- [Ship](https://groups.google.com/d/msg/mozilla.dev.platform/-VDYiEAWjw4/SspRnY1HAQAJ) event-based form participation (incl. `formdata` event)
- [Ship](https://groups.google.com/d/msg/mozilla.dev.platform/nC0DLYQsR5w/etyfo4sDAQAJ) `X-Content-Type-Options: nosniff` for navigations

August 2019

- [Ship](https://groups.google.com/d/msg/mozilla.dev.platform/RM5O36MZ4x4/FV5Tp9y4EQAJ) CSS `clip-path: path()` values
- [Implement](https://groups.google.com/d/msg/mozilla.dev.platform/eFx-93iBPpU/Hs4jUZRgDgAJ) double-keyed HTTP cache
- [Ship](https://groups.google.com/d/msg/mozilla.dev.platform/ddztUGUpYbE/YonPIdjUCwAJ) multi-keyword values for the CSS `display` property
- [Ship](https://groups.google.com/d/msg/mozilla.dev.platform/0WFI1WvBbic/2yVDD9_UCwAJ) `inline list-item` and `inline flow-root list-item` values for the CSS `display` property
- [Ship](https://groups.google.com/d/msg/mozilla.dev.platform/371s6O1xcJo/gwK89OLUCwAJ) `block ruby` value for the CSS `display` property
- [Ship](https://groups.google.com/d/msg/mozilla.dev.platform/eu2WCpjpRQA/v1Ww22aiAAAJ) CSS `font-size: xxx-large` value
- [Implement](https://groups.google.com/d/msg/mozilla.dev.platform/Xsts-2ORpRY/j96vHsIRAAAJ) CSS `text-decoration-skip-ink` property

July 2019

- [Implement](https://groups.google.com/d/msg/mozilla.dev.platform/VWcV5QUzJF0/O9hET80TAgAJ) CSS `text-decoration-width` property
- [Ship](https://groups.google.com/d/msg/mozilla.dev.platform/IgqT8s21rsQ/hddyOIIFAwAJ) percentage opacity values in CSS
- [Implement and ship](https://groups.google.com/d/msg/mozilla.dev.platform/J6Ra3i77mRQ/K3EY4p-NAgAJ) CSS `quotes: auto` value
- [Implement](https://groups.google.com/d/msg/mozilla.dev.platform/7tgkiUSa70w/6UPVgRbPCgAJ) CSS `backdrop-filter` property
- [Experiment](https://groups.google.com/d/msg/mozilla.dev.platform/RHk3QJbV_7o/YCDCWRCCCgAJ) Web Share API

June 2019

- [Experiment](https://groups.google.com/d/msg/mozilla.dev.platform/axGM9N0-jZk/SG3bRYlyCQAJ): Infer `aspect-ratio` from image `width`/`height` attributes
- [Ship](https://groups.google.com/d/msg/mozilla.dev.platform/xeODJ3-0jH4/RAz3vmY-CQAJ) CSS `@supports selector()` function
- [Implement and ship](https://groups.google.com/d/msg/mozilla.dev.platform/i71d0e4EWow/Rwsti6OhBAAJ) `webkitURL` constructor (legacy compatibility alias of `URL`)
- [Implement and ship](https://groups.google.com/d/msg/mozilla.dev.platform/RB8dwZ3_DeA/ZCaq16JxAQAJ) CSS `white-space: break-spaces` value
- [Implement and ship](https://groups.google.com/d/msg/mozilla.dev.platform/WXeYAj_ji8I/ighAqJ3DAQAJ) Resize Observer API
- [Implement](https://groups.google.com/d/msg/mozilla.dev.platform/VWcV5QUzJF0/O9hET80TAgAJ) CSS `text-decoration-width` property
- [Implement](https://groups.google.com/d/msg/mozilla.dev.platform/iwkhLi-2mxw/2aJPi80TAgAJ) CSS `text-underline-offset` property
- [Implement and ship](https://groups.google.com/d/msg/mozilla.dev.platform/-xbC8eAcy7k/6k8CsZ3xAQAJ) CSS `overflow-block` and `overflow-inline` properties
- [Implement and ship](https://groups.google.com/d/msg/mozilla.dev.platform/26MI90sjjSY/BX_TWFfwAAAJ) `text`, `arrayBuffer`, and `stream` methods on `Blob` interface

May 2019

- [Implement and ship](https://groups.google.com/d/msg/mozilla.dev.platform/QFSmwlof1_I/lHLmiFw7AgAJ) `queueMicrotask` function
- [Implement](https://groups.google.com/d/msg/mozilla.dev.platform/nx2uP0CzA9k/BNVPWDHsAQAJ) changes to cookies (add `SameSite=Lax` by default, require `Secure` for `SameSite=None`)
- [Implement](https://groups.google.com/d/msg/mozilla.dev.platform/NSpFyh3WBN4/1H1bGmROAQAJ) CSS `line-break` property
- [Ship](https://groups.google.com/d/msg/mozilla.dev.platform/Mkw_Toh9Siw/CHiWMZmAAAAJ) Visual Viewport API on Android

April 2019

- [Implement and ship](https://groups.google.com/d/msg/mozilla.dev.platform/eTt1nd1Ia_Y/x-8JIf2TCwAJ) `noreferrer` feature for `window.open` method
- [Implement and ship](https://groups.google.com/d/msg/mozilla.dev.platform/BdgNaChHnpY/mhXzCBwSCgAJ) `<link rel="stylesheet" disabled>` attribute
- [Implement and ship](https://groups.google.com/d/msg/mozilla.dev.platform/bF2yaNQ1rWs/Ndshaq-oCgAJ) `preventScroll` option for the `focus` method

March 2019

- [Implement and ship](https://groups.google.com/d/msg/mozilla.dev.platform/PSbIck_Jj4s/CG2eGjpiAwAJ) CSS `::marker` pseudo-element
- [Implement and ship](https://groups.google.com/d/msg/mozilla.dev.platform/vOGqau_-5qo/tU9IjS5iAwAJ) CSS `counter-set` property
- [Ship](https://groups.google.com/d/msg/mozilla.dev.platform/lcGPwhu1Bcg/TxZz8qz2BgAJ) CSS `contain` property
- [Ship](https://groups.google.com/d/msg/mozilla.dev.platform/Mji-LGbuPOg/heV3n1BvAwAJ) JavaScript `import()` syntax for dynamic imports
- [Implement and ship](https://groups.google.com/d/msg/mozilla.dev.platform/AvR6VqGeSJs/HgWB907xCAAJ) CSS `revert` keyword
- [Implement and ship](https://groups.google.com/d/msg/mozilla.dev.platform/s0rMvOBnO_4/AFjL0qHpAwAJ) CSS Scroll Snap

February 2019

- [Implement and ship](https://groups.google.com/d/msg/mozilla.dev.platform/VnJ49XN6flE/rKSza-TyGQAJ) CSS `prefers-color-scheme` media feature
- [Implement](https://groups.google.com/d/msg/mozilla.dev.platform/oJBDSC6ENtk/WTHh6Jm9GQAJ) CSS `-webkit-line-clamp` property
- [Implement and ship](https://groups.google.com/d/msg/mozilla.dev.platform/To_1vtUtCN0/HW3s0k-hGgAJ) `InputEvent` `data` and `dataTransfer` properties

January 2019

- [Ship](https://groups.google.com/d/msg/mozilla.dev.platform/DDQP5xIKYiY/3ppe9V-ZCgAJ) implicit `rel="noopener"` for `<a target="_blank">` elements
- [Implement and ship](https://groups.google.com/d/msg/mozilla.dev.platform/WjKAMVeKb7o/xLqWZafbEQAJ) CSS `border-block-color`, etc. properties and shorthands
- [Implement and ship](https://groups.google.com/d/msg/mozilla.dev.platform/Pjf2a6t-sFA/M8uHtP4vEgAJ) CSS `border-start-start-radius`, etc. properties
- [Implement and ship](https://groups.google.com/d/msg/mozilla.dev.platform/8dvTjUpgcqU/ndU2k8faEQAJ) CSS `inset`, `inset-block`, and `inset-inline` shorthands
- [Implement and ship](https://groups.google.com/d/msg/mozilla.dev.platform/SSDCEvyqAAE/gEFqO9jSDQAJ) CSS `margin-block` and `margin-inline` shorthands
- [Implement and ship](https://groups.google.com/d/msg/mozilla.dev.platform/gpubhXTxI6o/8CzbtxK7DQAJ) CSS `padding-block` and `padding-inline` shorthands
- [Implement](https://groups.google.com/d/msg/mozilla.dev.platform/7dykNEdqvzA/DWcGTm4tDwAJ) HTTP `Report-To` header (part of Reporting API)

December 2018

- [Implement and ship](https://groups.google.com/d/msg/mozilla.dev.platform/0XQjow3t5vY/tmgRdojAAgAJ) CSS `overflow-inline` and `overflow-block` media features
- [Ship](https://groups.google.com/d/msg/mozilla.dev.platform/BZ36ZDV0Fik/i5ZtGyN8CgAJ) Storage Access API
- [Ship](https://groups.google.com/d/msg/mozilla.dev.platform/qqPRzzvkAE0/28u0Nl-2CAAJ) `InputEvent` `inputType` property
- [Implement and ship](https://groups.google.com/d/msg/mozilla.dev.platform/NMpix5gqXlY/dbvk94zuBgAJ) `s` modifier for attribute selectors
- [Implement and ship](https://groups.google.com/d/msg/mozilla.dev.platform/pZBNiEwBhyA/KMjTYg6zBQAJ) CSS `break-before`, `break-after`, and `break-inside` properties

November 2018

- [Ship](https://groups.google.com/d/msg/mozilla.dev.platform/E8DyIJBhu1g/dggFj14MBQAJ) no `"keypress"` events when pressed key does not introduce text input
- [Ship](https://groups.google.com/d/msg/mozilla.dev.platform/DrYa0gDxI5Q/5odWBZcLBQAJ) `"keydown"` and `"keyup"` events during IME composition
- [Implement](https://groups.google.com/d/msg/mozilla.dev.platform/d4R7WIHSOMY/KqovfoeFCQAJ) implicit `rel="noopener"` for `<a target="_blank">` elements
- [Implement](https://groups.google.com/d/msg/mozilla.dev.platform/4TxLKumAOiE/Feuvlg9jAAAJ) CSS Scroll Anchoring
- [Implement](https://groups.google.com/d/msg/mozilla.dev.platform/B9VPjyia7wA/_qhevcK0BwAJ) Reporting API (`ReportingObserver`)
- [Implement and ship](https://groups.google.com/d/msg/mozilla.dev.platform/B36jo-tK9Wk/tssG8exBBgAJ) CSS `overflow-wrap: anywhere` value
- [Implement and ship](https://groups.google.com/d/msg/mozilla.dev.platform/7l8FJCEwdaI/-C9kVDXzBQAJ) image `decode` method
- [Implement and ship](https://groups.google.com/d/msg/mozilla.dev.platform/EVKyR1B87T0/_l-_qK8SAAAJ) CSS `env()` notation (environment variables)

October 2018

- [Implement](https://groups.google.com/d/msg/mozilla.dev.platform/eeyxS9WDCOs/M1dLpEFfDAAJ) `<script referrerpolicy>` attribute
- [Implement](https://groups.google.com/d/msg/mozilla.dev.platform/8xmgmr9wJhc/DKWJOQgfBAAJ) JavaScript `import()` syntax for dynamic imports
- [Implement and ship](https://groups.google.com/d/msg/mozilla.dev.platform/BBUhv8zLy7Y/_jvOE3h1BQAJ) `screenLeft` and `screenTop` properties (aliases for `screenX` and `screenY`)
- [Implement](https://groups.google.com/d/msg/mozilla.dev.platform/JNLPcIZRd2w/r6Boq0h2BQAJ) CSS `@supports` `selector` function
- [Implement and ship](https://groups.google.com/d/msg/mozilla.dev.platform/ywu0gzoQfRY/1xMM1bfUAwAJ) WebP image format

September 2018

- [Ship](https://groups.google.com/d/msg/mozilla.dev.platform/YtuN54Fi-84/6CuLmKxODAAJ) CSS `scrollbar-color` and `scrollbar-width` properties
- [Implement and ship](https://groups.google.com/d/msg/mozilla.dev.platform/oFZivEmLC40/1rHs3IuICQAJ) new cookie jar policy to block storage access from tracking resources
- [Implement and ship](https://groups.google.com/d/msg/mozilla.dev.platform/20EhEy_ahKg/2OWJTbGeCgAJ) `navigator.getDisplayMedia` method (Screen Capture)
- [Ship](https://groups.google.com/d/msg/mozilla.dev.platform/uizXjqHDmQ8/5yrdVG-LCQAJ) unprefixed Fullscreen API
- [Implement](https://groups.google.com/d/msg/mozilla.dev.platform/w3elPpZlqIE/ZA5cuKOMCAAJ) Feature Policy
- [Implement](https://groups.google.com/d/msg/mozilla.dev.platform/l8bV4RFgAc4/MKl9jbJpBQAJ) Storage Access API

August 2018

- [Implement](https://groups.google.com/d/msg/mozilla.dev.platform/YU4jPJc6p6Y/CS-f2qeOAQAJ): “Treat `-webkit-` prefixed pseudo elements as valid CSS selectors”
- [Ship](https://groups.google.com/d/msg/mozilla.dev.platform/RcanREo7hU0/TCS3Un6aBwAJ) Custom Elements and Shadow DOM
- [Implement and ship](https://groups.google.com/d/msg/mozilla.dev.platform/MQph7NaIYmM/cViEVLg0BwAJ) `block` and `inline` values for the CSS `resize` property
- [Ship](https://groups.google.com/d/msg/mozilla.dev.platform/Fq6OH5SWeRo/lxHDXFnwCQAJ) CSS `-webkit-appearance` property
- [Ship](https://groups.google.com/d/msg/mozilla.dev.platform/ef7O7PrmNh0/qy8k9HDjCQAJ) Async Clipboard API
- [Implement](https://groups.google.com/d/msg/mozilla.dev.platform/JhdWiVwgQeo/tSKKqatvCQAJ) CSS `scrollbar-width` property
- [Implement](https://groups.google.com/d/msg/mozilla.dev.platform/hWuUoeDVPQo/TNIspBwICQAJ) CSS Motion Paths
- [Implement and ship](https://groups.google.com/d/msg/mozilla.dev.platform/K-i_WXuZ_bY/1-XAkm6wCQAJ) WebXR Device API (successor to WebVR)
- [Implement and ship](https://groups.google.com/d/msg/mozilla.dev.platform/BPZHwDp_Ciw/Blo-G1tqCQAJ) `HTMLMediaElement` `allowedToPlay` property
- [Implement](https://groups.google.com/d/msg/mozilla.dev.platform/gchNtWfv_bk/kQEfdc0LBgAJ) Visual Viewport API

July 2018

- [Implement and ship](https://groups.google.com/d/msg/mozilla.dev.platform/bxyc26iatiQ/7FurvkSfCAAJ) `<img decoding>` attribute
- [Implement and ship](https://groups.google.com/d/msg/mozilla.dev.platform/faQvST2piv4/prtBa7rCBwAJ) CSS `prefers-reduced-motion` media feature (on Windows and macOS)
- [Ship](https://groups.google.com/d/msg/mozilla.dev.platform/YzuvitvaFbY/CsIPdgDXBgAJ) HTTP `Clear-Site-Data` header
- [Ship](https://groups.google.com/d/msg/mozilla.dev.platform/fcFctnUjs7A/mWv9pLMbBgAJ) Web Animations API (core interfaces)
- [Implement](https://groups.google.com/d/msg/mozilla.dev.platform/X_tv4aH4NxQ/w497k6J7CQAJ) CSS `scrollbar-face-color` and `scrollbar-track-color` properties

June 2018

- [Ship](https://groups.google.com/d/msg/mozilla.dev.platform/wwU0TW80u1g/X_V3091yCAAJ) DOM `Element` `toggleAttribute` method
- [Ship](https://groups.google.com/d/msg/mozilla.dev.platform/sSx7WPiVLbw/Dd2dPBksBQAJ) range context for CSS media queries (with limitations)
- [Ship](https://groups.google.com/d/msg/mozilla.dev.platform/IUQBiW8wDrs/Urt2rnmlAwAJ) Storage API on Android (`persist` and `estimate` methods)
- [Implement](https://groups.google.com/d/msg/mozilla.dev.platform/aDRU2iM0X-k/yTH1g65BBgAJ) HTTP `Clear-Site-Data` header
- [Ship](https://groups.google.com/d/msg/mozilla.dev.platform/KrJoz5XB8J4/pu8CMEWOAwAJ) CSS `shape-outside` property

May 2018

- [Ship](https://groups.google.com/d/msg/mozilla.dev.platform/HW64jE5y2r0/rpm3fbvgCQAJ) speech synthesis on Android (part of Web Speech API)
- [Implement and ship](https://groups.google.com/d/msg/mozilla.dev.platform/ASfzHokKin0/-EpzV-GeCwAJ) `import.meta` meta property in module scripts
- [Ship](https://groups.google.com/d/msg/mozilla.dev.platform/jKWIKsOpUwc/uM7wtRdfAQAJ) Media Capabilities API
- [Implement](https://groups.google.com/d/msg/mozilla.dev.platform/skHoHwfapEY/VQZZXvNxAQAJ) Async Clipboard API
- [Implement](https://groups.google.com/d/msg/mozilla.dev.platform/EtjfqRd9FI0/30DfQ3c6DgAJ) `AudioWorklet` interface (Web Audio API)
- [Ship](https://groups.google.com/d/msg/mozilla.dev.platform/y9KU21IBFvo/dVwVG9b1DgAJ) `Event` `srcElement` property (alias of `target` property)

April 2018

- [Ship](https://groups.google.com/d/msg/mozilla.dev.platform/MSzaY7_4mvg/hGpUlTzxAgAJ) Server Timing
- [Implement](https://groups.google.com/d/msg/mozilla.dev.platform/1ZrtZlcI888/jOr1cTRHBQAJ) `application/javascript+binast` (JavaScript Binary AST content encoding)
- [Ship](https://groups.google.com/d/msg/mozilla.dev.platform/4vy-a5_a35o/FH_KnQFGBQAJ) CSS `overflow` shorthand (accepts two values)
- [Implement](https://groups.google.com/d/msg/mozilla.dev.platform/-1SfS4jWqd8/D6aJ7XprBQAJ) CSS subgrid layout (prototype)
- [Implement and ship](https://groups.google.com/d/msg/mozilla.dev.platform/7hOKZDuO3qI/w9FVLatSAAAJ) `SameSite` attribute for cookies

March 2018

- [Ship](https://groups.google.com/d/msg/mozilla.dev.platform/MO2S2FepLPk/mhDzdc1WAAAJ) OpenType variable fonts

February 2018

- [Ship](https://groups.google.com/d/msg/mozilla.dev.platform/DZ7YctNoUUk/c2w8Ue8QCgAJ) module scripts (`<script type="module">`)
- [Implement and ship](https://groups.google.com/d/msg/mozilla.dev.platform/GRNpjC4MuH8/hjxJxwgtAgAJ) `navigator.webdriver` (Boolean) property
- [Ship](https://groups.google.com/d/msg/mozilla.dev.platform/djQGD_wRw5E/-GsC9AMaAgAJ) CSS `paint-order` property for HTML text

January 2018

- [Ship](https://groups.google.com/d/msg/mozilla.dev.platform/6fVRnF4_g8s/piNtMNxBAAAJ) CSS `overscroll-behavior` property

December 2017

- [Implement](https://groups.google.com/d/msg/mozilla.dev.platform/mogT087VmJM/1263_6MlCQAJ) CSS `paint-order` property for HTML text
- [Remove](https://groups.google.com/d/msg/mozilla.dev.platform/DcSi_wLG4fc/QI1X8SjbCgAJ) Ambient Light and Proximity Sensor APIs
- [Implement](https://groups.google.com/d/msg/mozilla.dev.platform/uidYTDXu1CE/_Ax4VvckCgAJ) CSS `translate`, `scale`, and `rotate` properties (individual transforms)
- [Ship](https://groups.google.com/d/msg/mozilla.dev.platform/tsevyqfBHLE/lccldWNNBwAJ) Web Authentication API (initially for FIDO U2F tokens)

November 2017

- [Ship](https://groups.google.com/d/msg/mozilla.dev.platform/Cy2rIx2MACc/mXn9qHsFBQAJ) CSS Shapes
- [Implement](https://groups.google.com/d/msg/mozilla.dev.platform/BI3I0U7TDw0/6-W39tXpBAAJ) Custom Elements v1
- [Implement](https://groups.google.com/d/msg/mozilla.dev.platform/aJvUlADn-Hk/BYB52MgDBQAJ) Shadow DOM v1
- [Ship](https://groups.google.com/d/msg/mozilla.dev.platform/tP_PiNFay7E/8gHVWT8OBQAJ) stricter `X-Frame-Options: SAMEORIGIN` (check all ancestor frames)
- [Ship](https://groups.google.com/d/msg/mozilla.dev.platform/H2IL9XAO8dA/EjeQA8yuAwAJ) WebVTT regions
- [Implement and ship](https://groups.google.com/d/msg/mozilla.dev.platform/lSlpiE2Y5j4/AqKZx19PAQAJ) (subclassable) `EventTarget` constructor
- [Ship](https://groups.google.com/d/msg/mozilla.dev.platform/c6PqC5RuKLs/7X9pu7m4AAAJ) CSP violation events

October 2017

- [Implement](https://groups.google.com/d/msg/mozilla.dev.platform/3hujzpw-LDA/pKl0V27zAwAJ) CSS `overscroll-behavior` property
- [Ship](https://groups.google.com/d/msg/mozilla.dev.platform/RPELgLHAhjM/gmkupELMAgAJ) Pointer Events on desktop
- [Unship](https://groups.google.com/d/msg/mozilla.dev.platform/aNUUx0S6PxE/3E3TkBXtAgAJ) `preload` link relation (temporary)
- [Ship](https://groups.google.com/d/msg/mozilla.dev.platform/1OZrP1hR_SE/d_2TOCIeAgAJ) `"navigation"` performance entry (replacement for `navigation.timing`)
- [Ship](https://groups.google.com/d/msg/mozilla.dev.platform/hcEqovQrBts/87NoUmTgAAAJ) “throttle timeouts in background tabs”
- [Implement and ship](https://groups.google.com/d/msg/mozilla.dev.platform/lw0ylqXLil0/PjYSsoHkAAAJ) Resource Timing `workerStart` property
- [Implement](https://groups.google.com/d/msg/mozilla.dev.platform/WhXB19qGVkI/J5rGuFydCAAJ) CSS interaction media features (`pointer`, `hover`, `any-pointer`, `any-hover`)
- [Ship](https://groups.google.com/d/msg/mozilla.dev.platform/t9tz_hN6WMs/qsxb169ECAAJ) `<a ping>` attribute

September 2017

- [Ship](https://groups.google.com/d/msg/mozilla.dev.platform/MCSJOhbqSVE/ce6sF7JkAAAJ) WebVR on macOS
- [Ship](https://groups.google.com/d/msg/mozilla.dev.platform/ELX9G6OOAjw/_axw46TQAAAJ) Performance Observer API

August 2017

- [Ship](https://groups.google.com/d/msg/mozilla.dev.platform/jk6XtUch4GQ/lYNjSuHDBQAJ) Abort API (`AbortController`)
- [Ship](https://groups.google.com/d/msg/mozilla.dev.platform/gPcjLOuCFWg/8hWKvdAcBQAJ) CSS `font-display` descriptor

July 2017

- [Ship](https://groups.google.com/d/msg/mozilla.dev.platform/Q8R1O_2rG6w/10xkqIUjAgAJ) `preload` link relation

May 2017

- [Ship](https://groups.google.com/d/msg/mozilla.dev.platform/s9MOnejqLsc/jSoAGdIjAwAJ) HTTP `SourceMap` response header

March 2017

- [Implement](https://groups.google.com/d/msg/mozilla.dev.platform/cnEN_sccXJY/-0W_P31cCwAJ) CSS `line-height-step` property
- [Implement and ship](https://groups.google.com/d/msg/mozilla.dev.platform/xAtirsgM86c/A_qupX7TCgAJ) CSS `::cue` pseudo-element
- [Implement](https://groups.google.com/d/msg/mozilla.dev.platform/4YST7JQysiU/65zkGTd0CQAJ) ScrollTimeline API (for creating scroll-linked animations)
- [Ship](https://groups.google.com/d/msg/mozilla.dev.platform/YdKTMvQygl0/cl2vdYt3BgAJ) Intersection Observer
- [Ship](https://groups.google.com/d/msg/mozilla.dev.platform/prq-D_PUq6w/bJQcbkT-AwAJ) CSS `frames()` timing function
- [Ship](https://groups.google.com/d/msg/mozilla.dev.platform/DsJQaLUjqhc/vjyjSr1wAgAJ) CSS `text-justify` property
- [Ship](https://groups.google.com/d/msg/mozilla.dev.platform/ssV6H4_3WGU/SJN8SgkfAgAJ) CSS `transform-box` property
- [Ship](https://groups.google.com/d/msg/mozilla.dev.platform/TB2gVavDe6w/Be2oSxwdAgAJ) WebVR (on Windows)

February 2017

- [Implement](https://groups.google.com/d/msg/mozilla.dev.platform/w-3HBnN3sc4/p1geixAzAAAJ) CSS `frames()` timing function
- [Implement and ship](https://groups.google.com/d/msg/mozilla.dev.platform/8RJ6lACmJTM/M9dDRkphBQAJ) CSS `animationcancel` event
- [Implement and ship](https://groups.google.com/d/msg/mozilla.dev.platform/B4F7jCC9jAI/A2c8c7_zBAAJ) global `origin` property (`self.origin`)
- [Implement](https://groups.google.com/d/msg/mozilla.dev.platform/I00tLlnmTYk/Tz8wcRTJBAAJ) CSS `text-justify` property
- [Ship](https://groups.google.com/d/msg/mozilla.dev.platform/X29xtxQRPJc/gxRNbLFzBAAJ) basic shape values for CSS `clip-path` property (`inset()`, `circle()`, `ellipse()`, `polygon()`)

January 2017

- [Ship](https://groups.google.com/d/msg/mozilla.dev.platform/kXX7TrKhIRw/4eS85MEwAAAJ) new syntax of CSS color functions (e.g. `rgb(0 0 0 / 100%)`)
- [Implement and ship](https://groups.google.com/d/msg/mozilla.dev.platform/WAaqNIo9Fvc/4-24kwmJAgAJ) HTTP `Large-Allocation` header (non-standard)
- [Implement](https://groups.google.com/d/msg/mozilla.dev.platform/dr67sITwva8/G3aHo1MKGAAJ) module scripts (`<script type="module">`)
- [Experiment](https://groups.google.com/d/msg/mozilla.dev.platform/uI5bHZil2KU/VPrlTdOQFQAJ) CSS Houdini Paint API Level 1

December 2016

- [Implement](https://groups.google.com/d/msg/mozilla.dev.platform/Ycr5zeYEcgs/ajxJ8nseEwAJ) CSS box alignment properties on block containers
- [Implement](https://groups.google.com/d/msg/mozilla.dev.platform/T_7HTTdt-Es/QCZVZw-zEgAJ) SVG `vector-effect` property (additional values)
- [Implement and ship](https://groups.google.com/d/msg/mozilla.dev.platform/lOpCwCMIWwo/nom3la3CEAAJ) CSS `caret-color` property
- [Implement](https://groups.google.com/d/msg/mozilla.dev.platform/vTPGW1aJq24/JnEnoH3BEAAJ) HTML5 `<dialog>` element
- [Implement and ship](https://groups.google.com/d/msg/mozilla.dev.platform/bG9Kpgr5LC4/GW4qQnD8EAAJ) CSS `display: flow-root` value
- [Implement and ship](https://groups.google.com/d/msg/mozilla.dev.platform/YdFwg3VpGMg/t9FO09meEAAJ) Selection `setBaseAndExtent` method
- [Ship](https://groups.google.com/d/msg/mozilla.dev.platform/15nssyOe1gc/PCt1uWkBDwAJ) CSS `mask-image` property (repeated intent)
- [Ship](https://groups.google.com/d/msg/mozilla.dev.platform/lCZmhCDGHPY/hq3CgPkFDwAJ) Network Information API
- [Implement](https://groups.google.com/d/msg/mozilla.dev.platform/Js-pI-6dSQA/ZtsgzJWdDgAJ) “Store IndexedDB databases for the lifetime of private browsing sessions”
- [Implement](https://groups.google.com/d/msg/mozilla.dev.platform/_FacI6Aw2BQ/hUHKggjFDAAJ) OpenType variable fonts
- [Ship](https://groups.google.com/d/msg/mozilla.dev.platform/Q-dSrp4PYe4/hS7r9Y3OCwAJ) Presentation API (on Android)

November 2016

- [Implement](https://groups.google.com/d/msg/mozilla.dev.platform/1K_Uq_fx1l4/Yc93M2P2CgAJ) Web2Native Bridge
- [Implement](https://groups.google.com/d/msg/mozilla.dev.platform/B9bIszPlVX4/3OVBjLBTCQAJ) CSS `background-repeat-x`/`background-repeat-y` and `mask-repeat-x`/`mask-repeat-y` properties
- [Implement](https://groups.google.com/d/msg/mozilla.dev.platform/n-2o58jcTK8/sFisJf6pCAAJ) Payment Request API
- [Ship](https://groups.google.com/d/msg/mozilla.dev.platform/6shk3TZX5vo/avSCrtLCBgAJ) CSS Grid Layout
- [Implement and ship](https://groups.google.com/d/msg/mozilla.dev.platform/F0rCRF8z87E/CPh7dIJ9BQAJ) Web Authentication API
- [Ship](https://groups.google.com/d/msg/mozilla.dev.platform/PYPzrwNh6kA/_ErvsqkEAwAJ) `requestIdleCallback` function

October 2016

- [Implement and ship](https://groups.google.com/d/msg/mozilla.dev.platform/Yy4WAqnGxGo/8bUPmXyJBgAJ) `transitionrun`, `transitionstart`, and `transitioncancel` events
- [Ship](https://groups.google.com/d/msg/mozilla.dev.platform/sfeqeMkyxCI/J04LFWcnBgAJ) TLS 1.3 (draft 16)
- [Implement](https://groups.google.com/d/msg/mozilla.dev.platform/PhG4Upk4Mo4/ie0Mr2xsBAAJ) CSS `shape-outside` property
- [Ship](https://groups.google.com/d/msg/mozilla.dev.platform/mziFttqlkDM/t-CHVMJCBAAJ) Selection API events (`selectionstart`, `selectionchange`)
- [Ship](https://groups.google.com/d/msg/mozilla.dev.platform/6CGjsm1XpD4/GDbW6mCDAQAJ) CSS `touch-action` property (only Level 1 values)

September 2016

- [Implement](https://groups.google.com/d/msg/mozilla.dev.platform/FO-x9WCJfxM/yfH9YpnDBQAJ) CSS `initial-letter` property
- [Implement and ship](https://groups.google.com/d/msg/mozilla.dev.platform/UnBVw8R4Kl0/tOIqsr0qBAAJ) global `isSecureContext` property in workers
- [Ship](https://groups.google.com/d/msg/mozilla.dev.platform/-stfRvwwEHU/J5P1mzlHAwAJ) Storage API `estimate` method
- [Implement](https://groups.google.com/d/msg/mozilla.dev.platform/dYn5Fel_p-M/3sPPJvLqCQAJ) Canvas 2d context `getTransform`/`setTransform` methods

August 2016

- [Ship](https://groups.google.com/d/msg/mozilla.dev.platform/ozygu09pg_o/ux577V_zBAAJ) Canvas 2D context `imageSmoothingEnabled` property
- [Implement](https://groups.google.com/d/msg/mozilla.dev.platform/PR_AP6i-xIo/YQ_qTJqyBAAJ) `transitionstart` event
- [Implement and ship](https://groups.google.com/d/msg/mozilla.dev.platform/S1_0_G6lqAs/7C4P3xb4AwAJ) HTML `minlength` attribute and `tooShort` validity state
- [Implement and ship](https://groups.google.com/d/msg/mozilla.dev.platform/Ja4GCMopHVg/0D2Zu4VNAQAJ) `dataset` API on SVG elements

July 2016

- [Implement and ship](https://groups.google.com/d/msg/mozilla.dev.platform/YnTqCbrusb0/ENLHDcUhBAAJ) `forEach` method on NodeList and DOMTokenList
- [Ship]() Blink’s Entries API (`webkitGetAsEntry` method) incl. file input `webkitdirectory` attribute
- [Ship](https://groups.google.com/d/msg/mozilla.dev.platform/UwD8xIPNK0c/CBlM4FxiAwAJ) (unprefixed) CSS `:any-link` pseudo-class
- [Implement](https://groups.google.com/d/msg/mozilla.dev.platform/mC06HKQ45hs/np7OxIYYCgAJ) MediaDevices `devicechange` event
- [Implement and ship](https://groups.google.com/d/msg/mozilla.dev.platform/acFKZpcVw8o/8s9L4lPyCQAJ) MediaStreamTrack `getConstraints` and `getSettings` methods
- [Implement](https://groups.google.com/d/msg/mozilla.dev.platform/CNmJeMkUv88/oLmZacPECAAJ) CSS Properties and Values API
- [Implement and ship](https://groups.google.com/d/msg/mozilla.dev.platform/U_drxJ1LCQE/YL6TGfELCAAJ) `once` option for `addEventListener` method
- [Implement and ship](https://groups.google.com/d/msg/mozilla.dev.platform/32Z6O50rM5k/Fbx9lRaQBwAJ) `__Secure-`/`__Host-` cookie prefixes
- [Ship](https://groups.google.com/d/msg/mozilla.dev.platform/SYEzvXJKw9M/eGhL0RAKBwAJ) CSS `touch-action` property
- [Implement and ship](https://groups.google.com/d/msg/mozilla.dev.platform/NGms9X06tW8/ZK5jthS3BQAJ) “Force flattening of `transform-style: preserve-3d` when opacity is applied”

June 2016

- [Implement and ship](https://groups.google.com/d/msg/mozilla.dev.platform/azNSLhfv978/Rb2evmprBQAJ) Service Worker `WindowClient.navigate` method
- [Ship](https://groups.google.com/d/msg/mozilla.dev.platform/6lMOvomdZFU/Q1AScq2SAgAJ) CSS `mask-image` property

May 2016

- [Ship](https://groups.google.com/d/msg/mozilla.dev.platform/KaFZG0WoJnw/DqI5UA0OPAAJ) filters in 2D canvas
- [Ship](https://groups.google.com/d/msg/mozilla.dev.platform/jbMO8mkFZwE/ATXLMHECPAAJ) unprefixed CSS `text-align-last` property
- [Implement and ship](https://groups.google.com/d/msg/mozilla.dev.platform/VzYoDjzn1CE/-YmQS3LpOwAJ) HTMLMediaElement `seekToNextFrame` method (non-standard)
- [Ship](https://groups.google.com/d/msg/mozilla.dev.platform/S4Aicrg9uiA/XRAsBB75OgAJ) `PerformanceObserver` API
- [Unship](https://groups.google.com/d/msg/mozilla.dev.platform/tgXlkRhF6wo/aVVSmT6mOQAJ) HTML microdata API
- [Implement and ship](https://groups.google.com/d/msg/mozilla.dev.platform/ohoKhFTv80w/P8x5ToZ0AAAJ) `space`/`round` values for CSS `background-repeat` property
- [Ship](https://groups.google.com/d/msg/mozilla.dev.platform/F0_UbXAfB_4/TvkG6SwbAAAJ) unprefixed CSS `:dir` pseudo-class
- [Implement and ship](https://groups.google.com/d/msg/mozilla.dev.platform/00Tq2s58GwA/OSO6V33dAAAJ) 8 and 4-digit hex color notation (#RRGGBBAA and #RGBA)
- [Implement and ship](https://groups.google.com/d/msg/mozilla.dev.platform/cOpESN6_osE/W9zB7m3eAAAJ) “sandbox propagates to auxiliary browsing contexts” flag (`allow-popups-to-escape-sandbox` keyword)
- [Implement and ship](https://groups.google.com/d/msg/mozilla.dev.platform/02aLOHxPqKA/6Y673m7eAAAJ) “sandboxed modals” flag (`allow-modals` keyword)
- [Implement and ship](https://groups.google.com/d/msg/mozilla.dev.platform/xgdSNY6-Dn0/ORLCyeu0AAAJ) passive event listeners (`passive` option)
- [Implement and ship](https://groups.google.com/d/msg/mozilla.dev.platform/YFRTGKaY5-g/vgam5EksAAAJ) `DOMTokenList.prototype.supports` property

April 2016

- [Ship](https://groups.google.com/d/msg/mozilla.dev.platform/5FwFLRW5bBE/lYHzKIb0AwAJ) Speech Synthesis API
- [Implement and ship](https://groups.google.com/d/msg/mozilla.dev.platform/2gjY07E0D5E/6MxWoygDAwAJ) `"noopener"` link relation
- [Ship](https://groups.google.com/d/msg/mozilla.dev.platform/wouDQLBbm9A/D9K5e2PIAQAJ) “Restrict `geolocation.watchPosition` to secure contexts”
- [Ship](https://groups.google.com/d/msg/mozilla.dev.platform/1cTAxTf916c/-9fwpSORAQAJ) basic shapes (`polygon` et al) for CSS `clip-path` property
- [Implement](https://groups.google.com/d/msg/mozilla.dev.platform/q6AQnTEeX6o/dqS48DbtAwAJ) `requestIdleCallback` function
- [Ship](https://groups.google.com/d/msg/mozilla.dev.platform/2INRr96R3IU/do-AigNwAwAJ) `Element.animate` method
- [Ship](https://groups.google.com/d/msg/mozilla.dev.platform/SeuzXf0mdRs/Z1x-wh-hAwAJ) ParentNode `prepend`, `append`, `before`, `after`, `replaceWith` methods
- [Ship](https://groups.google.com/d/msg/mozilla.dev.platform/v11adKDvK04/W05rm0f0AgAJ) `document.scrollingElement` property
- [Ship](https://groups.google.com/d/msg/mozilla.dev.platform/OrUOw3ag258/Te3rqqRLAgAJ) “Treat cookies set over non-secure HTTP as session cookies”
- [Ship](https://groups.google.com/d/msg/mozilla.dev.platform/FCQSOydoE-8/YeAp3VZIAgAJ) HTML `<details>` and `<summary>` elements
- [Implement and ship](https://groups.google.com/d/msg/mozilla.dev.platform/d_zmnSd_yts/guM1BxZHAgAJ) CSS `-webkit-text-stroke` property

March 2016

- [Implement](https://groups.google.com/d/msg/mozilla.dev.platform/eEm0CPr8lGI/x0AZZxzgCAAJ) CSS `-webkit-background-clip: text`
- [Implement and ship](https://groups.google.com/d/msg/mozilla.dev.platform/RKTuYDrsnvo/ysG8aeLhCAAJ) CSS `text-combine-upright: all`
- [Ship](https://groups.google.com/d/msg/mozilla.dev.platform/1ExwWZOmV74/BerMieDzBgAJ) `navigator.hardwareConcurrency`
- [Implement](https://groups.google.com/d/msg/mozilla.dev.platform/uqDMOCfDhMQ/KcGlZnWaBQAJ) Credential Management API
- [Ship](https://groups.google.com/d/msg/mozilla.dev.platform/RN7bLChacKM/EdqbE7i2AwAJ) CSS `color-adjust` property
- [Implement](https://groups.google.com/d/msg/mozilla.dev.platform/Bp02mJMc7V4/O1iYSRsjAwAJ) Push API in Firefox for Android

February 2016

- [Implement and ship](https://groups.google.com/d/msg/mozilla.dev.platform/hmFYDmGlzRU/vQNnYWOnAQAJ) `IDBKeyRange.includes()`
- [Implement and ship](https://groups.google.com/d/msg/mozilla.dev.platform/UWqtgnztHts/ENmvJiSQAQAJ) `fetch()` referrer and Referrer Policy API

January 2016

- [Implement and ship](https://groups.google.com/d/msg/mozilla.dev.platform/Hcudhkexz8A/YvafGQcnAgAJ) `document.elementsFromPoint` method

December 2015

- [Implement and ship](https://groups.google.com/d/msg/mozilla.dev.platform/969k-Iryiyo/LsqkHKZ0BAAJ) Support for a subset of `-webkit-` prefixed CSS properties and features
- [Implement](https://groups.google.com/d/msg/mozilla.dev.platform/cTAnBeZFtUE/kx0I4UC-AQAJ) One-off Background Sync API
- [Ship](https://groups.google.com/d/msg/mozilla.dev.platform/TXFImc_r9Jo/iW_5u0ICCwAJ) `referrerpolicy` attribute
- [Implement and ship](https://groups.google.com/d/msg/mozilla.dev.platform/IVGEJnQW3Uo/Eu5tvyLmCgAJ) FIDO U2F API

November 2015

- [Ship](https://groups.google.com/d/msg/mozilla.dev.platform/2gn7ywXZ6e4/5R6JdndvBwAJ) Service Workers with FetchEvent
- [Implement](https://groups.google.com/d/msg/mozilla.dev.platform/b0UMDIasfq8/tW49QLgCBwAJ) HTML `<details>` and `<summary>` elements
- [Implement and ship](https://groups.google.com/d/msg/mozilla.dev.platform/Udt3psYNFuY/7qDFZK8sBwAJ) `Performance.translateTime` method
- [Ship](https://groups.google.com/d/msg/mozilla.dev.platform/QFJO6aqQwIs/Miln8pb4BgAJ) CSS `unicode-range` descriptor
- [Implement and ship](https://groups.google.com/d/msg/mozilla.dev.platform/uWyfl_szAcw/y-2EsjRhBgAJ) CSS Emphasis Marks (`text-emphasis` property)
- [Ship](https://groups.google.com/d/msg/mozilla.dev.platform/P6_ADO2sOxE/48RwgUE4BAAJ) CSS Mask Image properties
- [Ship](https://groups.google.com/d/msg/mozilla.dev.platform/bRDUCA4tb84/_c1Ch4T2AQAJ) Web Speech API - Synthesis

October 2015

- [Ship](https://groups.google.com/d/msg/mozilla.dev.platform/BeVaHGEgZNA/vIVnbrLgBwAJ) WebVR
- [Implement and ship](https://groups.google.com/d/msg/mozilla.dev.platform/N3i7Yc2UpR0/huNQI2fVBQAJ) `window.orientation` and `'orientationchange'` event
- [Implement and ship](https://groups.google.com/d/msg/mozilla.dev.platform/pH98pOjGgX4/u1D_zBiVBAAJ) `::backdrop pseudo-element` for Fullscreen API
