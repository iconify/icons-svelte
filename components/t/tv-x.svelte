<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ouc-p8bhp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ouc-p8bhp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:tv-x" {...props}></Icon>
