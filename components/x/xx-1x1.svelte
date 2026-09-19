<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cb76bo8sb.css';
import '../../css/w/wvlg02bvg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="cb76bo8sb"/><path class="wvlg02bvg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flag:xx-1x1" {...props}></Icon>
