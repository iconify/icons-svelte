<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wv_j0tbdn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="wv_j0tbdn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:user-settings" {...props}></Icon>
