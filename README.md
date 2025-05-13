#  Unicycle & Visai Robot Simulation in Python

Mô phỏng các robot **Unicycle** và **Visai (Differential Drive)** di chuyển tới một điểm đích xác định trong không gian 2D bằng Python và Matplotlib. Các ví dụ trực quan minh họa các thuật toán điều khiển cơ bản.

---

##  Unicycle Robot

Mô hình robot bánh đơn (unicycle) với 3 trường hợp điều khiển khác nhau:

### TH1 – Robot quay rồi tiến
![Unicycle TH1](https://github.com/user-attachments/assets/1ad106a7-72e4-496a-8e63-f27623cc9a72)

### TH2 – Robot điều chỉnh hướng liên tục khi tiến
![Unicycle TH2](https://github.com/user-attachments/assets/824169b3-e683-47d6-aa96-e2dcbb02d690)

### TH3 – Robot quay nhanh, sau đó tiến
![Unicycle TH3](https://github.com/user-attachments/assets/def5ffc9-99e9-47a9-ab4f-84701db2478a)

---

##  Visai (Differential Drive) Robot

Mô hình robot hai bánh độc lập điều khiển bằng tốc độ tuyến tính và góc quay (v, ω):

![Visai Robot](https://github.com/user-attachments/assets/2371e542-f7b1-40e9-a819-0c66a48509c5)

---

##  Công nghệ sử dụng

- `Python 3`
- `Matplotlib` (vẽ và animate)
- `numpy` (xử lý số học)
- `FuncAnimation` (animation mô phỏng chuyển động)
- `IPython.display` (hiển thị trên Colab)

---

##  Cấu trúc file

```bash
.
├── unicycle_simulation.ipynb       # Mô phỏng robot unicycle
├── differential_drive_sim.ipynb    # Mô phỏng robot visai
├── README.md
