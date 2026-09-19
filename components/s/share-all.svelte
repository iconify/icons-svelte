<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cn79_h0_p.css';
import '../../css/q/qt5cq3bzf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="cn79_h0_p"/><path class="qt5cq3bzf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:share-all" {...props}></Icon>
