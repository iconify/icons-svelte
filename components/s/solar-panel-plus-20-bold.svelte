<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jsqrtwbgr.css';
import '../../css/y/y3ygpgbwz.css';
import '../../css/e/eia-tm77s.css';
import '../../css/f/fd646mbuc.css';
import '../../css/e/ehc07rbtk.css';
import '../../css/r/r1fb64blm.css';
import '../../css/r/rfbbfrbbx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="jsqrtwbgr"/><path class="y3ygpgbwz"/><path class="eia-tm77s"/><path class="fd646mbuc"/><path class="ehc07rbtk"/><path class="r1fb64blm"/><path class="rfbbfrbbx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:solar-panel-plus-20-bold" {...props}></Icon>
