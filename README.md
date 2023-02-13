# Challenge-B
2.times do
  sample :drum_snare_soft, amp: 2
  sleep 2
end
4.times do
  sample :drum_heavy_kick, amp: 2
  sleep 1
end
live_loop :hi do
  sample :drum_cymbal_closed
  sleep 0.5
  sample :drum_cymbal_closed
  sleep 0.5
  sample :drum_cymbal_closed
  sleep 0.5
end
live_loop :oops do
  sample :drum_splash_hard, sustain: 3
  sample :drum_cymbal_hard
  sample :drum_cowbell, amp: 1.5
end
live_loop :bye do
  sleep 0.5
  sample :drum_cymbal_closed
  sleep 0.5
  sample :drum_cymbal_closed
  sleep 0.5
  sample :drum_cymbal_closed
  sleep 0.5
  sample :drum_cymbal_closed
  sleep 0.5
  sample :drum_cymbal_closed
  sleep 0.5
end
