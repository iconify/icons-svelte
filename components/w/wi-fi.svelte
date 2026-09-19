<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h01tyzbfu.css';
import '../../css/a/az38-2bov.css';
import '../../css/a/azk4kkbbo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="h01tyzbfu"><path class="az38-2bov"/><path class="azk4kkbbo"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="guidance:wi-fi" {...props}></Icon>
