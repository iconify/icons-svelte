<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c9mz1tb_r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="c9mz1tb_r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:t-mobile-light" {...props}></Icon>
