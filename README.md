# Jquery-image-upload-preview-delete
this is image upload and filter non-image objects and used for the image uploading tasks

<input type="file"  id="fileupload" name="fileupload">

use this example id name must give the script file

<div id="dvPreview"></div>

display the div function preview images id

                        <div id="dvPreview"></div>
                        <span class=" btn btn-primary btn-file">
                               Upload Logo <input type="file"  id="fileupload" name="fileupload">
                        </span>
                        
                        
                        
  <style>
    .remove_img_preview {
        position:relative;
        top:-25px;
        right:5px;
        background:black;
        color:white;
        border-radius:50px;
        font-size:0.9em;
        padding: 0 0.3em 0;
        text-align:center;
        cursor:pointer;
    }
    .remove_img_preview:before {
        content:"×";
    }
</style>
