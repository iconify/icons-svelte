<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g1nbikbny.css';
import '../../css/j/jmf54fbtj.css';
import '../../css/t/tbtey3bjo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="g1nbikbny"/><path class="jmf54fbtj"/><path class="tbtey3bjo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:sidebar-close-bold-duotone" {...props}></Icon>
