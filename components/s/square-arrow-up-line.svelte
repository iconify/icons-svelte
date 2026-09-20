<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dta8wy3ag.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dta8wy3ag"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:square-arrow-up-line" {...props}></Icon>
