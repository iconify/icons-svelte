<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r62amn8ij.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r62amn8ij"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:x-circle" {...props}></Icon>
