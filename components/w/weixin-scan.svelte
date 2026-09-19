<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wbk62sb0n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="wbk62sb0n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:weixin-scan" {...props}></Icon>
