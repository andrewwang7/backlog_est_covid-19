# 台灣COVID-19 backlog預估

利用過去幾天公告的原始數字跟Backlog之後的數字預估未來backlog值, 早期看出趨勢

目前2021/5/17~2021/5/25原始公告和Backlog數值如下
可得到Backlog比率如下

通報日	    原始公告	Backlog	Backlog比率
2021/5/17	333	      533	    1.60 
2021/5/18	240	      454	    1.89 
2021/5/19	267	      525	    1.97 
2021/5/20	286	      474	    1.66 
2021/5/21	312	      424	    1.36 
2021/5/22	321	      464	    1.45 
2021/5/23	287	      476	    1.66 
2021/5/24	334	      485	    1.45 
2021/5/25	281	      463	    1.65 

##平均Backlog比率為1.63


通報日	    原始公告	Backlog	Backlog比率	Backlog比率預測	Backlog比率預測誤差
2021/5/17	333	      533	    1.60 	      543 	          10 
2021/5/18	240	      454	    1.89 	      391 	          63 
2021/5/19	267	      525	    1.97 	      435 	          90 
2021/5/20	286	      474	    1.66 	      466 	          8 
2021/5/21	312	      424	    1.36 	      509 	          85 
2021/5/22	321	      464	    1.45 	      524 	          60 
2021/5/23	287   	  476	    1.66 	      468 	          8 
2021/5/24	334	      485	    1.45 	      545 	          60 
2021/5/25	281	      463	    1.65 	      458 	          5 

#平均誤差(mae) 為43人
#最大誤差(mae) 為90人
#最小誤差(mae) 為5人

預估2021/5/26~2021/5/28預估為

通報日	    原始公告	Backlog比率預測
2021/5/26	302	      493 
2021/5/27	401	      654 
2021/5/28	297			  484 

![image](https://github.com/andrewwang7/backlog_est_covid-19/blob/main/backlog.png)



