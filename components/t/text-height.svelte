<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uxebszz2b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":576,"height":512};
const content = `<path class="uxebszz2b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:text-height" {...props}></Icon>
