<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m231y5u4n.css';
import '../../css/c/cfsdedcbv.css';
import '../../css/e/e8un-zbtr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m231y5u4n"/><path class="cfsdedcbv"/><circle class="e8un-zbtr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="circum:square-info" {...props}></Icon>
