<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k5kweu8nd.css';
import '../../css/y/yj9yfrb2m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="k5kweu8nd"/><path class="yj9yfrb2m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:screen" {...props}></Icon>
