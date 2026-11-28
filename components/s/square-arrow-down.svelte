<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m4gs8zqfn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m4gs8zqfn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:square-arrow-down" {...props}></Icon>
