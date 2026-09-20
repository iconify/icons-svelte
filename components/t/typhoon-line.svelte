<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xdb0sxb4a.css';
import '../../css/x/x14f6wb8c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xdb0sxb4a"/><path class="x14f6wb8c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:typhoon-line" {...props}></Icon>
