<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/temu-lr3v.css';
import '../../css/n/nbj6_5v5v.css';
import '../../css/t/t6587jiay.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="temu-lr3v"/><path class="nbj6_5v5v"/><path class="t6587jiay"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:ship-20-bold" {...props}></Icon>
