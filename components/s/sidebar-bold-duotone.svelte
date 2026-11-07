<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g1nbikbny.css';
import '../../css/l/lq958rfxi.css';
import '../../css/y/yy5pkcb2v.css';
import '../../css/v/vhokyxbgc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="g1nbikbny"/><path class="lq958rfxi"/><path class="yy5pkcb2v"/><path class="vhokyxbgc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:sidebar-bold-duotone" {...props}></Icon>
