40

CUDA_VISIBLE_DEVICES=7 python eval.py data/hcvrp/hcvrp_40_seed24610.pkl --model outputs/hcvrp_40/hcvrp40_rollout_20240226T165446/epoch-99.pt --decode_strategy sample --obj 'min-sum' --width 1280 --eval_batch_size 1  -f --UAMSO

CUDA_VISIBLE_DEVICES=6 python eval.py data/hcvrp/hcvrp_40_seed24610.pkl --model outputs/hcvrp_40/hcvrp40_rollout_20240226T165446/epoch-99.pt --decode_strategy greedy --obj 'min-sum' --eval_batch_size 1280  -f

CUDA_VISIBLE_DEVICES=6 python eval.py data/hcvrp/hcvrp_60_seed24610.pkl --model outputs/hcvrp_60/hcvrp60_rollout_20240226T165449/epoch-99.pt --decode_strategy greedy --eval_batch_size 1280 --obj 'min-sum' -f

CUDA_VISIBLE_DEVICES=6 python eval.py data/hcvrp/hcvrp_80_seed24610.pkl --model outputs/hcvrp_80/hcvrp80_rollout_20240226T165452/epoch-99.pt --decode_strategy greedy  --eval_batch_size 1280 --obj 'min-sum' -f 

CUDA_VISIBLE_DEVICES=6 python eval.py data/hcvrp/hcvrp_100_seed24610.pkl --model outputs/hcvrp_100/hcvrp100_rollout_20240226T165454/epoch-99.pt --decode_strategy greedy  --eval_batch_size 1280 --obj 'min-sum' -f 

CUDA_VISIBLE_DEVICES=6 python eval.py data/hcvrp/hcvrp_120_seed24610.pkl --model outputs/hcvrp_120/hcvrp120_rollout_20240226T165457/epoch-99.pt --decode_strategy greedy  --eval_batch_size 1280 --obj 'min-sum'  -f 


# sample

40

`

CUDA_VISIBLE_DEVICES=6 python eval.py data/hcvrp/hcvrp_40_seed24610.pkl --model outputs/hcvrp_40/hcvrp40_rollout_20240226T165446/epoch-99.pt --decode_strategy sample --obj 'min-sum' --width 1280 --eval_batch_size 1  -f 
`

60

`

CUDA_VISIBLE_DEVICES=6 python eval.py data/hcvrp/hcvrp_60_seed24610.pkl --model outputs/hcvrp_60/hcvrp60_rollout_20240226T165449/epoch-99.pt --decode_strategy sample --width 1280 --eval_batch_size 1 --obj 'min-sum' -f  
`

80

`

CUDA_VISIBLE_DEVICES=6 python eval.py data/hcvrp/hcvrp_80_seed24610.pkl --model outputs/hcvrp_80/hcvrp80_rollout_20240226T165452/epoch-99.pt --decode_strategy sample --width 1280 --eval_batch_size 1 --obj 'min-sum' -f  
`

100

`

CUDA_VISIBLE_DEVICES=6 python eval.py data/hcvrp/hcvrp_100_seed24610.pkl --model outputs/hcvrp_100/hcvrp100_rollout_20240226T165454/epoch-99.pt --decode_strategy sample --width 1280 --eval_batch_size 1 --obj 'min-sum' -f  
`

120

`

CUDA_VISIBLE_DEVICES=6 python eval.py data/hcvrp/hcvrp_120_seed24610.pkl --model outputs/hcvrp_120/hcvrp120_rollout_20240226T165457/epoch-99.pt --decode_strategy sample --width 1280 --eval_batch_size 1 --obj 'min-sum'  -f  
`

# sample 12800

40

`

CUDA_VISIBLE_DEVICES=2 python eval.py data/hcvrp/hcvrp_40_seed24610.pkl --model outputs/hcvrp_40/hcvrp40_rollout_20240226T165446/epoch-99.pt --decode_strategy sample --obj 'min-sum' --width 12800 --eval_batch_size 1  -f --UAMSO
`

60

`

CUDA_VISIBLE_DEVICES=2 python eval.py data/hcvrp/hcvrp_60_seed24610.pkl --model outputs/hcvrp_60/hcvrp60_rollout_20240226T165449/epoch-99.pt --decode_strategy sample --width 12800 --eval_batch_size 1 --obj 'min-sum' -f --UAMSO  
`

80

`

CUDA_VISIBLE_DEVICES=4 python eval.py data/hcvrp/hcvrp_80_seed24610.pkl --model outputs/hcvrp_80/hcvrp80_rollout_20240226T165452/epoch-99.pt --decode_strategy sample --width 12800 --eval_batch_size 1 --obj 'min-sum' -f --UAMSO  
`

100

`

CUDA_VISIBLE_DEVICES=2 python eval.py data/hcvrp/hcvrp_100_seed24610.pkl --model outputs/hcvrp_100/hcvrp100_rollout_20240226T165454/epoch-99.pt --decode_strategy sample --width 12800 --eval_batch_size 1 --obj 'min-sum' -f --UAMSO  
`

120

`

CUDA_VISIBLE_DEVICES=4 python eval.py data/hcvrp/hcvrp_120_seed24610.pkl --model outputs/hcvrp_120/hcvrp120_rollout_20240226T165457/epoch-99.pt --decode_strategy sample --width 12800 --eval_batch_size 1 --obj 'min-sum'  -f --UAMSO  
`