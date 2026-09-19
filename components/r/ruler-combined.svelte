<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z0zyy8ctg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="z0zyy8ctg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:ruler-combined" {...props}></Icon>
