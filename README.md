<h1 align='center'>Predictive Queue Management in Supermarkets</h1>

<p align='center'>University of Trento</p>
<p align='center'>Bachelor's degree in Computer Science</p>

<h3 align='center'>Matteo Destro</h3>

<p align='center'>Academic year 2019/2020</p>

---
Long waiting queues at the checkouts are one of the major causes of customers’ dissatisfaction in retailing. In the context of supermarkets, the only way for store managers to control the queues length is by increasing staffing levels, in an attempt to provide a uniform level of service at all times. However, keeping a checkout open has a cost in terms of manned staff: an optimization which takes in account both cost and customers’ satisfaction is therefore necessary.

The work presented on this thesis focuses on the development of a predictive model for the queueing behavior in retail stores, with the aim of forecasting near-term arrival rates at the checkouts, supporting the management in a more efficient pre-positioning of the staff to avoid, or at least reduce, waiting queues. The system shall suggest an optimal checkouts configuration, minimizing the staffing costs while maintaining the customers’ waiting times under a maximum threshold.

The final predictive model is able to produce an accurate forecast of the queue length and to determine the best checkouts configuration. First, a model for forecasting the number of customers entering the store is used in order to achieve a multi-step forecast. Next, the measured and predicted inflow rates are combined with the dwell time distributions to get a near-term forecast of the rates of customers arriving at the checkouts. Finally, a predictive model for the expected value of the queue length and waiting time is defined by applying queueing theory. With these forecasts, once a maximum acceptable queue length has been defined, different checkouts configurations can be evaluated to determine the optimal one. 
