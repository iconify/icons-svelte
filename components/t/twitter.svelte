<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/youkbbcbw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="cls-1 youkbbcbw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="formkit:twitter" {...props}></Icon>
