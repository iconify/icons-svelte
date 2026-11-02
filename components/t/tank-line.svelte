<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wnv3q6b_e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wnv3q6b_e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:tank-line" {...props}></Icon>
