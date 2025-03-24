해당 프로젝트는 hailo-CLIP에 있는 community_projects로 Hailo Hackathon 2024에서 진행된 프로젝트입니다.

본 레포지토리는 해당 프로젝트를 라즈베리파이에서 실행되도록 구현했습니다.

설치방법
git clone https://github.com/hailo-ai/hailo-rpi5-examples.git
cd hailo-rpi5-examples
./install.sh
exit
cd ..
git clone https://github.com/BCMTech-utilization/ad-genie.git
cd ad-genie
./install.sh
source setup_env.sh
cd community_projects/ad_genie
get-usb-camera
python ad_genie.py -d person -i /dev/video0 --json-path resources/data_embdedding.json
