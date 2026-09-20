<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gxl2eck4h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="gxl2eck4h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:stock" {...props}></Icon>
