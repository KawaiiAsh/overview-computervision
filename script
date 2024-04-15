import subprocess

# 仓库的URL
repo_url = "https://github.com/KawaiiAsh/overview-computervision.git"

# 目标目录
destination_dir = "/path/to/destination_directory"

# 构建git clone指令
clone_command = ["git", "clone", repo_url, destination_dir]

# 执行git clone指令
try:
    subprocess.run(clone_command, check=True)
    print("Repository cloned successfully!")
except subprocess.CalledProcessError as e:
    print("Error:", e)
