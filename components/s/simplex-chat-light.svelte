<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zrb6tcbsq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="zrb6tcbsq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:simplex-chat-light" {...props}></Icon>
