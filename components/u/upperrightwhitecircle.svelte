<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yf9n4lb9d.css';
import '../../css/z/zdtpxix4e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="yf9n4lb9d"/><circle class="zdtpxix4e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:upperrightwhitecircle" {...props}></Icon>
