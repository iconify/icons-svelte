<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mf25d2r7d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":384};
const content = `<path class="mf25d2r7d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:vibration" {...props}></Icon>
