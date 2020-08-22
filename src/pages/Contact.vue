<template>
   <Layout>
      <h1>Contact Us</h1>
      <div>
        
        <br>
        <h2>Getform.io - Gridsome Contact Form Example</h2>
            <form autocomplete="off" accept-charset="UTF-8" action="https://getform.io/f/e17c8d17-64a2-436f-809c-effafbb33f38" enctype="multipart/form-data" method="POST"  target="_blank">
                <div>
                    <label>Full Name</label>
                    <div>
                        <input style="margin-top: 5px; background-color: #fff; height:35px; width:235px; text-indent: 5px; border-radius:5px;" 
                        type="text" name="first_name" placeholder="Enter your name and surname" required="required" autocomplete="new-password">
                    </div>
                </div>
                <br>
                <div>
                    <label>Email address</label>
                    <div>
                        <input style="margin-top: 5px;background-color: #fff; height:35px; width:235px; text-indent: 5px; border-radius:5px;" 
                        type="email" name="email" placeholder="Enter your email address" required="required" autocomplete="off">
                    </div>
                </div>
                <br>
                <div>
                    <label for="favourite-platform">Favourite Static Site Generator</label>
                    <div>
                        <select style="margin-top: 5px; background-color: #fff; height:40px; width:245px; text-indent: 5px; border-radius:5px;" 
                        class="form-control" id="favourite-platform" name="platform" required="required">
                        <option>Gridsome</option>
                        <option>Jekyll</option>
                        <option>Vuepress</option>
                        </select>
                    </div>
                </div>
                <div style="margin-top: 15px;">
                    <label >Upload a file:</label>
                    <input style="margin-left: 5px" type="file" name="file" required="required">
                </div>
                <br>
                <input type="hidden" name="utf8" value="✓">
                <button style="font-size:14px; background-color:#6b7ddf; color:#fff; font-weight:bold; padding:10px 35px; margin: 5px 0 0 0;    
                    border: 1px solid; border-radius: 5px;" 
                    type="submit">SUBMIT</button>
            </form>
        </div>
      </div>
   </Layout>
</template>

<script>
export default {
  metaInfo: {
    title: 'About us'
  }
}
</script>
