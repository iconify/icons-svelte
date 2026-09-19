<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jd0jblbxb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="jd0jblbxb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-brands:square-upwork" {...props}></Icon>
