<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fkpslib-l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fkpslib-l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:text-start-a" {...props}></Icon>
