<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rk1z5mbzq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rk1z5mbzq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:spray" {...props}></Icon>
