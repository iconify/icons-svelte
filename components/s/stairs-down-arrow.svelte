<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pxzzg3bol.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pxzzg3bol"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="guidance:stairs-down-arrow" {...props}></Icon>
