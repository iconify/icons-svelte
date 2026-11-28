<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r8b0dutxn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r8b0dutxn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:tree" {...props}></Icon>
