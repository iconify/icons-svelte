<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h01tyzbfu.css';
import '../../css/j/j27ze1b2l.css';
import '../../css/j/jdxgfcblx.css';
import '../../css/f/fh-xrsb1t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="h01tyzbfu"><path class="j27ze1b2l"/><circle class="jdxgfcblx"/><path class="fh-xrsb1t"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:sertificate-light" {...props}></Icon>
