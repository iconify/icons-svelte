<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/ddrfoxb_v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":512};
const content = `<path class="ddrfoxb_v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:stop" {...props}></Icon>
