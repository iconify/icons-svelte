<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oqa0afbxi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="oqa0afbxi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pullo:stack-simple-plus" {...props}></Icon>
