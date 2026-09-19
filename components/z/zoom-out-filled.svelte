<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ykxdrx_sp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="ykxdrx_sp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:zoom-out-filled" {...props}></Icon>
