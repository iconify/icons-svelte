<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lgeuypctf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="lgeuypctf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:rupiah-sign" {...props}></Icon>
