<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>jiang的个人主页</title>
    <link rel="stylesheet" type="text/css" href="rel.css">
    <style type="text/css">
        p{
            color: gold;
        }
    </style>
    <style type="text/css">
        body{
            margin: 0px;
        }
        #full{
            width: 100%;height: 5000px;
        }
        #heading{
            width: 100%;height: 12%;
        }
        #menu_1{
            width: 20%;height: 78%;
            float: left;
        }
        #comment1{
            width: 80%;height: 9%;
            float: right;
        }
        #comment2{
            width: 80%;height: 69%;
            float: right;
        }
        #bottom{
            width: 100%;height: 15%;
            float: bottom;
        }



    </style>
</head>
<body>
    <div id="full">
        <div id="heading">
            <h1 align="center"><b><em><i><strong>欢迎！！！</strong></i></em></b></h1>
            <br/><br/><br/><br/><br/>
            <a name="tips"><h2 align="center">let"s start from here</h2></a>
        </div>
        <div id="menu_1">
            <ul type="square">
                <li>pictures</li>
                <ol>
                    <li><a href="#">...</a> </li>
                </ol>
                <li>videos</li>
                <ol>
                    <li>...</li>
                </ol>
                <form>
                    用户名<input  type="text ">
                    <br/>
                    密码<input type="password">
                    <input type="button" value="confim" >
                    <input type="button" value="cancel">
                    <br/> <br/> <br/>
                    您的年龄是？
                    <br/>
                    小于20<input type="checkbox">
                    <br/>
                    20~30<input type="checkbox">
                    <br/>
                    30~40<input type="checkbox">
                    <br/>
                    大于40<input type="checkbox">
                    <br/> <br/> <br/>
                    您的性别？
                    <br/>
                    男<input type="radio" name="sex">
                    女<input type="radio" name="swx">
                    <br/> <br/> <br/>
                    您的学历？
                    <br/>
                    <select>
                        <option>本科</option>
                        <option>研究生</option>
                        <option>博士</option>
                        <option>其他</option>
                    </select>
                    <br/> <br/> <br/>
                </form>
                <textarea cols="25" rows="25" >
        您的建议是？
    </textarea>
            </ul>
        </div>
        <div id="comment1" >
           <nav>
                   <table  cellpadding="5" border="5" width="200px">
                   <caption>导航</caption>
                   <tr style="background: gold">
                       <th><i>试试吧</i></th>
                   </tr>
                   <tr>
                       <td><a href="http://www.baidu.com">打开百度试试</a></td>
                       <td><a href="http://jersay727.github.io/gushi/">打开这个试试</a></td>
                   </tr>
                   </table>
           </nav>

        </div>
        <div id="comment2">
          <ul>
              <li>图片1</li>
              <li>视频1</li>
          </ul>
        </div>
        <div id="bottom" align="center">
            <dl>
                <dt>结尾选项1</dt>
                <dd><a href="https://jersay727.github.io/gushi/">打开百度</a></dd>
                <dt>结尾选项2</dt>
                <dd><a href="#tips">返回开始</a></dd>
            </dl>
        </div>

    </div>


</body>
</html>
