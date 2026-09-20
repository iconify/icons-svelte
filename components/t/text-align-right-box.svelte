<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t-9m9rnsc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t-9m9rnsc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:text-align-right-box" {...props}></Icon>
