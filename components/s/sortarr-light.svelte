<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rcadwc-xf.css';
import '../../css/k/kdwpv2bov.css';
import '../../css/a/a-z8z7pww.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<circle class="rcadwc-xf"/><path class="kdwpv2bov"/><path class="a-z8z7pww"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:sortarr-light" {...props}></Icon>
