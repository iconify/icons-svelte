<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i6r_tccsq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="i6r_tccsq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:shield-alt" {...props}></Icon>
