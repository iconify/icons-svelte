<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xyj-u1l1e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xyj-u1l1e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:safe-shield-2-line" {...props}></Icon>
