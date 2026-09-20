<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/be-q5ibtf.css';
import '../../css/o/oe3dp0-yz.css';
import '../../css/x/xsj4v2blh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="be-q5ibtf"/><path class="oe3dp0-yz"/><path class="xsj4v2blh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:stirling-pdf" {...props}></Icon>
