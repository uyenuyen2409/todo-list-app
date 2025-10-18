# todo-list-app
Một ứng dụng to-do-list đơn giản bằng python
# Danh sách để lưu các công việc
tasks = []
def add_task(task_name):
    """Thêm một công việc mới vào danh sách."""
    tasks.append(task_name)
    print(f"Đã thêm công việc:'{task_name}"')
# --- Điểm bắt đầu của chương trình ---
if_name_=="_main_":
    print("Chào mừng deesn với ứng dụng To-Do List!")
    add_task("Học bài Git và Github")
    add_task("Làm bài tập thực hành ở nhà")
