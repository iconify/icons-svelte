<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bhwezzbsp.css';
import '../../css/b/b_21f101v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="bhwezzbsp"/><path class="b_21f101v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:tanker-truck-20" {...props}></Icon>
