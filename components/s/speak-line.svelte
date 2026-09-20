<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xjq3w6t5c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xjq3w6t5c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:speak-line" {...props}></Icon>
