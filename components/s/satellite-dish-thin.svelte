<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kyxml4bzt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="kyxml4bzt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pullo:satellite-dish-thin" {...props}></Icon>
