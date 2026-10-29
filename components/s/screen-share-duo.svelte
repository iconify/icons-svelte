<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/t/tu0-m0rqe.css';
import '../../css/j/jmku5acuo.css';
import '../../css/c/csac9jvtl.css';
import '../../css/v/vxuqhab0r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="tu0-m0rqe"/><path class="jmku5acuo wm-s"/><path class="csac9jvtl"/><path class="vxuqhab0r wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:screen-share-duo" {...props}></Icon>
