# whouse
Scartch3.0�ŕϐ��u���b�N�Ƃ�����g�p���Ă���X�v���C�g�𒲍�����R�}���h

## Usage

whouse.exe sb3_project [csv]

Scratch3.0�̃v���W�F�N�g��n���ƁA�ϐ����Ƃ�����g�p���Ă���X�v���C�g�̃��X�g�����L��json�`���ŏo�͂��܂��B  
>{'�ϐ���1': ['�X�v���C�g1', '�X�v���C�g2'...], '�ϐ���2': ['�X�v���C�g1', '�X�v���C�g3'...] ... }

csv�I�v�V������t�����csv�`���ŏo�͂��܂��B  
>�ϐ���1, �X�v���C�g1, �X�v���C�g2  
�ϐ���2, �X�v���C�g1, �X�v���C�g3  
...

## Example


���L����_�E�����[�h�����v���W�F�N�g("Dear Lisa.sb3")�ɑ΂��Ď��s�������ʂł��B  

https://scratch.mit.edu/projects/314166329/editor/


```
whouse.exe "Dear Lisa.sb3"
```

{'intro': ['Stage', 'Open Text', 'Control'], 'Message #': ['Stage', 'Open Text', 'Control', 'CB', 'Zinnea', 'mres', 'me_win', 'me_win2', 'Champ99', 'Lilyland', 'Khanning', 'KayOh', 'carmelo', 'Eric1', 'Eric2', 'Eric3', 'Me', 'ChrisG', 'Shruit'], 'card ready': ['Stage'], 'clone stop': ['Shruit']}

```
whouse.exe "Dear Lisa.sb3" csv
```

intro,Stage,Open Text,Control,
Message #,Stage,Open Text,Control,CB,Zinnea,mres,me_win,me_win2,Champ99,Lilyland,Khanning,KayOh,carmelo,Eric1,Eric2,Eric3,Me,ChrisG,Shruit,
card ready,Stage,
clone stop,Shruit,

