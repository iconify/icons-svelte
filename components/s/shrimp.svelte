<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/s/s92qk0c1o.css';
import '../../css/i/i9l7f6f9f.css';
import '../../css/s/sj5y__bmo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="s92qk0c1o"/><path class="i9l7f6f9f"/><path class="sj5y__bmo"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:shrimp" {...props}></Icon>
