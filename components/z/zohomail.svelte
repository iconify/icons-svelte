<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fxwjsibxu.css';
import '../../css/t/trpnkyp1z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="fxwjsibxu"/><path class="trpnkyp1z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:zohomail" {...props}></Icon>
