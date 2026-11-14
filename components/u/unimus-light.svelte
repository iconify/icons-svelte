<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/un65ooazk.css';
import '../../css/w/wlb9i1ctt.css';
import '../../css/k/kpzxgnq_j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="un65ooazk"/><path class="wlb9i1ctt"/><path class="kpzxgnq_j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:unimus-light" {...props}></Icon>
