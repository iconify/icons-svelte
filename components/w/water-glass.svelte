<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mlu4xcbir.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mlu4xcbir"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:water-glass" {...props}></Icon>
