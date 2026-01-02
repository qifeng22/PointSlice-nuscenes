Here is the **PointSlice** code for the **nuScenes** dataset. You can run it using the following command:
```
bash scripts/dist_train.sh cfgs/pointslice/safdnet_20e_nuscenes.yaml 8 --batch_size 16 --epoch 20 --workers=2
```
You can evaluate your trained model using the following command:
```
python test.py --cfg_file cfgs/pointslice/pointslice_20e_nuscenes.yaml --ckpt path/to/your/checkpoint.pth --dataset nuscenes
```
### Results
![image](https://github.com/user-attachments/assets/6b5d8609-8939-420a-bbbd-f2ce9872bfda)

