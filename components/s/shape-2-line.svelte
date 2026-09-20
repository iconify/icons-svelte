<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sl_q4-bkr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sl_q4-bkr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:shape-2-line" {...props}></Icon>
