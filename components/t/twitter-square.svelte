<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q3y7vob_d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="q3y7vob_d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-brands:twitter-square" {...props}></Icon>
