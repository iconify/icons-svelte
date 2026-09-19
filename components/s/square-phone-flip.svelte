<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y__td5brh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="y__td5brh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:square-phone-flip" {...props}></Icon>
