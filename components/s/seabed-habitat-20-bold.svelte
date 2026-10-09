<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yv842m9yr.css';
import '../../css/u/um4pykb1b.css';
import '../../css/d/d8en99qry.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="yv842m9yr"/><path class="um4pykb1b"/><path class="d8en99qry"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:seabed-habitat-20-bold" {...props}></Icon>
