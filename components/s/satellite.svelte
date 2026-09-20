<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mpjyrl2cd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="mpjyrl2cd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:satellite" {...props}></Icon>
