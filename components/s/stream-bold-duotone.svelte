<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gn_f1tn5f.css';
import '../../css/d/ddsunemne.css';
import '../../css/h/htpdpeg8u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gn_f1tn5f"/><path class="ddsunemne"/><path class="htpdpeg8u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:stream-bold-duotone" {...props}></Icon>
