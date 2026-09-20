<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k9ly5k7oj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k9ly5k7oj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:wall" {...props}></Icon>
