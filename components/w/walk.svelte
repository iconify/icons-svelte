<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h7zv2cbtr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":280,"height":464};
const content = `<path class="h7zv2cbtr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:walk" {...props}></Icon>
