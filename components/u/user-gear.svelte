<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bvs4s8b2p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="bvs4s8b2p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:user-gear" {...props}></Icon>
