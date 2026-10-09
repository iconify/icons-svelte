<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h92e2tbsy.css';
import '../../css/i/i_nsi3ucm.css';
import '../../css/p/p4-i55byq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="h92e2tbsy"/><path class="i_nsi3ucm"/><path class="p4-i55byq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:wood-stove-20-bold" {...props}></Icon>
