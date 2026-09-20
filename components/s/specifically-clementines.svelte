<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bx6h-ubow.css';
import '../../css/s/sx13j5bfm.css';
import '../../css/k/k5kkv_n6l.css';
import '../../css/u/ula6avb3k.css';
import '../../css/v/vus1pgyxj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="bx6h-ubow"/><path class="sx13j5bfm"/><path class="k5kkv_n6l"/><path class="ula6avb3k"/><path class="vus1pgyxj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:specifically-clementines" {...props}></Icon>
