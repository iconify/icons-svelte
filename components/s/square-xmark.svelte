<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/diaox2bxh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="diaox2bxh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:square-xmark" {...props}></Icon>
