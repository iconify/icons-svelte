<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v0im_gbxt.css';
import '../../css/t/t1ca65brz.css';
import '../../css/t/tw6980btg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="v0im_gbxt"/><path class="t1ca65brz"/><path class="tw6980btg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:snapchat" {...props}></Icon>
