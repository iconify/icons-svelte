<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jc26ied2w.css';
import '../../css/z/zrv1yxb_h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="jc26ied2w"/><path class="zrv1yxb_h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:roundcube-light" {...props}></Icon>
