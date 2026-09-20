<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xrsdmp1_y.css';
import '../../css/t/tjg9g-oad.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="xrsdmp1_y"/><path class="tjg9g-oad"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:verdaccio" {...props}></Icon>
