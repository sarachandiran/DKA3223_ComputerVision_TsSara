## WEEK 2  ##

### GITHUB COLLABORATORS AND MARKDOWN ##
[https://colab.research.google.com/drive/1AdPRmKN3JT7ChMgHytDfwgpWIq_FuV4w#scrollTo=HIqvNqRual_0&line=1&uniqifier=1](https://colab.research.google.com/drive/1AdPRmKN3JT7ChMgHytDfwgpWIq_FuV4w#scrollTo=HIqvNqRual_0&line=1&uniqifier=1)

# ==========================================================
# FIX ME CHALLENGE: PROFIL PERMULAAN ROBOT
# ==========================================================

robot_name = "FIX_ME"          # Contoh: "KV-TRON Safety Patrol"
robot_id = None                # Contoh: 205
battery_level = None           # Contoh: 95
operation_mode = "FIX_ME"      # Contoh: "Pemeriksaan Bengkel"
robot_location = "FIX_ME"      # Contoh: "Bengkel TVET A"

# FIX ME: Tukar kepada input("Masukkan nama jurutera: ")
engineer_name = "FIX_ME"

print("\n====================================")
print("       PROFIL PERMULAAN ROBOT")
print("====================================")
print("Nama Robot    :", robot_name)
print("ID Robot      :", robot_id)
print("Bateri        :", battery_level, "%")
print("Mod Operasi   :", operation_mode)
print("Lokasi        :", robot_location)
print("Jurutera      :", engineer_name)

lengkap = (
    robot_name != "FIX_ME"
    and robot_id is not None
    and battery_level is not None
    and operation_mode != "FIX_ME"
    and robot_location != "FIX_ME"
    and engineer_name != "FIX_ME"
)

print("------------------------------------")
print("[ROBOT ONLINE] Identiti lengkap." if lengkap
      else "[BELUM LENGKAP] Baiki semua bahagian FIX ME.")


