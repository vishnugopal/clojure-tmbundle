## Prerequisites

The Clojure bundle depends on the following external utilities to work:

* ruby
* osascript

If either of those aren't on your Textmate's PATH, these commands will fail in unknown and spectacular fashion.

Additionally, if clj is not found on your Textmate's PATH, then it will use the one included in this bundle. You can manually specify it with the TM_CLJ variable.

## Installation

* Run this:
 
<pre>
cd ~/Library/Application\ Support/TextMate/Bundles
git clone git://github.com/stephenroller/clojure-tmbundle.git Clojure.tmbundle
osascript -e 'tell app "TextMate" to reload bundles'
</pre>

## Future goals

I hope to incorporate either nullstyle's REPL or make my own. The vendor clojure implementation has readline support, but not completions. I might use the clj suggested on the clojure wiki instead.