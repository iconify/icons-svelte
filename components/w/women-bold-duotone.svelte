<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/esxisibaw.css';
import '../../css/e/ejfpiglxl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<circle class="esxisibaw"/><path class="ejfpiglxl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:women-bold-duotone" {...props}></Icon>
