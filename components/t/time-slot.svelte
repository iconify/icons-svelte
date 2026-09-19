<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n050cnbpt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="n050cnbpt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="entypo:time-slot" {...props}></Icon>
