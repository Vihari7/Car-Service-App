from tkinter import *
import datetime as dt

root=Tk()
root.geometry ('1250x600')
root.title('DV Cab Service')


label_0 =Label(root,text="Welcome to DV Cab Service", width=30,font=("bold",25))
label_0.place(x=350,y=10)


#Customer Details
label_0 =Label(root,text="Customer Details", width=20,font=("bold",20))
label_0.place(x=0,y=60)

#name=lable_1
label_1 =Label(root,text="Customer Name", width=20,font=("bold",10))
label_1.place(x=0,y=110)

#input text
entry_1=Entry(root)
entry_1.place(x=150,y=110)
#Address=lable_2
label_2 =Label(root,text="Address", width=20,font=("bold",10))
label_2.place(x=15,y=140)
entry_2=Entry(root)
entry_2.place(x=150,y=140)
#Telephone No=lable_3
label_3 =Label(root,text="Telephone No", width=20,font=("bold",10))
label_3.place(x=10,y=170)

entry_3=Entry(root)
entry_3.place(x=150,y=170)


Button(root, text='Submit' , width=10,bg="black",fg='white').place(x=110,y=200)
Button(root, text='Reset' , width=10,bg="black",fg='white').place(x=200,y=200)

#vehecle booking details
label_0 =Label(root,text="Booking Details", width=20,font=("bold",20))
label_0.place(x=10,y=240)

#Vehicle TypeNo=lable_5
label_5 =Label(root,text="Vehicle Type", width=20,font=("bold",10))
label_5.place(x=10,y=300)

entry_5=Entry(root)
entry_5.place(x=150,y=300)

#AC/Non AC=lable_3
label_6 =Label(root,text="AC/Non AC", width=20,font=("bold",10))
label_6.place(x=10,y=330)
var=IntVar()
Radiobutton(root,text="AC",padx= 5, variable= var, value=1).place(x=150,y=330)
Radiobutton(root,text="Non AC",padx= 20, variable= var, value=2).place(x=135,y=350)

#No.of passengers=lable_3
label_7 =Label(root,text="No.of passengers", width=20,font=("bold",10))
label_7.place(x=10,y=380)

entry_7=Entry(root)
entry_7.place(x=150,y=380)

#Max load(Kg)=lable_3
label_8 =Label(root,text="Max load(Kg)", width=20,font=("bold",10))
label_8.place(x=10,y=410)

entry_8=Entry(root)
entry_8.place(x=150,y=410)
#Size(ft)=lable_3
label_9 =Label(root,text="Size(ft)", width=20,font=("bold",10))
label_9.place(x=10,y=440)

entry_9=Entry(root)
entry_9.place(x=150,y=440)

Button(root, text='Submit' , width=10,bg="black",fg='white').place(x=110,y=480)
Button(root, text='Reset' , width=10,bg="black",fg='white').place(x=200,y=480)



#Driver Details
label_x =Label(root,text="Hiring for Drivers", width=20,font=("bold",20))
label_x.place(x=450,y=60)

#name=lable_1
label_a =Label(root,text=" Name", width=20,font=("bold",10))
label_a.place(x=450,y=110)

#input text
entry_a=Entry(root)
entry_a.place(x=600,y=110)
#Address=lable_2
label_b =Label(root,text="Address", width=20,font=("bold",10))
label_b.place(x=445,y=140)
entry_b=Entry(root)
entry_b.place(x=600,y=140)
#Age=lable_c
label_c =Label(root,text="Age", width=20,font=("bold",10))
label_c.place(x=445,y=170)
entry_c=Entry(root)
entry_c.place(x=600,y=170)

#Telephone No=lable_d
label_d =Label(root,text="Telephone No", width=20,font=("bold",10))
label_d.place(x=445,y=200)

entry_d=Entry(root)
entry_d.place(x=600,y=200)
#driving licence=lable_e
label_e =Label(root,text="Driving Licence", width=20,font=("bold",10))
label_e.place(x=450,y=230)

entry_e=Entry(root)
entry_e.place(x=600,y=230)

Button(root, text='Submit' , width=10,bg="black",fg='white').place(x=560,y=280)
Button(root, text='Reset' , width=10,bg="black",fg='white').place(x=650,y=280)

#Details of Vehicles
label_x =Label(root,text="Details of Vehicles", width=20,font=("bold",20))
label_x.place(x=530,y=310)

#Vehicles
label_x =Label(root,text="Vehicles", width=20,font=("bold",14))
label_x.place(x=360,y=350)

#No of passengers
label_x =Label(root,text="No of", width=20,font=("bold",14))
label_x.place(x=510,y=350)
label_x =Label(root,text="passengers", width=20,font=("bold",14))
label_x.place(x=490,y=380)

#Size
label_x =Label(root,text="Size(ft)", width=20,font=("bold",14))
label_x.place(x=630,y=350)


#Max load and size
label_x =Label(root,text="Max load", width=20,font=("bold",14))
label_x.place(x=773,y=350)
label_x =Label(root,text="(Kg)", width=20,font=("bold",14))
label_x.place(x=765,y=380)

#Cars=lable_q
label_q =Label(root,text="Cars:", width=20,font=("bold",10))
label_q.place(x=380,y=420)
label_q =Label(root,text="3 and 4", width=20,font=("bold",10))
label_q.place(x=520,y=420)
label_q =Label(root,text="-", width=20,font=("bold",10))
label_q.place(x=650,y=420)
label_q =Label(root,text="-", width=20,font=("bold",10))
label_q.place(x=790,y=420)

#Vans=lable_r
label_r =Label(root,text="Vans:", width=20,font=("bold",10))
label_r.place(x=380,y=450)
label_q =Label(root,text="6 and 8", width=20,font=("bold",10))
label_q.place(x=520,y=450)
label_q =Label(root,text="-", width=20,font=("bold",10))
label_q.place(x=650,y=450)
label_q =Label(root,text="-", width=20,font=("bold",10))
label_q.place(x=790,y=450)

#3 wheels=lable_s
label_s =Label(root,text="3 Wheelers:", width=20,font=("bold",10))
label_s.place(x=380,y=480)
label_q =Label(root,text="3", width=20,font=("bold",10))
label_q.place(x=520,y=480)
label_q =Label(root,text="-", width=20,font=("bold",10))
label_q.place(x=650,y=480)
label_q =Label(root,text="-", width=20,font=("bold",10))
label_q.place(x=790,y=480)

#Trucks=lable_t
label_t =Label(root,text="Trucks:", width=20,font=("bold",10))
label_t.place(x=380,y=510)
label_q =Label(root,text="-", width=20,font=("bold",10))
label_q.place(x=520,y=510)
label_q =Label(root,text="7 ft and 12 ft", width=20,font=("bold",10))
label_q.place(x=650,y=510)
label_q =Label(root,text="-", width=20,font=("bold",10))
label_q.place(x=790,y=510)

#Lorry=lable_u
label_u =Label(root,text="Lorry:", width=20,font=("bold",10))
label_u.place(x=380,y=540)
label_q =Label(root,text="-", width=20,font=("bold",10))
label_q.place(x=520,y=540)
label_q =Label(root,text="-", width=20,font=("bold",10))
label_q.place(x=650,y=540)
label_q =Label(root,text="2500kg and 3500kg", width=20,font=("bold",10))
label_q.place(x=790,y=530)


#Available Vehicles Details
label_x =Label(root,text="Available Vehicles Today", width=20,font=("bold",20))
label_x.place(x=850,y=60)

#current date
date = dt.datetime.now()
label_ti = Label(root, text=f"{date:%A, %B %d, %Y}", font="Calibri, 11")
label_ti.pack(pady=20)
label_ti.place(x=950,y=100)

label_a =Label(root,text=" Cars:", width=20,font=("bold",11))
label_a.place(x=850,y=130)
entry_a=Entry(root)
entry_a.place(x=980,y=130)

label_b =Label(root,text="Vans:", width=20,font=("bold",11))
label_b.place(x=850,y=160)
entry_b=Entry(root)
entry_b.place(x=980,y=160)

label_c =Label(root,text="3 Wheelers:", width=20,font=("bold",11))
label_c.place(x=850,y=190)
entry_c=Entry(root)
entry_c.place(x=980,y=190)

label_d =Label(root,text="Trucks:", width=20,font=("bold",11))
label_d.place(x=850,y=220)
entry_c=Entry(root)
entry_c.place(x=980,y=220)


label_e =Label(root,text="Lorry:", width=20,font=("bold",11))
label_e.place(x=850,y=250)
entry_e=Entry(root)
entry_e.place(x=980,y=250)

#Update Vehicle Details
label_x =Label(root,text="Updating Vehicle ", width=20,font=("bold",20))
label_x.place(x=930,y=310)
label_x =Label(root,text="Details", width=20,font=("bold",20))
label_x.place(x=930,y=350)

label_a =Label(root,text=" Cars:", width=20,font=("bold",10))
label_a.place(x=930,y=390)
Button(root, text='Add' , width=10,bg="black",fg='white').place(x=1050,y=390)
Button(root, text='Delete' , width=10,bg="black",fg='white').place(x=1125,y=390)

label_b =Label(root,text="Vans:", width=20,font=("bold",10))
label_b.place(x=930,y=420)
Button(root, text='Add' , width=10,bg="black",fg='white').place(x=1050,y=420)
Button(root, text='Delete' , width=10,bg="black",fg='white').place(x=1125,y=420)

label_c =Label(root,text="3 Wheelers:", width=20,font=("bold",10))
label_c.place(x=930,y=450)
Button(root, text='Add' , width=10,bg="black",fg='white').place(x=1050,y=450)
Button(root, text='Delete' , width=10,bg="black",fg='white').place(x=1125,y=450)

label_d =Label(root,text="Trucks:", width=20,font=("bold",10))
label_d.place(x=930,y=480)
Button(root, text='Add' , width=10,bg="black",fg='white').place(x=1050,y=480)
Button(root, text='Delete' , width=10,bg="black",fg='white').place(x=1125,y=480)

label_e =Label(root,text="Lorry:", width=20,font=("bold",10))
label_e.place(x=930,y=510)
Button(root, text='Add' , width=10,bg="black",fg='white').place(x=1050,y=510)
Button(root, text='Delete' , width=10,bg="black",fg='white').place(x=1125,y=510)


root.mainloop()