<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rkxt-8bvb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="rkxt-8bvb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:uruguay" {...props}></Icon>
