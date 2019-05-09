<!-- NewPage --></p> 

<script type="text/javascript"><!--
    try {
        if (location.href.indexOf('is-external=true') == -1) {
            parent.document.title="KeyboardFocusManager (Java Platform SE 8 )";
        }
    }
    catch(err) {
    }
//-->
var methods = {"i0":10,"i1":10,"i2":10,"i3":10,"i4":10,"i5":10,"i6":10,"i7":10,"i8":6,"i9":6,"i10":6,"i11":6,"i12":10,"i13":6,"i14":6,"i15":10,"i16":10,"i17":10,"i18":6,"i19":10,"i20":6,"i21":10,"i22":10,"i23":9,"i24":10,"i25":10,"i26":10,"i27":10,"i28":10,"i29":10,"i30":10,"i31":10,"i32":10,"i33":10,"i34":10,"i35":10,"i36":10,"i37":10,"i38":10,"i39":10,"i40":6,"i41":6,"i42":10,"i43":10,"i44":10,"i45":10,"i46":10,"i47":10,"i48":10,"i49":9,"i50":10,"i51":10,"i52":10,"i53":10,"i54":10,"i55":10,"i56":10,"i57":10,"i58":6};
var tabs = {65535:["t0","All Methods"],1:["t1","Static Methods"],2:["t2","Instance Methods"],4:["t3","Abstract Methods"],8:["t4","Concrete Methods"]};
var altColor = "altColor";
var rowColor = "rowColor";
var tableTab = "tableTab";
var activeTableTab = "activeTableTab";
</script>

<noscript>
<div>JavaScript is disabled on your browser.</div>
</noscript>

<!-- ========= START OF TOP NAVBAR ======= -->

<div class="topNav">
  <a name="navbar.top"> <!--   --></a>
<div class="skipNav"><a href="#skip.navbar.top" title="Skip navigation links">Skip navigation links</a></div>
<a name="navbar.top.firstrow">
<!--   -->
</a>
  
  <ul class="navList" title="Navigation">
    
<li><a href="../../overview-summary.html">Overview</a></li>
<li><a href="package-summary.html">Package</a></li>
<li class="navBarCell1Rev">Class</li>
<li><a href="class-use/KeyboardFocusManager.html">Use</a></li>
<li><a href="package-tree.html">Tree</a></li>
<li><a href="../../deprecated-list.html">Deprecated</a></li>
<li><a href="../../index-files/index-1.html">Index</a></li>
<li><a href="../../help-doc.html">Help</a></li>
  </ul>
<div class="aboutLanguage"><strong>Java&trade;&nbsp;Platform<br>Standard&nbsp;Ed.&nbsp;8</strong></div>
</div>

<div class="subNav">
  <ul class="navList">
    
<li><a href="../../java/awt/JobAttributes.SidesType.html" title="class in java.awt"><span class="typeNameLink">Prev&nbsp;Class</span></a></li>
<li><a href="../../java/awt/KeyEventDispatcher.html" title="interface in java.awt"><span class="typeNameLink">Next&nbsp;Class</span></a></li>
  </ul>
  
  <ul class="navList">
    
<li><a href="../../index.html?java/awt/KeyboardFocusManager.html" target="_top">Frames</a></li>
<li><a href="KeyboardFocusManager.html" target="_top">No&nbsp;Frames</a></li>
  </ul>
<ul class="navList" id="allclasses_navbar_top">
<li><a href="../../allclasses-noframe.html">All&nbsp;Classes</a></li>
</ul>
  
  <div>
    
<script type="text/javascript"><!--
  allClassesLink = document.getElementById("allclasses_navbar_top");
  if(window==top) {
    allClassesLink.style.display = "block";
  }
  else {
    allClassesLink.style.display = "none";
  }
  //-->
</script>
  </div>
  
  <div>
    <ul class="subNavList">
      
<li>Summary:&nbsp;</li>
<li>Nested&nbsp;|&nbsp;</li>
<li><a href="#field.summary">Field</a>&nbsp;|&nbsp;</li>
<li><a href="#constructor.summary">Constr</a>&nbsp;|&nbsp;</li>
<li><a href="#method.summary">Method</a></li>
    </ul>
    
    <ul class="subNavList">
      
<li>Detail:&nbsp;</li>
<li><a href="#field.detail">Field</a>&nbsp;|&nbsp;</li>
<li><a href="#constructor.detail">Constr</a>&nbsp;|&nbsp;</li>
<li><a href="#method.detail">Method</a></li>
    </ul>
  </div>
<a name="skip.navbar.top">
<!--   -->
</a></div>

<!-- ========= END OF TOP NAVBAR ========= -->

<!-- ======== START OF CLASS DATA ======== -->

<div class="header">
  
<div class="subTitle">java.awt</div>
<h2 title="Class KeyboardFocusManager" class="title">Class KeyboardFocusManager</h2>
</div>

<div class="contentContainer">
  <ul class="inheritance">
    
<li><a href="../../java/lang/Object.html" title="class in java.lang">java.lang.Object</a></li>
    
    <li>
      
<ul class="inheritance">
<li>java.awt.KeyboardFocusManager</li>
</ul>
    </li>
  </ul>
  
  <div class="description">
    <ul class="blockList">
      <li class="blockList">
        <dl>
          
<dt>All Implemented Interfaces:</dt>
<dd><a href="../../java/awt/KeyEventDispatcher.html" title="interface in java.awt">KeyEventDispatcher</a>, <a href="../../java/awt/KeyEventPostProcessor.html" title="interface in java.awt">KeyEventPostProcessor</a></dd>
        </dl>
        <dl>
          
<dt>Direct Known Subclasses:</dt>
<dd><a href="../../java/awt/DefaultKeyboardFocusManager.html" title="class in java.awt">DefaultKeyboardFocusManager</a></dd>
        </dl>
        <hr />
        
        <br /> <pre>public abstract class <span class="typeNameLabel">KeyboardFocusManager</span>
extends <a href="../../java/lang/Object.html" title="class in java.lang">Object</a>
implements <a href="../../java/awt/KeyEventDispatcher.html" title="interface in java.awt">KeyEventDispatcher</a>, <a href="../../java/awt/KeyEventPostProcessor.html" title="interface in java.awt">KeyEventPostProcessor</a></pre>
        <div class="block">
          The KeyboardFocusManager is responsible for managing the active and focused Windows, and the current focus owner. The focus owner is defined as the Component in an application that will typically receive all KeyEvents generated by the user. The focused Window is the Window that is, or contains, the focus owner. Only a Frame or a Dialog can be the active Window. The native windowing system may denote the active Window or its children with special decorations, such as a highlighted title bar. The active Window is always either the focused Window, or the first Frame or Dialog that is an owner of the focused Window. 
          
          <p>
            The KeyboardFocusManager is both a centralized location for client code to query for the focus owner and initiate focus changes, and an event dispatcher for all FocusEvents, WindowEvents related to focus, and KeyEvents. 
            
            <p>
              Some browsers partition applets in different code bases into separate contexts, and establish walls between these contexts. In such a scenario, there will be one KeyboardFocusManager per context. Other browsers place all applets into the same context, implying that there will be only a single, global KeyboardFocusManager for all applets. This behavior is implementation-dependent. Consult your browser's documentation for more information. No matter how many contexts there may be, however, there can never be more than one focus owner, focused Window, or active Window, per ClassLoader. 
              
              <p>
                Please see <a href="https://docs.oracle.com/javase/tutorial/uiswing/misc/focus.html"> How to Use the Focus Subsystem</a>, a section in <em>The Java Tutorial</em>, and the <a href="../../java/awt/doc-files/FocusSpec.html">Focus Specification</a> for more information.</div> 
                
                <dl>
                  
<dt><span class="simpleTagLabel">Since:</span></dt>
<dd>1.4</dd>
<dt><span class="seeLabel">See Also:</span></dt>
                  
                  <dd>
                    <a href="../../java/awt/Window.html" title="class in java.awt"><code>Window</code></a>, 
<a href="../../java/awt/Frame.html" title="class in java.awt"><code>Frame</code></a>, 
<a href="../../java/awt/Dialog.html" title="class in java.awt"><code>Dialog</code></a>, 
<a href="../../java/awt/event/FocusEvent.html" title="class in java.awt.event"><code>FocusEvent</code></a>, 
<a href="../../java/awt/event/WindowEvent.html" title="class in java.awt.event"><code>WindowEvent</code></a>, 
<a href="../../java/awt/event/KeyEvent.html" title="class in java.awt.event"><code>KeyEvent</code></a>                  </dd>
                </dl></li> </ul> </div> 
                
                <div class="summary">
                  <ul class="blockList">
                    <li class="blockList">
                      <!-- =========== FIELD SUMMARY =========== -->
                      
                      <ul class="blockList">
                        <li class="blockList">
                          <a name="field.summary"> <!--   --></a>
<h3>Field Summary</h3>
                          
                          <table class="memberSummary" border="0" cellpadding="3" cellspacing="0" summary="Field Summary table, listing fields, and an explanation">
                            
<caption><span>Fields</span><span class="tabEnd">&nbsp;</span></caption>
                            
                            <tr>
                              
<th class="colFirst" scope="col">Modifier and Type</th>
<th class="colLast" scope="col">Field and Description</th>
                            </tr>
                            
                            <tr class="altColor">
                              
<td class="colFirst"><code>static int</code></td>
                              
                              <td class="colLast">
                                <code>&lt;span class="memberNameLink">&lt;a href="../../java/awt/KeyboardFocusManager.html#BACKWARD_TRAVERSAL_KEYS">BACKWARD_TRAVERSAL_KEYS&lt;/a>&lt;/span></code>
<div class="block">The identifier for the Backward focus traversal keys.</div>
                              </td>
                            </tr>
                            
                            <tr class="rowColor">
                              
<td class="colFirst"><code>static int</code></td>
                              
                              <td class="colLast">
                                <code>&lt;span class="memberNameLink">&lt;a href="../../java/awt/KeyboardFocusManager.html#DOWN_CYCLE_TRAVERSAL_KEYS">DOWN_CYCLE_TRAVERSAL_KEYS&lt;/a>&lt;/span></code>
<div class="block">The identifier for the Down Cycle focus traversal keys.</div>
                              </td>
                            </tr>
                            
                            <tr class="altColor">
                              
<td class="colFirst"><code>static int</code></td>
                              
                              <td class="colLast">
                                <code>&lt;span class="memberNameLink">&lt;a href="../../java/awt/KeyboardFocusManager.html#FORWARD_TRAVERSAL_KEYS">FORWARD_TRAVERSAL_KEYS&lt;/a>&lt;/span></code>
<div class="block">The identifier for the Forward focus traversal keys.</div>
                              </td>
                            </tr>
                            
                            <tr class="rowColor">
                              
<td class="colFirst"><code>static int</code></td>
                              
                              <td class="colLast">
                                <code>&lt;span class="memberNameLink">&lt;a href="../../java/awt/KeyboardFocusManager.html#UP_CYCLE_TRAVERSAL_KEYS">UP_CYCLE_TRAVERSAL_KEYS&lt;/a>&lt;/span></code>
<div class="block">The identifier for the Up Cycle focus traversal keys.</div>
                              </td>
                            </tr>
                          </table>
                        </li>
                      </ul>
                      
                      <!-- ======== CONSTRUCTOR SUMMARY ======== -->
                      
                      <ul class="blockList">
                        <li class="blockList">
                          <a name="constructor.summary"> <!--   --></a>
<h3>Constructor Summary</h3>
                          
                          <table class="memberSummary" border="0" cellpadding="3" cellspacing="0" summary="Constructor Summary table, listing constructors, and an explanation">
                            
<caption><span>Constructors</span><span class="tabEnd">&nbsp;</span></caption>
<tr>
<th class="colOne" scope="col">Constructor and Description</th>
</tr>
                            
                            <tr class="altColor">
                              <td class="colOne">
                                <code>&lt;span class="memberNameLink">&lt;a href="../../java/awt/KeyboardFocusManager.html#KeyboardFocusManager--">KeyboardFocusManager&lt;/a>&lt;/span>()</code>
<div class="block">Initializes a KeyboardFocusManager.</div>
                              </td>
                            </tr>
                          </table>
                        </li>
                      </ul>
                      
                      <!-- ========== METHOD SUMMARY =========== -->
                      
                      <ul class="blockList">
                        <li class="blockList">
                          <a name="method.summary"> <!--   --></a>
<h3>Method Summary</h3>
                          
                          <table class="memberSummary" border="0" cellpadding="3" cellspacing="0" summary="Method Summary table, listing methods, and an explanation">
                            
<caption><span id="t0" class="activeTableTab"><span>All Methods</span><span class="tabEnd">&nbsp;</span></span><span id="t1" class="tableTab"><span><a href="javascript:show(1);">Static Methods</a></span><span class="tabEnd">&nbsp;</span></span><span id="t2" class="tableTab"><span><a href="javascript:show(2);">Instance Methods</a></span><span class="tabEnd">&nbsp;</span></span><span id="t3" class="tableTab"><span><a href="javascript:show(4);">Abstract Methods</a></span><span class="tabEnd">&nbsp;</span></span><span id="t4" class="tableTab"><span><a href="javascript:show(8);">Concrete Methods</a></span><span class="tabEnd">&nbsp;</span></span></caption>
                            
                            <tr>
                              
<th class="colFirst" scope="col">Modifier and Type</th>
<th class="colLast" scope="col">Method and Description</th>
                            </tr>
                            
                            <tr id="i0" class="altColor">
                              
<td class="colFirst"><code>void</code></td>
                              
                              <td class="colLast">
                                <code>&lt;span class="memberNameLink">&lt;a href="../../java/awt/KeyboardFocusManager.html#addKeyEventDispatcher-java.awt.KeyEventDispatcher-">addKeyEventDispatcher&lt;/a>&lt;/span>(&lt;a href="../../java/awt/KeyEventDispatcher.html" title="interface in java.awt">KeyEventDispatcher&lt;/a>&nbsp;dispatcher)</code> 
                                
                                <div class="block">
                                  Adds a KeyEventDispatcher to this KeyboardFocusManager's dispatcher chain.
                                </div>
                              </td>
                            </tr>
                            
                            <tr id="i1" class="rowColor">
                              
<td class="colFirst"><code>void</code></td>
                              
                              <td class="colLast">
                                <code>&lt;span class="memberNameLink">&lt;a href="../../java/awt/KeyboardFocusManager.html#addKeyEventPostProcessor-java.awt.KeyEventPostProcessor-">addKeyEventPostProcessor&lt;/a>&lt;/span>(&lt;a href="../../java/awt/KeyEventPostProcessor.html" title="interface in java.awt">KeyEventPostProcessor&lt;/a>&nbsp;processor)</code> 
                                
                                <div class="block">
                                  Adds a KeyEventPostProcessor to this KeyboardFocusManager's post- processor chain.
                                </div>
                              </td>
                            </tr>
                            
                            <tr id="i2" class="altColor">
                              
<td class="colFirst"><code>void</code></td>
                              
                              <td class="colLast">
                                <code>&lt;span class="memberNameLink">&lt;a href="../../java/awt/KeyboardFocusManager.html#addPropertyChangeListener-java.beans.PropertyChangeListener-">addPropertyChangeListener&lt;/a>&lt;/span>(&lt;a href="../../java/beans/PropertyChangeListener.html" title="interface in java.beans">PropertyChangeListener&lt;/a>&nbsp;listener)</code>
<div class="block">Adds a PropertyChangeListener to the listener list.</div>
                              </td>
                            </tr>
                            
                            <tr id="i3" class="rowColor">
                              
<td class="colFirst"><code>void</code></td>
                              
                              <td class="colLast">
                                <code>&lt;span class="memberNameLink">&lt;a href="../../java/awt/KeyboardFocusManager.html#addPropertyChangeListener-java.lang.String-java.beans.PropertyChangeListener-">addPropertyChangeListener&lt;/a>&lt;/span>(&lt;a href="../../java/lang/String.html" title="class in java.lang">String&lt;/a>&nbsp;propertyName,
                         &lt;a href="../../java/beans/PropertyChangeListener.html" title="interface in java.beans">PropertyChangeListener&lt;/a>&nbsp;listener)</code> 
                                
                                <div class="block">
                                  Adds a PropertyChangeListener to the listener list for a specific property.
                                </div>
                              </td>
                            </tr>
                            
                            <tr id="i4" class="altColor">
                              
<td class="colFirst"><code>void</code></td>
                              
                              <td class="colLast">
                                <code>&lt;span class="memberNameLink">&lt;a href="../../java/awt/KeyboardFocusManager.html#addVetoableChangeListener-java.lang.String-java.beans.VetoableChangeListener-">addVetoableChangeListener&lt;/a>&lt;/span>(&lt;a href="../../java/lang/String.html" title="class in java.lang">String&lt;/a>&nbsp;propertyName,
                         &lt;a href="../../java/beans/VetoableChangeListener.html" title="interface in java.beans">VetoableChangeListener&lt;/a>&nbsp;listener)</code> 
                                
                                <div class="block">
                                  Adds a VetoableChangeListener to the listener list for a specific property.
                                </div>
                              </td>
                            </tr>
                            
                            <tr id="i5" class="rowColor">
                              
<td class="colFirst"><code>void</code></td>
                              
                              <td class="colLast">
                                <code>&lt;span class="memberNameLink">&lt;a href="../../java/awt/KeyboardFocusManager.html#addVetoableChangeListener-java.beans.VetoableChangeListener-">addVetoableChangeListener&lt;/a>&lt;/span>(&lt;a href="../../java/beans/VetoableChangeListener.html" title="interface in java.beans">VetoableChangeListener&lt;/a>&nbsp;listener)</code>
<div class="block">Adds a VetoableChangeListener to the listener list.</div>
                              </td>
                            </tr>
                            
                            <tr id="i6" class="altColor">
                              
<td class="colFirst"><code>void</code></td>
                              
                              <td class="colLast">
                                <code>&lt;span class="memberNameLink">&lt;a href="../../java/awt/KeyboardFocusManager.html#clearFocusOwner--">clearFocusOwner&lt;/a>&lt;/span>()</code> 
                                
                                <div class="block">
                                  Clears the focus owner at both the Java and native levels if the focus owner exists and resides in the same context as the calling thread, otherwise the method returns silently.
                                </div>
                              </td>
                            </tr>
                            
                            <tr id="i7" class="rowColor">
                              
<td class="colFirst"><code>void</code></td>
                              
                              <td class="colLast">
                                <code>&lt;span class="memberNameLink">&lt;a href="../../java/awt/KeyboardFocusManager.html#clearGlobalFocusOwner--">clearGlobalFocusOwner&lt;/a>&lt;/span>()</code>
<div class="block">Clears the global focus owner at both the Java and native levels.</div>
                              </td>
                            </tr>
                            
                            <tr id="i8" class="altColor">
                              
<td class="colFirst"><code>protected abstract void</code></td>
                              
                              <td class="colLast">
                                <code>&lt;span class="memberNameLink">&lt;a href="../../java/awt/KeyboardFocusManager.html#dequeueKeyEvents-long-java.awt.Component-">dequeueKeyEvents&lt;/a>&lt;/span>(long&nbsp;after,
                &lt;a href="../../java/awt/Component.html" title="class in java.awt">Component&lt;/a>&nbsp;untilFocused)</code> 
                                
                                <div class="block">
                                  Called by the AWT to notify the KeyboardFocusManager that it should cancel delayed dispatching of KeyEvents.
                                </div>
                              </td>
                            </tr>
                            
                            <tr id="i9" class="rowColor">
                              
<td class="colFirst"><code>protected abstract void</code></td>
                              
                              <td class="colLast">
                                <code>&lt;span class="memberNameLink">&lt;a href="../../java/awt/KeyboardFocusManager.html#discardKeyEvents-java.awt.Component-">discardKeyEvents&lt;/a>&lt;/span>(&lt;a href="../../java/awt/Component.html" title="class in java.awt">Component&lt;/a>&nbsp;comp)</code> 
                                
                                <div class="block">
                                  Called by the AWT to notify the KeyboardFocusManager that it should cancel delayed dispatching of KeyEvents.
                                </div>
                              </td>
                            </tr>
                            
                            <tr id="i10" class="altColor">
                              
<td class="colFirst"><code>abstract boolean</code></td>
                              
                              <td class="colLast">
                                <code>&lt;span class="memberNameLink">&lt;a href="../../java/awt/KeyboardFocusManager.html#dispatchEvent-java.awt.AWTEvent-">dispatchEvent&lt;/a>&lt;/span>(&lt;a href="../../java/awt/AWTEvent.html" title="class in java.awt">AWTEvent&lt;/a>&nbsp;e)</code> 
                                
                                <div class="block">
                                  This method is called by the AWT event dispatcher requesting that the current KeyboardFocusManager dispatch the specified event on its behalf.
                                </div>
                              </td>
                            </tr>
                            
                            <tr id="i11" class="rowColor">
                              
<td class="colFirst"><code>abstract boolean</code></td>
                              
                              <td class="colLast">
                                <code>&lt;span class="memberNameLink">&lt;a href="../../java/awt/KeyboardFocusManager.html#dispatchKeyEvent-java.awt.event.KeyEvent-">dispatchKeyEvent&lt;/a>&lt;/span>(&lt;a href="../../java/awt/event/KeyEvent.html" title="class in java.awt.event">KeyEvent&lt;/a>&nbsp;e)</code> 
                                
                                <div class="block">
                                  Typically this method will be called by <code>dispatchEvent</code> if no other KeyEventDispatcher in the dispatcher chain dispatched the KeyEvent, or if no other KeyEventDispatchers are registered.
                                </div>
                              </td>
                            </tr>
                            
                            <tr id="i12" class="altColor">
                              
<td class="colFirst"><code>void</code></td>
                              
                              <td class="colLast">
                                <code>&lt;span class="memberNameLink">&lt;a href="../../java/awt/KeyboardFocusManager.html#downFocusCycle--">downFocusCycle&lt;/a>&lt;/span>()</code> 
                                
                                <div class="block">
                                  Moves the focus down one focus traversal cycle from the current focus owner, if and only if the current focus owner is a Container that is a focus cycle root.
                                </div>
                              </td>
                            </tr>
                            
                            <tr id="i13" class="rowColor">
                              
<td class="colFirst"><code>abstract void</code></td>
                              
                              <td class="colLast">
                                <code>&lt;span class="memberNameLink">&lt;a href="../../java/awt/KeyboardFocusManager.html#downFocusCycle-java.awt.Container-">downFocusCycle&lt;/a>&lt;/span>(&lt;a href="../../java/awt/Container.html" title="class in java.awt">Container&lt;/a>&nbsp;aContainer)</code>
<div class="block">Moves the focus down one focus traversal cycle.</div>
                              </td>
                            </tr>
                            
                            <tr id="i14" class="altColor">
                              
<td class="colFirst"><code>protected abstract void</code></td>
                              
                              <td class="colLast">
                                <code>&lt;span class="memberNameLink">&lt;a href="../../java/awt/KeyboardFocusManager.html#enqueueKeyEvents-long-java.awt.Component-">enqueueKeyEvents&lt;/a>&lt;/span>(long&nbsp;after,
                &lt;a href="../../java/awt/Component.html" title="class in java.awt">Component&lt;/a>&nbsp;untilFocused)</code> 
                                
                                <div class="block">
                                  Called by the AWT to notify the KeyboardFocusManager that it should delay dispatching of KeyEvents until the specified Component becomes the focus owner.
                                </div>
                              </td>
                            </tr>
                            
                            <tr id="i15" class="rowColor">
                              
<td class="colFirst"><code>protected void</code></td>
                              
                              <td class="colLast">
                                <code>&lt;span class="memberNameLink">&lt;a href="../../java/awt/KeyboardFocusManager.html#firePropertyChange-java.lang.String-java.lang.Object-java.lang.Object-">firePropertyChange&lt;/a>&lt;/span>(&lt;a href="../../java/lang/String.html" title="class in java.lang">String&lt;/a>&nbsp;propertyName,
                  &lt;a href="../../java/lang/Object.html" title="class in java.lang">Object&lt;/a>&nbsp;oldValue,
                  &lt;a href="../../java/lang/Object.html" title="class in java.lang">Object&lt;/a>&nbsp;newValue)</code>
<div class="block">Fires a PropertyChangeEvent in response to a change in a bound property.</div>
                              </td>
                            </tr>
                            
                            <tr id="i16" class="altColor">
                              
<td class="colFirst"><code>protected void</code></td>
                              
                              <td class="colLast">
                                <code>&lt;span class="memberNameLink">&lt;a href="../../java/awt/KeyboardFocusManager.html#fireVetoableChange-java.lang.String-java.lang.Object-java.lang.Object-">fireVetoableChange&lt;/a>&lt;/span>(&lt;a href="../../java/lang/String.html" title="class in java.lang">String&lt;/a>&nbsp;propertyName,
                  &lt;a href="../../java/lang/Object.html" title="class in java.lang">Object&lt;/a>&nbsp;oldValue,
                  &lt;a href="../../java/lang/Object.html" title="class in java.lang">Object&lt;/a>&nbsp;newValue)</code> 
                                
                                <div class="block">
                                  Fires a PropertyChangeEvent in response to a change in a vetoable property.
                                </div>
                              </td>
                            </tr>
                            
                            <tr id="i17" class="rowColor">
                              
<td class="colFirst"><code>void</code></td>
                              
                              <td class="colLast">
                                <code>&lt;span class="memberNameLink">&lt;a href="../../java/awt/KeyboardFocusManager.html#focusNextComponent--">focusNextComponent&lt;/a>&lt;/span>()</code>
<div class="block">Focuses the Component after the current focus owner.</div>
                              </td>
                            </tr>
                            
                            <tr id="i18" class="altColor">
                              
<td class="colFirst"><code>abstract void</code></td>
                              
                              <td class="colLast">
                                <code>&lt;span class="memberNameLink">&lt;a href="../../java/awt/KeyboardFocusManager.html#focusNextComponent-java.awt.Component-">focusNextComponent&lt;/a>&lt;/span>(&lt;a href="../../java/awt/Component.html" title="class in java.awt">Component&lt;/a>&nbsp;aComponent)</code> 
                                
                                <div class="block">
                                  Focuses the Component after aComponent, typically based on a FocusTraversalPolicy.
                                </div>
                              </td>
                            </tr>
                            
                            <tr id="i19" class="rowColor">
                              
<td class="colFirst"><code>void</code></td>
                              
                              <td class="colLast">
                                <code>&lt;span class="memberNameLink">&lt;a href="../../java/awt/KeyboardFocusManager.html#focusPreviousComponent--">focusPreviousComponent&lt;/a>&lt;/span>()</code>
<div class="block">Focuses the Component before the current focus owner.</div>
                              </td>
                            </tr>
                            
                            <tr id="i20" class="altColor">
                              
<td class="colFirst"><code>abstract void</code></td>
                              
                              <td class="colLast">
                                <code>&lt;span class="memberNameLink">&lt;a href="../../java/awt/KeyboardFocusManager.html#focusPreviousComponent-java.awt.Component-">focusPreviousComponent&lt;/a>&lt;/span>(&lt;a href="../../java/awt/Component.html" title="class in java.awt">Component&lt;/a>&nbsp;aComponent)</code> 
                                
                                <div class="block">
                                  Focuses the Component before aComponent, typically based on a FocusTraversalPolicy.
                                </div>
                              </td>
                            </tr>
                            
                            <tr id="i21" class="rowColor">
                              
<td class="colFirst"><code><a href="../../java/awt/Window.html" title="class in java.awt">Window</a></code></td>
                              
                              <td class="colLast">
                                <code>&lt;span class="memberNameLink">&lt;a href="../../java/awt/KeyboardFocusManager.html#getActiveWindow--">getActiveWindow&lt;/a>&lt;/span>()</code> 
                                
                                <div class="block">
                                  Returns the active Window, if the active Window is in the same context as the calling thread.
                                </div>
                              </td>
                            </tr>
                            
                            <tr id="i22" class="altColor">
                              
<td class="colFirst"><code><a href="../../java/awt/Container.html" title="class in java.awt">Container</a></code></td>
                              
                              <td class="colLast">
                                <code>&lt;span class="memberNameLink">&lt;a href="../../java/awt/KeyboardFocusManager.html#getCurrentFocusCycleRoot--">getCurrentFocusCycleRoot&lt;/a>&lt;/span>()</code> 
                                
                                <div class="block">
                                  Returns the current focus cycle root, if the current focus cycle root is in the same context as the calling thread.
                                </div>
                              </td>
                            </tr>
                            
                            <tr id="i23" class="rowColor">
                              
<td class="colFirst"><code>static <a href="../../java/awt/KeyboardFocusManager.html" title="class in java.awt">KeyboardFocusManager</a></code></td>
                              
                              <td class="colLast">
                                <code>&lt;span class="memberNameLink">&lt;a href="../../java/awt/KeyboardFocusManager.html#getCurrentKeyboardFocusManager--">getCurrentKeyboardFocusManager&lt;/a>&lt;/span>()</code> 
                                
                                <div class="block">
                                  Returns the current KeyboardFocusManager instance for the calling thread's context.
                                </div>
                              </td>
                            </tr>
                            
                            <tr id="i24" class="altColor">
                              
<td class="colFirst"><code><a href="../../java/util/Set.html" title="interface in java.util">Set</a>&lt;<a href="../../java/awt/AWTKeyStroke.html" title="class in java.awt">AWTKeyStroke</a>&gt;</code></td>
                              
                              <td class="colLast">
                                <code>&lt;span class="memberNameLink">&lt;a href="../../java/awt/KeyboardFocusManager.html#getDefaultFocusTraversalKeys-int-">getDefaultFocusTraversalKeys&lt;/a>&lt;/span>(int&nbsp;id)</code> 
                                
                                <div class="block">
                                  Returns a Set of default focus traversal keys for a given traversal operation.
                                </div>
                              </td>
                            </tr>
                            
                            <tr id="i25" class="rowColor">
                              
<td class="colFirst"><code><a href="../../java/awt/FocusTraversalPolicy.html" title="class in java.awt">FocusTraversalPolicy</a></code></td>
                              
                              <td class="colLast">
                                <code>&lt;span class="memberNameLink">&lt;a href="../../java/awt/KeyboardFocusManager.html#getDefaultFocusTraversalPolicy--">getDefaultFocusTraversalPolicy&lt;/a>&lt;/span>()</code>
<div class="block">Returns the default FocusTraversalPolicy.</div>
                              </td>
                            </tr>
                            
                            <tr id="i26" class="altColor">
                              
<td class="colFirst"><code><a href="../../java/awt/Window.html" title="class in java.awt">Window</a></code></td>
                              
                              <td class="colLast">
                                <code>&lt;span class="memberNameLink">&lt;a href="../../java/awt/KeyboardFocusManager.html#getFocusedWindow--">getFocusedWindow&lt;/a>&lt;/span>()</code> 
                                
                                <div class="block">
                                  Returns the focused Window, if the focused Window is in the same context as the calling thread.
                                </div>
                              </td>
                            </tr>
                            
                            <tr id="i27" class="rowColor">
                              
<td class="colFirst"><code><a href="../../java/awt/Component.html" title="class in java.awt">Component</a></code></td>
                              
                              <td class="colLast">
                                <code>&lt;span class="memberNameLink">&lt;a href="../../java/awt/KeyboardFocusManager.html#getFocusOwner--">getFocusOwner&lt;/a>&lt;/span>()</code> 
                                
                                <div class="block">
                                  Returns the focus owner, if the focus owner is in the same context as the calling thread.
                                </div>
                              </td>
                            </tr>
                            
                            <tr id="i28" class="altColor">
                              
<td class="colFirst"><code>protected <a href="../../java/awt/Window.html" title="class in java.awt">Window</a></code></td>
                              
                              <td class="colLast">
                                <code>&lt;span class="memberNameLink">&lt;a href="../../java/awt/KeyboardFocusManager.html#getGlobalActiveWindow--">getGlobalActiveWindow&lt;/a>&lt;/span>()</code> 
                                
                                <div class="block">
                                  Returns the active Window, even if the calling thread is in a different context than the active Window.
                                </div>
                              </td>
                            </tr>
                            
                            <tr id="i29" class="rowColor">
                              
<td class="colFirst"><code>protected <a href="../../java/awt/Container.html" title="class in java.awt">Container</a></code></td>
                              
                              <td class="colLast">
                                <code>&lt;span class="memberNameLink">&lt;a href="../../java/awt/KeyboardFocusManager.html#getGlobalCurrentFocusCycleRoot--">getGlobalCurrentFocusCycleRoot&lt;/a>&lt;/span>()</code> 
                                
                                <div class="block">
                                  Returns the current focus cycle root, even if the calling thread is in a different context than the current focus cycle root.
                                </div>
                              </td>
                            </tr>
                            
                            <tr id="i30" class="altColor">
                              
<td class="colFirst"><code>protected <a href="../../java/awt/Window.html" title="class in java.awt">Window</a></code></td>
                              
                              <td class="colLast">
                                <code>&lt;span class="memberNameLink">&lt;a href="../../java/awt/KeyboardFocusManager.html#getGlobalFocusedWindow--">getGlobalFocusedWindow&lt;/a>&lt;/span>()</code> 
                                
                                <div class="block">
                                  Returns the focused Window, even if the calling thread is in a different context than the focused Window.
                                </div>
                              </td>
                            </tr>
                            
                            <tr id="i31" class="rowColor">
                              
<td class="colFirst"><code>protected <a href="../../java/awt/Component.html" title="class in java.awt">Component</a></code></td>
                              
                              <td class="colLast">
                                <code>&lt;span class="memberNameLink">&lt;a href="../../java/awt/KeyboardFocusManager.html#getGlobalFocusOwner--">getGlobalFocusOwner&lt;/a>&lt;/span>()</code> 
                                
                                <div class="block">
                                  Returns the focus owner, even if the calling thread is in a different context than the focus owner.
                                </div>
                              </td>
                            </tr>
                            
                            <tr id="i32" class="altColor">
                              
<td class="colFirst"><code>protected <a href="../../java/awt/Component.html" title="class in java.awt">Component</a></code></td>
                              
                              <td class="colLast">
                                <code>&lt;span class="memberNameLink">&lt;a href="../../java/awt/KeyboardFocusManager.html#getGlobalPermanentFocusOwner--">getGlobalPermanentFocusOwner&lt;/a>&lt;/span>()</code> 
                                
                                <div class="block">
                                  Returns the permanent focus owner, even if the calling thread is in a different context than the permanent focus owner.
                                </div>
                              </td>
                            </tr>
                            
                            <tr id="i33" class="rowColor">
                              
<td class="colFirst"><code>protected <a href="../../java/util/List.html" title="interface in java.util">List</a>&lt;<a href="../../java/awt/KeyEventDispatcher.html" title="interface in java.awt">KeyEventDispatcher</a>&gt;</code></td>
                              
                              <td class="colLast">
                                <code>&lt;span class="memberNameLink">&lt;a href="../../java/awt/KeyboardFocusManager.html#getKeyEventDispatchers--">getKeyEventDispatchers&lt;/a>&lt;/span>()</code>
<div class="block">Returns this KeyboardFocusManager's KeyEventDispatcher chain as a List.</div>
                              </td>
                            </tr>
                            
                            <tr id="i34" class="altColor">
                              
<td class="colFirst"><code>protected <a href="../../java/util/List.html" title="interface in java.util">List</a>&lt;<a href="../../java/awt/KeyEventPostProcessor.html" title="interface in java.awt">KeyEventPostProcessor</a>&gt;</code></td>
                              
                              <td class="colLast">
                                <code>&lt;span class="memberNameLink">&lt;a href="../../java/awt/KeyboardFocusManager.html#getKeyEventPostProcessors--">getKeyEventPostProcessors&lt;/a>&lt;/span>()</code> 
                                
                                <div class="block">
                                  Returns this KeyboardFocusManager's KeyEventPostProcessor chain as a List.
                                </div>
                              </td>
                            </tr>
                            
                            <tr id="i35" class="rowColor">
                              
<td class="colFirst"><code><a href="../../java/awt/Component.html" title="class in java.awt">Component</a></code></td>
                              
                              <td class="colLast">
                                <code>&lt;span class="memberNameLink">&lt;a href="../../java/awt/KeyboardFocusManager.html#getPermanentFocusOwner--">getPermanentFocusOwner&lt;/a>&lt;/span>()</code> 
                                
                                <div class="block">
                                  Returns the permanent focus owner, if the permanent focus owner is in the same context as the calling thread.
                                </div>
                              </td>
                            </tr>
                            
                            <tr id="i36" class="altColor">
                              
<td class="colFirst"><code><a href="../../java/beans/PropertyChangeListener.html" title="interface in java.beans">PropertyChangeListener</a>[]</code></td>
                              
                              <td class="colLast">
                                <code>&lt;span class="memberNameLink">&lt;a href="../../java/awt/KeyboardFocusManager.html#getPropertyChangeListeners--">getPropertyChangeListeners&lt;/a>&lt;/span>()</code> 
                                
                                <div class="block">
                                  Returns an array of all the property change listeners registered on this keyboard focus manager.
                                </div>
                              </td>
                            </tr>
                            
                            <tr id="i37" class="rowColor">
                              
<td class="colFirst"><code><a href="../../java/beans/PropertyChangeListener.html" title="interface in java.beans">PropertyChangeListener</a>[]</code></td>
                              
                              <td class="colLast">
                                <code>&lt;span class="memberNameLink">&lt;a href="../../java/awt/KeyboardFocusManager.html#getPropertyChangeListeners-java.lang.String-">getPropertyChangeListeners&lt;/a>&lt;/span>(&lt;a href="../../java/lang/String.html" title="class in java.lang">String&lt;/a>&nbsp;propertyName)</code> 
                                
                                <div class="block">
                                  Returns an array of all the <code>PropertyChangeListener</code>s associated with the named property.
                                </div>
                              </td>
                            </tr>
                            
                            <tr id="i38" class="altColor">
                              
<td class="colFirst"><code><a href="../../java/beans/VetoableChangeListener.html" title="interface in java.beans">VetoableChangeListener</a>[]</code></td>
                              
                              <td class="colLast">
                                <code>&lt;span class="memberNameLink">&lt;a href="../../java/awt/KeyboardFocusManager.html#getVetoableChangeListeners--">getVetoableChangeListeners&lt;/a>&lt;/span>()</code> 
                                
                                <div class="block">
                                  Returns an array of all the vetoable change listeners registered on this keyboard focus manager.
                                </div>
                              </td>
                            </tr>
                            
                            <tr id="i39" class="rowColor">
                              
<td class="colFirst"><code><a href="../../java/beans/VetoableChangeListener.html" title="interface in java.beans">VetoableChangeListener</a>[]</code></td>
                              
                              <td class="colLast">
                                <code>&lt;span class="memberNameLink">&lt;a href="../../java/awt/KeyboardFocusManager.html#getVetoableChangeListeners-java.lang.String-">getVetoableChangeListeners&lt;/a>&lt;/span>(&lt;a href="../../java/lang/String.html" title="class in java.lang">String&lt;/a>&nbsp;propertyName)</code> 
                                
                                <div class="block">
                                  Returns an array of all the <code>VetoableChangeListener</code>s associated with the named property.
                                </div>
                              </td>
                            </tr>
                            
                            <tr id="i40" class="altColor">
                              
<td class="colFirst"><code>abstract boolean</code></td>
                              
                              <td class="colLast">
                                <code>&lt;span class="memberNameLink">&lt;a href="../../java/awt/KeyboardFocusManager.html#postProcessKeyEvent-java.awt.event.KeyEvent-">postProcessKeyEvent&lt;/a>&lt;/span>(&lt;a href="../../java/awt/event/KeyEvent.html" title="class in java.awt.event">KeyEvent&lt;/a>&nbsp;e)</code>
<div class="block">This method will be called by <code>dispatchKeyEvent</code>.</div>
                              </td>
                            </tr>
                            
                            <tr id="i41" class="rowColor">
                              
<td class="colFirst"><code>abstract void</code></td>
                              
                              <td class="colLast">
                                <code>&lt;span class="memberNameLink">&lt;a href="../../java/awt/KeyboardFocusManager.html#processKeyEvent-java.awt.Component-java.awt.event.KeyEvent-">processKeyEvent&lt;/a>&lt;/span>(&lt;a href="../../java/awt/Component.html" title="class in java.awt">Component&lt;/a>&nbsp;focusedComponent,
               &lt;a href="../../java/awt/event/KeyEvent.html" title="class in java.awt.event">KeyEvent&lt;/a>&nbsp;e)</code> 
                                
                                <div class="block">
                                  This method initiates a focus traversal operation if and only if the KeyEvent represents a focus traversal key for the specified focusedComponent.
                                </div>
                              </td>
                            </tr>
                            
                            <tr id="i42" class="altColor">
                              
<td class="colFirst"><code>void</code></td>
                              
                              <td class="colLast">
                                <code>&lt;span class="memberNameLink">&lt;a href="../../java/awt/KeyboardFocusManager.html#redispatchEvent-java.awt.Component-java.awt.AWTEvent-">redispatchEvent&lt;/a>&lt;/span>(&lt;a href="../../java/awt/Component.html" title="class in java.awt">Component&lt;/a>&nbsp;target,
               &lt;a href="../../java/awt/AWTEvent.html" title="class in java.awt">AWTEvent&lt;/a>&nbsp;e)</code> 
                                
                                <div class="block">
                                  Redispatches an AWTEvent in such a way that the AWT event dispatcher will not recursively request that the KeyboardFocusManager, or any installed KeyEventDispatchers, dispatch the event again.
                                </div>
                              </td>
                            </tr>
                            
                            <tr id="i43" class="rowColor">
                              
<td class="colFirst"><code>void</code></td>
                              
                              <td class="colLast">
                                <code>&lt;span class="memberNameLink">&lt;a href="../../java/awt/KeyboardFocusManager.html#removeKeyEventDispatcher-java.awt.KeyEventDispatcher-">removeKeyEventDispatcher&lt;/a>&lt;/span>(&lt;a href="../../java/awt/KeyEventDispatcher.html" title="interface in java.awt">KeyEventDispatcher&lt;/a>&nbsp;dispatcher)</code> 
                                
                                <div class="block">
                                  Removes a KeyEventDispatcher which was previously added to this KeyboardFocusManager's dispatcher chain.
                                </div>
                              </td>
                            </tr>
                            
                            <tr id="i44" class="altColor">
                              
<td class="colFirst"><code>void</code></td>
                              
                              <td class="colLast">
                                <code>&lt;span class="memberNameLink">&lt;a href="../../java/awt/KeyboardFocusManager.html#removeKeyEventPostProcessor-java.awt.KeyEventPostProcessor-">removeKeyEventPostProcessor&lt;/a>&lt;/span>(&lt;a href="../../java/awt/KeyEventPostProcessor.html" title="interface in java.awt">KeyEventPostProcessor&lt;/a>&nbsp;processor)</code> 
                                
                                <div class="block">
                                  Removes a previously added KeyEventPostProcessor from this KeyboardFocusManager's post-processor chain.
                                </div>
                              </td>
                            </tr>
                            
                            <tr id="i45" class="rowColor">
                              
<td class="colFirst"><code>void</code></td>
                              
                              <td class="colLast">
                                <code>&lt;span class="memberNameLink">&lt;a href="../../java/awt/KeyboardFocusManager.html#removePropertyChangeListener-java.beans.PropertyChangeListener-">removePropertyChangeListener&lt;/a>&lt;/span>(&lt;a href="../../java/beans/PropertyChangeListener.html" title="interface in java.beans">PropertyChangeListener&lt;/a>&nbsp;listener)</code>
<div class="block">Removes a PropertyChangeListener from the listener list.</div>
                              </td>
                            </tr>
                            
                            <tr id="i46" class="altColor">
                              
<td class="colFirst"><code>void</code></td>
                              
                              <td class="colLast">
                                <code>&lt;span class="memberNameLink">&lt;a href="../../java/awt/KeyboardFocusManager.html#removePropertyChangeListener-java.lang.String-java.beans.PropertyChangeListener-">removePropertyChangeListener&lt;/a>&lt;/span>(&lt;a href="../../java/lang/String.html" title="class in java.lang">String&lt;/a>&nbsp;propertyName,
                            &lt;a href="../../java/beans/PropertyChangeListener.html" title="interface in java.beans">PropertyChangeListener&lt;/a>&nbsp;listener)</code> 
                                
                                <div class="block">
                                  Removes a PropertyChangeListener from the listener list for a specific property.
                                </div>
                              </td>
                            </tr>
                            
                            <tr id="i47" class="rowColor">
                              
<td class="colFirst"><code>void</code></td>
                              
                              <td class="colLast">
                                <code>&lt;span class="memberNameLink">&lt;a href="../../java/awt/KeyboardFocusManager.html#removeVetoableChangeListener-java.lang.String-java.beans.VetoableChangeListener-">removeVetoableChangeListener&lt;/a>&lt;/span>(&lt;a href="../../java/lang/String.html" title="class in java.lang">String&lt;/a>&nbsp;propertyName,
                            &lt;a href="../../java/beans/VetoableChangeListener.html" title="interface in java.beans">VetoableChangeListener&lt;/a>&nbsp;listener)</code> 
                                
                                <div class="block">
                                  Removes a VetoableChangeListener from the listener list for a specific property.
                                </div>
                              </td>
                            </tr>
                            
                            <tr id="i48" class="altColor">
                              
<td class="colFirst"><code>void</code></td>
                              
                              <td class="colLast">
                                <code>&lt;span class="memberNameLink">&lt;a href="../../java/awt/KeyboardFocusManager.html#removeVetoableChangeListener-java.beans.VetoableChangeListener-">removeVetoableChangeListener&lt;/a>&lt;/span>(&lt;a href="../../java/beans/VetoableChangeListener.html" title="interface in java.beans">VetoableChangeListener&lt;/a>&nbsp;listener)</code>
<div class="block">Removes a VetoableChangeListener from the listener list.</div>
                              </td>
                            </tr>
                            
                            <tr id="i49" class="rowColor">
                              
<td class="colFirst"><code>static void</code></td>
                              
                              <td class="colLast">
                                <code>&lt;span class="memberNameLink">&lt;a href="../../java/awt/KeyboardFocusManager.html#setCurrentKeyboardFocusManager-java.awt.KeyboardFocusManager-">setCurrentKeyboardFocusManager&lt;/a>&lt;/span>(&lt;a href="../../java/awt/KeyboardFocusManager.html" title="class in java.awt">KeyboardFocusManager&lt;/a>&nbsp;newManager)</code> 
                                
                                <div class="block">
                                  Sets the current KeyboardFocusManager instance for the calling thread's context.
                                </div>
                              </td>
                            </tr>
                            
                            <tr id="i50" class="altColor">
                              
<td class="colFirst"><code>void</code></td>
                              
                              <td class="colLast">
                                <code>&lt;span class="memberNameLink">&lt;a href="../../java/awt/KeyboardFocusManager.html#setDefaultFocusTraversalKeys-int-java.util.Set-">setDefaultFocusTraversalKeys&lt;/a>&lt;/span>(int&nbsp;id,
                            &lt;a href="../../java/util/Set.html" title="interface in java.util">Set&lt;/a>&lt;? extends &lt;a href="../../java/awt/AWTKeyStroke.html" title="class in java.awt">AWTKeyStroke&lt;/a>&gt;&nbsp;keystrokes)</code>
<div class="block">Sets the default focus traversal keys for a given traversal operation.</div>
                              </td>
                            </tr>
                            
                            <tr id="i51" class="rowColor">
                              
<td class="colFirst"><code>void</code></td>
                              
                              <td class="colLast">
                                <code>&lt;span class="memberNameLink">&lt;a href="../../java/awt/KeyboardFocusManager.html#setDefaultFocusTraversalPolicy-java.awt.FocusTraversalPolicy-">setDefaultFocusTraversalPolicy&lt;/a>&lt;/span>(&lt;a href="../../java/awt/FocusTraversalPolicy.html" title="class in java.awt">FocusTraversalPolicy&lt;/a>&nbsp;defaultPolicy)</code>
<div class="block">Sets the default FocusTraversalPolicy.</div>
                              </td>
                            </tr>
                            
                            <tr id="i52" class="altColor">
                              
<td class="colFirst"><code>protected void</code></td>
                              
                              <td class="colLast">
                                <code>&lt;span class="memberNameLink">&lt;a href="../../java/awt/KeyboardFocusManager.html#setGlobalActiveWindow-java.awt.Window-">setGlobalActiveWindow&lt;/a>&lt;/span>(&lt;a href="../../java/awt/Window.html" title="class in java.awt">Window&lt;/a>&nbsp;activeWindow)</code>
<div class="block">Sets the active Window.</div>
                              </td>
                            </tr>
                            
                            <tr id="i53" class="rowColor">
                              
<td class="colFirst"><code>void</code></td>
                              
                              <td class="colLast">
                                <code>&lt;span class="memberNameLink">&lt;a href="../../java/awt/KeyboardFocusManager.html#setGlobalCurrentFocusCycleRoot-java.awt.Container-">setGlobalCurrentFocusCycleRoot&lt;/a>&lt;/span>(&lt;a href="../../java/awt/Container.html" title="class in java.awt">Container&lt;/a>&nbsp;newFocusCycleRoot)</code>
<div class="block">Sets the current focus cycle root.</div>
                              </td>
                            </tr>
                            
                            <tr id="i54" class="altColor">
                              
<td class="colFirst"><code>protected void</code></td>
                              
                              <td class="colLast">
                                <code>&lt;span class="memberNameLink">&lt;a href="../../java/awt/KeyboardFocusManager.html#setGlobalFocusedWindow-java.awt.Window-">setGlobalFocusedWindow&lt;/a>&lt;/span>(&lt;a href="../../java/awt/Window.html" title="class in java.awt">Window&lt;/a>&nbsp;focusedWindow)</code>
<div class="block">Sets the focused Window.</div>
                              </td>
                            </tr>
                            
                            <tr id="i55" class="rowColor">
                              
<td class="colFirst"><code>protected void</code></td>
                              
                              <td class="colLast">
                                <code>&lt;span class="memberNameLink">&lt;a href="../../java/awt/KeyboardFocusManager.html#setGlobalFocusOwner-java.awt.Component-">setGlobalFocusOwner&lt;/a>&lt;/span>(&lt;a href="../../java/awt/Component.html" title="class in java.awt">Component&lt;/a>&nbsp;focusOwner)</code>
<div class="block">Sets the focus owner.</div>
                              </td>
                            </tr>
                            
                            <tr id="i56" class="altColor">
                              
<td class="colFirst"><code>protected void</code></td>
                              
                              <td class="colLast">
                                <code>&lt;span class="memberNameLink">&lt;a href="../../java/awt/KeyboardFocusManager.html#setGlobalPermanentFocusOwner-java.awt.Component-">setGlobalPermanentFocusOwner&lt;/a>&lt;/span>(&lt;a href="../../java/awt/Component.html" title="class in java.awt">Component&lt;/a>&nbsp;permanentFocusOwner)</code>
<div class="block">Sets the permanent focus owner.</div>
                              </td>
                            </tr>
                            
                            <tr id="i57" class="rowColor">
                              
<td class="colFirst"><code>void</code></td>
                              
                              <td class="colLast">
                                <code>&lt;span class="memberNameLink">&lt;a href="../../java/awt/KeyboardFocusManager.html#upFocusCycle--">upFocusCycle&lt;/a>&lt;/span>()</code> 
                                
                                <div class="block">
                                  Moves the focus up one focus traversal cycle from the current focus owner.
                                </div>
                              </td>
                            </tr>
                            
                            <tr id="i58" class="altColor">
                              
<td class="colFirst"><code>abstract void</code></td>
                              
                              <td class="colLast">
                                <code>&lt;span class="memberNameLink">&lt;a href="../../java/awt/KeyboardFocusManager.html#upFocusCycle-java.awt.Component-">upFocusCycle&lt;/a>&lt;/span>(&lt;a href="../../java/awt/Component.html" title="class in java.awt">Component&lt;/a>&nbsp;aComponent)</code>
<div class="block">Moves the focus up one focus traversal cycle.</div>
                              </td>
                            </tr>
                          </table>
                          
                          <ul class="blockList">
                            <li class="blockList">
                              <a name="methods.inherited.from.class.java.lang.Object"> <!--   --></a>
<h3>Methods inherited from class&nbsp;java.lang.<a href="../../java/lang/Object.html" title="class in java.lang">Object</a></h3>
<code><a href="../../java/lang/Object.html#clone--">clone</a>, <a href="../../java/lang/Object.html#equals-java.lang.Object-">equals</a>, <a href="../../java/lang/Object.html#finalize--">finalize</a>, <a href="../../java/lang/Object.html#getClass--">getClass</a>, <a href="../../java/lang/Object.html#hashCode--">hashCode</a>, <a href="../../java/lang/Object.html#notify--">notify</a>, <a href="../../java/lang/Object.html#notifyAll--">notifyAll</a>, <a href="../../java/lang/Object.html#toString--">toString</a>, <a href="../../java/lang/Object.html#wait--">wait</a>, <a href="../../java/lang/Object.html#wait-long-">wait</a>, <a href="../../java/lang/Object.html#wait-long-int-">wait</a></code>                            </li>
                          </ul>
                        </li>
                      </ul>
                    </li>
                  </ul>
                </div>
                
                <div class="details">
                  <ul class="blockList">
                    <li class="blockList">
                      <!-- ============ FIELD DETAIL =========== -->
                      
                      <ul class="blockList">
                        <li class="blockList">
                          <a name="field.detail"> <!--   --></a>
<h3>Field Detail</h3>
<a name="FORWARD_TRAVERSAL_KEYS">
<!--   -->
</a>
                          
                          <ul class="blockList">
                            <li class="blockList">
                              
<h4>FORWARD_TRAVERSAL_KEYS</h4>
<pre>public static final&nbsp;int FORWARD_TRAVERSAL_KEYS</pre>
<div class="block">The identifier for the Forward focus traversal keys.</div>
<dl>
                                
<dt><span class="seeLabel">See Also:</span></dt>
                                
                                <dd>
                                  <a href="../../java/awt/KeyboardFocusManager.html#setDefaultFocusTraversalKeys-int-java.util.Set-"><code>setDefaultFocusTraversalKeys(int, java.util.Set&lt;? extends java.awt.AWTKeyStroke&gt;)</code></a>, 
<a href="../../java/awt/KeyboardFocusManager.html#getDefaultFocusTraversalKeys-int-"><code>getDefaultFocusTraversalKeys(int)</code></a>, 
<a href="../../java/awt/Component.html#setFocusTraversalKeys-int-java.util.Set-"><code>Component.setFocusTraversalKeys(int, java.util.Set&lt;? extends java.awt.AWTKeyStroke&gt;)</code></a>, 
<a href="../../java/awt/Component.html#getFocusTraversalKeys-int-"><code>Component.getFocusTraversalKeys(int)</code></a>, 
<a href="../../constant-values.html#java.awt.KeyboardFocusManager.FORWARD_TRAVERSAL_KEYS">Constant Field Values</a>                                </dd>
                              </dl>
                            </li>
                          </ul>
<a name="BACKWARD_TRAVERSAL_KEYS">
<!--   -->
</a>
                          
                          <ul class="blockList">
                            <li class="blockList">
                              
<h4>BACKWARD_TRAVERSAL_KEYS</h4>
<pre>public static final&nbsp;int BACKWARD_TRAVERSAL_KEYS</pre>
<div class="block">The identifier for the Backward focus traversal keys.</div>
<dl>
                                
<dt><span class="seeLabel">See Also:</span></dt>
                                
                                <dd>
                                  <a href="../../java/awt/KeyboardFocusManager.html#setDefaultFocusTraversalKeys-int-java.util.Set-"><code>setDefaultFocusTraversalKeys(int, java.util.Set&lt;? extends java.awt.AWTKeyStroke&gt;)</code></a>, 
<a href="../../java/awt/KeyboardFocusManager.html#getDefaultFocusTraversalKeys-int-"><code>getDefaultFocusTraversalKeys(int)</code></a>, 
<a href="../../java/awt/Component.html#setFocusTraversalKeys-int-java.util.Set-"><code>Component.setFocusTraversalKeys(int, java.util.Set&lt;? extends java.awt.AWTKeyStroke&gt;)</code></a>, 
<a href="../../java/awt/Component.html#getFocusTraversalKeys-int-"><code>Component.getFocusTraversalKeys(int)</code></a>, 
<a href="../../constant-values.html#java.awt.KeyboardFocusManager.BACKWARD_TRAVERSAL_KEYS">Constant Field Values</a>                                </dd>
                              </dl>
                            </li>
                          </ul>
<a name="UP_CYCLE_TRAVERSAL_KEYS">
<!--   -->
</a>
                          
                          <ul class="blockList">
                            <li class="blockList">
                              
<h4>UP_CYCLE_TRAVERSAL_KEYS</h4>
<pre>public static final&nbsp;int UP_CYCLE_TRAVERSAL_KEYS</pre>
<div class="block">The identifier for the Up Cycle focus traversal keys.</div>
<dl>
                                
<dt><span class="seeLabel">See Also:</span></dt>
                                
                                <dd>
                                  <a href="../../java/awt/KeyboardFocusManager.html#setDefaultFocusTraversalKeys-int-java.util.Set-"><code>setDefaultFocusTraversalKeys(int, java.util.Set&lt;? extends java.awt.AWTKeyStroke&gt;)</code></a>, 
<a href="../../java/awt/KeyboardFocusManager.html#getDefaultFocusTraversalKeys-int-"><code>getDefaultFocusTraversalKeys(int)</code></a>, 
<a href="../../java/awt/Component.html#setFocusTraversalKeys-int-java.util.Set-"><code>Component.setFocusTraversalKeys(int, java.util.Set&lt;? extends java.awt.AWTKeyStroke&gt;)</code></a>, 
<a href="../../java/awt/Component.html#getFocusTraversalKeys-int-"><code>Component.getFocusTraversalKeys(int)</code></a>, 
<a href="../../constant-values.html#java.awt.KeyboardFocusManager.UP_CYCLE_TRAVERSAL_KEYS">Constant Field Values</a>                                </dd>
                              </dl>
                            </li>
                          </ul>
<a name="DOWN_CYCLE_TRAVERSAL_KEYS">
<!--   -->
</a>
                          
                          <ul class="blockListLast">
                            <li class="blockList">
                              
<h4>DOWN_CYCLE_TRAVERSAL_KEYS</h4>
<pre>public static final&nbsp;int DOWN_CYCLE_TRAVERSAL_KEYS</pre>
<div class="block">The identifier for the Down Cycle focus traversal keys.</div>
<dl>
                                
<dt><span class="seeLabel">See Also:</span></dt>
                                
                                <dd>
                                  <a href="../../java/awt/KeyboardFocusManager.html#setDefaultFocusTraversalKeys-int-java.util.Set-"><code>setDefaultFocusTraversalKeys(int, java.util.Set&lt;? extends java.awt.AWTKeyStroke&gt;)</code></a>, 
<a href="../../java/awt/KeyboardFocusManager.html#getDefaultFocusTraversalKeys-int-"><code>getDefaultFocusTraversalKeys(int)</code></a>, 
<a href="../../java/awt/Component.html#setFocusTraversalKeys-int-java.util.Set-"><code>Component.setFocusTraversalKeys(int, java.util.Set&lt;? extends java.awt.AWTKeyStroke&gt;)</code></a>, 
<a href="../../java/awt/Component.html#getFocusTraversalKeys-int-"><code>Component.getFocusTraversalKeys(int)</code></a>, 
<a href="../../constant-values.html#java.awt.KeyboardFocusManager.DOWN_CYCLE_TRAVERSAL_KEYS">Constant Field Values</a>                                </dd>
                              </dl>
                            </li>
                          </ul>
                        </li>
                      </ul>
                      
                      <!-- ========= CONSTRUCTOR DETAIL ======== -->
                      
                      <ul class="blockList">
                        <li class="blockList">
                          <a name="constructor.detail"> <!--   --></a>
<h3>Constructor Detail</h3>
<a name="KeyboardFocusManager--">
<!--   -->
</a>
                          
                          <ul class="blockListLast">
                            <li class="blockList">
                              
<h4>KeyboardFocusManager</h4>
<pre>public&nbsp;KeyboardFocusManager()</pre>
<div class="block">Initializes a KeyboardFocusManager.</div>
                            </li>
                          </ul>
                        </li>
                      </ul>
                      <!-- ============ METHOD DETAIL ========== -->
                      
                      <ul class="blockList">
                        <li class="blockList">
                          <a name="method.detail"> <!--   --></a>
<h3>Method Detail</h3>
<a name="getCurrentKeyboardFocusManager--">
<!--   -->
</a>
                          
                          <ul class="blockList">
                            <li class="blockList">
                              
<h4>getCurrentKeyboardFocusManager</h4>
<pre>public static&nbsp;<a href="../../java/awt/KeyboardFocusManager.html" title="class in java.awt">KeyboardFocusManager</a>&nbsp;getCurrentKeyboardFocusManager()</pre>
<div class="block">
                                Returns the current KeyboardFocusManager instance for the calling thread's context.
                              </div>
                              <dl>
                                
<dt><span class="returnLabel">Returns:</span></dt>
<dd>this thread's context's KeyboardFocusManager</dd>
<dt><span class="seeLabel">See Also:</span></dt>
<dd><a href="../../java/awt/KeyboardFocusManager.html#setCurrentKeyboardFocusManager-java.awt.KeyboardFocusManager-"><code>setCurrentKeyboardFocusManager(java.awt.KeyboardFocusManager)</code></a></dd>
                              </dl>
                            </li>
                          </ul>
<a name="setCurrentKeyboardFocusManager-java.awt.KeyboardFocusManager-">
<!--   -->
</a>
                          <ul class="blockList">
                            <li class="blockList">
                              
<h4>setCurrentKeyboardFocusManager</h4>
<pre>public static&nbsp;void&nbsp;setCurrentKeyboardFocusManager(<a href="../../java/awt/KeyboardFocusManager.html" title="class in java.awt">KeyboardFocusManager</a>&nbsp;newManager)
                                           throws <a href="../../java/lang/SecurityException.html" title="class in java.lang">SecurityException</a></pre>
                              <div class="block">
                                Sets the current KeyboardFocusManager instance for the calling thread's context. If null is specified, then the current KeyboardFocusManager is replaced with a new instance of DefaultKeyboardFocusManager. 
                                
                                <p>
                                  If a SecurityManager is installed, the calling thread must be granted the AWTPermission "replaceKeyboardFocusManager" in order to replace the the current KeyboardFocusManager. If this permission is not granted, this method will throw a SecurityException, and the current KeyboardFocusManager will be unchanged.</div> 
                                  
                                  <dl>
                                    
<dt><span class="paramLabel">Parameters:</span></dt>
<dd><code>newManager</code> - the new KeyboardFocusManager for this thread's context</dd>
<dt><span class="throwsLabel">Throws:</span></dt>
                                    
                                    <dd>
                                      <code>&lt;a href="../../java/lang/SecurityException.html" title="class in java.lang">SecurityException&lt;/a></code> - if the calling thread does not have permission to replace the current KeyboardFocusManager
                                    </dd>
<dt><span class="seeLabel">See Also:</span></dt>
                                    
                                    <dd>
                                      <a href="../../java/awt/KeyboardFocusManager.html#getCurrentKeyboardFocusManager--"><code>getCurrentKeyboardFocusManager()</code></a>, 
<a href="../../java/awt/DefaultKeyboardFocusManager.html" title="class in java.awt"><code>DefaultKeyboardFocusManager</code></a>                                    </dd>
                                  </dl></li> </ul>
<a name="getFocusOwner--">
<!--   -->
</a>
                                  
                                  <ul class="blockList">
                                    <li class="blockList">
                                      
<h4>getFocusOwner</h4>
<pre>public&nbsp;<a href="../../java/awt/Component.html" title="class in java.awt">Component</a>&nbsp;getFocusOwner()</pre>
<div class="block">
                                        Returns the focus owner, if the focus owner is in the same context as the calling thread. The focus owner is defined as the Component in an application that will typically receive all KeyEvents generated by the user. KeyEvents which map to the focus owner's focus traversal keys will not be delivered if focus traversal keys are enabled for the focus owner. In addition, KeyEventDispatchers may retarget or consume KeyEvents before they reach the focus owner.
                                      </div>
                                      <dl>
                                        
<dt><span class="returnLabel">Returns:</span></dt>
                                        
                                        <dd>
                                          the focus owner, or null if the focus owner is not a member of the calling thread's context
                                        </dd>
<dt><span class="seeLabel">See Also:</span></dt>
                                        
                                        <dd>
                                          <a href="../../java/awt/KeyboardFocusManager.html#getGlobalFocusOwner--"><code>getGlobalFocusOwner()</code></a>, 
<a href="../../java/awt/KeyboardFocusManager.html#setGlobalFocusOwner-java.awt.Component-"><code>setGlobalFocusOwner(java.awt.Component)</code></a>                                        </dd>
                                      </dl>
                                    </li>
                                  </ul>
<a name="getGlobalFocusOwner--">
<!--   -->
</a>
                                  
                                  <ul class="blockList">
                                    <li class="blockList">
                                      
<h4>getGlobalFocusOwner</h4>
<pre>protected&nbsp;<a href="../../java/awt/Component.html" title="class in java.awt">Component</a>&nbsp;getGlobalFocusOwner()
                                 throws <a href="../../java/lang/SecurityException.html" title="class in java.lang">SecurityException</a></pre>
                                      <div class="block">
                                        Returns the focus owner, even if the calling thread is in a different context than the focus owner. The focus owner is defined as the Component in an application that will typically receive all KeyEvents generated by the user. KeyEvents which map to the focus owner's focus traversal keys will not be delivered if focus traversal keys are enabled for the focus owner. In addition, KeyEventDispatchers may retarget or consume KeyEvents before they reach the focus owner. 
                                        
                                        <p>
                                          This method will throw a SecurityException if this KeyboardFocusManager is not the current KeyboardFocusManager for the calling thread's context.</div> 
                                          
                                          <dl>
                                            
<dt><span class="returnLabel">Returns:</span></dt>
<dd>the focus owner</dd>
<dt><span class="throwsLabel">Throws:</span></dt>
                                            
                                            <dd>
                                              <code>&lt;a href="../../java/lang/SecurityException.html" title="class in java.lang">SecurityException&lt;/a></code> - if this KeyboardFocusManager is not the current KeyboardFocusManager for the calling thread's context and if the calling thread does not have "replaceKeyboardFocusManager" permission
                                            </dd>
<dt><span class="seeLabel">See Also:</span></dt>
                                            
                                            <dd>
                                              <a href="../../java/awt/KeyboardFocusManager.html#getFocusOwner--"><code>getFocusOwner()</code></a>, 
<a href="../../java/awt/KeyboardFocusManager.html#setGlobalFocusOwner-java.awt.Component-"><code>setGlobalFocusOwner(java.awt.Component)</code></a>                                            </dd>
                                          </dl></li> </ul>
<a name="setGlobalFocusOwner-java.awt.Component-">
<!--   -->
</a>
                                          
                                          <ul class="blockList">
                                            <li class="blockList">
                                              
<h4>setGlobalFocusOwner</h4>
<pre>protected&nbsp;void&nbsp;setGlobalFocusOwner(<a href="../../java/awt/Component.html" title="class in java.awt">Component</a>&nbsp;focusOwner)
                            throws <a href="../../java/lang/SecurityException.html" title="class in java.lang">SecurityException</a></pre>
                                              <div class="block">
                                                Sets the focus owner. The operation will be cancelled if the Component is not focusable. The focus owner is defined as the Component in an application that will typically receive all KeyEvents generated by the user. KeyEvents which map to the focus owner's focus traversal keys will not be delivered if focus traversal keys are enabled for the focus owner. In addition, KeyEventDispatchers may retarget or consume KeyEvents before they reach the focus owner. 
                                                
                                                <p>
                                                  This method does not actually set the focus to the specified Component. It merely stores the value to be subsequently returned by <code>getFocusOwner()</code>. Use <code>Component.requestFocus()</code> or <code>Component.requestFocusInWindow()</code> to change the focus owner, subject to platform limitations.</div> 
                                                  
                                                  <dl>
                                                    
<dt><span class="paramLabel">Parameters:</span></dt>
<dd><code>focusOwner</code> - the focus owner</dd>
<dt><span class="throwsLabel">Throws:</span></dt>
                                                    
                                                    <dd>
                                                      <code>&lt;a href="../../java/lang/SecurityException.html" title="class in java.lang">SecurityException&lt;/a></code> - if this KeyboardFocusManager is not the current KeyboardFocusManager for the calling thread's context and if the calling thread does not have "replaceKeyboardFocusManager" permission
                                                    </dd>
<dt><span class="seeLabel">See Also:</span></dt>
                                                    
                                                    <dd>
                                                      <a href="../../java/awt/KeyboardFocusManager.html#getFocusOwner--"><code>getFocusOwner()</code></a>, 
<a href="../../java/awt/KeyboardFocusManager.html#getGlobalFocusOwner--"><code>getGlobalFocusOwner()</code></a>, 
<a href="../../java/awt/Component.html#requestFocus--"><code>Component.requestFocus()</code></a>, 
<a href="../../java/awt/Component.html#requestFocusInWindow--"><code>Component.requestFocusInWindow()</code></a>, 
<a href="../../java/awt/Component.html#isFocusable--"><code>Component.isFocusable()</code></a>                                                    </dd>
                                                  </dl></li> </ul>
<a name="clearFocusOwner--">
<!--   -->
</a>
                                                  
                                                  <ul class="blockList">
                                                    <li class="blockList">
                                                      
<h4>clearFocusOwner</h4>
<pre>public&nbsp;void&nbsp;clearFocusOwner()</pre>
<div class="block">
                                                        Clears the focus owner at both the Java and native levels if the focus owner exists and resides in the same context as the calling thread, otherwise the method returns silently. 
                                                        
                                                        <p>
                                                          The focus owner component will receive a permanent FOCUS_LOST event. After this operation completes, the native windowing system will discard all user-generated KeyEvents until the user selects a new Component to receive focus, or a Component is given focus explicitly via a call to <code>requestFocus()</code>. This operation does not change the focused or active Windows.</div> 
                                                          
                                                          <dl>
                                                            
<dt><span class="simpleTagLabel">Since:</span></dt>
<dd>1.8</dd>
<dt><span class="seeLabel">See Also:</span></dt>
                                                            
                                                            <dd>
                                                              <a href="../../java/awt/Component.html#requestFocus--"><code>Component.requestFocus()</code></a>, 
<a href="../../java/awt/event/FocusEvent.html#FOCUS_LOST"><code>FocusEvent.FOCUS_LOST</code></a>                                                            </dd>
                                                          </dl></li> </ul>
<a name="clearGlobalFocusOwner--">
<!--   -->
</a>
                                                          
                                                          <ul class="blockList">
                                                            <li class="blockList">
                                                              
<h4>clearGlobalFocusOwner</h4>
<pre>public&nbsp;void&nbsp;clearGlobalFocusOwner()
                           throws <a href="../../java/lang/SecurityException.html" title="class in java.lang">SecurityException</a></pre>
                                                              <div class="block">
                                                                Clears the global focus owner at both the Java and native levels. If there exists a focus owner, that Component will receive a permanent FOCUS_LOST event. After this operation completes, the native windowing system will discard all user-generated KeyEvents until the user selects a new Component to receive focus, or a Component is given focus explicitly via a call to <code>requestFocus()</code>. This operation does not change the focused or active Windows. 
                                                                
                                                                <p>
                                                                  If a SecurityManager is installed, the calling thread must be granted the "replaceKeyboardFocusManager" AWTPermission. If this permission is not granted, this method will throw a SecurityException, and the current focus owner will not be cleared. 
                                                                  
                                                                  <p>
                                                                    This method is intended to be used only by KeyboardFocusManager set as current KeyboardFocusManager for the calling thread's context. It is not for general client use.</div> 
                                                                    
                                                                    <dl>
                                                                      
<dt><span class="throwsLabel">Throws:</span></dt>
                                                                      
                                                                      <dd>
                                                                        <code>&lt;a href="../../java/lang/SecurityException.html" title="class in java.lang">SecurityException&lt;/a></code> - if the calling thread does not have "replaceKeyboardFocusManager" permission
                                                                      </dd>
<dt><span class="seeLabel">See Also:</span></dt>
                                                                      
                                                                      <dd>
                                                                        <a href="../../java/awt/KeyboardFocusManager.html#clearFocusOwner--"><code>clearFocusOwner()</code></a>, 
<a href="../../java/awt/Component.html#requestFocus--"><code>Component.requestFocus()</code></a>, 
<a href="../../java/awt/event/FocusEvent.html#FOCUS_LOST"><code>FocusEvent.FOCUS_LOST</code></a>                                                                      </dd>
                                                                    </dl></li> </ul>
<a name="getPermanentFocusOwner--">
<!--   -->
</a>
                                                                    
                                                                    <ul class="blockList">
                                                                      <li class="blockList">
                                                                        
<h4>getPermanentFocusOwner</h4>
<pre>public&nbsp;<a href="../../java/awt/Component.html" title="class in java.awt">Component</a>&nbsp;getPermanentFocusOwner()</pre>
<div class="block">
                                                                          Returns the permanent focus owner, if the permanent focus owner is in the same context as the calling thread. The permanent focus owner is defined as the last Component in an application to receive a permanent FOCUS_GAINED event. The focus owner and permanent focus owner are equivalent unless a temporary focus change is currently in effect. In such a situation, the permanent focus owner will again be the focus owner when the temporary focus change ends.
                                                                        </div>
                                                                        <dl>
                                                                          
<dt><span class="returnLabel">Returns:</span></dt>
                                                                          
                                                                          <dd>
                                                                            the permanent focus owner, or null if the permanent focus owner is not a member of the calling thread's context
                                                                          </dd>
<dt><span class="seeLabel">See Also:</span></dt>
                                                                          
                                                                          <dd>
                                                                            <a href="../../java/awt/KeyboardFocusManager.html#getGlobalPermanentFocusOwner--"><code>getGlobalPermanentFocusOwner()</code></a>, 
<a href="../../java/awt/KeyboardFocusManager.html#setGlobalPermanentFocusOwner-java.awt.Component-"><code>setGlobalPermanentFocusOwner(java.awt.Component)</code></a>                                                                          </dd>
                                                                        </dl>
                                                                      </li>
                                                                    </ul>
<a name="getGlobalPermanentFocusOwner--">
<!--   -->
</a>
                                                                    
                                                                    <ul class="blockList">
                                                                      <li class="blockList">
                                                                        
<h4>getGlobalPermanentFocusOwner</h4>
<pre>protected&nbsp;<a href="../../java/awt/Component.html" title="class in java.awt">Component</a>&nbsp;getGlobalPermanentFocusOwner()
                                          throws <a href="../../java/lang/SecurityException.html" title="class in java.lang">SecurityException</a></pre>
                                                                        <div class="block">
                                                                          Returns the permanent focus owner, even if the calling thread is in a different context than the permanent focus owner. The permanent focus owner is defined as the last Component in an application to receive a permanent FOCUS_GAINED event. The focus owner and permanent focus owner are equivalent unless a temporary focus change is currently in effect. In such a situation, the permanent focus owner will again be the focus owner when the temporary focus change ends.
                                                                        </div>
                                                                        <dl>
                                                                          
<dt><span class="returnLabel">Returns:</span></dt>
<dd>the permanent focus owner</dd>
<dt><span class="throwsLabel">Throws:</span></dt>
                                                                          
                                                                          <dd>
                                                                            <code>&lt;a href="../../java/lang/SecurityException.html" title="class in java.lang">SecurityException&lt;/a></code> - if this KeyboardFocusManager is not the current KeyboardFocusManager for the calling thread's context and if the calling thread does not have "replaceKeyboardFocusManager" permission
                                                                          </dd>
<dt><span class="seeLabel">See Also:</span></dt>
                                                                          
                                                                          <dd>
                                                                            <a href="../../java/awt/KeyboardFocusManager.html#getPermanentFocusOwner--"><code>getPermanentFocusOwner()</code></a>, 
<a href="../../java/awt/KeyboardFocusManager.html#setGlobalPermanentFocusOwner-java.awt.Component-"><code>setGlobalPermanentFocusOwner(java.awt.Component)</code></a>                                                                          </dd>
                                                                        </dl>
                                                                      </li>
                                                                    </ul>
<a name="setGlobalPermanentFocusOwner-java.awt.Component-">
<!--   -->
</a>
                                                                    
                                                                    <ul class="blockList">
                                                                      <li class="blockList">
                                                                        
<h4>setGlobalPermanentFocusOwner</h4>
<pre>protected&nbsp;void&nbsp;setGlobalPermanentFocusOwner(<a href="../../java/awt/Component.html" title="class in java.awt">Component</a>&nbsp;permanentFocusOwner)
                                     throws <a href="../../java/lang/SecurityException.html" title="class in java.lang">SecurityException</a></pre>
                                                                        <div class="block">
                                                                          Sets the permanent focus owner. The operation will be cancelled if the Component is not focusable. The permanent focus owner is defined as the last Component in an application to receive a permanent FOCUS_GAINED event. The focus owner and permanent focus owner are equivalent unless a temporary focus change is currently in effect. In such a situation, the permanent focus owner will again be the focus owner when the temporary focus change ends. 
                                                                          
                                                                          <p>
                                                                            This method does not actually set the focus to the specified Component. It merely stores the value to be subsequently returned by <code>getPermanentFocusOwner()</code>. Use <code>Component.requestFocus()</code> or <code>Component.requestFocusInWindow()</code> to change the focus owner, subject to platform limitations.</div> 
                                                                            
                                                                            <dl>
                                                                              
<dt><span class="paramLabel">Parameters:</span></dt>
<dd><code>permanentFocusOwner</code> - the permanent focus owner</dd>
<dt><span class="throwsLabel">Throws:</span></dt>
                                                                              
                                                                              <dd>
                                                                                <code>&lt;a href="../../java/lang/SecurityException.html" title="class in java.lang">SecurityException&lt;/a></code> - if this KeyboardFocusManager is not the current KeyboardFocusManager for the calling thread's context and if the calling thread does not have "replaceKeyboardFocusManager" permission
                                                                              </dd>
<dt><span class="seeLabel">See Also:</span></dt>
                                                                              
                                                                              <dd>
                                                                                <a href="../../java/awt/KeyboardFocusManager.html#getPermanentFocusOwner--"><code>getPermanentFocusOwner()</code></a>, 
<a href="../../java/awt/KeyboardFocusManager.html#getGlobalPermanentFocusOwner--"><code>getGlobalPermanentFocusOwner()</code></a>, 
<a href="../../java/awt/Component.html#requestFocus--"><code>Component.requestFocus()</code></a>, 
<a href="../../java/awt/Component.html#requestFocusInWindow--"><code>Component.requestFocusInWindow()</code></a>, 
<a href="../../java/awt/Component.html#isFocusable--"><code>Component.isFocusable()</code></a>                                                                              </dd>
                                                                            </dl></li> </ul>
<a name="getFocusedWindow--">
<!--   -->
</a>
                                                                            
                                                                            <ul class="blockList">
                                                                              <li class="blockList">
                                                                                
<h4>getFocusedWindow</h4>
<pre>public&nbsp;<a href="../../java/awt/Window.html" title="class in java.awt">Window</a>&nbsp;getFocusedWindow()</pre>
<div class="block">
                                                                                  Returns the focused Window, if the focused Window is in the same context as the calling thread. The focused Window is the Window that is or contains the focus owner.
                                                                                </div>
                                                                                <dl>
                                                                                  
<dt><span class="returnLabel">Returns:</span></dt>
                                                                                  
                                                                                  <dd>
                                                                                    the focused Window, or null if the focused Window is not a member of the calling thread's context
                                                                                  </dd>
<dt><span class="seeLabel">See Also:</span></dt>
                                                                                  
                                                                                  <dd>
                                                                                    <a href="../../java/awt/KeyboardFocusManager.html#getGlobalFocusedWindow--"><code>getGlobalFocusedWindow()</code></a>, 
<a href="../../java/awt/KeyboardFocusManager.html#setGlobalFocusedWindow-java.awt.Window-"><code>setGlobalFocusedWindow(java.awt.Window)</code></a>                                                                                  </dd>
                                                                                </dl>
                                                                              </li>
                                                                            </ul>
<a name="getGlobalFocusedWindow--">
<!--   -->
</a>
                                                                            
                                                                            <ul class="blockList">
                                                                              <li class="blockList">
                                                                                
<h4>getGlobalFocusedWindow</h4>
<pre>protected&nbsp;<a href="../../java/awt/Window.html" title="class in java.awt">Window</a>&nbsp;getGlobalFocusedWindow()
                                 throws <a href="../../java/lang/SecurityException.html" title="class in java.lang">SecurityException</a></pre>
                                                                                <div class="block">
                                                                                  Returns the focused Window, even if the calling thread is in a different context than the focused Window. The focused Window is the Window that is or contains the focus owner.
                                                                                </div>
                                                                                <dl>
                                                                                  
<dt><span class="returnLabel">Returns:</span></dt>
<dd>the focused Window</dd>
<dt><span class="throwsLabel">Throws:</span></dt>
                                                                                  
                                                                                  <dd>
                                                                                    <code>&lt;a href="../../java/lang/SecurityException.html" title="class in java.lang">SecurityException&lt;/a></code> - if this KeyboardFocusManager is not the current KeyboardFocusManager for the calling thread's context and if the calling thread does not have "replaceKeyboardFocusManager" permission
                                                                                  </dd>
<dt><span class="seeLabel">See Also:</span></dt>
                                                                                  
                                                                                  <dd>
                                                                                    <a href="../../java/awt/KeyboardFocusManager.html#getFocusedWindow--"><code>getFocusedWindow()</code></a>, 
<a href="../../java/awt/KeyboardFocusManager.html#setGlobalFocusedWindow-java.awt.Window-"><code>setGlobalFocusedWindow(java.awt.Window)</code></a>                                                                                  </dd>
                                                                                </dl>
                                                                              </li>
                                                                            </ul>
<a name="setGlobalFocusedWindow-java.awt.Window-">
<!--   -->
</a>
                                                                            
                                                                            <ul class="blockList">
                                                                              <li class="blockList">
                                                                                
<h4>setGlobalFocusedWindow</h4>
<pre>protected&nbsp;void&nbsp;setGlobalFocusedWindow(<a href="../../java/awt/Window.html" title="class in java.awt">Window</a>&nbsp;focusedWindow)
                               throws <a href="../../java/lang/SecurityException.html" title="class in java.lang">SecurityException</a></pre>
                                                                                <div class="block">
                                                                                  Sets the focused Window. The focused Window is the Window that is or contains the focus owner. The operation will be cancelled if the specified Window to focus is not a focusable Window. 
                                                                                  
                                                                                  <p>
                                                                                    This method does not actually change the focused Window as far as the native windowing system is concerned. It merely stores the value to be subsequently returned by <code>getFocusedWindow()</code>. Use <code>Component.requestFocus()</code> or <code>Component.requestFocusInWindow()</code> to change the focused Window, subject to platform limitations.</div> 
                                                                                    
                                                                                    <dl>
                                                                                      
<dt><span class="paramLabel">Parameters:</span></dt>
<dd><code>focusedWindow</code> - the focused Window</dd>
<dt><span class="throwsLabel">Throws:</span></dt>
                                                                                      
                                                                                      <dd>
                                                                                        <code>&lt;a href="../../java/lang/SecurityException.html" title="class in java.lang">SecurityException&lt;/a></code> - if this KeyboardFocusManager is not the current KeyboardFocusManager for the calling thread's context and if the calling thread does not have "replaceKeyboardFocusManager" permission
                                                                                      </dd>
<dt><span class="seeLabel">See Also:</span></dt>
                                                                                      
                                                                                      <dd>
                                                                                        <a href="../../java/awt/KeyboardFocusManager.html#getFocusedWindow--"><code>getFocusedWindow()</code></a>, 
<a href="../../java/awt/KeyboardFocusManager.html#getGlobalFocusedWindow--"><code>getGlobalFocusedWindow()</code></a>, 
<a href="../../java/awt/Component.html#requestFocus--"><code>Component.requestFocus()</code></a>, 
<a href="../../java/awt/Component.html#requestFocusInWindow--"><code>Component.requestFocusInWindow()</code></a>, 
<a href="../../java/awt/Window.html#isFocusableWindow--"><code>Window.isFocusableWindow()</code></a>                                                                                      </dd>
                                                                                    </dl></li> </ul>
<a name="getActiveWindow--">
<!--   -->
</a>
                                                                                    
                                                                                    <ul class="blockList">
                                                                                      <li class="blockList">
                                                                                        
<h4>getActiveWindow</h4>
<pre>public&nbsp;<a href="../../java/awt/Window.html" title="class in java.awt">Window</a>&nbsp;getActiveWindow()</pre>
<div class="block">
                                                                                          Returns the active Window, if the active Window is in the same context as the calling thread. Only a Frame or a Dialog can be the active Window. The native windowing system may denote the active Window or its children with special decorations, such as a highlighted title bar. The active Window is always either the focused Window, or the first Frame or Dialog that is an owner of the focused Window.
                                                                                        </div>
                                                                                        <dl>
                                                                                          
<dt><span class="returnLabel">Returns:</span></dt>
                                                                                          
                                                                                          <dd>
                                                                                            the active Window, or null if the active Window is not a member of the calling thread's context
                                                                                          </dd>
<dt><span class="seeLabel">See Also:</span></dt>
                                                                                          
                                                                                          <dd>
                                                                                            <a href="../../java/awt/KeyboardFocusManager.html#getGlobalActiveWindow--"><code>getGlobalActiveWindow()</code></a>, 
<a href="../../java/awt/KeyboardFocusManager.html#setGlobalActiveWindow-java.awt.Window-"><code>setGlobalActiveWindow(java.awt.Window)</code></a>                                                                                          </dd>
                                                                                        </dl>
                                                                                      </li>
                                                                                    </ul>
<a name="getGlobalActiveWindow--">
<!--   -->
</a>
                                                                                    
                                                                                    <ul class="blockList">
                                                                                      <li class="blockList">
                                                                                        
<h4>getGlobalActiveWindow</h4>
<pre>protected&nbsp;<a href="../../java/awt/Window.html" title="class in java.awt">Window</a>&nbsp;getGlobalActiveWindow()
                                throws <a href="../../java/lang/SecurityException.html" title="class in java.lang">SecurityException</a></pre>
                                                                                        <div class="block">
                                                                                          Returns the active Window, even if the calling thread is in a different context than the active Window. Only a Frame or a Dialog can be the active Window. The native windowing system may denote the active Window or its children with special decorations, such as a highlighted title bar. The active Window is always either the focused Window, or the first Frame or Dialog that is an owner of the focused Window.
                                                                                        </div>
                                                                                        <dl>
                                                                                          
<dt><span class="returnLabel">Returns:</span></dt>
<dd>the active Window</dd>
<dt><span class="throwsLabel">Throws:</span></dt>
                                                                                          
                                                                                          <dd>
                                                                                            <code>&lt;a href="../../java/lang/SecurityException.html" title="class in java.lang">SecurityException&lt;/a></code> - if this KeyboardFocusManager is not the current KeyboardFocusManager for the calling thread's context and if the calling thread does not have "replaceKeyboardFocusManager" permission
                                                                                          </dd>
<dt><span class="seeLabel">See Also:</span></dt>
                                                                                          
                                                                                          <dd>
                                                                                            <a href="../../java/awt/KeyboardFocusManager.html#getActiveWindow--"><code>getActiveWindow()</code></a>, 
<a href="../../java/awt/KeyboardFocusManager.html#setGlobalActiveWindow-java.awt.Window-"><code>setGlobalActiveWindow(java.awt.Window)</code></a>                                                                                          </dd>
                                                                                        </dl>
                                                                                      </li>
                                                                                    </ul>
<a name="setGlobalActiveWindow-java.awt.Window-">
<!--   -->
</a>
                                                                                    
                                                                                    <ul class="blockList">
                                                                                      <li class="blockList">
                                                                                        
<h4>setGlobalActiveWindow</h4>
<pre>protected&nbsp;void&nbsp;setGlobalActiveWindow(<a href="../../java/awt/Window.html" title="class in java.awt">Window</a>&nbsp;activeWindow)
                              throws <a href="../../java/lang/SecurityException.html" title="class in java.lang">SecurityException</a></pre>
                                                                                        <div class="block">
                                                                                          Sets the active Window. Only a Frame or a Dialog can be the active Window. The native windowing system may denote the active Window or its children with special decorations, such as a highlighted title bar. The active Window is always either the focused Window, or the first Frame or Dialog that is an owner of the focused Window. 
                                                                                          
                                                                                          <p>
                                                                                            This method does not actually change the active Window as far as the native windowing system is concerned. It merely stores the value to be subsequently returned by <code>getActiveWindow()</code>. Use <code>Component.requestFocus()</code> or <code>Component.requestFocusInWindow()</code>to change the active Window, subject to platform limitations.</div> 
                                                                                            
                                                                                            <dl>
                                                                                              
<dt><span class="paramLabel">Parameters:</span></dt>
<dd><code>activeWindow</code> - the active Window</dd>
<dt><span class="throwsLabel">Throws:</span></dt>
                                                                                              
                                                                                              <dd>
                                                                                                <code>&lt;a href="../../java/lang/SecurityException.html" title="class in java.lang">SecurityException&lt;/a></code> - if this KeyboardFocusManager is not the current KeyboardFocusManager for the calling thread's context and if the calling thread does not have "replaceKeyboardFocusManager" permission
                                                                                              </dd>
<dt><span class="seeLabel">See Also:</span></dt>
                                                                                              
                                                                                              <dd>
                                                                                                <a href="../../java/awt/KeyboardFocusManager.html#getActiveWindow--"><code>getActiveWindow()</code></a>, 
<a href="../../java/awt/KeyboardFocusManager.html#getGlobalActiveWindow--"><code>getGlobalActiveWindow()</code></a>, 
<a href="../../java/awt/Component.html#requestFocus--"><code>Component.requestFocus()</code></a>, 
<a href="../../java/awt/Component.html#requestFocusInWindow--"><code>Component.requestFocusInWindow()</code></a>                                                                                              </dd>
                                                                                            </dl></li> </ul>
<a name="getDefaultFocusTraversalPolicy--">
<!--   -->
</a>
                                                                                            
                                                                                            <ul class="blockList">
                                                                                              <li class="blockList">
                                                                                                
<h4>getDefaultFocusTraversalPolicy</h4>
<pre>public&nbsp;<a href="../../java/awt/FocusTraversalPolicy.html" title="class in java.awt">FocusTraversalPolicy</a>&nbsp;getDefaultFocusTraversalPolicy()</pre>
<div class="block">
                                                                                                  Returns the default FocusTraversalPolicy. Top-level components use this value on their creation to initialize their own focus traversal policy by explicit call to Container.setFocusTraversalPolicy.
                                                                                                </div>
                                                                                                <dl>
                                                                                                  
<dt><span class="returnLabel">Returns:</span></dt>
<dd>the default FocusTraversalPolicy. null will never be returned.</dd>
<dt><span class="seeLabel">See Also:</span></dt>
                                                                                                  
                                                                                                  <dd>
                                                                                                    <a href="../../java/awt/KeyboardFocusManager.html#setDefaultFocusTraversalPolicy-java.awt.FocusTraversalPolicy-"><code>setDefaultFocusTraversalPolicy(java.awt.FocusTraversalPolicy)</code></a>, 
<a href="../../java/awt/Container.html#setFocusTraversalPolicy-java.awt.FocusTraversalPolicy-"><code>Container.setFocusTraversalPolicy(java.awt.FocusTraversalPolicy)</code></a>, 
<a href="../../java/awt/Container.html#getFocusTraversalPolicy--"><code>Container.getFocusTraversalPolicy()</code></a>                                                                                                  </dd>
                                                                                                </dl>
                                                                                              </li>
                                                                                            </ul>
<a name="setDefaultFocusTraversalPolicy-java.awt.FocusTraversalPolicy-">
<!--   -->
</a>
                                                                                            
                                                                                            <ul class="blockList">
                                                                                              <li class="blockList">
                                                                                                
<h4>setDefaultFocusTraversalPolicy</h4>
<pre>public&nbsp;void&nbsp;setDefaultFocusTraversalPolicy(<a href="../../java/awt/FocusTraversalPolicy.html" title="class in java.awt">FocusTraversalPolicy</a>&nbsp;defaultPolicy)</pre>
<div class="block">
                                                                                                  Sets the default FocusTraversalPolicy. Top-level components use this value on their creation to initialize their own focus traversal policy by explicit call to Container.setFocusTraversalPolicy. Note: this call doesn't affect already created components as they have their policy initialized. Only new components will use this policy as their default policy.
                                                                                                </div>
                                                                                                <dl>
                                                                                                  
<dt><span class="paramLabel">Parameters:</span></dt>
<dd><code>defaultPolicy</code> - the new, default FocusTraversalPolicy</dd>
<dt><span class="throwsLabel">Throws:</span></dt>
<dd><code><a href="../../java/lang/IllegalArgumentException.html" title="class in java.lang">IllegalArgumentException</a></code> - if defaultPolicy is null</dd>
<dt><span class="seeLabel">See Also:</span></dt>
                                                                                                  
                                                                                                  <dd>
                                                                                                    <a href="../../java/awt/KeyboardFocusManager.html#getDefaultFocusTraversalPolicy--"><code>getDefaultFocusTraversalPolicy()</code></a>, 
<a href="../../java/awt/Container.html#setFocusTraversalPolicy-java.awt.FocusTraversalPolicy-"><code>Container.setFocusTraversalPolicy(java.awt.FocusTraversalPolicy)</code></a>, 
<a href="../../java/awt/Container.html#getFocusTraversalPolicy--"><code>Container.getFocusTraversalPolicy()</code></a>                                                                                                  </dd>
                                                                                                </dl>
                                                                                              </li>
                                                                                            </ul>
<a name="setDefaultFocusTraversalKeys-int-java.util.Set-">
<!--   -->
</a>
                                                                                            
                                                                                            <ul class="blockList">
                                                                                              <li class="blockList">
                                                                                                
<h4>setDefaultFocusTraversalKeys</h4>
<pre>public&nbsp;void&nbsp;setDefaultFocusTraversalKeys(int&nbsp;id,
                                         <a href="../../java/util/Set.html" title="interface in java.util">Set</a>&lt;? extends <a href="../../java/awt/AWTKeyStroke.html" title="class in java.awt">AWTKeyStroke</a>&gt;&nbsp;keystrokes)</pre>
                                                                                                <div class="block">
                                                                                                  Sets the default focus traversal keys for a given traversal operation. This traversal key <code>Set</code> will be in effect on all <code>Window</code>s that have no such <code>Set</code> of their own explicitly defined. This <code>Set</code> will also be inherited, recursively, by any child <code>Component</code> of those <code>Windows</code> that has no such <code>Set</code> of its own explicitly defined. 
                                                                                                  
                                                                                                  <p>
                                                                                                    The default values for the default focus traversal keys are implementation-dependent. Sun recommends that all implementations for a particular native platform use the same default values. The recommendations for Windows and Unix are listed below. These recommendations are used in the Sun AWT implementations. <table border=1 summary="Recommended default values for focus traversal keys"> 
                                                                                                    
                                                                                                    <tr>
                                                                                                      <th>
                                                                                                        Identifier
                                                                                                      </th>
                                                                                                      
                                                                                                      <th>
                                                                                                        Meaning
                                                                                                      </th>
                                                                                                      
                                                                                                      <th>
                                                                                                        Default
                                                                                                      </th>
                                                                                                    </tr>
                                                                                                    
                                                                                                    <tr>
                                                                                                      <td>
                                                                                                        <code>KeyboardFocusManager.FORWARD_TRAVERSAL_KEYS</code>
                                                                                                      </td>
                                                                                                      
                                                                                                      <td>
                                                                                                        Normal forward keyboard traversal
                                                                                                      </td>
                                                                                                      
                                                                                                      <td>
                                                                                                        <code>TAB</code> on <code>KEY_PRESSED</code>, <code>CTRL-TAB</code> on <code>KEY_PRESSED</code>
                                                                                                      </td>
                                                                                                    </tr>
                                                                                                    
                                                                                                    <tr>
                                                                                                      <td>
                                                                                                        <code>KeyboardFocusManager.BACKWARD_TRAVERSAL_KEYS</code>
                                                                                                      </td>
                                                                                                      
                                                                                                      <td>
                                                                                                        Normal reverse keyboard traversal
                                                                                                      </td>
                                                                                                      
                                                                                                      <td>
                                                                                                        <code>SHIFT-TAB</code> on <code>KEY_PRESSED</code>, <code>CTRL-SHIFT-TAB</code> on <code>KEY_PRESSED</code>
                                                                                                      </td>
                                                                                                    </tr>
                                                                                                    
                                                                                                    <tr>
                                                                                                      <td>
                                                                                                        <code>KeyboardFocusManager.UP_CYCLE_TRAVERSAL_KEYS</code>
                                                                                                      </td>
                                                                                                      
                                                                                                      <td>
                                                                                                        Go up one focus traversal cycle
                                                                                                      </td>
                                                                                                      
                                                                                                      <td>
                                                                                                        none
                                                                                                      </td>
                                                                                                    </tr>
                                                                                                    
                                                                                                    <tr>
                                                                                                      <td>
                                                                                                        <code>KeyboardFocusManager.DOWN_CYCLE_TRAVERSAL_KEYS</code>
                                                                                                      </td>
                                                                                                      
                                                                                                      <td>
                                                                                                        Go down one focus traversal cycle
                                                                                                      </td>
                                                                                                      
                                                                                                      <td>
                                                                                                        none
                                                                                                      </td>
                                                                                                    </tr></table> To disable a traversal key, use an empty 
                                                                                                    
                                                                                                    <code>Set</code>; <code>Collections.EMPTY_SET</code> is recommended. 
                                                                                                    
                                                                                                    <p>
                                                                                                      Using the <code>AWTKeyStroke</code> API, client code can specify on which of two specific <code>KeyEvent</code>s, <code>KEY_PRESSED</code> or <code>KEY_RELEASED</code>, the focus traversal operation will occur. Regardless of which <code>KeyEvent</code> is specified, however, all <code>KeyEvent</code>s related to the focus traversal key, including the associated <code>KEY_TYPED</code> event, will be consumed, and will not be dispatched to any <code>Component</code>. It is a runtime error to specify a <code>KEY_TYPED</code> event as mapping to a focus traversal operation, or to map the same event to multiple default focus traversal operations. 
                                                                                                      
                                                                                                      <p>
                                                                                                        This method may throw a <code>ClassCastException</code> if any <code>Object</code> in <code>keystrokes</code> is not an <code>AWTKeyStroke</code>.</div> 
                                                                                                        
                                                                                                        <dl>
                                                                                                          
<dt><span class="paramLabel">Parameters:</span></dt>
                                                                                                          
                                                                                                          <dd>
                                                                                                            <code>id</code> - one of <code>KeyboardFocusManager.FORWARD_TRAVERSAL_KEYS</code>, <code>KeyboardFocusManager.BACKWARD_TRAVERSAL_KEYS</code>, <code>KeyboardFocusManager.UP_CYCLE_TRAVERSAL_KEYS</code>, or <code>KeyboardFocusManager.DOWN_CYCLE_TRAVERSAL_KEYS</code>
                                                                                                          </dd>
                                                                                                          
                                                                                                          <dd>
                                                                                                            <code>keystrokes</code> - the Set of <code>AWTKeyStroke</code>s for the specified operation
                                                                                                          </dd>
<dt><span class="throwsLabel">Throws:</span></dt>
                                                                                                          
                                                                                                          <dd>
                                                                                                            <code>&lt;a href="../../java/lang/IllegalArgumentException.html" title="class in java.lang">IllegalArgumentException&lt;/a></code> - if id is not one of <code>KeyboardFocusManager.FORWARD_TRAVERSAL_KEYS</code>, <code>KeyboardFocusManager.BACKWARD_TRAVERSAL_KEYS</code>, <code>KeyboardFocusManager.UP_CYCLE_TRAVERSAL_KEYS</code>, or <code>KeyboardFocusManager.DOWN_CYCLE_TRAVERSAL_KEYS</code>, or if keystrokes is <code>null</code>, or if keystrokes contains <code>null</code>, or if any keystroke represents a <code>KEY_TYPED</code> event, or if any keystroke already maps to another default focus traversal operation
                                                                                                          </dd>
<dt><span class="seeLabel">See Also:</span></dt>
                                                                                                          
                                                                                                          <dd>
                                                                                                            <a href="../../java/awt/KeyboardFocusManager.html#getDefaultFocusTraversalKeys-int-"><code>getDefaultFocusTraversalKeys(int)</code></a>, 
<a href="../../java/awt/Component.html#setFocusTraversalKeys-int-java.util.Set-"><code>Component.setFocusTraversalKeys(int, java.util.Set&lt;? extends java.awt.AWTKeyStroke&gt;)</code></a>, 
<a href="../../java/awt/Component.html#getFocusTraversalKeys-int-"><code>Component.getFocusTraversalKeys(int)</code></a>                                                                                                          </dd>
                                                                                                        </dl></li> </ul>
<a name="getDefaultFocusTraversalKeys-int-">
<!--   -->
</a>
                                                                                                        
                                                                                                        <ul class="blockList">
                                                                                                          <li class="blockList">
                                                                                                            
<h4>getDefaultFocusTraversalKeys</h4>
<pre>public&nbsp;<a href="../../java/util/Set.html" title="interface in java.util">Set</a>&lt;<a href="../../java/awt/AWTKeyStroke.html" title="class in java.awt">AWTKeyStroke</a>&gt;&nbsp;getDefaultFocusTraversalKeys(int&nbsp;id)</pre>
<div class="block">
                                                                                                              Returns a Set of default focus traversal keys for a given traversal operation. This traversal key Set will be in effect on all Windows that have no such Set of their own explicitly defined. This Set will also be inherited, recursively, by any child Component of those Windows that has no such Set of its own explicitly defined. (See <code>setDefaultFocusTraversalKeys</code> for a full description of each operation.)
                                                                                                            </div>
                                                                                                            <dl>
                                                                                                              
<dt><span class="paramLabel">Parameters:</span></dt>
                                                                                                              
                                                                                                              <dd>
                                                                                                                <code>id</code> - one of KeyboardFocusManager.FORWARD_TRAVERSAL_KEYS, KeyboardFocusManager.BACKWARD_TRAVERSAL_KEYS, KeyboardFocusManager.UP_CYCLE_TRAVERSAL_KEYS, or KeyboardFocusManager.DOWN_CYCLE_TRAVERSAL_KEYS
                                                                                                              </dd>
<dt><span class="returnLabel">Returns:</span></dt>
                                                                                                              
                                                                                                              <dd>
                                                                                                                the <code>Set</code> of <code>AWTKeyStroke</code>s for the specified operation; the <code>Set</code> will be unmodifiable, and may be empty; <code>null</code> will never be returned
                                                                                                              </dd>
<dt><span class="throwsLabel">Throws:</span></dt>
                                                                                                              
                                                                                                              <dd>
                                                                                                                <code>&lt;a href="../../java/lang/IllegalArgumentException.html" title="class in java.lang">IllegalArgumentException&lt;/a></code> - if id is not one of KeyboardFocusManager.FORWARD_TRAVERSAL_KEYS, KeyboardFocusManager.BACKWARD_TRAVERSAL_KEYS, KeyboardFocusManager.UP_CYCLE_TRAVERSAL_KEYS, or KeyboardFocusManager.DOWN_CYCLE_TRAVERSAL_KEYS
                                                                                                              </dd>
<dt><span class="seeLabel">See Also:</span></dt>
                                                                                                              
                                                                                                              <dd>
                                                                                                                <a href="../../java/awt/KeyboardFocusManager.html#setDefaultFocusTraversalKeys-int-java.util.Set-"><code>setDefaultFocusTraversalKeys(int, java.util.Set&lt;? extends java.awt.AWTKeyStroke&gt;)</code></a>, 
<a href="../../java/awt/Component.html#setFocusTraversalKeys-int-java.util.Set-"><code>Component.setFocusTraversalKeys(int, java.util.Set&lt;? extends java.awt.AWTKeyStroke&gt;)</code></a>, 
<a href="../../java/awt/Component.html#getFocusTraversalKeys-int-"><code>Component.getFocusTraversalKeys(int)</code></a>                                                                                                              </dd>
                                                                                                            </dl>
                                                                                                          </li>
                                                                                                        </ul>
<a name="getCurrentFocusCycleRoot--">
<!--   -->
</a>
                                                                                                        
                                                                                                        <ul class="blockList">
                                                                                                          <li class="blockList">
                                                                                                            
<h4>getCurrentFocusCycleRoot</h4>
<pre>public&nbsp;<a href="../../java/awt/Container.html" title="class in java.awt">Container</a>&nbsp;getCurrentFocusCycleRoot()</pre>
<div class="block">
                                                                                                              Returns the current focus cycle root, if the current focus cycle root is in the same context as the calling thread. If the focus owner is itself a focus cycle root, then it may be ambiguous as to which Components represent the next and previous Components to focus during normal focus traversal. In that case, the current focus cycle root is used to differentiate among the possibilities. 
                                                                                                              
                                                                                                              <p>
                                                                                                                This method is intended to be used only by KeyboardFocusManagers and focus implementations. It is not for general client use.</div> 
                                                                                                                
                                                                                                                <dl>
                                                                                                                  
<dt><span class="returnLabel">Returns:</span></dt>
                                                                                                                  
                                                                                                                  <dd>
                                                                                                                    the current focus cycle root, or null if the current focus cycle root is not a member of the calling thread's context
                                                                                                                  </dd>
<dt><span class="seeLabel">See Also:</span></dt>
                                                                                                                  
                                                                                                                  <dd>
                                                                                                                    <a href="../../java/awt/KeyboardFocusManager.html#getGlobalCurrentFocusCycleRoot--"><code>getGlobalCurrentFocusCycleRoot()</code></a>, 
<a href="../../java/awt/KeyboardFocusManager.html#setGlobalCurrentFocusCycleRoot-java.awt.Container-"><code>setGlobalCurrentFocusCycleRoot(java.awt.Container)</code></a>                                                                                                                  </dd>
                                                                                                                </dl></li> </ul>
<a name="getGlobalCurrentFocusCycleRoot--">
<!--   -->
</a>
                                                                                                                
                                                                                                                <ul class="blockList">
                                                                                                                  <li class="blockList">
                                                                                                                    
<h4>getGlobalCurrentFocusCycleRoot</h4>
<pre>protected&nbsp;<a href="../../java/awt/Container.html" title="class in java.awt">Container</a>&nbsp;getGlobalCurrentFocusCycleRoot()
                                            throws <a href="../../java/lang/SecurityException.html" title="class in java.lang">SecurityException</a></pre>
                                                                                                                    <div class="block">
                                                                                                                      Returns the current focus cycle root, even if the calling thread is in a different context than the current focus cycle root. If the focus owner is itself a focus cycle root, then it may be ambiguous as to which Components represent the next and previous Components to focus during normal focus traversal. In that case, the current focus cycle root is used to differentiate among the possibilities.
                                                                                                                    </div>
                                                                                                                    <dl>
                                                                                                                      
<dt><span class="returnLabel">Returns:</span></dt>
                                                                                                                      
                                                                                                                      <dd>
                                                                                                                        the current focus cycle root, or null if the current focus cycle root is not a member of the calling thread's context
                                                                                                                      </dd>
<dt><span class="throwsLabel">Throws:</span></dt>
                                                                                                                      
                                                                                                                      <dd>
                                                                                                                        <code>&lt;a href="../../java/lang/SecurityException.html" title="class in java.lang">SecurityException&lt;/a></code> - if this KeyboardFocusManager is not the current KeyboardFocusManager for the calling thread's context and if the calling thread does not have "replaceKeyboardFocusManager" permission
                                                                                                                      </dd>
<dt><span class="seeLabel">See Also:</span></dt>
                                                                                                                      
                                                                                                                      <dd>
                                                                                                                        <a href="../../java/awt/KeyboardFocusManager.html#getCurrentFocusCycleRoot--"><code>getCurrentFocusCycleRoot()</code></a>, 
<a href="../../java/awt/KeyboardFocusManager.html#setGlobalCurrentFocusCycleRoot-java.awt.Container-"><code>setGlobalCurrentFocusCycleRoot(java.awt.Container)</code></a>                                                                                                                      </dd>
                                                                                                                    </dl>
                                                                                                                  </li>
                                                                                                                </ul>
<a name="setGlobalCurrentFocusCycleRoot-java.awt.Container-">
<!--   -->
</a>
                                                                                                                
                                                                                                                <ul class="blockList">
                                                                                                                  <li class="blockList">
                                                                                                                    
<h4>setGlobalCurrentFocusCycleRoot</h4>
<pre>public&nbsp;void&nbsp;setGlobalCurrentFocusCycleRoot(<a href="../../java/awt/Container.html" title="class in java.awt">Container</a>&nbsp;newFocusCycleRoot)
                                    throws <a href="../../java/lang/SecurityException.html" title="class in java.lang">SecurityException</a></pre>
                                                                                                                    <div class="block">
                                                                                                                      Sets the current focus cycle root. If the focus owner is itself a focus cycle root, then it may be ambiguous as to which Components represent the next and previous Components to focus during normal focus traversal. In that case, the current focus cycle root is used to differentiate among the possibilities. 
                                                                                                                      
                                                                                                                      <p>
                                                                                                                        If a SecurityManager is installed, the calling thread must be granted the "replaceKeyboardFocusManager" AWTPermission. If this permission is not granted, this method will throw a SecurityException, and the current focus cycle root will not be changed. 
                                                                                                                        
                                                                                                                        <p>
                                                                                                                          This method is intended to be used only by KeyboardFocusManagers and focus implementations. It is not for general client use.</div> 
                                                                                                                          
                                                                                                                          <dl>
                                                                                                                            
<dt><span class="paramLabel">Parameters:</span></dt>
<dd><code>newFocusCycleRoot</code> - the new focus cycle root</dd>
<dt><span class="throwsLabel">Throws:</span></dt>
                                                                                                                            
                                                                                                                            <dd>
                                                                                                                              <code>&lt;a href="../../java/lang/SecurityException.html" title="class in java.lang">SecurityException&lt;/a></code> - if the calling thread does not have "replaceKeyboardFocusManager" permission
                                                                                                                            </dd>
<dt><span class="seeLabel">See Also:</span></dt>
                                                                                                                            
                                                                                                                            <dd>
                                                                                                                              <a href="../../java/awt/KeyboardFocusManager.html#getCurrentFocusCycleRoot--"><code>getCurrentFocusCycleRoot()</code></a>, 
<a href="../../java/awt/KeyboardFocusManager.html#getGlobalCurrentFocusCycleRoot--"><code>getGlobalCurrentFocusCycleRoot()</code></a>                                                                                                                            </dd>
                                                                                                                          </dl></li> </ul>
<a name="addPropertyChangeListener-java.beans.PropertyChangeListener-">
<!--   -->
</a>
                                                                                                                          
                                                                                                                          <ul class="blockList">
                                                                                                                            <li class="blockList">
                                                                                                                              
<h4>addPropertyChangeListener</h4>
<pre>public&nbsp;void&nbsp;addPropertyChangeListener(<a href="../../java/beans/PropertyChangeListener.html" title="interface in java.beans">PropertyChangeListener</a>&nbsp;listener)</pre>
<div class="block">
                                                                                                                                Adds a PropertyChangeListener to the listener list. The listener is registered for all bound properties of this class, including the following: 
                                                                                                                                
                                                                                                                                <ul>
                                                                                                                                  <li>
                                                                                                                                    whether the KeyboardFocusManager is currently managing focus for this application or applet's browser context ("managingFocus")
                                                                                                                                  </li>
                                                                                                                                  <li>
                                                                                                                                    the focus owner ("focusOwner")
                                                                                                                                  </li>
                                                                                                                                  <li>
                                                                                                                                    the permanent focus owner ("permanentFocusOwner")
                                                                                                                                  </li>
                                                                                                                                  <li>
                                                                                                                                    the focused Window ("focusedWindow")
                                                                                                                                  </li>
                                                                                                                                  <li>
                                                                                                                                    the active Window ("activeWindow")
                                                                                                                                  </li>
                                                                                                                                  <li>
                                                                                                                                    the default focus traversal policy ("defaultFocusTraversalPolicy")
                                                                                                                                  </li>
                                                                                                                                  <li>
                                                                                                                                    the Set of default FORWARD_TRAVERSAL_KEYS ("forwardDefaultFocusTraversalKeys")
                                                                                                                                  </li>
                                                                                                                                  <li>
                                                                                                                                    the Set of default BACKWARD_TRAVERSAL_KEYS ("backwardDefaultFocusTraversalKeys")
                                                                                                                                  </li>
                                                                                                                                  <li>
                                                                                                                                    the Set of default UP_CYCLE_TRAVERSAL_KEYS ("upCycleDefaultFocusTraversalKeys")
                                                                                                                                  </li>
                                                                                                                                  <li>
                                                                                                                                    the Set of default DOWN_CYCLE_TRAVERSAL_KEYS ("downCycleDefaultFocusTraversalKeys")
                                                                                                                                  </li>
                                                                                                                                  <li>
                                                                                                                                    the current focus cycle root ("currentFocusCycleRoot")
                                                                                                                                  </li>
                                                                                                                                </ul> If listener is null, no exception is thrown and no action is performed.
                                                                                                                              </div>
                                                                                                                              
                                                                                                                              <dl>
                                                                                                                                
<dt><span class="paramLabel">Parameters:</span></dt>
<dd><code>listener</code> - the PropertyChangeListener to be added</dd>
<dt><span class="seeLabel">See Also:</span></dt>
                                                                                                                                
                                                                                                                                <dd>
                                                                                                                                  <a href="../../java/awt/KeyboardFocusManager.html#removePropertyChangeListener-java.beans.PropertyChangeListener-"><code>removePropertyChangeListener(java.beans.PropertyChangeListener)</code></a>, 
<a href="../../java/awt/KeyboardFocusManager.html#getPropertyChangeListeners--"><code>getPropertyChangeListeners()</code></a>, 
<a href="../../java/awt/KeyboardFocusManager.html#addPropertyChangeListener-java.lang.String-java.beans.PropertyChangeListener-"><code>addPropertyChangeListener(java.lang.String,java.beans.PropertyChangeListener)</code></a>                                                                                                                                </dd>
                                                                                                                              </dl>
                                                                                                                            </li>
                                                                                                                          </ul>
<a name="removePropertyChangeListener-java.beans.PropertyChangeListener-">
<!--   -->
</a>
                                                                                                                          
                                                                                                                          <ul class="blockList">
                                                                                                                            <li class="blockList">
                                                                                                                              
<h4>removePropertyChangeListener</h4>
<pre>public&nbsp;void&nbsp;removePropertyChangeListener(<a href="../../java/beans/PropertyChangeListener.html" title="interface in java.beans">PropertyChangeListener</a>&nbsp;listener)</pre>
<div class="block">
                                                                                                                                Removes a PropertyChangeListener from the listener list. This method should be used to remove the PropertyChangeListeners that were registered for all bound properties of this class. 
                                                                                                                                
                                                                                                                                <p>
                                                                                                                                  If listener is null, no exception is thrown and no action is performed.</div> 
                                                                                                                                  
                                                                                                                                  <dl>
                                                                                                                                    
<dt><span class="paramLabel">Parameters:</span></dt>
<dd><code>listener</code> - the PropertyChangeListener to be removed</dd>
<dt><span class="seeLabel">See Also:</span></dt>
                                                                                                                                    
                                                                                                                                    <dd>
                                                                                                                                      <a href="../../java/awt/KeyboardFocusManager.html#addPropertyChangeListener-java.beans.PropertyChangeListener-"><code>addPropertyChangeListener(java.beans.PropertyChangeListener)</code></a>, 
<a href="../../java/awt/KeyboardFocusManager.html#getPropertyChangeListeners--"><code>getPropertyChangeListeners()</code></a>, 
<a href="../../java/awt/KeyboardFocusManager.html#removePropertyChangeListener-java.lang.String-java.beans.PropertyChangeListener-"><code>removePropertyChangeListener(java.lang.String,java.beans.PropertyChangeListener)</code></a>                                                                                                                                    </dd>
                                                                                                                                  </dl></li> </ul>
<a name="getPropertyChangeListeners--">
<!--   -->
</a>
                                                                                                                                  
                                                                                                                                  <ul class="blockList">
                                                                                                                                    <li class="blockList">
                                                                                                                                      
<h4>getPropertyChangeListeners</h4>
<pre>public&nbsp;<a href="../../java/beans/PropertyChangeListener.html" title="interface in java.beans">PropertyChangeListener</a>[]&nbsp;getPropertyChangeListeners()</pre>
<div class="block">
                                                                                                                                        Returns an array of all the property change listeners registered on this keyboard focus manager.
                                                                                                                                      </div>
                                                                                                                                      <dl>
                                                                                                                                        
<dt><span class="returnLabel">Returns:</span></dt>
                                                                                                                                        
                                                                                                                                        <dd>
                                                                                                                                          all of this keyboard focus manager's <code>PropertyChangeListener</code>s or an empty array if no property change listeners are currently registered
                                                                                                                                        </dd>
<dt><span class="simpleTagLabel">Since:</span></dt>
<dd>1.4</dd>
<dt><span class="seeLabel">See Also:</span></dt>
                                                                                                                                        
                                                                                                                                        <dd>
                                                                                                                                          <a href="../../java/awt/KeyboardFocusManager.html#addPropertyChangeListener-java.beans.PropertyChangeListener-"><code>addPropertyChangeListener(java.beans.PropertyChangeListener)</code></a>, 
<a href="../../java/awt/KeyboardFocusManager.html#removePropertyChangeListener-java.beans.PropertyChangeListener-"><code>removePropertyChangeListener(java.beans.PropertyChangeListener)</code></a>, 
<a href="../../java/awt/KeyboardFocusManager.html#getPropertyChangeListeners-java.lang.String-"><code>getPropertyChangeListeners(java.lang.String)</code></a>                                                                                                                                        </dd>
                                                                                                                                      </dl>
                                                                                                                                    </li>
                                                                                                                                  </ul>
<a name="addPropertyChangeListener-java.lang.String-java.beans.PropertyChangeListener-">
<!--   -->
</a>
                                                                                                                                  
                                                                                                                                  <ul class="blockList">
                                                                                                                                    <li class="blockList">
                                                                                                                                      
<h4>addPropertyChangeListener</h4>
<pre>public&nbsp;void&nbsp;addPropertyChangeListener(<a href="../../java/lang/String.html" title="class in java.lang">String</a>&nbsp;propertyName,
                                      <a href="../../java/beans/PropertyChangeListener.html" title="interface in java.beans">PropertyChangeListener</a>&nbsp;listener)</pre>
                                                                                                                                      <div class="block">
                                                                                                                                        Adds a PropertyChangeListener to the listener list for a specific property. The specified property may be user-defined, or one of the following: 
                                                                                                                                        
                                                                                                                                        <ul>
                                                                                                                                          <li>
                                                                                                                                            whether the KeyboardFocusManager is currently managing focus for this application or applet's browser context ("managingFocus")
                                                                                                                                          </li>
                                                                                                                                          <li>
                                                                                                                                            the focus owner ("focusOwner")
                                                                                                                                          </li>
                                                                                                                                          <li>
                                                                                                                                            the permanent focus owner ("permanentFocusOwner")
                                                                                                                                          </li>
                                                                                                                                          <li>
                                                                                                                                            the focused Window ("focusedWindow")
                                                                                                                                          </li>
                                                                                                                                          <li>
                                                                                                                                            the active Window ("activeWindow")
                                                                                                                                          </li>
                                                                                                                                          <li>
                                                                                                                                            the default focus traversal policy ("defaultFocusTraversalPolicy")
                                                                                                                                          </li>
                                                                                                                                          <li>
                                                                                                                                            the Set of default FORWARD_TRAVERSAL_KEYS ("forwardDefaultFocusTraversalKeys")
                                                                                                                                          </li>
                                                                                                                                          <li>
                                                                                                                                            the Set of default BACKWARD_TRAVERSAL_KEYS ("backwardDefaultFocusTraversalKeys")
                                                                                                                                          </li>
                                                                                                                                          <li>
                                                                                                                                            the Set of default UP_CYCLE_TRAVERSAL_KEYS ("upCycleDefaultFocusTraversalKeys")
                                                                                                                                          </li>
                                                                                                                                          <li>
                                                                                                                                            the Set of default DOWN_CYCLE_TRAVERSAL_KEYS ("downCycleDefaultFocusTraversalKeys")
                                                                                                                                          </li>
                                                                                                                                          <li>
                                                                                                                                            the current focus cycle root ("currentFocusCycleRoot")
                                                                                                                                          </li>
                                                                                                                                        </ul> If listener is null, no exception is thrown and no action is performed.
                                                                                                                                      </div>
                                                                                                                                      
                                                                                                                                      <dl>
                                                                                                                                        
<dt><span class="paramLabel">Parameters:</span></dt>
<dd><code>propertyName</code> - one of the property names listed above</dd>
<dd><code>listener</code> - the PropertyChangeListener to be added</dd>
<dt><span class="seeLabel">See Also:</span></dt>
                                                                                                                                        
                                                                                                                                        <dd>
                                                                                                                                          <a href="../../java/awt/KeyboardFocusManager.html#addPropertyChangeListener-java.beans.PropertyChangeListener-"><code>addPropertyChangeListener(java.beans.PropertyChangeListener)</code></a>, 
<a href="../../java/awt/KeyboardFocusManager.html#removePropertyChangeListener-java.lang.String-java.beans.PropertyChangeListener-"><code>removePropertyChangeListener(java.lang.String,java.beans.PropertyChangeListener)</code></a>, 
<a href="../../java/awt/KeyboardFocusManager.html#getPropertyChangeListeners-java.lang.String-"><code>getPropertyChangeListeners(java.lang.String)</code></a>                                                                                                                                        </dd>
                                                                                                                                      </dl>
                                                                                                                                    </li>
                                                                                                                                  </ul>
<a name="removePropertyChangeListener-java.lang.String-java.beans.PropertyChangeListener-">
<!--   -->
</a>
                                                                                                                                  
                                                                                                                                  <ul class="blockList">
                                                                                                                                    <li class="blockList">
                                                                                                                                      
<h4>removePropertyChangeListener</h4>
<pre>public&nbsp;void&nbsp;removePropertyChangeListener(<a href="../../java/lang/String.html" title="class in java.lang">String</a>&nbsp;propertyName,
                                         <a href="../../java/beans/PropertyChangeListener.html" title="interface in java.beans">PropertyChangeListener</a>&nbsp;listener)</pre>
                                                                                                                                      <div class="block">
                                                                                                                                        Removes a PropertyChangeListener from the listener list for a specific property. This method should be used to remove PropertyChangeListeners that were registered for a specific bound property. 
                                                                                                                                        
                                                                                                                                        <p>
                                                                                                                                          If listener is null, no exception is thrown and no action is performed.</div> 
                                                                                                                                          
                                                                                                                                          <dl>
                                                                                                                                            
<dt><span class="paramLabel">Parameters:</span></dt>
<dd><code>propertyName</code> - a valid property name</dd>
<dd><code>listener</code> - the PropertyChangeListener to be removed</dd>
<dt><span class="seeLabel">See Also:</span></dt>
                                                                                                                                            
                                                                                                                                            <dd>
                                                                                                                                              <a href="../../java/awt/KeyboardFocusManager.html#addPropertyChangeListener-java.lang.String-java.beans.PropertyChangeListener-"><code>addPropertyChangeListener(java.lang.String,java.beans.PropertyChangeListener)</code></a>, 
<a href="../../java/awt/KeyboardFocusManager.html#getPropertyChangeListeners-java.lang.String-"><code>getPropertyChangeListeners(java.lang.String)</code></a>, 
<a href="../../java/awt/KeyboardFocusManager.html#removePropertyChangeListener-java.beans.PropertyChangeListener-"><code>removePropertyChangeListener(java.beans.PropertyChangeListener)</code></a>                                                                                                                                            </dd>
                                                                                                                                          </dl></li> </ul>
<a name="getPropertyChangeListeners-java.lang.String-">
<!--   -->
</a>
                                                                                                                                          
                                                                                                                                          <ul class="blockList">
                                                                                                                                            <li class="blockList">
                                                                                                                                              
<h4>getPropertyChangeListeners</h4>
<pre>public&nbsp;<a href="../../java/beans/PropertyChangeListener.html" title="interface in java.beans">PropertyChangeListener</a>[]&nbsp;getPropertyChangeListeners(<a href="../../java/lang/String.html" title="class in java.lang">String</a>&nbsp;propertyName)</pre>
<div class="block">
                                                                                                                                                Returns an array of all the <code>PropertyChangeListener</code>s associated with the named property.
                                                                                                                                              </div>
                                                                                                                                              <dl>
                                                                                                                                                
<dt><span class="returnLabel">Returns:</span></dt>
                                                                                                                                                
                                                                                                                                                <dd>
                                                                                                                                                  all of the <code>PropertyChangeListener</code>s associated with the named property or an empty array if no such listeners have been added.
                                                                                                                                                </dd>
<dt><span class="simpleTagLabel">Since:</span></dt>
<dd>1.4</dd>
<dt><span class="seeLabel">See Also:</span></dt>
                                                                                                                                                
                                                                                                                                                <dd>
                                                                                                                                                  <a href="../../java/awt/KeyboardFocusManager.html#addPropertyChangeListener-java.lang.String-java.beans.PropertyChangeListener-"><code>addPropertyChangeListener(java.lang.String,java.beans.PropertyChangeListener)</code></a>, 
<a href="../../java/awt/KeyboardFocusManager.html#removePropertyChangeListener-java.lang.String-java.beans.PropertyChangeListener-"><code>removePropertyChangeListener(java.lang.String,java.beans.PropertyChangeListener)</code></a>                                                                                                                                                </dd>
                                                                                                                                              </dl>
                                                                                                                                            </li>
                                                                                                                                          </ul>
<a name="firePropertyChange-java.lang.String-java.lang.Object-java.lang.Object-">
<!--   -->
</a>
                                                                                                                                          
                                                                                                                                          <ul class="blockList">
                                                                                                                                            <li class="blockList">
                                                                                                                                              
<h4>firePropertyChange</h4>
<pre>protected&nbsp;void&nbsp;firePropertyChange(<a href="../../java/lang/String.html" title="class in java.lang">String</a>&nbsp;propertyName,
                                  <a href="../../java/lang/Object.html" title="class in java.lang">Object</a>&nbsp;oldValue,
                                  <a href="../../java/lang/Object.html" title="class in java.lang">Object</a>&nbsp;newValue)</pre>
                                                                                                                                              <div class="block">
                                                                                                                                                Fires a PropertyChangeEvent in response to a change in a bound property. The event will be delivered to all registered PropertyChangeListeners. No event will be delivered if oldValue and newValue are the same.
                                                                                                                                              </div>
                                                                                                                                              <dl>
                                                                                                                                                
<dt><span class="paramLabel">Parameters:</span></dt>
<dd><code>propertyName</code> - the name of the property that has changed</dd>
<dd><code>oldValue</code> - the property's previous value</dd>
<dd><code>newValue</code> - the property's new value</dd>
                                                                                                                                              </dl>
                                                                                                                                            </li>
                                                                                                                                          </ul>
<a name="addVetoableChangeListener-java.beans.VetoableChangeListener-">
<!--   -->
</a>
                                                                                                                                          
                                                                                                                                          <ul class="blockList">
                                                                                                                                            <li class="blockList">
                                                                                                                                              
<h4>addVetoableChangeListener</h4>
<pre>public&nbsp;void&nbsp;addVetoableChangeListener(<a href="../../java/beans/VetoableChangeListener.html" title="interface in java.beans">VetoableChangeListener</a>&nbsp;listener)</pre>
<div class="block">
                                                                                                                                                Adds a VetoableChangeListener to the listener list. The listener is registered for all vetoable properties of this class, including the following: 
                                                                                                                                                
                                                                                                                                                <ul>
                                                                                                                                                  <li>
                                                                                                                                                    the focus owner ("focusOwner")
                                                                                                                                                  </li>
                                                                                                                                                  <li>
                                                                                                                                                    the permanent focus owner ("permanentFocusOwner")
                                                                                                                                                  </li>
                                                                                                                                                  <li>
                                                                                                                                                    the focused Window ("focusedWindow")
                                                                                                                                                  </li>
                                                                                                                                                  <li>
                                                                                                                                                    the active Window ("activeWindow")
                                                                                                                                                  </li>
                                                                                                                                                </ul> If listener is null, no exception is thrown and no action is performed.
                                                                                                                                              </div>
                                                                                                                                              
                                                                                                                                              <dl>
                                                                                                                                                
<dt><span class="paramLabel">Parameters:</span></dt>
<dd><code>listener</code> - the VetoableChangeListener to be added</dd>
<dt><span class="seeLabel">See Also:</span></dt>
                                                                                                                                                
                                                                                                                                                <dd>
                                                                                                                                                  <a href="../../java/awt/KeyboardFocusManager.html#removeVetoableChangeListener-java.beans.VetoableChangeListener-"><code>removeVetoableChangeListener(java.beans.VetoableChangeListener)</code></a>, 
<a href="../../java/awt/KeyboardFocusManager.html#getVetoableChangeListeners--"><code>getVetoableChangeListeners()</code></a>, 
<a href="../../java/awt/KeyboardFocusManager.html#addVetoableChangeListener-java.lang.String-java.beans.VetoableChangeListener-"><code>addVetoableChangeListener(java.lang.String,java.beans.VetoableChangeListener)</code></a>                                                                                                                                                </dd>
                                                                                                                                              </dl>
                                                                                                                                            </li>
                                                                                                                                          </ul>
<a name="removeVetoableChangeListener-java.beans.VetoableChangeListener-">
<!--   -->
</a>
                                                                                                                                          
                                                                                                                                          <ul class="blockList">
                                                                                                                                            <li class="blockList">
                                                                                                                                              
<h4>removeVetoableChangeListener</h4>
<pre>public&nbsp;void&nbsp;removeVetoableChangeListener(<a href="../../java/beans/VetoableChangeListener.html" title="interface in java.beans">VetoableChangeListener</a>&nbsp;listener)</pre>
<div class="block">
                                                                                                                                                Removes a VetoableChangeListener from the listener list. This method should be used to remove the VetoableChangeListeners that were registered for all vetoable properties of this class. 
                                                                                                                                                
                                                                                                                                                <p>
                                                                                                                                                  If listener is null, no exception is thrown and no action is performed.</div> 
                                                                                                                                                  
                                                                                                                                                  <dl>
                                                                                                                                                    
<dt><span class="paramLabel">Parameters:</span></dt>
<dd><code>listener</code> - the VetoableChangeListener to be removed</dd>
<dt><span class="seeLabel">See Also:</span></dt>
                                                                                                                                                    
                                                                                                                                                    <dd>
                                                                                                                                                      <a href="../../java/awt/KeyboardFocusManager.html#addVetoableChangeListener-java.beans.VetoableChangeListener-"><code>addVetoableChangeListener(java.beans.VetoableChangeListener)</code></a>, 
<a href="../../java/awt/KeyboardFocusManager.html#getVetoableChangeListeners--"><code>getVetoableChangeListeners()</code></a>, 
<a href="../../java/awt/KeyboardFocusManager.html#removeVetoableChangeListener-java.lang.String-java.beans.VetoableChangeListener-"><code>removeVetoableChangeListener(java.lang.String,java.beans.VetoableChangeListener)</code></a>                                                                                                                                                    </dd>
                                                                                                                                                  </dl></li> </ul>
<a name="getVetoableChangeListeners--">
<!--   -->
</a>
                                                                                                                                                  
                                                                                                                                                  <ul class="blockList">
                                                                                                                                                    <li class="blockList">
                                                                                                                                                      
<h4>getVetoableChangeListeners</h4>
<pre>public&nbsp;<a href="../../java/beans/VetoableChangeListener.html" title="interface in java.beans">VetoableChangeListener</a>[]&nbsp;getVetoableChangeListeners()</pre>
<div class="block">
                                                                                                                                                        Returns an array of all the vetoable change listeners registered on this keyboard focus manager.
                                                                                                                                                      </div>
                                                                                                                                                      <dl>
                                                                                                                                                        
<dt><span class="returnLabel">Returns:</span></dt>
                                                                                                                                                        
                                                                                                                                                        <dd>
                                                                                                                                                          all of this keyboard focus manager's <code>VetoableChangeListener</code>s or an empty array if no vetoable change listeners are currently registered
                                                                                                                                                        </dd>
<dt><span class="simpleTagLabel">Since:</span></dt>
<dd>1.4</dd>
<dt><span class="seeLabel">See Also:</span></dt>
                                                                                                                                                        
                                                                                                                                                        <dd>
                                                                                                                                                          <a href="../../java/awt/KeyboardFocusManager.html#addVetoableChangeListener-java.beans.VetoableChangeListener-"><code>addVetoableChangeListener(java.beans.VetoableChangeListener)</code></a>, 
<a href="../../java/awt/KeyboardFocusManager.html#removeVetoableChangeListener-java.beans.VetoableChangeListener-"><code>removeVetoableChangeListener(java.beans.VetoableChangeListener)</code></a>, 
<a href="../../java/awt/KeyboardFocusManager.html#getVetoableChangeListeners-java.lang.String-"><code>getVetoableChangeListeners(java.lang.String)</code></a>                                                                                                                                                        </dd>
                                                                                                                                                      </dl>
                                                                                                                                                    </li>
                                                                                                                                                  </ul>
<a name="addVetoableChangeListener-java.lang.String-java.beans.VetoableChangeListener-">
<!--   -->
</a>
                                                                                                                                                  
                                                                                                                                                  <ul class="blockList">
                                                                                                                                                    <li class="blockList">
                                                                                                                                                      
<h4>addVetoableChangeListener</h4>
<pre>public&nbsp;void&nbsp;addVetoableChangeListener(<a href="../../java/lang/String.html" title="class in java.lang">String</a>&nbsp;propertyName,
                                      <a href="../../java/beans/VetoableChangeListener.html" title="interface in java.beans">VetoableChangeListener</a>&nbsp;listener)</pre>
                                                                                                                                                      <div class="block">
                                                                                                                                                        Adds a VetoableChangeListener to the listener list for a specific property. The specified property may be user-defined, or one of the following: 
                                                                                                                                                        
                                                                                                                                                        <ul>
                                                                                                                                                          <li>
                                                                                                                                                            the focus owner ("focusOwner")
                                                                                                                                                          </li>
                                                                                                                                                          <li>
                                                                                                                                                            the permanent focus owner ("permanentFocusOwner")
                                                                                                                                                          </li>
                                                                                                                                                          <li>
                                                                                                                                                            the focused Window ("focusedWindow")
                                                                                                                                                          </li>
                                                                                                                                                          <li>
                                                                                                                                                            the active Window ("activeWindow")
                                                                                                                                                          </li>
                                                                                                                                                        </ul> If listener is null, no exception is thrown and no action is performed.
                                                                                                                                                      </div>
                                                                                                                                                      
                                                                                                                                                      <dl>
                                                                                                                                                        
<dt><span class="paramLabel">Parameters:</span></dt>
<dd><code>propertyName</code> - one of the property names listed above</dd>
<dd><code>listener</code> - the VetoableChangeListener to be added</dd>
<dt><span class="seeLabel">See Also:</span></dt>
                                                                                                                                                        
                                                                                                                                                        <dd>
                                                                                                                                                          <a href="../../java/awt/KeyboardFocusManager.html#addVetoableChangeListener-java.beans.VetoableChangeListener-"><code>addVetoableChangeListener(java.beans.VetoableChangeListener)</code></a>, 
<a href="../../java/awt/KeyboardFocusManager.html#removeVetoableChangeListener-java.beans.VetoableChangeListener-"><code>removeVetoableChangeListener(java.beans.VetoableChangeListener)</code></a>, 
<a href="../../java/awt/KeyboardFocusManager.html#getVetoableChangeListeners--"><code>getVetoableChangeListeners()</code></a>                                                                                                                                                        </dd>
                                                                                                                                                      </dl>
                                                                                                                                                    </li>
                                                                                                                                                  </ul>
<a name="removeVetoableChangeListener-java.lang.String-java.beans.VetoableChangeListener-">
<!--   -->
</a>
                                                                                                                                                  
                                                                                                                                                  <ul class="blockList">
                                                                                                                                                    <li class="blockList">
                                                                                                                                                      
<h4>removeVetoableChangeListener</h4>
<pre>public&nbsp;void&nbsp;removeVetoableChangeListener(<a href="../../java/lang/String.html" title="class in java.lang">String</a>&nbsp;propertyName,
                                         <a href="../../java/beans/VetoableChangeListener.html" title="interface in java.beans">VetoableChangeListener</a>&nbsp;listener)</pre>
                                                                                                                                                      <div class="block">
                                                                                                                                                        Removes a VetoableChangeListener from the listener list for a specific property. This method should be used to remove VetoableChangeListeners that were registered for a specific bound property. 
                                                                                                                                                        
                                                                                                                                                        <p>
                                                                                                                                                          If listener is null, no exception is thrown and no action is performed.</div> 
                                                                                                                                                          
                                                                                                                                                          <dl>
                                                                                                                                                            
<dt><span class="paramLabel">Parameters:</span></dt>
<dd><code>propertyName</code> - a valid property name</dd>
<dd><code>listener</code> - the VetoableChangeListener to be removed</dd>
<dt><span class="seeLabel">See Also:</span></dt>
                                                                                                                                                            
                                                                                                                                                            <dd>
                                                                                                                                                              <a href="../../java/awt/KeyboardFocusManager.html#addVetoableChangeListener-java.beans.VetoableChangeListener-"><code>addVetoableChangeListener(java.beans.VetoableChangeListener)</code></a>, 
<a href="../../java/awt/KeyboardFocusManager.html#getVetoableChangeListeners--"><code>getVetoableChangeListeners()</code></a>, 
<a href="../../java/awt/KeyboardFocusManager.html#removeVetoableChangeListener-java.beans.VetoableChangeListener-"><code>removeVetoableChangeListener(java.beans.VetoableChangeListener)</code></a>                                                                                                                                                            </dd>
                                                                                                                                                          </dl></li> </ul>
<a name="getVetoableChangeListeners-java.lang.String-">
<!--   -->
</a>
                                                                                                                                                          
                                                                                                                                                          <ul class="blockList">
                                                                                                                                                            <li class="blockList">
                                                                                                                                                              
<h4>getVetoableChangeListeners</h4>
<pre>public&nbsp;<a href="../../java/beans/VetoableChangeListener.html" title="interface in java.beans">VetoableChangeListener</a>[]&nbsp;getVetoableChangeListeners(<a href="../../java/lang/String.html" title="class in java.lang">String</a>&nbsp;propertyName)</pre>
<div class="block">
                                                                                                                                                                Returns an array of all the <code>VetoableChangeListener</code>s associated with the named property.
                                                                                                                                                              </div>
                                                                                                                                                              <dl>
                                                                                                                                                                
<dt><span class="returnLabel">Returns:</span></dt>
                                                                                                                                                                
                                                                                                                                                                <dd>
                                                                                                                                                                  all of the <code>VetoableChangeListener</code>s associated with the named property or an empty array if no such listeners have been added.
                                                                                                                                                                </dd>
<dt><span class="simpleTagLabel">Since:</span></dt>
<dd>1.4</dd>
<dt><span class="seeLabel">See Also:</span></dt>
                                                                                                                                                                
                                                                                                                                                                <dd>
                                                                                                                                                                  <a href="../../java/awt/KeyboardFocusManager.html#addVetoableChangeListener-java.lang.String-java.beans.VetoableChangeListener-"><code>addVetoableChangeListener(java.lang.String,java.beans.VetoableChangeListener)</code></a>, 
<a href="../../java/awt/KeyboardFocusManager.html#removeVetoableChangeListener-java.lang.String-java.beans.VetoableChangeListener-"><code>removeVetoableChangeListener(java.lang.String,java.beans.VetoableChangeListener)</code></a>, 
<a href="../../java/awt/KeyboardFocusManager.html#getVetoableChangeListeners--"><code>getVetoableChangeListeners()</code></a>                                                                                                                                                                </dd>
                                                                                                                                                              </dl>
                                                                                                                                                            </li>
                                                                                                                                                          </ul>
<a name="fireVetoableChange-java.lang.String-java.lang.Object-java.lang.Object-">
<!--   -->
</a>
                                                                                                                                                          
                                                                                                                                                          <ul class="blockList">
                                                                                                                                                            <li class="blockList">
                                                                                                                                                              
<h4>fireVetoableChange</h4>
<pre>protected&nbsp;void&nbsp;fireVetoableChange(<a href="../../java/lang/String.html" title="class in java.lang">String</a>&nbsp;propertyName,
                                  <a href="../../java/lang/Object.html" title="class in java.lang">Object</a>&nbsp;oldValue,
                                  <a href="../../java/lang/Object.html" title="class in java.lang">Object</a>&nbsp;newValue)
                           throws <a href="../../java/beans/PropertyVetoException.html" title="class in java.beans">PropertyVetoException</a></pre>
                                                                                                                                                              <div class="block">
                                                                                                                                                                Fires a PropertyChangeEvent in response to a change in a vetoable property. The event will be delivered to all registered VetoableChangeListeners. If a VetoableChangeListener throws a PropertyVetoException, a new event is fired reverting all VetoableChangeListeners to the old value and the exception is then rethrown. No event will be delivered if oldValue and newValue are the same.
                                                                                                                                                              </div>
                                                                                                                                                              <dl>
                                                                                                                                                                
<dt><span class="paramLabel">Parameters:</span></dt>
<dd><code>propertyName</code> - the name of the property that has changed</dd>
<dd><code>oldValue</code> - the property's previous value</dd>
<dd><code>newValue</code> - the property's new value</dd>
<dt><span class="throwsLabel">Throws:</span></dt>
                                                                                                                                                                
                                                                                                                                                                <dd>
                                                                                                                                                                  <code>&lt;a href="../../java/beans/PropertyVetoException.html" title="class in java.beans">PropertyVetoException&lt;/a></code> - if a <code>VetoableChangeListener</code> threw <code>PropertyVetoException</code>
                                                                                                                                                                </dd>
                                                                                                                                                              </dl>
                                                                                                                                                            </li>
                                                                                                                                                          </ul>
<a name="addKeyEventDispatcher-java.awt.KeyEventDispatcher-">
<!--   -->
</a>
                                                                                                                                                          
                                                                                                                                                          <ul class="blockList">
                                                                                                                                                            <li class="blockList">
                                                                                                                                                              
<h4>addKeyEventDispatcher</h4>
<pre>public&nbsp;void&nbsp;addKeyEventDispatcher(<a href="../../java/awt/KeyEventDispatcher.html" title="interface in java.awt">KeyEventDispatcher</a>&nbsp;dispatcher)</pre>
<div class="block">
                                                                                                                                                                Adds a KeyEventDispatcher to this KeyboardFocusManager's dispatcher chain. This KeyboardFocusManager will request that each KeyEventDispatcher dispatch KeyEvents generated by the user before finally dispatching the KeyEvent itself. KeyEventDispatchers will be notified in the order in which they were added. Notifications will halt as soon as one KeyEventDispatcher returns <code>true</code> from its <code>dispatchKeyEvent</code> method. There is no limit to the total number of KeyEventDispatchers which can be added, nor to the number of times which a particular KeyEventDispatcher instance can be added. 
                                                                                                                                                                
                                                                                                                                                                <p>
                                                                                                                                                                  If a null dispatcher is specified, no action is taken and no exception is thrown. 
                                                                                                                                                                  
                                                                                                                                                                  <p>
                                                                                                                                                                    In a multithreaded application, <a href="../../java/awt/KeyEventDispatcher.html" title="interface in java.awt"><code>KeyEventDispatcher</code></a> behaves the same as other AWT listeners. See <a href="doc-files/AWTThreadIssues.html#ListenersThreads"
 >AWT Threading Issues</a> for more details.</div> 
                                                                                                                                                                    
                                                                                                                                                                    <dl>
                                                                                                                                                                      
<dt><span class="paramLabel">Parameters:</span></dt>
<dd><code>dispatcher</code> - the KeyEventDispatcher to add to the dispatcher chain</dd>
<dt><span class="seeLabel">See Also:</span></dt>
<dd><a href="../../java/awt/KeyboardFocusManager.html#removeKeyEventDispatcher-java.awt.KeyEventDispatcher-"><code>removeKeyEventDispatcher(java.awt.KeyEventDispatcher)</code></a></dd>
                                                                                                                                                                    </dl></li> </ul>
<a name="removeKeyEventDispatcher-java.awt.KeyEventDispatcher-">
<!--   -->
</a>
                                                                                                                                                                    
                                                                                                                                                                    <ul class="blockList">
                                                                                                                                                                      <li class="blockList">
                                                                                                                                                                        
<h4>removeKeyEventDispatcher</h4>
<pre>public&nbsp;void&nbsp;removeKeyEventDispatcher(<a href="../../java/awt/KeyEventDispatcher.html" title="interface in java.awt">KeyEventDispatcher</a>&nbsp;dispatcher)</pre>
<div class="block">
                                                                                                                                                                          Removes a KeyEventDispatcher which was previously added to this KeyboardFocusManager's dispatcher chain. This KeyboardFocusManager cannot itself be removed, unless it was explicitly re-registered via a call to <code>addKeyEventDispatcher</code>. 
                                                                                                                                                                          
                                                                                                                                                                          <p>
                                                                                                                                                                            If a null dispatcher is specified, if the specified dispatcher is not in the dispatcher chain, or if this KeyboardFocusManager is specified without having been explicitly re-registered, no action is taken and no exception is thrown. 
                                                                                                                                                                            
                                                                                                                                                                            <p>
                                                                                                                                                                              In a multithreaded application, <a href="../../java/awt/KeyEventDispatcher.html" title="interface in java.awt"><code>KeyEventDispatcher</code></a> behaves the same as other AWT listeners. See <a href="doc-files/AWTThreadIssues.html#ListenersThreads"
 >AWT Threading Issues</a> for more details.</div> 
                                                                                                                                                                              
                                                                                                                                                                              <dl>
                                                                                                                                                                                
<dt><span class="paramLabel">Parameters:</span></dt>
                                                                                                                                                                                
                                                                                                                                                                                <dd>
                                                                                                                                                                                  <code>dispatcher</code> - the KeyEventDispatcher to remove from the dispatcher chain
                                                                                                                                                                                </dd>
<dt><span class="seeLabel">See Also:</span></dt>
<dd><a href="../../java/awt/KeyboardFocusManager.html#addKeyEventDispatcher-java.awt.KeyEventDispatcher-"><code>addKeyEventDispatcher(java.awt.KeyEventDispatcher)</code></a></dd>
                                                                                                                                                                              </dl></li> </ul>
<a name="getKeyEventDispatchers--">
<!--   -->
</a>
                                                                                                                                                                              
                                                                                                                                                                              <ul class="blockList">
                                                                                                                                                                                <li class="blockList">
                                                                                                                                                                                  
<h4>getKeyEventDispatchers</h4>
<pre>protected&nbsp;<a href="../../java/util/List.html" title="interface in java.util">List</a>&lt;<a href="../../java/awt/KeyEventDispatcher.html" title="interface in java.awt">KeyEventDispatcher</a>&gt;&nbsp;getKeyEventDispatchers()</pre>
<div class="block">
                                                                                                                                                                                    Returns this KeyboardFocusManager's KeyEventDispatcher chain as a List. The List will not include this KeyboardFocusManager unless it was explicitly re-registered via a call to <code>addKeyEventDispatcher</code>. If no other KeyEventDispatchers are registered, implementations are free to return null or a List of length 0. Client code should not assume one behavior over another, nor should it assume that the behavior, once established, will not change.
                                                                                                                                                                                  </div>
                                                                                                                                                                                  <dl>
                                                                                                                                                                                    
<dt><span class="returnLabel">Returns:</span></dt>
<dd>a possibly null or empty List of KeyEventDispatchers</dd>
<dt><span class="seeLabel">See Also:</span></dt>
                                                                                                                                                                                    
                                                                                                                                                                                    <dd>
                                                                                                                                                                                      <a href="../../java/awt/KeyboardFocusManager.html#addKeyEventDispatcher-java.awt.KeyEventDispatcher-"><code>addKeyEventDispatcher(java.awt.KeyEventDispatcher)</code></a>, 
<a href="../../java/awt/KeyboardFocusManager.html#removeKeyEventDispatcher-java.awt.KeyEventDispatcher-"><code>removeKeyEventDispatcher(java.awt.KeyEventDispatcher)</code></a>                                                                                                                                                                                    </dd>
                                                                                                                                                                                  </dl>
                                                                                                                                                                                </li>
                                                                                                                                                                              </ul>
<a name="addKeyEventPostProcessor-java.awt.KeyEventPostProcessor-">
<!--   -->
</a>
                                                                                                                                                                              
                                                                                                                                                                              <ul class="blockList">
                                                                                                                                                                                <li class="blockList">
                                                                                                                                                                                  
<h4>addKeyEventPostProcessor</h4>
<pre>public&nbsp;void&nbsp;addKeyEventPostProcessor(<a href="../../java/awt/KeyEventPostProcessor.html" title="interface in java.awt">KeyEventPostProcessor</a>&nbsp;processor)</pre>
<div class="block">
                                                                                                                                                                                    Adds a KeyEventPostProcessor to this KeyboardFocusManager's post- processor chain. After a KeyEvent has been dispatched to and handled by its target, KeyboardFocusManager will request that each KeyEventPostProcessor perform any necessary post-processing as part of the KeyEvent's final resolution. KeyEventPostProcessors will be notified in the order in which they were added; the current KeyboardFocusManager will be notified last. Notifications will halt as soon as one KeyEventPostProcessor returns <code>true</code> from its <code>postProcessKeyEvent</code> method. There is no limit to the the total number of KeyEventPostProcessors that can be added, nor to the number of times that a particular KeyEventPostProcessor instance can be added. 
                                                                                                                                                                                    
                                                                                                                                                                                    <p>
                                                                                                                                                                                      If a null post-processor is specified, no action is taken and no exception is thrown. 
                                                                                                                                                                                      
                                                                                                                                                                                      <p>
                                                                                                                                                                                        In a multithreaded application, <a href="../../java/awt/KeyEventPostProcessor.html" title="interface in java.awt"><code>KeyEventPostProcessor</code></a> behaves the same as other AWT listeners. See <a href="doc-files/AWTThreadIssues.html#ListenersThreads"
 >AWT Threading Issues</a> for more details.</div> 
                                                                                                                                                                                        
                                                                                                                                                                                        <dl>
                                                                                                                                                                                          
<dt><span class="paramLabel">Parameters:</span></dt>
                                                                                                                                                                                          
                                                                                                                                                                                          <dd>
                                                                                                                                                                                            <code>processor</code> - the KeyEventPostProcessor to add to the post-processor chain
                                                                                                                                                                                          </dd>
<dt><span class="seeLabel">See Also:</span></dt>
<dd><a href="../../java/awt/KeyboardFocusManager.html#removeKeyEventPostProcessor-java.awt.KeyEventPostProcessor-"><code>removeKeyEventPostProcessor(java.awt.KeyEventPostProcessor)</code></a></dd>
                                                                                                                                                                                        </dl></li> </ul>
<a name="removeKeyEventPostProcessor-java.awt.KeyEventPostProcessor-">
<!--   -->
</a>
                                                                                                                                                                                        
                                                                                                                                                                                        <ul class="blockList">
                                                                                                                                                                                          <li class="blockList">
                                                                                                                                                                                            
<h4>removeKeyEventPostProcessor</h4>
<pre>public&nbsp;void&nbsp;removeKeyEventPostProcessor(<a href="../../java/awt/KeyEventPostProcessor.html" title="interface in java.awt">KeyEventPostProcessor</a>&nbsp;processor)</pre>
<div class="block">
                                                                                                                                                                                              Removes a previously added KeyEventPostProcessor from this KeyboardFocusManager's post-processor chain. This KeyboardFocusManager cannot itself be entirely removed from the chain. Only additional references added via <code>addKeyEventPostProcessor</code> can be removed. 
                                                                                                                                                                                              
                                                                                                                                                                                              <p>
                                                                                                                                                                                                If a null post-processor is specified, if the specified post-processor is not in the post-processor chain, or if this KeyboardFocusManager is specified without having been explicitly added, no action is taken and no exception is thrown. 
                                                                                                                                                                                                
                                                                                                                                                                                                <p>
                                                                                                                                                                                                  In a multithreaded application, <a href="../../java/awt/KeyEventPostProcessor.html" title="interface in java.awt"><code>KeyEventPostProcessor</code></a> behaves the same as other AWT listeners. See <a href="doc-files/AWTThreadIssues.html#ListenersThreads"
 >AWT Threading Issues</a> for more details.</div> 
                                                                                                                                                                                                  
                                                                                                                                                                                                  <dl>
                                                                                                                                                                                                    
<dt><span class="paramLabel">Parameters:</span></dt>
                                                                                                                                                                                                    
                                                                                                                                                                                                    <dd>
                                                                                                                                                                                                      <code>processor</code> - the KeyEventPostProcessor to remove from the post- processor chain
                                                                                                                                                                                                    </dd>
<dt><span class="seeLabel">See Also:</span></dt>
<dd><a href="../../java/awt/KeyboardFocusManager.html#addKeyEventPostProcessor-java.awt.KeyEventPostProcessor-"><code>addKeyEventPostProcessor(java.awt.KeyEventPostProcessor)</code></a></dd>
                                                                                                                                                                                                  </dl></li> </ul>
<a name="getKeyEventPostProcessors--">
<!--   -->
</a>
                                                                                                                                                                                                  
                                                                                                                                                                                                  <ul class="blockList">
                                                                                                                                                                                                    <li class="blockList">
                                                                                                                                                                                                      
<h4>getKeyEventPostProcessors</h4>
<pre>protected&nbsp;<a href="../../java/util/List.html" title="interface in java.util">List</a>&lt;<a href="../../java/awt/KeyEventPostProcessor.html" title="interface in java.awt">KeyEventPostProcessor</a>&gt;&nbsp;getKeyEventPostProcessors()</pre>
<div class="block">
                                                                                                                                                                                                        Returns this KeyboardFocusManager's KeyEventPostProcessor chain as a List. The List will not include this KeyboardFocusManager unless it was explicitly added via a call to <code>addKeyEventPostProcessor</code>. If no KeyEventPostProcessors are registered, implementations are free to return null or a List of length 0. Client code should not assume one behavior over another, nor should it assume that the behavior, once established, will not change.
                                                                                                                                                                                                      </div>
                                                                                                                                                                                                      <dl>
                                                                                                                                                                                                        
<dt><span class="returnLabel">Returns:</span></dt>
<dd>a possibly null or empty List of KeyEventPostProcessors</dd>
<dt><span class="seeLabel">See Also:</span></dt>
                                                                                                                                                                                                        
                                                                                                                                                                                                        <dd>
                                                                                                                                                                                                          <a href="../../java/awt/KeyboardFocusManager.html#addKeyEventPostProcessor-java.awt.KeyEventPostProcessor-"><code>addKeyEventPostProcessor(java.awt.KeyEventPostProcessor)</code></a>, 
<a href="../../java/awt/KeyboardFocusManager.html#removeKeyEventPostProcessor-java.awt.KeyEventPostProcessor-"><code>removeKeyEventPostProcessor(java.awt.KeyEventPostProcessor)</code></a>                                                                                                                                                                                                        </dd>
                                                                                                                                                                                                      </dl>
                                                                                                                                                                                                    </li>
                                                                                                                                                                                                  </ul>
<a name="dispatchEvent-java.awt.AWTEvent-">
<!--   -->
</a>
                                                                                                                                                                                                  
                                                                                                                                                                                                  <ul class="blockList">
                                                                                                                                                                                                    <li class="blockList">
                                                                                                                                                                                                      
<h4>dispatchEvent</h4>
<pre>public abstract&nbsp;boolean&nbsp;dispatchEvent(<a href="../../java/awt/AWTEvent.html" title="class in java.awt">AWTEvent</a>&nbsp;e)</pre>
<div class="block">
                                                                                                                                                                                                        This method is called by the AWT event dispatcher requesting that the current KeyboardFocusManager dispatch the specified event on its behalf. It is expected that all KeyboardFocusManagers will dispatch all FocusEvents, all WindowEvents related to focus, and all KeyEvents. These events should be dispatched based on the KeyboardFocusManager's notion of the focus owner and the focused and active Windows, sometimes overriding the source of the specified AWTEvent. Dispatching must be done using <code>redispatchEvent</code> to prevent the AWT event dispatcher from recursively requesting that the KeyboardFocusManager dispatch the event again. If this method returns <code>false</code>, then the AWT event dispatcher will attempt to dispatch the event itself.
                                                                                                                                                                                                      </div>
                                                                                                                                                                                                      <dl>
                                                                                                                                                                                                        
<dt><span class="paramLabel">Parameters:</span></dt>
<dd><code>e</code> - the AWTEvent to be dispatched</dd>
<dt><span class="returnLabel">Returns:</span></dt>
                                                                                                                                                                                                        
                                                                                                                                                                                                        <dd>
                                                                                                                                                                                                          <code>true</code> if this method dispatched the event; <code>false</code> otherwise
                                                                                                                                                                                                        </dd>
<dt><span class="seeLabel">See Also:</span></dt>
                                                                                                                                                                                                        
                                                                                                                                                                                                        <dd>
                                                                                                                                                                                                          <a href="../../java/awt/KeyboardFocusManager.html#redispatchEvent-java.awt.Component-java.awt.AWTEvent-"><code>redispatchEvent(java.awt.Component, java.awt.AWTEvent)</code></a>, 
<a href="../../java/awt/KeyboardFocusManager.html#dispatchKeyEvent-java.awt.event.KeyEvent-"><code>dispatchKeyEvent(java.awt.event.KeyEvent)</code></a>                                                                                                                                                                                                        </dd>
                                                                                                                                                                                                      </dl>
                                                                                                                                                                                                    </li>
                                                                                                                                                                                                  </ul>
<a name="redispatchEvent-java.awt.Component-java.awt.AWTEvent-">
<!--   -->
</a>
                                                                                                                                                                                                  
                                                                                                                                                                                                  <ul class="blockList">
                                                                                                                                                                                                    <li class="blockList">
                                                                                                                                                                                                      
<h4>redispatchEvent</h4>
<pre>public final&nbsp;void&nbsp;redispatchEvent(<a href="../../java/awt/Component.html" title="class in java.awt">Component</a>&nbsp;target,
                                  <a href="../../java/awt/AWTEvent.html" title="class in java.awt">AWTEvent</a>&nbsp;e)</pre>
                                                                                                                                                                                                      <div class="block">
                                                                                                                                                                                                        Redispatches an AWTEvent in such a way that the AWT event dispatcher will not recursively request that the KeyboardFocusManager, or any installed KeyEventDispatchers, dispatch the event again. Client implementations of <code>dispatchEvent</code> and client-defined KeyEventDispatchers must call <code>redispatchEvent(target, e)</code> instead of <code>target.dispatchEvent(e)</code> to dispatch an event. 
                                                                                                                                                                                                        
                                                                                                                                                                                                        <p>
                                                                                                                                                                                                          This method is intended to be used only by KeyboardFocusManagers and KeyEventDispatchers. It is not for general client use.</div> 
                                                                                                                                                                                                          
                                                                                                                                                                                                          <dl>
                                                                                                                                                                                                            
<dt><span class="paramLabel">Parameters:</span></dt>
<dd><code>target</code> - the Component to which the event should be dispatched</dd>
<dd><code>e</code> - the event to dispatch</dd>
<dt><span class="seeLabel">See Also:</span></dt>
                                                                                                                                                                                                            
                                                                                                                                                                                                            <dd>
                                                                                                                                                                                                              <a href="../../java/awt/KeyboardFocusManager.html#dispatchEvent-java.awt.AWTEvent-"><code>dispatchEvent(java.awt.AWTEvent)</code></a>, 
<a href="../../java/awt/KeyEventDispatcher.html" title="interface in java.awt"><code>KeyEventDispatcher</code></a>                                                                                                                                                                                                            </dd>
                                                                                                                                                                                                          </dl></li> </ul>
<a name="dispatchKeyEvent-java.awt.event.KeyEvent-">
<!--   -->
</a>
                                                                                                                                                                                                          
                                                                                                                                                                                                          <ul class="blockList">
                                                                                                                                                                                                            <li class="blockList">
                                                                                                                                                                                                              
<h4>dispatchKeyEvent</h4>
<pre>public abstract&nbsp;boolean&nbsp;dispatchKeyEvent(<a href="../../java/awt/event/KeyEvent.html" title="class in java.awt.event">KeyEvent</a>&nbsp;e)</pre>
<div class="block">
                                                                                                                                                                                                                Typically this method will be called by <code>dispatchEvent</code> if no other KeyEventDispatcher in the dispatcher chain dispatched the KeyEvent, or if no other KeyEventDispatchers are registered. If an implementation of this method returns <code>false</code>, <code>dispatchEvent</code> may try to dispatch the KeyEvent itself, or may simply return <code>false</code>. If <code>true</code> is returned, <code>dispatchEvent</code> should return <code>true</code> as well.
                                                                                                                                                                                                              </div>
                                                                                                                                                                                                              <dl>
                                                                                                                                                                                                                
<dt><span class="overrideSpecifyLabel">Specified by:</span></dt>
<dd><code><a href="../../java/awt/KeyEventDispatcher.html#dispatchKeyEvent-java.awt.event.KeyEvent-">dispatchKeyEvent</a></code>&nbsp;in interface&nbsp;<code><a href="../../java/awt/KeyEventDispatcher.html" title="interface in java.awt">KeyEventDispatcher</a></code></dd>
<dt><span class="paramLabel">Parameters:</span></dt>
                                                                                                                                                                                                                
                                                                                                                                                                                                                <dd>
                                                                                                                                                                                                                  <code>e</code> - the KeyEvent which the current KeyboardFocusManager has requested that this KeyEventDispatcher dispatch
                                                                                                                                                                                                                </dd>
<dt><span class="returnLabel">Returns:</span></dt>
                                                                                                                                                                                                                
                                                                                                                                                                                                                <dd>
                                                                                                                                                                                                                  <code>true</code> if the KeyEvent was dispatched; <code>false</code> otherwise
                                                                                                                                                                                                                </dd>
<dt><span class="seeLabel">See Also:</span></dt>
<dd><a href="../../java/awt/KeyboardFocusManager.html#dispatchEvent-java.awt.AWTEvent-"><code>dispatchEvent(java.awt.AWTEvent)</code></a></dd>
                                                                                                                                                                                                              </dl>
                                                                                                                                                                                                            </li>
                                                                                                                                                                                                          </ul>
<a name="postProcessKeyEvent-java.awt.event.KeyEvent-">
<!--   -->
</a>
                                                                                                                                                                                                          
                                                                                                                                                                                                          <ul class="blockList">
                                                                                                                                                                                                            <li class="blockList">
                                                                                                                                                                                                              
<h4>postProcessKeyEvent</h4>
<pre>public abstract&nbsp;boolean&nbsp;postProcessKeyEvent(<a href="../../java/awt/event/KeyEvent.html" title="class in java.awt.event">KeyEvent</a>&nbsp;e)</pre>
<div class="block">
                                                                                                                                                                                                                This method will be called by <code>dispatchKeyEvent</code>. By default, this method will handle any unconsumed KeyEvents that map to an AWT <code>MenuShortcut</code> by consuming the event and activating the shortcut.
                                                                                                                                                                                                              </div>
                                                                                                                                                                                                              <dl>
                                                                                                                                                                                                                
<dt><span class="overrideSpecifyLabel">Specified by:</span></dt>
<dd><code><a href="../../java/awt/KeyEventPostProcessor.html#postProcessKeyEvent-java.awt.event.KeyEvent-">postProcessKeyEvent</a></code>&nbsp;in interface&nbsp;<code><a href="../../java/awt/KeyEventPostProcessor.html" title="interface in java.awt">KeyEventPostProcessor</a></code></dd>
<dt><span class="paramLabel">Parameters:</span></dt>
<dd><code>e</code> - the KeyEvent to post-process</dd>
<dt><span class="returnLabel">Returns:</span></dt>
                                                                                                                                                                                                                
                                                                                                                                                                                                                <dd>
                                                                                                                                                                                                                  <code>true</code> to indicate that no other KeyEventPostProcessor will be notified of the KeyEvent.
                                                                                                                                                                                                                </dd>
<dt><span class="seeLabel">See Also:</span></dt>
                                                                                                                                                                                                                
                                                                                                                                                                                                                <dd>
                                                                                                                                                                                                                  <a href="../../java/awt/KeyboardFocusManager.html#dispatchKeyEvent-java.awt.event.KeyEvent-"><code>dispatchKeyEvent(java.awt.event.KeyEvent)</code></a>, 
<a href="../../java/awt/MenuShortcut.html" title="class in java.awt"><code>MenuShortcut</code></a>                                                                                                                                                                                                                </dd>
                                                                                                                                                                                                              </dl>
                                                                                                                                                                                                            </li>
                                                                                                                                                                                                          </ul>
<a name="processKeyEvent-java.awt.Component-java.awt.event.KeyEvent-">
<!--   -->
</a>
                                                                                                                                                                                                          
                                                                                                                                                                                                          <ul class="blockList">
                                                                                                                                                                                                            <li class="blockList">
                                                                                                                                                                                                              
<h4>processKeyEvent</h4>
<pre>public abstract&nbsp;void&nbsp;processKeyEvent(<a href="../../java/awt/Component.html" title="class in java.awt">Component</a>&nbsp;focusedComponent,
                                     <a href="../../java/awt/event/KeyEvent.html" title="class in java.awt.event">KeyEvent</a>&nbsp;e)</pre>
                                                                                                                                                                                                              <div class="block">
                                                                                                                                                                                                                This method initiates a focus traversal operation if and only if the KeyEvent represents a focus traversal key for the specified focusedComponent. It is expected that focusedComponent is the current focus owner, although this need not be the case. If it is not, focus traversal will nevertheless proceed as if focusedComponent were the current focus owner.
                                                                                                                                                                                                              </div>
                                                                                                                                                                                                              <dl>
                                                                                                                                                                                                                
<dt><span class="paramLabel">Parameters:</span></dt>
                                                                                                                                                                                                                
                                                                                                                                                                                                                <dd>
                                                                                                                                                                                                                  <code>focusedComponent</code> - the Component that will be the basis for a focus traversal operation if the specified event represents a focus traversal key for the Component
                                                                                                                                                                                                                </dd>
<dd><code>e</code> - the event that may represent a focus traversal key</dd>
                                                                                                                                                                                                              </dl>
                                                                                                                                                                                                            </li>
                                                                                                                                                                                                          </ul>
<a name="enqueueKeyEvents-long-java.awt.Component-">
<!--   -->
</a>
                                                                                                                                                                                                          
                                                                                                                                                                                                          <ul class="blockList">
                                                                                                                                                                                                            <li class="blockList">
                                                                                                                                                                                                              
<h4>enqueueKeyEvents</h4>
<pre>protected abstract&nbsp;void&nbsp;enqueueKeyEvents(long&nbsp;after,
                                         <a href="../../java/awt/Component.html" title="class in java.awt">Component</a>&nbsp;untilFocused)</pre>
                                                                                                                                                                                                              <div class="block">
                                                                                                                                                                                                                Called by the AWT to notify the KeyboardFocusManager that it should delay dispatching of KeyEvents until the specified Component becomes the focus owner. If client code requests a focus change, and the AWT determines that this request might be granted by the native windowing system, then the AWT will call this method. It is the responsibility of the KeyboardFocusManager to delay dispatching of KeyEvents with timestamps later than the specified time stamp until the specified Component receives a FOCUS_GAINED event, or the AWT cancels the delay request by invoking <code>dequeueKeyEvents</code> or <code>discardKeyEvents</code>.
                                                                                                                                                                                                              </div>
                                                                                                                                                                                                              <dl>
                                                                                                                                                                                                                
<dt><span class="paramLabel">Parameters:</span></dt>
                                                                                                                                                                                                                
                                                                                                                                                                                                                <dd>
                                                                                                                                                                                                                  <code>after</code> - timestamp of current event, or the current, system time if the current event has no timestamp, or the AWT cannot determine which event is currently being handled
                                                                                                                                                                                                                </dd>
                                                                                                                                                                                                                
                                                                                                                                                                                                                <dd>
                                                                                                                                                                                                                  <code>untilFocused</code> - Component which should receive a FOCUS_GAINED event before any pending KeyEvents
                                                                                                                                                                                                                </dd>
<dt><span class="seeLabel">See Also:</span></dt>
                                                                                                                                                                                                                
                                                                                                                                                                                                                <dd>
                                                                                                                                                                                                                  <a href="../../java/awt/KeyboardFocusManager.html#dequeueKeyEvents-long-java.awt.Component-"><code>dequeueKeyEvents(long, java.awt.Component)</code></a>, 
<a href="../../java/awt/KeyboardFocusManager.html#discardKeyEvents-java.awt.Component-"><code>discardKeyEvents(java.awt.Component)</code></a>                                                                                                                                                                                                                </dd>
                                                                                                                                                                                                              </dl>
                                                                                                                                                                                                            </li>
                                                                                                                                                                                                          </ul>
<a name="dequeueKeyEvents-long-java.awt.Component-">
<!--   -->
</a>
                                                                                                                                                                                                          
                                                                                                                                                                                                          <ul class="blockList">
                                                                                                                                                                                                            <li class="blockList">
                                                                                                                                                                                                              
<h4>dequeueKeyEvents</h4>
<pre>protected abstract&nbsp;void&nbsp;dequeueKeyEvents(long&nbsp;after,
                                         <a href="../../java/awt/Component.html" title="class in java.awt">Component</a>&nbsp;untilFocused)</pre>
                                                                                                                                                                                                              <div class="block">
                                                                                                                                                                                                                Called by the AWT to notify the KeyboardFocusManager that it should cancel delayed dispatching of KeyEvents. All KeyEvents which were enqueued because of a call to <code>enqueueKeyEvents</code> with the same timestamp and Component should be released for normal dispatching to the current focus owner. If the given timestamp is less than zero, the outstanding enqueue request for the given Component with the <b> oldest</b> timestamp (if any) should be cancelled.
                                                                                                                                                                                                              </div>
                                                                                                                                                                                                              <dl>
                                                                                                                                                                                                                
<dt><span class="paramLabel">Parameters:</span></dt>
                                                                                                                                                                                                                
                                                                                                                                                                                                                <dd>
                                                                                                                                                                                                                  <code>after</code> - the timestamp specified in the call to <code>enqueueKeyEvents</code>, or any value &lt; 0
                                                                                                                                                                                                                </dd>
                                                                                                                                                                                                                
                                                                                                                                                                                                                <dd>
                                                                                                                                                                                                                  <code>untilFocused</code> - the Component specified in the call to <code>enqueueKeyEvents</code>
                                                                                                                                                                                                                </dd>
<dt><span class="seeLabel">See Also:</span></dt>
                                                                                                                                                                                                                
                                                                                                                                                                                                                <dd>
                                                                                                                                                                                                                  <a href="../../java/awt/KeyboardFocusManager.html#enqueueKeyEvents-long-java.awt.Component-"><code>enqueueKeyEvents(long, java.awt.Component)</code></a>, 
<a href="../../java/awt/KeyboardFocusManager.html#discardKeyEvents-java.awt.Component-"><code>discardKeyEvents(java.awt.Component)</code></a>                                                                                                                                                                                                                </dd>
                                                                                                                                                                                                              </dl>
                                                                                                                                                                                                            </li>
                                                                                                                                                                                                          </ul>
<a name="discardKeyEvents-java.awt.Component-">
<!--   -->
</a>
                                                                                                                                                                                                          
                                                                                                                                                                                                          <ul class="blockList">
                                                                                                                                                                                                            <li class="blockList">
                                                                                                                                                                                                              
<h4>discardKeyEvents</h4>
<pre>protected abstract&nbsp;void&nbsp;discardKeyEvents(<a href="../../java/awt/Component.html" title="class in java.awt">Component</a>&nbsp;comp)</pre>
<div class="block">
                                                                                                                                                                                                                Called by the AWT to notify the KeyboardFocusManager that it should cancel delayed dispatching of KeyEvents. All KeyEvents which were enqueued because of one or more calls to <code>enqueueKeyEvents</code> with the same Component should be discarded.
                                                                                                                                                                                                              </div>
                                                                                                                                                                                                              <dl>
                                                                                                                                                                                                                
<dt><span class="paramLabel">Parameters:</span></dt>
                                                                                                                                                                                                                
                                                                                                                                                                                                                <dd>
                                                                                                                                                                                                                  <code>comp</code> - the Component specified in one or more calls to <code>enqueueKeyEvents</code>
                                                                                                                                                                                                                </dd>
<dt><span class="seeLabel">See Also:</span></dt>
                                                                                                                                                                                                                
                                                                                                                                                                                                                <dd>
                                                                                                                                                                                                                  <a href="../../java/awt/KeyboardFocusManager.html#enqueueKeyEvents-long-java.awt.Component-"><code>enqueueKeyEvents(long, java.awt.Component)</code></a>, 
<a href="../../java/awt/KeyboardFocusManager.html#dequeueKeyEvents-long-java.awt.Component-"><code>dequeueKeyEvents(long, java.awt.Component)</code></a>                                                                                                                                                                                                                </dd>
                                                                                                                                                                                                              </dl>
                                                                                                                                                                                                            </li>
                                                                                                                                                                                                          </ul>
<a name="focusNextComponent-java.awt.Component-">
<!--   -->
</a>
                                                                                                                                                                                                          
                                                                                                                                                                                                          <ul class="blockList">
                                                                                                                                                                                                            <li class="blockList">
                                                                                                                                                                                                              
<h4>focusNextComponent</h4>
<pre>public abstract&nbsp;void&nbsp;focusNextComponent(<a href="../../java/awt/Component.html" title="class in java.awt">Component</a>&nbsp;aComponent)</pre>
<div class="block">
                                                                                                                                                                                                                Focuses the Component after aComponent, typically based on a FocusTraversalPolicy.
                                                                                                                                                                                                              </div>
                                                                                                                                                                                                              <dl>
                                                                                                                                                                                                                
<dt><span class="paramLabel">Parameters:</span></dt>
                                                                                                                                                                                                                
                                                                                                                                                                                                                <dd>
                                                                                                                                                                                                                  <code>aComponent</code> - the Component that is the basis for the focus traversal operation
                                                                                                                                                                                                                </dd>
<dt><span class="seeLabel">See Also:</span></dt>
<dd><a href="../../java/awt/FocusTraversalPolicy.html" title="class in java.awt"><code>FocusTraversalPolicy</code></a></dd>
                                                                                                                                                                                                              </dl>
                                                                                                                                                                                                            </li>
                                                                                                                                                                                                          </ul>
<a name="focusPreviousComponent-java.awt.Component-">
<!--   -->
</a>
                                                                                                                                                                                                          
                                                                                                                                                                                                          <ul class="blockList">
                                                                                                                                                                                                            <li class="blockList">
                                                                                                                                                                                                              
<h4>focusPreviousComponent</h4>
<pre>public abstract&nbsp;void&nbsp;focusPreviousComponent(<a href="../../java/awt/Component.html" title="class in java.awt">Component</a>&nbsp;aComponent)</pre>
<div class="block">
                                                                                                                                                                                                                Focuses the Component before aComponent, typically based on a FocusTraversalPolicy.
                                                                                                                                                                                                              </div>
                                                                                                                                                                                                              <dl>
                                                                                                                                                                                                                
<dt><span class="paramLabel">Parameters:</span></dt>
                                                                                                                                                                                                                
                                                                                                                                                                                                                <dd>
                                                                                                                                                                                                                  <code>aComponent</code> - the Component that is the basis for the focus traversal operation
                                                                                                                                                                                                                </dd>
<dt><span class="seeLabel">See Also:</span></dt>
<dd><a href="../../java/awt/FocusTraversalPolicy.html" title="class in java.awt"><code>FocusTraversalPolicy</code></a></dd>
                                                                                                                                                                                                              </dl>
                                                                                                                                                                                                            </li>
                                                                                                                                                                                                          </ul>
<a name="upFocusCycle-java.awt.Component-">
<!--   -->
</a>
                                                                                                                                                                                                          
                                                                                                                                                                                                          <ul class="blockList">
                                                                                                                                                                                                            <li class="blockList">
                                                                                                                                                                                                              
<h4>upFocusCycle</h4>
<pre>public abstract&nbsp;void&nbsp;upFocusCycle(<a href="../../java/awt/Component.html" title="class in java.awt">Component</a>&nbsp;aComponent)</pre>
<div class="block">
                                                                                                                                                                                                                Moves the focus up one focus traversal cycle. Typically, the focus owner is set to aComponent's focus cycle root, and the current focus cycle root is set to the new focus owner's focus cycle root. If, however, aComponent's focus cycle root is a Window, then typically the focus owner is set to the Window's default Component to focus, and the current focus cycle root is unchanged.
                                                                                                                                                                                                              </div>
                                                                                                                                                                                                              <dl>
                                                                                                                                                                                                                
<dt><span class="paramLabel">Parameters:</span></dt>
                                                                                                                                                                                                                
                                                                                                                                                                                                                <dd>
                                                                                                                                                                                                                  <code>aComponent</code> - the Component that is the basis for the focus traversal operation
                                                                                                                                                                                                                </dd>
                                                                                                                                                                                                              </dl>
                                                                                                                                                                                                            </li>
                                                                                                                                                                                                          </ul>
<a name="downFocusCycle-java.awt.Container-">
<!--   -->
</a>
                                                                                                                                                                                                          
                                                                                                                                                                                                          <ul class="blockList">
                                                                                                                                                                                                            <li class="blockList">
                                                                                                                                                                                                              
<h4>downFocusCycle</h4>
<pre>public abstract&nbsp;void&nbsp;downFocusCycle(<a href="../../java/awt/Container.html" title="class in java.awt">Container</a>&nbsp;aContainer)</pre>
<div class="block">
                                                                                                                                                                                                                Moves the focus down one focus traversal cycle. Typically, if aContainer is a focus cycle root, then the focus owner is set to aContainer's default Component to focus, and the current focus cycle root is set to aContainer. If aContainer is not a focus cycle root, then no focus traversal operation occurs.
                                                                                                                                                                                                              </div>
                                                                                                                                                                                                              <dl>
                                                                                                                                                                                                                
<dt><span class="paramLabel">Parameters:</span></dt>
                                                                                                                                                                                                                
                                                                                                                                                                                                                <dd>
                                                                                                                                                                                                                  <code>aContainer</code> - the Container that is the basis for the focus traversal operation
                                                                                                                                                                                                                </dd>
                                                                                                                                                                                                              </dl>
                                                                                                                                                                                                            </li>
                                                                                                                                                                                                          </ul>
<a name="focusNextComponent--">
<!--   -->
</a>
                                                                                                                                                                                                          
                                                                                                                                                                                                          <ul class="blockList">
                                                                                                                                                                                                            <li class="blockList">
                                                                                                                                                                                                              
<h4>focusNextComponent</h4>
<pre>public final&nbsp;void&nbsp;focusNextComponent()</pre>
<div class="block">Focuses the Component after the current focus owner.</div>
                                                                                                                                                                                                            </li>
                                                                                                                                                                                                          </ul>
<a name="focusPreviousComponent--">
<!--   -->
</a>
                                                                                                                                                                                                          
                                                                                                                                                                                                          <ul class="blockList">
                                                                                                                                                                                                            <li class="blockList">
                                                                                                                                                                                                              
<h4>focusPreviousComponent</h4>
<pre>public final&nbsp;void&nbsp;focusPreviousComponent()</pre>
<div class="block">Focuses the Component before the current focus owner.</div>
                                                                                                                                                                                                            </li>
                                                                                                                                                                                                          </ul>
<a name="upFocusCycle--">
<!--   -->
</a>
                                                                                                                                                                                                          
                                                                                                                                                                                                          <ul class="blockList">
                                                                                                                                                                                                            <li class="blockList">
                                                                                                                                                                                                              
<h4>upFocusCycle</h4>
<pre>public final&nbsp;void&nbsp;upFocusCycle()</pre>
<div class="block">
                                                                                                                                                                                                                Moves the focus up one focus traversal cycle from the current focus owner. Typically, the new focus owner is set to the current focus owner's focus cycle root, and the current focus cycle root is set to the new focus owner's focus cycle root. If, however, the current focus owner's focus cycle root is a Window, then typically the focus owner is set to the focus cycle root's default Component to focus, and the current focus cycle root is unchanged.
                                                                                                                                                                                                              </div>
                                                                                                                                                                                                            </li>
                                                                                                                                                                                                          </ul>
<a name="downFocusCycle--">
<!--   -->
</a>
                                                                                                                                                                                                          
                                                                                                                                                                                                          <ul class="blockListLast">
                                                                                                                                                                                                            <li class="blockList">
                                                                                                                                                                                                              
<h4>downFocusCycle</h4>
<pre>public final&nbsp;void&nbsp;downFocusCycle()</pre>
<div class="block">
                                                                                                                                                                                                                Moves the focus down one focus traversal cycle from the current focus owner, if and only if the current focus owner is a Container that is a focus cycle root. Typically, the focus owner is set to the current focus owner's default Component to focus, and the current focus cycle root is set to the current focus owner. If the current focus owner is not a Container that is a focus cycle root, then no focus traversal operation occurs.
                                                                                                                                                                                                              </div>
                                                                                                                                                                                                            </li>
                                                                                                                                                                                                          </ul></li> </ul> </li> </ul> </div> </div> 
                                                                                                                                                                                                          
                                                                                                                                                                                                          <p>
                                                                                                                                                                                                            <!-- ========= END OF CLASS DATA ========= -->
                                                                                                                                                                                                            
                                                                                                                                                                                                            <!-- ======= START OF BOTTOM NAVBAR ====== -->
                                                                                                                                                                                                          </p>
                                                                                                                                                                                                          
                                                                                                                                                                                                          <div class="bottomNav">
                                                                                                                                                                                                            <a name="navbar.bottom"> <!--   --></a>
<div class="skipNav"><a href="#skip.navbar.bottom" title="Skip navigation links">Skip navigation links</a></div>
<a name="navbar.bottom.firstrow">
<!--   -->
</a>
                                                                                                                                                                                                            
                                                                                                                                                                                                            <ul class="navList" title="Navigation">
                                                                                                                                                                                                              
<li><a href="../../overview-summary.html">Overview</a></li>
<li><a href="package-summary.html">Package</a></li>
<li class="navBarCell1Rev">Class</li>
<li><a href="class-use/KeyboardFocusManager.html">Use</a></li>
<li><a href="package-tree.html">Tree</a></li>
<li><a href="../../deprecated-list.html">Deprecated</a></li>
<li><a href="../../index-files/index-1.html">Index</a></li>
<li><a href="../../help-doc.html">Help</a></li>
                                                                                                                                                                                                            </ul>
<div class="aboutLanguage"><strong>Java&trade;&nbsp;Platform<br>Standard&nbsp;Ed.&nbsp;8</strong></div>
                                                                                                                                                                                                          </div>
                                                                                                                                                                                                          
                                                                                                                                                                                                          <div class="subNav">
                                                                                                                                                                                                            <ul class="navList">
                                                                                                                                                                                                              
<li><a href="../../java/awt/JobAttributes.SidesType.html" title="class in java.awt"><span class="typeNameLink">Prev&nbsp;Class</span></a></li>
<li><a href="../../java/awt/KeyEventDispatcher.html" title="interface in java.awt"><span class="typeNameLink">Next&nbsp;Class</span></a></li>
                                                                                                                                                                                                            </ul>
                                                                                                                                                                                                            
                                                                                                                                                                                                            <ul class="navList">
                                                                                                                                                                                                              
<li><a href="../../index.html?java/awt/KeyboardFocusManager.html" target="_top">Frames</a></li>
<li><a href="KeyboardFocusManager.html" target="_top">No&nbsp;Frames</a></li>
                                                                                                                                                                                                            </ul>
<ul class="navList" id="allclasses_navbar_bottom">
<li><a href="../../allclasses-noframe.html">All&nbsp;Classes</a></li>
</ul>
                                                                                                                                                                                                            
                                                                                                                                                                                                            <div>
                                                                                                                                                                                                              
<script type="text/javascript"><!--
  allClassesLink = document.getElementById("allclasses_navbar_bottom");
  if(window==top) {
    allClassesLink.style.display = "block";
  }
  else {
    allClassesLink.style.display = "none";
  }
  //-->
</script>
                                                                                                                                                                                                            </div>
                                                                                                                                                                                                            
                                                                                                                                                                                                            <div>
                                                                                                                                                                                                              <ul class="subNavList">
                                                                                                                                                                                                                
<li>Summary:&nbsp;</li>
<li>Nested&nbsp;|&nbsp;</li>
<li><a href="#field.summary">Field</a>&nbsp;|&nbsp;</li>
<li><a href="#constructor.summary">Constr</a>&nbsp;|&nbsp;</li>
<li><a href="#method.summary">Method</a></li>
                                                                                                                                                                                                              </ul>
                                                                                                                                                                                                              
                                                                                                                                                                                                              <ul class="subNavList">
                                                                                                                                                                                                                
<li>Detail:&nbsp;</li>
<li><a href="#field.detail">Field</a>&nbsp;|&nbsp;</li>
<li><a href="#constructor.detail">Constr</a>&nbsp;|&nbsp;</li>
<li><a href="#method.detail">Method</a></li>
                                                                                                                                                                                                              </ul>
                                                                                                                                                                                                            </div>
<a name="skip.navbar.bottom">
<!--   -->
</a>                                                                                                                                                                                                          </div>
                                                                                                                                                                                                          
                                                                                                                                                                                                          <!-- ======== END OF BOTTOM NAVBAR ======= -->

<p class="legalCopy"><small><font size="-1"> <a href="http://bugreport.sun.com/bugreport/">Submit a bug or feature</a> <br>For further API reference and developer documentation, see <a href="https://docs.oracle.com/javase/8/docs/index.html" target="_blank">Java SE Documentation</a>. That documentation contains more detailed, developer-targeted descriptions, with conceptual overviews, definitions of terms, workarounds, and working code examples.<br> <a href="../../../legal/cpyr.html">Copyright</a> &#x00a9; 1993, 2018, Oracle and/or its affiliates.  All rights reserved. Use is subject to <a href="http://download.oracle.com/otndocs/jcp/java_se-8-mrel-spec/license.html">license terms</a>. Also see the <a target="_blank" href="http://www.oracle.com/technetwork/java/redist-137594.html">documentation redistribution policy</a>. </font></small></p>

                                                                                                                                                                                                          
                                                                                                                                                                                                          <p>
                                                                                                                                                                                                            </body> </html>
                                                                                                                                                                                                          </p>