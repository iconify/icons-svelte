<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w-6k85rjb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="w-6k85rjb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:soup" {...props}></Icon>
