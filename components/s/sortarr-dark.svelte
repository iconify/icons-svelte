<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e7vmbpvxl.css';
import '../../css/f/flopf26xs.css';
import '../../css/g/gra5yw4ra.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<circle class="e7vmbpvxl"/><path class="flopf26xs"/><path class="gra5yw4ra"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:sortarr-dark" {...props}></Icon>
