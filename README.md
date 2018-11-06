# 4d-component-tinymce-editor

## Update-History
- Nov. 2018 4D update to v16 

## Further links
- https://www.tiny.cloud/docs/
- https://www.tiny.cloud/get-tiny/custom-builds/
- https://www.tiny.cloud/get-tiny/language-packages/

## Your own setup
In the html file you can adjust your own preferences. See the online documentation: https://www.tiny.cloud/docs/.
As an example in the component the current setup: (../Resources/tinymce/htmleditor.html)

	<script>tinymce.init({
		plugins: 'link code',
		selector:'textarea',
		resize: true,
		width : '100%',
		height : '80%',
		menu : 'newdocument undo redo visualaid cut copy paste ...',
		toolbar: 'newdocument undo redo bold styleselect italic underline  alignleft  bullist numlist outdent indent link removeformat code'
	});</script>