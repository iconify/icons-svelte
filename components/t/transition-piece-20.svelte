<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rgu7rtifi.css';
import '../../css/z/zo-uulbpt.css';
import '../../css/b/b_y3iwjuc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="rgu7rtifi"/><path class="zo-uulbpt"/><path class="b_y3iwjuc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:transition-piece-20" {...props}></Icon>
