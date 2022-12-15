# ScrabbleDictionary


## Project structure ##

<pre>
package Dictionary{
    
    package Trie{
        
        public class WordTrie Implements Trie;
        protected class TrieNode Implements Map<Character, TrieNode>;
        public interface Trie;
        
        package RegexMatcher {
        
            package RegexSymbol {
                public class LetterSymbol implements RegexSymbol;
                public class DotSymbol implements RegexSymbol;
                public class StarSymbol implements RegexSymbol;
                public interface RegexSymbol;
            }
            
            public class Pattern;
             
        }
        
    }
}
</pre>
