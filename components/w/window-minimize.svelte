<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ug51cgjtq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ug51cgjtq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-regular:window-minimize" {...props}></Icon>
