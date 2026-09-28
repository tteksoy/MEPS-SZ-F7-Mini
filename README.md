# MEPS-SZ-F7-Mini

https://www.firstquadcopter.com/reviews/meps-sz-f7-mini-small-and-versatile-f722-flight-controller/

https://www.mepsking.shop/f7-mini-fpv-flight-controller.html

Simply modified following lines.

    DEF_TIM(TIM8,  CH1,  PC6,  TIM_USE_OUTPUT_AUTO, 0, 0),
    
    DEF_TIM(TIM8,  CH2,  PC7,  TIM_USE_OUTPUT_AUTO, 0, 0),
    

for TMOTORF7
