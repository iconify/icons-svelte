<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h8flh6_xz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="h8flh6_xz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:swatchbook" {...props}></Icon>
