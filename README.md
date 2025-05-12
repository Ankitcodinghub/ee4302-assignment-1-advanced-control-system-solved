# ee4302-assignment-1-advanced-control-system-solved
**TO GET THIS SOLUTION VISIT:** [EE4302 Assignment 1-Advanced Control System Solved](https://www.ankitcodinghub.com/product/ee4302-assignment-1-advanced-control-system-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;91271&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;4&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (4 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;EE4302 Assignment 1-Advanced Control System Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (4 votes)    </div>
    </div>
<div class="page" title="Page 1">
<div class="layoutArea">
<div class="column">
1.0 Objective

In this experiment, the design of a state-feedback controller is considered. The desired closed-loop response is given by specifications in the frequency domain, and a computer-aided design procedure is used to interactively achieve the specifications.

2.0 Equipment

(a). PCs in the Control &amp; Simulation Laboratory, E4A level 3, ECE Dept. (b). MATLAB software package.

3.0 Introduction (CA1 &amp; CA3)

The use of state-space ideas in control system design allows the control engineer great flexibility in shaping the dynamic response of systems. State-space techniques are powerful and also provide useful insight into the structure of the system under study. However, the calculations involved in design using state-space ideas are often very tedious, and have been one of the drawbacks to widespread use of these techniques. Further, specifications for the desired closed-loop system are often given in the frequency domain (typically bandwidth requirements), and a control engineer using state-space techniques must be able to interactively relate the choice of the state-feedback gains to resulting frequency domain plots.

In recent years, software packages to assist the control engineer have become available, and fairly comprehensive ones are now available for the personal computer environment. In the experiment, we will use the MATLAB package.

3.1 Review of State-Variables and MATLAB (CA1 &amp; CA3)

Basic familiarity with MATLAB is a pre-requisite for this experiment. (If you have difficulty with MATLAB, you should consult your instructor for introductory material on the MATLAB package.)

</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
Consider the following plant (for EE4302 Special Sem. 15/16) described in the state-space notation.

􏰀̇􏰁 = 􏰀􏰂

􏰀̇􏰂 = −3.71􏰀􏰂 − 1.20􏰀􏰁 + 􏰃 􏰄 = 􏰀􏰁

The state-variables are 􏰀􏰁(􏰅) and 􏰀􏰂(􏰅); 􏰃(􏰅) is the input to the system while 􏰄(􏰅) is the output of the system. Assume that both state variables are measurable.

Use the MATLAB function BODE to obtain plots of the frequency response from 􏰃 to 􏰀􏰁, and from 􏰃 to 􏰀􏰂.

􏰃 = −􏰆􏰁􏰀􏰁 − 􏰆􏰂􏰀􏰂

for the particular values of 􏰆􏰁 = 0.1 and 􏰆􏰂 = 0.1. Use the function FEEDBACK to obtain the closed-

loop system. Plot the frequency response of the closed-loop system.

4.0 Simple State-Feedback Design [CA1- 20 module marks]

Consider the plant described in the previous section. It is desired to design a closed-loop system (Fig. 1) such that the frequency response from the commanded signal, 􏰇, to the output, 􏰄, has the following specifications:

</div>
</div>
<div class="layoutArea">
<div class="column">
Closed-loop bandwidth:

Resonant Peak, 􏰈􏰉 :

Steady-state gain between 􏰇 and 􏰄:

</div>
<div class="column">
Not lower than 3.5 rad/s; Not larger than 2dB; 0dB.

</div>
</div>
<div class="layoutArea">
<div class="column">
Original Plant 􏰇􏰊+􏰃 􏰄=􏰌􏰀

Figure 1

4.1 Design Using Ackermann’s Formula

Based on the closed-loop specifications given above, and the relation between location of poles and bandwidth, choose your desired closed-loop pole locations using the ITAE criterion. Then using Ackermann’s formula, calculate the state-feedback gains to place the poles of the closed-loop at the desired locations.

Provide a listing of how you used MATLAB to do the computations in the Ackermann’s formula, and also results of the computations.

Provide calculations to show how the scaling gain was chosen.

</div>
</div>
<div class="layoutArea">
<div class="column">
􏰀̇􏰁 = 􏰀􏰂

􏰀̇􏰂 = −3.71􏰀􏰂 − 1.20􏰀􏰁

+􏰃

</div>
</div>
<div class="layoutArea">
<div class="column">
􏰄

</div>
</div>
<div class="layoutArea">
<div class="column">
􏰋-􏰀 􏰊

</div>
</div>
</div>
<div class="page" title="Page 3">
<div class="layoutArea">
<div class="column">
Provide frequency response plots of the final closed-loop.

(You may have to go through several iterations of choice of desired pole locations to achieve the specifications. If so, provide the representative plots.)

In addition to the (a) ITAE methodology above, experiment further with the (b) Bessel prototype table methodology; and the (c) Second-Order Dominant Response methodology. Document, describe and discuss all your experimentation. (Note!!)

4.2 Design Using Linear Quadratic Regulator Weightings

The design using Ackermann’s formula focuses on choosing precisely the desired closed-loop pole locations. In a system where the dimension is large, such a procedure may be problematic as it is not always clear where exactly to place all the closed-loop poles. The linear Quadratic Regulator (LQR) method adopts a different approach. It focuses on calculating a set of gain to minimize the criterion

􏰒

􏰍=􏰎 (􏰀􏰏􏰐􏰀+􏰇􏰃􏰂)􏰑􏰅 􏰓

Obviously, this procedure considers only the problem of regulation. However, we can still use this method by modifying it for use in the following manner:

<ol>
<li>(a) &nbsp;Choose a set of weighting gains for the LQR problem;</li>
<li>(b) &nbsp;Use the MATLAB function LQR to compute the state-feedback gains that will minimize this
criterion;
</li>
<li>(c) &nbsp;Form the feedback loop for this set of gains, and check if it satisfies the closed-loop specifications;</li>
<li>(d) &nbsp;If the specs are not met, then go back to step (a), otherwise, proceed to the next step;</li>
<li>(e) &nbsp;Finally,choosethescalinggaintomeetthesteady-statecondition.</li>
</ol>
As is in Section 4.1, provide plots and listings that are representative of your efforts in this section. You may restrict your design to only using a diagonal matrix 􏰐 in the LQR formulation. Likewise, document, describe and discuss all your experimentations.

In the work in Section 4, the steady-state specification was met by the use of a scaling gain. Briefly explain the disadvantage, if any, of that approach.

Consider next the situation in Fig. 2. The plant has the state-variable description given in Section 3.

􏰀̇􏰁 = 􏰀􏰂

􏰀̇􏰂 = −3.71􏰀􏰂 − 1.20􏰀􏰁 + 􏰃 􏰄 = 􏰀􏰁

</div>
</div>
<div class="layoutArea">
<div class="column">
5.0 State-Feedback Design Including State-Augmentation [CA3 – 30 module marks. Self-

</div>
</div>
<div class="layoutArea">
<div class="column">
investigations. No GA “step-by-step” assistance for this part!! GA will still be available to

</div>
</div>
<div class="layoutArea">
<div class="column">
“guide” lah… :-):-)]

</div>
</div>
</div>
<div class="page" title="Page 4">
<div class="layoutArea">
<div class="column">
Figure 2

However, it is now desired to obtain the following frequency specs between 􏰇 and 􏰄:

</div>
</div>
<div class="layoutArea">
<div class="column">
Closed-loop bandwidth:

Resonant Peak, 􏰈􏰉 :

Steady-state gain between 􏰇 and 􏰄:

</div>
<div class="column">
Not lower than 1.5 rad/s; Not larger than 2dB; 0dB.

</div>
</div>
<div class="layoutArea">
<div class="column">
In addition, the response in 􏰄 to a step in the un-measurable disturbance 􏰔 should be zero in the steady- state.

Use the method of state-augmentation to design a controller for the system in Fig. 2. Explain carefully why state augmentation will result in a closed-loop system meeting the specs for the two items of steady- state requirement. (Then, note that since this is the case and the system is linear, it suffices to consider the state-feedback with 􏰔 = 0 to meet the remaining frequency response requirements.)

For the choice of the controller gains, first use the ITAE criterion to select the closed loop poles, and then use Ackermann’s formula to calculate the state feedback gains.

As a second method, use the LQR design method (with a diagonal matrix for 􏰐). Provide a listing (with sufficient comments) on how the MATLAB package was used in the design for this part. Investigate the effect of varying each of the weighting parameters on the frequency response between 􏰇 and 􏰄. For both methods, provide frequency response plots showing the frequency response between 􏰇 and 􏰄. (You should at least have one set of resulting controller gains that meet the required specs.)

Provide plots showing the response of the output, 􏰄, to a unit step in 􏰇.

Provide plots showing the response of the output, 􏰄, to a unit step in the unmeasurable disturbance, 􏰔,. For this case, provide, in addition a plot of the control input, 􏰃, in response to the step in the unmeasurable disturbance.

In all cases, as far as possible, provide listings to show how you used MATLAB to generate the various variables and plots.

In addition to the (a) ITAE and LQR methodologies above, experiment further with the (b) Bessel prototype table methodology; and the (c) Second-Order Dominant Response methodology. Document, describe and discuss all your experimentations. (Note!!)

</div>
</div>
</div>
<div class="page" title="Page 5">
<div class="layoutArea">
<div class="column">
<ol>
<li>5.1 &nbsp;Why does it make sense (assuming that we are operating using an identical “hardware set” in real-life) to require a lower closed-loop bandwidth (􏰕. 􏰖 􏰗􏰘􏰙 ∙ 􏰚􏰛􏰕) here? Experiment, explore and discuss.</li>
<li>5.2 &nbsp;Calculate the closed-loop transfer functions, attained in this Section 5 and discuss all pertinent aspects.</li>
<li>5.3 &nbsp;Additional Explorations</li>
</ol>
In all of the above, note that your design/calculations were based on:

􏰀̇􏰁 = 􏰀􏰂

􏰀̇􏰂 = −3.71􏰀􏰂 − 1.20􏰀􏰁 + 􏰃 􏰄 = 􏰀􏰁

Consider next, that unknown to you, the system has in fact changed to: 􏰀̇􏰁 = 􏰀􏰂

􏰀̇􏰂 = −3.51􏰀􏰂 − 0.77􏰀􏰁 + 1.10􏰃

􏰄 = 􏰀􏰁

Explore, discuss, analyze with all suitable simulations, analysis and descriptions in this type of situation on the use of the methods of:

o Usinga“ScalingGain”

o Using the augmented state variable 􏰀̇􏰜 = 􏰄 − 􏰇

Provide a suitably comprehensive exploration / discussion.

6.0 Additional Points to be Covered in the Reports

Document, describe and discuss all your experimentations. Where there are other issues that you have considered, likewise document, describe and discuss all of these.

</div>
</div>
</div>
