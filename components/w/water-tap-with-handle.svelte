<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gx3flsb5x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="gx3flsb5x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:water-tap-with-handle" {...props}></Icon>
