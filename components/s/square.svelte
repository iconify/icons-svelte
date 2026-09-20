<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k0-q9nbjj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k0-q9nbjj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:square" {...props}></Icon>
