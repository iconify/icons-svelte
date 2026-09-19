<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h5plgss1t.css';
import '../../css/r/r8af-vbfd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="h5plgss1t"/><path class="r8af-vbfd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:trash" {...props}></Icon>
