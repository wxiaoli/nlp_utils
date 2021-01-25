## tricks for training neural networks
- 加载数据时都会把长度接近的文本放在同一个batch中.
- batch_size
    > "Training with large minibatches is bad for your health. More importantly, it's bad for your test error. Friends don‘t let friends use minibatches larger than 32. Let's face it: the only people have switched to minibatch sizes larger than one since 2012 is because GPUs are inefficient for batch sizes smaller than 32. That's a terrible reason. It just means our hardware sucks." --Yann LeCun
