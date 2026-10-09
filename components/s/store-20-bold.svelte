<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sjo2tqb0v.css';
import '../../css/s/sw3irebjg.css';
import '../../css/x/x-qw326ms.css';
import '../../css/i/i51_k7tim.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="sjo2tqb0v"/><path class="sw3irebjg"/><path class="x-qw326ms"/><path class="i51_k7tim"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:store-20-bold" {...props}></Icon>
