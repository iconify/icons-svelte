<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wj71hlv2d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="wj71hlv2d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-brands:sitrox" {...props}></Icon>
