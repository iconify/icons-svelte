<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uvzj0b48k.css';
import '../../css/x/xg6ua4r-y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uvzj0b48k"/><path class="xg6ua4r-y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:yinyang-line" {...props}></Icon>
