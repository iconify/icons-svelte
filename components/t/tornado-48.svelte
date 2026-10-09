<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zr_7szbsp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="zr_7szbsp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:tornado-48" {...props}></Icon>
