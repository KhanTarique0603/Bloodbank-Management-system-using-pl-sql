create table seeker(
seeker_id int primary key,
name varchar2(20),
age int,
city varchar2(20),
bloodgroup varchar2(5),
phone_no number,
gender varchar2(10),
registration_date date
)
create table hospital(
hospital_id int primary key,
name varchar2(20),
address varchar2(20),
phone_no number,
website varchar2(20),
email varchar2(25),
location varchar2(20),
city varchar2(20)
)
create table blood_bank(
bloodbank_id int primary key,
blood_type varchar2(20),
address varchar2(20),
bloodbank_phone number,
location varchar2(20),
website varchar2(20),
email varchar2(25)
)
create table blood_stock(
stock_id int primary key,
blood_groups varchar2(15),
quantity_In_Litres number,
best_before date
)
create table request(
request_id int primary key,
request_date date,
required_blood varchar2(20),
contact number
)
create table donor(
D_id int primary key,
D_name varchar2(20),
contact_no number,
D_city varchar2(20)
)

insert into seeker values(1951,'sachin',31,'Mumbai','B',9532656589,'Male','19-Mar-2019');
insert into hospital values(4478,'City Hospital','Maharashtra',9765876534,'www.cityhosp.com','city1@gmail.com','MUMBAI','MUMBAI');
insert into blood_bank values(5328,'Positive','Maharashtra',9876589787,'MUMBAI','www.bloodbank.com','blood@gmail.com');
insert into blood_stock values(7834,'A,B,AB,O',20,'19-Jan-2020');
insert into request values(1951,'19-Mar-2019','B-Positive',9532656589);
insert into donor values(6786,'Ajay',8456745675,'MUMBAI');

insert into seeker values(1952,'Jameel',41,'Mumbai','B',7345678614,'Male','21-Oct-2019');
insert into hospital values(4478,'City Hospital','Maharashtra',9765876534,'www.cityhosp.com','city1@gmail.com','MUMBAI','MUMBAI');
insert into blood_bank values(5328,'Positive','Maharashtra',9876589787,'MUMBAI','www.bloodbank.com','blood@gmail.com');
insert into blood_stock values(7834,'A,B,AB,O',20,'19-Jan-2020');
insert into request values(1952,'21-Oct-2019','B-Negative',7345678614);
insert into donor values(6787,'Akshay',9765432530,'MUMBAI');

insert into seeker values(1953,'Singh',35,'Mumbai','A',8423567352,'Male','28-Feb-2019');
insert into hospital values(4478,'City Hospital','Maharashtra',9765876534,'www.cityhosp.com','city1@gmail.com','MUMBAI','MUMBAI');
insert into blood_bank values(5328,'Positive','Maharashtra',9876589787,'MUMBAI','www.bloodbank.com','blood@gmail.com');
insert into blood_stock values(7834,'A,B,AB,O',20,'19-Jan-2020');
insert into request values(1953,'28-Feb-2019','A-Positive',8423567352);
insert into donor values(6789,'Vijay',9876543876,'MUMBAI');

insert into seeker values(1954,'Vinod',28,'Mumbai','A',9876350589,'Male','17-Jun-2019');
insert into hospital values(4478,'City Hospital','Maharashtra',9765876534,'www.cityhosp.com','city1@gmail.com','MUMBAI','MUMBAI');
insert into blood_bank values(5328,'Positive','Maharashtra',9876589787,'MUMBAI','www.bloodbank.com','blood@gmail.com');
insert into blood_stock values(7834,'A,B,AB,O',20,'19-Jan-2020');
insert into request values(1954,'17-Jun-2019','A-Negative',9876350589);
insert into donor values(6783,'Vicky',8531278575,'MUMBAI');

insert into seeker values(1955,'Rahul',39,'Mumbai','AB',7536272389,'Male','25-Aug-2019');
insert into hospital values(4478,'City Hospital','Maharashtra',9765876534,'www.cityhosp.com','city1@gmail.com','MUMBAI','MUMBAI');
insert into blood_bank values(5328,'Positive','Maharashtra',9876589787,'MUMBAI','www.bloodbank.com','blood@gmail.com');
insert into blood_stock values(7834,'A,B,AB,O',20,'19-Jan-2020');
insert into request values(1955,'25-Aug-2019','AB-Positive',7536272389);
insert into donor values(6784,'Savita',7435261890,'MUMBAI');

insert into seeker values(1956,'Pankaj',31,'Mumbai','AB',7023665658,'Male','27-Nov-2019');
insert into hospital values(4478,'City Hospital','Maharashtra',9765876534,'www.cityhosp.com','city1@gmail.com','MUMBAI','MUMBAI');
insert into blood_bank values(5328,'Positive','Maharashtra',9876589787,'MUMBAI','www.bloodbank.com','blood@gmail.com');
insert into blood_stock values(7834,'A,B,AB,O',20,'19-Jan-2020');
insert into request values(1956,'27-Nov-2019','AB-Negative',7023665658);
insert into donor values(6782,'Roshan',9702889672,'MUMBAI');

insert into seeker values(1957,'Nasim',31,'Mumbai','O',7738144695,'Male','31-Dec-2019');
insert into hospital values(4478,'City Hospital','Maharashtra',9765876534,'www.cityhosp.com','city1@gmail.com','MUMBAI','MUMBAI');
insert into blood_bank values(5328,'Positive','Maharashtra',9876589787,'MUMBAI','www.bloodbank.com','blood@gmail.com');
insert into blood_stock values(7834,'A,B,AB,O',20,'19-Jan-2020');
insert into request values(1957,'31-Dec-2019','O',7738144695);
insert into donor values(6791,'Rocky',9702889672,'MUMBAI');

select *from seeker
select *from hospital
select *from blood_bank
select *from blood_stock
select *from request
select *from donor
