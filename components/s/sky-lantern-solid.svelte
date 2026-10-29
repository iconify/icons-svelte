<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/x/x-7kuccws.css';
import '../../css/m/mnp9e5b6g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="wm-k x-7kuccws"/><path class="mnp9e5b6g wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:sky-lantern-solid" {...props}></Icon>
