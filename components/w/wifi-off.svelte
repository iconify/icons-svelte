<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jd6pj_b9o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jd6pj_b9o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:wifi-off" {...props}></Icon>
