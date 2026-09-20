<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/otfa01r4d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="otfa01r4d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:square-chevron-up" {...props}></Icon>
