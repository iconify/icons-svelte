<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h4-haccyb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":21,"height":24};
const content = `<path class="h4-haccyb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:shopify" {...props}></Icon>
