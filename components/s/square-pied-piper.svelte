<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zcc6q1bxt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="zcc6q1bxt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-brands:square-pied-piper" {...props}></Icon>
