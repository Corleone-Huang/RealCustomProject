# RealCustom++

Existing text-to-image customization (or subject-driven generation) methods follow the pseudo-word paradigm, 
which involves representing given subjects as pseudo-words and combining them with given texts to collectively guide the generation.
However, the inherent conflict and entanglement between the pseudo-words and texts result in a dual-optimum paradox, where subject similarity and text controllability cannot be optimal simultaneously.
In this paper, we present RealCustom++, for the first time, disentangles subject similarity from text controllability and thereby allows both to be optimized simultaneously without any conflicts.
The core idea of RealCustom++ is to represent given subjects as real words that can be seamlessly integrated with given texts, 
and further leveraging the relevance between real words and image regions to disentangle subjects from texts. 

![motivation](assets/motivation.jpg)
![motivation](assets/generation.jpg)

## Enjoy on [Dreamina](https://jimeng.jianying.com/ai-tool/home)



## About Code Release

## Reference

```
@inproceedings{huang2024realcustom,
  title={RealCustom: Narrowing Real Text Word for Real-Time Open-Domain Text-to-Image Customization},
  author={Huang, Mengqi and Mao, Zhendong and Liu, Mingcong and He, Qian and Zhang, Yongdong},
  booktitle={Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition},
  pages={7476--7485},
  year={2024}
}
```