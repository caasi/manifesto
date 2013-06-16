The Extensible Web Manifesto
============================

可擴充的全球資訊網宣言
======================

We—the undersigned—advocate a change to the approach that web standards committees use to create and prioritize new features. We believe that this is critical to the long-term health of the web.

我們，即簽署者，主張改變，網頁標準委員會過去創造與決定新功能優先次序的途徑。我們相信這對網路的長期健康十分重要。

Our primary goal is to tighten the feedback loop between the editors of web standards and web developers. We prefer an evolutionary model of standardization, driven by the vast army of web developers, to a top-down model of progress driven by standardization.

我們的主要目標是讓標準制定者與開發者間的回饋循環更緊密。我們偏好進化式的標準化模型，由開發者大軍驅動，更勝於從上而下，由標準驅動的模型。

Browser vendors should provide new low-level capabilities that expose the possibilities of the underlying platform as closely as possible. They should seed the discussion of high-level APIs through JavaScript implementations of new features (as done in the cases of [Mozilla’s X-Tags](http://www.x-tags.org/) and [Google’s Polymer](http://www.polymer-project.org/)). This involves web developers in the process and by iterating outside of the browser, avoids the platform getting stuck with bad APIs.

瀏覽器供應商應該提供，可以顯露下層平台所有可能性的新低階能力。藉由 JavaScript 的實作結果，為高階 API 相關討論播種（就像[ Mozilla 的 X-Tags ](http://www.x-tags.org/)與[ Google 的 Polymer ](http://www.polymer-project.org/)正在做的）。讓開發者能在瀏覽器外參與標準化過程，避免平台本身被壞 API 卡住。

Specifically, we offer the following design principles for an Extensible Web Platform:
* The standards process should focus on adding ***_new low-level capabilities_*** to the web platform that are secure and efficient.
* The web platform should expose low-level capabilities that ***_explain existing features_***, such as HTML and CSS, allowing authors to understand and replicate them.
* The web platform should develop, describe and test new high-level features in JavaScript, and allow web developers to iterate on them before they become standardized. This creates a ***_virtuous cycle_*** between standards and developers.
* The standards process should ***_prioritize efforts_*** that follow these recommendations and deprioritize and refocus those which do not.

具體地說，我們對可擴充的全球資訊網，提出以下設計原則：
* 標準過程應該專注在為網頁平台增加安全且有效率的***_新低階能力_***。
* 網頁平台應該揭露，可以***_解釋現有功能_***的低階能力，例如 HTML 與 CSS ，讓開發者能瞭解並重製它們。
* 網頁平台應該以 JavaScript 開發、描述與測試新的高階功能，使開發者在這些功能標準化前能漸進改善它們。這在標準與開發者間建立起一種***_良善的循環_***。
* 標準過程應該***_優先處理_***那些遵循以上建議的工作，反之則並降低它們的優先權。

------

By focusing on standardizing ***_new low-level capabilities_***, and building new features in terms of them, we:
* Contain new security surface area.
* Allow optimizations in browser engines to focus on the stable core, which affects more APIs as they are added. This leads to better performance with less implementation effort.
* Allow browser vendors and library authors to iterate on libraries that provide developer-friendly, high-level APIs.

By explaining existing and new features ***_in terms of low-level capabilities_***, we:
* Reduce the rate of growth in complexity, and therefore bugs, in implementations.
* Make it possible to polyfill more of the platform's new features.
* Require less developer education for new features. Educational materials can build off of concepts that are already in the platform.

Making new features easy to understand and polyfill introduces a ***_virtuous cycle_***:
* Developers can ramp up more quickly on new APIs, providing quicker feedback to the platform while the APIs are still the most malleable.
* Mistakes in APIs can be corrected quickly by the developers who use them, and library authors who serve them, providing high-fidelity, critical feedback to browser vendors and platform designers.
* Library authors can experiment with new APIs and create more cow-paths for the platform to pave.

By ***_prioritizing efforts_*** that follow these principles, we:
* Free up the standards process (especially in the short-term) to focus on features with security or performance concerns, and features that can only be added at the platform level, such as new hardware.
* Allow web developers and browser-initiated libraries to take the lead in costly explorations.
* Simplify and streamline the longer-term process of standardizing new APIs, which will already have implementations and significant real-world usage.


We want web developers to write more declarative code, not less. This calls for eliminating the standards bottleneck to introducing new declarative forms, and giving library and framework authors the tools to create them.


In order for the open web to compete with its walled competitors, there must be a clear path for good ideas by web developers to become part of the infrastructure of the web. We must enable web developers to build the future web.


In support of these principles,

* Brendan Eich <br>
CTO and SVP Engineering, Mozilla; Creator of JavaScript

* Yehuda Katz <br>
Member, TC39, W3C TAG; Core Team, Ember.js, Rails

* Alex Russell <br>
TC39, W3C TAG; Google Chrome Team

* Brian Kardell <br>
Chair, Extensible Web Community Group, W3C

* François REMY <br>
Co-founder, Extensible Web Community Group, W3C

* Clint Hill <br>
Co-founder, Extensible Web Community Group, W3C

* Marcos Caceres <br> 
Co-founder, Extensible Web Community Group, W3C

* Tom Dale <br>
Core Team, Ember.js

* Anne van Kesteren <br>
Editor of standards, Architecture Astronaut at Mozilla

* Sam Tobin-Hochstadt <br>
Member, TC39

* Domenic Denicola <br>
Co-Editor, Promises/A+

* Chris Eppstein <br>
Maintainer, Sass

* Dave Herman <br>
Mozilla Research and TC39

* Alan Stearns <br>
Member, CSSWG

* Rick Waldron <br>
Member, TC39

* Paul Irish <br>
Google

* Ted Han <br>
Lead Developer, DocumentCloud

* Tab Atkins <br>
Member, CSS WG; Google

-----

**Related reading**
* [Extend the Web Forward](http://yehudakatz.com/2013/05/21/extend-the-web-forward/), by Yehuda Katz, which fleshes out these ideas more.
* [An Extensible Approach to Browser Security Policy](http://yehudakatz.com/2013/05/24/an-extensible-approach-to-browser-security-policy/), by Yehuda Katz, which presents a practical application of these principles to the problem of designing an API for the browser's Content Security Policy.
* [Dropping the F-Bomb on Web Standards](https://briankardell.wordpress.com/2013/05/17/dropping-the-f-bomb/), by Brian Kardell, a practical discussion of how ideas and language from the developer community can be integrated back into interoperable standards.
* [Bedrock](http://infrequently.org/2012/04/bedrock/), by Alex Russell, a 2012 post that explores, in-depth, the philosophy and practice of designing the platform in an extensible ("layered") way.
