<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/np56-gb_v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="np56-gb_v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:square-up-right" {...props}></Icon>
