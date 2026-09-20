<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fag4w5bml.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="fag4w5bml"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ooui:table" {...props}></Icon>
