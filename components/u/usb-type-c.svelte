<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q3_4s2eta.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="q3_4s2eta"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:usb-type-c" {...props}></Icon>
