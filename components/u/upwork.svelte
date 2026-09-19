<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fxj3tdbao.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":641,"height":512};
const content = `<path class="fxj3tdbao"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-brands:upwork" {...props}></Icon>
