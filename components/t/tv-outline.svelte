<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/axrqxtt4y.css';
import '../../css/l/l8k158baf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<rect class="axrqxtt4y"/><path class="l8k158baf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:tv-outline" {...props}></Icon>
