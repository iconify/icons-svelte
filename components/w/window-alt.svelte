<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/umrv9kb7n.css';
import '../../css/q/qx05z4bvk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="umrv9kb7n"/><path class="qx05z4bvk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:window-alt" {...props}></Icon>
