<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n4i99xbag.css';
import '../../css/y/yh894zb-l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="n4i99xbag"/><circle class="yh894zb-l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ooui:user-group-rtl" {...props}></Icon>
