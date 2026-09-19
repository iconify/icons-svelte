<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/it3rg1bvf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":512};
const content = `<path class="it3rg1bvf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:ruble-sign" {...props}></Icon>
