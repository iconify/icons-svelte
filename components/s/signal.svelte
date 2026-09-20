<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l-vdk0s_v.css';
import '../../css/z/z0v-de56k.css';
import '../../css/h/hxkc6pbym.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="l-vdk0s_v"/><path class="z0v-de56k"/><path class="hxkc6pbym"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:signal" {...props}></Icon>
