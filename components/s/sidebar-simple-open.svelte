<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gda9zkbbt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="gda9zkbbt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pullo:sidebar-simple-open" {...props}></Icon>
