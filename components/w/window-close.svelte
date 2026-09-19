<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mglnvccod.css';
import '../../css/x/xzv0t0boi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mglnvccod"/><path class="xzv0t0boi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:window-close" {...props}></Icon>
