<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tjh5jabrj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="tjh5jabrj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pullo:satellite-dish" {...props}></Icon>
