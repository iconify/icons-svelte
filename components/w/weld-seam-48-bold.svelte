<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vmvltcbxl.css';
import '../../css/f/fhr9nlrmx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="vmvltcbxl"/><path class="fhr9nlrmx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:weld-seam-48-bold" {...props}></Icon>
