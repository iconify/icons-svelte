<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gogk23mvb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="gogk23mvb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:utility-valve-with-gas-flame" {...props}></Icon>
