#### This is project by book Linux from scratch to develop my own distributive to run my site:


- `main.sh` for main logic
- `steps/` for installation scripts step by step

#### to run project : 
docker run -it --privileged                             \
     -v /home/puzinanata/linux_from_scratch:/home/lfs   \
     -v /var/lib/lfs:/var/lib/lfs                       \
     -v /mnt/new_root_dir/:/mnt/new_root_dir/           \
      debian bash
- cd /home/lfs
- time bash main.sh

