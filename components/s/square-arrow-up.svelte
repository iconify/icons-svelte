<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ywp2qzbfd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ywp2qzbfd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:square-arrow-up" {...props}></Icon>
