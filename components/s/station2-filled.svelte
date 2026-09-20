<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/g/gxfzg3ajy.css';
import '../../css/x/xuod9ccmn.css';
import '../../css/z/znudi822w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="gxfzg3ajy"/><path class="xuod9ccmn"/><path clip-rule="evenodd" class="znudi822w"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:station2-filled" {...props}></Icon>
