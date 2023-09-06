SQL injection exists in the ibos office OA. Procedure

official website:http://www.ibos.com.cn/

version:4.5.5

 Function point: Background management = "Address book management =" Post management = "Add post =" Add member = "Function office

 ![WPS图片(1)](https://github.com/liuqiba12345678/cve/assets/144125181/29ab60bc-1547-4669-b78f-dc430283ec23)

Route: r=dashboard/position/edit&op=member

The injection parameter id exists

The user name was successfully popped by reporting an error injection

![WPS图片(2)](https://github.com/liuqiba12345678/cve/assets/144125181/6448cb4b-5037-45ed-901d-ecb86b66ad41)

Follow up the setPosition() method by calling it through the actionEdit() method

![WPS图片(3)](https://github.com/liuqiba12345678/cve/assets/144125181/66c8ede5-307f-4c56-9a51-763651066dbb)

![WPS图片(4)](https://github.com/liuqiba12345678/cve/assets/144125181/04351f4c-e4a3-4078-b92f-6874c0c2ff37)


![WPS图片(5)](https://github.com/liuqiba12345678/cve/assets/144125181/a0385565-cf5b-43a8-a321-c8c4c0efbb1a)

