<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rnq4f9bwa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rnq4f9bwa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:shopify" {...props}></Icon>
