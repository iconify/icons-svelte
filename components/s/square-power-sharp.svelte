<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aegt__b5d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="aegt__b5d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:square-power-sharp" {...props}></Icon>
