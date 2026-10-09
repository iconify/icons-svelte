<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ljgv6abmg.css';
import '../../css/x/xhptmubfq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ljgv6abmg"/><path class="xhptmubfq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:silo-20-bold" {...props}></Icon>
