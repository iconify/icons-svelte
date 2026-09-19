<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ygyd9kulc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":24};
const content = `<path class="ygyd9kulc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:underline" {...props}></Icon>
