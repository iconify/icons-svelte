<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ln87rknis.css';
import '../../css/c/ceswd_37u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ln87rknis"/><path class="ceswd_37u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:wave" {...props}></Icon>
