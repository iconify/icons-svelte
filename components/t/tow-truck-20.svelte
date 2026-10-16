<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i-nvxs2oj.css';
import '../../css/v/v7l69tbtr.css';
import '../../css/k/ka-asdb9s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="i-nvxs2oj"/><path class="v7l69tbtr"/><path class="ka-asdb9s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:tow-truck-20" {...props}></Icon>
