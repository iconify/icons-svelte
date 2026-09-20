<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ee3w8bc4b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="ee3w8bc4b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oi:timer" {...props}></Icon>
