<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x1dbcvb1r.css';
import '../../css/y/yiwa8gb3t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="x1dbcvb1r"/><path class="yiwa8gb3t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:shapes-outline" {...props}></Icon>
