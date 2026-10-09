<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/djc8x4bhg.css';
import '../../css/i/i24xrk73t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="djc8x4bhg"/><path class="i24xrk73t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:saf-48-bold" {...props}></Icon>
