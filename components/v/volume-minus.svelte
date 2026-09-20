<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jzwt4eysc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jzwt4eysc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:volume-minus" {...props}></Icon>
