<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jes5hmb-c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="jes5hmb-c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pullo:wc-bold" {...props}></Icon>
