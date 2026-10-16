<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qifb4r4in.css';
import '../../css/w/wtve9fz8c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="qifb4r4in"/><path class="wtve9fz8c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:usb-c-48" {...props}></Icon>
