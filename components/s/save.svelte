<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q0c_hvufd.css';
import '../../css/h/h3q-mcb9s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="q0c_hvufd"/><path class="h3q-mcb9s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:save" {...props}></Icon>
