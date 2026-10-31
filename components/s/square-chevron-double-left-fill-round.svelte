<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hjs_si8ps.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hjs_si8ps"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:square-chevron-double-left-fill-round" {...props}></Icon>
