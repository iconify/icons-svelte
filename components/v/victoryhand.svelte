<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g1unvhb9q.css';
import '../../css/i/inkg4h-8v.css';
import '../../css/l/lcly8xbdq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="g1unvhb9q"/><path class="inkg4h-8v"/><path class="lcly8xbdq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:victoryhand" {...props}></Icon>
