# Active-Noise-Cancellation
Simulate noise cancelling headphones.

Given a noisy signal measurement x(t) = s(t) + n(t), and an independent reference measurement that
captured just the noise source nref (t). Use active noise cancellation by estimating a filter h(t)
whose output gives you an estimate of the noise unknown n(t) in x(t). Then, an estimate of the
clean signal can be constructed as ˆs(t) = x(t) − h(t) ** nref (t), where ** denotes convolution.
