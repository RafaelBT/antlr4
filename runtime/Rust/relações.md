ANTLRErrorListener (interface)
    BaseErrorListener (classe)
    ProxyErrorListener (classe)

ANTLRErrorStrategy (interface)
    DefaultErrorStrategy (classe)

ANTLRInputStream (classe) (deprecated)
    ANTLRFileStream (classe) (deprecated)

BaseErrorListener (classe)
    ConsoleErrorListener (classe)
    DiagnosticErrorListener (classe)
    XPathLexerErrorListener (classe)

BufferedTokenStream (classe)
    CommonTokenStream (classe)

CharStreams (final)

CodePointBuffer (classe)

IntStream (interface)
    CharStream (interface)
        ANTLRInputStream (classe) (deprecated)
        CodePointCharStream (abstract)
    TokenStream (interface)
        BufferedTokenStream (classe)
            CommonTokenStream (classe)
        UnbufferedTokenStream (classe) (genérico)

Lexer (abstract)
    LexerInterpreter (classe)
    XPathLexer (classe)

Parser (abstract)
    ParserInterpreter (classe)

RecognitionException (classe) (externalidade)
    FailedPredicateException (classe)
    InputMismatchException (classe)
    LexerNoViableAltException (classe)
    NoViableAltException (classe)

Recognizer (abstract) (genérico)
    Lexer (abstract)
        LexerInterpreter (classe)
        XPathLexer (classe)
    Parser (abstract)
        ParserInterpreter (classe)

RuleContext (classe)
    ParserRuleContext (classe)
        RuleContextWithAltNum (classe)

RuntimeMetaData (classe)

Token (interface)
    Parser
    TokenFactory
    WritableToken (interface)
        CommonToken (classe) (externalidade)
            CommonTokenFactory (classe) (genérico)
            TokenTagToken (classe)

TokenSource (interface)
    ListTokenSource (classe)

Vocabulary (interface)
    VocabularyImpl (classe)

ATN (classe)

ATNConfig (classe)
    ATNConfigSet (classe) (genérico) (externalidade)
        OrderedATNConfigSet
    LexerATNConfig (classe)

ATNDeserializationOptions (classe)

ATNDeserializer (classe)

ATNSerializer (classe)

ATNSimulator (abstrata)
    Recognizer (genérico)
    LexerATNSimulator (classe)
    ParserATNSimulator (classe)
        ProfilingATNSimulator (classe)

ATNState (abstrata)
    BasicState (final)
    BlockEndState (final)
    DecisionState (abstrata)
        BlockStartState (abstrata)
            BasicBlockStartState (final)
            PlusBlockStartState (final)
            StarBlockStartState (final)
        PlusLoopbackState (final)
        StarLoopEntryState (final)
        TokensStartState (final)
    LoopEndState (final)
    RuleStartState (final)
    RuleStopState (final)
    StarLoopbackState (final)

ATNType (enum)

CodePointTransitions (abstrata)

DecisionEventInfo (classe)
    AmbiguityInfo (classe)
    ErrorInfo (classe)
    LookaheadEventInfo (classe)
    PredicateEvalInfo (classe)

DecisionInfo (classe)

LexerAction (interface)
    LexerChannelAction (final)
    LexerCustomAction (final)
    LexerIndexedCustomAction (final)
    LexerModeAction (final)
    LexerMoreAction (final)
    LexerPopModeAction (final)
    LexerPushModeAction (final)
    LexerSkipAction (final)
    LexerTypeAction (final)

LL1Analyzer (classe)

ParseInfo (classe)

PredictionContext (abstrata)
    ArrayPredictionContext (classe)
    SingletonPredictionContext (classe)

PredictionContextCache (classe)

PredictionMode (enum)

SemanticContext (abstrata)

Transition (abstrata)
    AbstractPredicateTransition (abstrata)
        PrecedencePredicateTransition (final)
        PredicateTransition (final)
    ActionTransition (final)
    AtomTransition (final)
    EpsilonTransition (final)
    RangeTransition (final)
    RuleTransition (final)
    SetTransition (classe)
        NotSetTransition (final)
    WildcardTransition (final)

DFA (classe)

DFASerializer (classe)
    LexerDFASerializer (classe)

DFAState (classe)

Array2DHashSet (classe) (externalidade)

DoubleKeyMap (classe)

EqualityComparator (interface)
    AbstractEqualityComparator (abstrata)
        ObjectEqualityComparator (final)

FlexibleHashMap (classe) (externalidade)

IntegerList (classe)
    IntegerStack (classe)

InterpreterDataReader (classe)

Interval (classe)

IntSet (interface)
    IntervalSet (classe)

LogManager (classe)

MultiMap (classe) (externalidade)

MurmurHash  (final)

NotNull (interface) (obsoleta)

OrderedHashSet (classe) (externalidade)

Pair (classe) (externalidade)

ParseCancellationException (classe) (externalidade)

Predicate (interface)

TestRig (classe) (obsoleta)

Triple (classe)

Utils (classe)

ParseTreeListener (interface)

ParseTreeProperty (classe)

ParseTreeVisitor (interface)
    AbstractParseTreeVisitor (abstrata)

ParseTreeWalker (classe)
    IterativeParseTreeWalker (classe)

Tree (interface)
    SyntaxTree (interface)
        ParseTree (interface)
            RuleNode (interface)
                RuleContext (classe)
                    ParserRuleContext (classe)
                        InterpreterRuleContext (classe)
                        RuleContextWithAltNum (classe)
            TerminalNode (interface)
                ErrorNode (interface)
                    ErrorNodeImpl (classe)
                TerminalNodeImpl (classe)
                    ErrorNodeImpl (classe)

Trees

Chunk (abstrata)
    TagChunk (privada)
    TextChunk (privada)

XPath (classe)

XPathElement (abstrata)
    XPathRuleAnywhereElement (classe)
    XPathRuleElement (classe)
    XPathTokenAnywhereElement (classe)
    XPathTokenElement (classe)
    XPathWildcardAnywhereElement (classe)
    XPathWildcardElement (classe)
