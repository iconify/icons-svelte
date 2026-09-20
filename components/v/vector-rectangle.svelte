<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rllqu9bus.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rllqu9bus"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:vector-rectangle" {...props}></Icon>
