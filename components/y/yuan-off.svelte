<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/r/r9gst35sp.css';
import '../../css/k/kfm7curke.css';
import '../../css/j/j96uhbcif.css';
import '../../css/n/n3yxckbfl.css';
import '../../css/m/mo5netbri.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="r9gst35sp"/><path clip-rule="evenodd" class="kfm7curke"/><path clip-rule="evenodd" class="j96uhbcif"/><path clip-rule="evenodd" class="n3yxckbfl"/><path class="mo5netbri"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons-pencil:yuan-off" {...props}></Icon>
