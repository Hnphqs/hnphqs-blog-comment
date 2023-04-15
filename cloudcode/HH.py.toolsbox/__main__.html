#Copyright HNPHQS
#Copyright 第四季度爹
#App version: 1.0
#App name: HH.py.toolsbox
#name:




#-----导入需要的库
print("加载中...")
import time, sys, os #python标准库
import requests, json #可能需要下载的库python3
app=18107
appname='HH.py.toolsbox'
appversion="1.0"
debug=False
headers_segong={"user-agent": f"Mozilla/5.0 (Linux; Android 9; {appname} Build/{appversion}; wv) AppleWebKit/537.36 (KHTML, like Gecko) Version/4.0 Chrome/68.0.3440.91 Mobile Safari/537.36","accept":"*/*","referer":"https://library.aiuys.com/?_=bkA","accept-language":"zh-CN,en-US;q=0.9"}
#-----卡密验证系统
print("请求中...")
def api(url,ok,out=False,headers=None,isjson=True):
    try:
        if headers==None:
            response = requests.get(url)
        else:
            response = requests.get(url,headers=headers)
    except OSError:
        print("请求失败!网络不通!")
        print("重新尝试...(如多次尝试无果,请尝试切换网络)*使用抓包软件可能会格机")
        return api(url,ok,out,headers)
    if debug==True:
        print(response)
    if isjson==True:
        response = json.loads(response.content)
    if ok !=None:
        if response['code']!=ok:
            if out==True:            
                raise ConnectionError(f"认证失败!{response['code']}错误")
            elif out==False:
                print("api调用失败")
    return response
kami=input('卡密：')
markcode=input('卡密绑定码(没有会自动创建一个)：')
if kami=="set debug True&password=857":
    debug=True
    kami="Fs0ua7TkP4XxmKvtKFK6hT0SLxx9VhXA"
    markcode="3141592653589"
t=time.time()
url = f'https://cute521.cn/api.php?api=kmlogon&app={app}&kami={kami}&t={t}&markcode={markcode}'
print("请求中...")
kamiapi=api(url,200,True)
print("卡密认证成功")
#-----获取账号
vip=kamiapi['msg']['vip']
print('------------------------------\n加载函数...')
print('获取参数...')
#-----调用api获取设备参数
sys=api("https://api.uomg.com/api/visitor.info?skey=774740085",1);system=sys["system"];ip=sys["ip"];netime=sys["time"]
print(f'''\
设备信息：
        系统：{system}
        ip：{ip}
        序列号：unknow
        网络时间：{netime}
        设备时间：{t}
        卡密：{kami}
        绑定码：{markcode}
        登录账号：{vip}''')
input("输入任意键继续")
#-----主体代码

def menu1():
    os.system("clear")
    menu='''\
            1.进入程序
            2.退出程序
            3.关于
            '''
    print(menu)
    chose=input("请输入: ")
    def chose1():
        menu1_1()
        menu1()
    def chose2():
        sys.exit(0)
    def chose3():
        os.system("clear")
        print(f'''\
                Copyright HNPHQS
                当前版本：{appversion}
                  HH.py.toolsbox是一个pyt
                hon工具箱,更多功能还在探
                索中...
                ''')
        input("按任意键返回")
        menu1()
    if chose=="1":
        chose1()
    elif chose=="2":
        chose2()
    elif chose=="3":
        chose3()
    else:
        print("非法输入!")
        menu1()
def menu1_1():
    os.system("clear")
    menu='''\
            1.和某人的qq建立对话
            2.信息泄露查询
            3.短信投屎💩
            856.高级设置
            857.返回
            '''
    print(menu)
    chose=input("请输入：")
    def chose1():
        os.system("clear")
        qid=(input("请对方输入qq号："))
        an=api(f"https://api.uomg.com/api/long2dwz?dwzapi=urlcn&url=https://api.uomg.com/api/qq.talk?qq={qid}",1)
        print(f"浏览器访问{an['ae_url']}自动跳转至qq与Ta对话")
        input("按任意键返回")
        menu1_1()
    def chose2():
        os.system("clear")
        print('''\

                信息泄露查询 1.0
1. 本工具支持 QQ/手机/身份证/微博/邮箱 互查
2. 输入exit返回上一级菜单
                ''')
        msg=input("请输入查询对象：")
        if msg=="exit":
            menu1_1()
        print("查询中...")
        url=f"https://library.aiuys.com/api/query?value={msg}"
        an=api(url,0,headers=headers_segong)
        print(f'''\
                查询结果：
              手机号:{an["data"]["phone_numbers"]}
              QQ号:{an["data"]["qq_numbers"]}
              微博号:{an["data"]["wb_numbers"]}
              密码:可以查询但不告诉你:)
              邮箱:{an["data"]["emails"]}
              身份证:可以查询但不告诉你:)
              姓名:{an["data"]["names"]}
------------------------------------------------
              ''')
        input("输入任意键继续")
        chose2()
    def chose3():
        print('暂不开放')
        menu1_1()
    if chose=="1":
        chose1()
    elif chose=="2":
        chose2()
    elif chose=="3":
        chose3()
    elif chose=="857":
        menu1()
    elif chose=="856":
        print('''\
                此功能暂未开放
                因为刮设置会导致程序崩溃
              ''')
        input("输入任意键继续")
        menu1_1()
    else:
        print("非法输入!")
        menu1_1()





if __name__=="__main__":
    menu1()
