<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mnlnjbcmb.css';
import '../../css/o/ozxr3zrwe.css';
import '../../css/j/j-_c-dbxp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="mnlnjbcmb"/><path class="ozxr3zrwe"/><path class="j-_c-dbxp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:save-series" {...props}></Icon>
