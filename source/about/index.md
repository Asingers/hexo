title: 关于
date: 2015-11-17 19:45:12
tags:
  - resume
categories:
  - 关于
---

<select onchange= "onLanChange(this.options[this.options.selectedIndex].value)">
    <option value="0" selected> 中文 Chinese </option>
    <option value="1"> 英语 English </option>
</select>

<!-- Chinese Version -->
<div class="zh">
    <blockquote>
        写写代码，搭搭博客，看看电影。
        世界那么大，多玩玩看看。
    </blockquote>
    <img src="http://7xqmgj.com1.z0.glb.clouddn.com/201607095.jpeg" alt="" class="shadow"/><br>
    世界就像个巨大的马戏团，它让你兴奋，却让我惶恐，因为我知道散场永远是——有限温存，无限辛酸。 

</div>

<!-- English Version -->
<div class="en">
    <blockquote>
        Designer or Engineer, things in between.
    </blockquote>

    <p>
        Your work is going to fill a large part of your life, and the only way to be truly satisfied is to do what you believe is great work. And the only way to do great work is to love what you do. If you haven’t found it yet, keep looking. Don’t settle. As with all matters of the heart, you’ll know when you find it.
    </p>

    <p>
    If you want to live your life in a creative way, as an artist, you have to not look back too much. You have to be willing to take whatever you’ve done and whoever you were and throw them away.
    </p>

    <p style="text-align:right;">
    -- Steve Jobs
    </p>

</div>

<!-- Handle Language Change -->
<script type="text/javascript">
    var $zh = document.querySelector(".zh");
    var $en = document.querySelector(".en");
    function onLanChange(index){
        if(index == 0){
            $zh.style.display = "block";
            $en.style.display = "none";
        }else{
            $en.style.display = "block";
            $zh.style.display = "none";
        }
    }
    onLanChange(0);
</script>




