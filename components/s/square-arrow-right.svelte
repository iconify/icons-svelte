<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fci3g6brk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fci3g6brk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:square-arrow-right" {...props}></Icon>
