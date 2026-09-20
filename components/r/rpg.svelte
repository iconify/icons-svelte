<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jxh105bzq.css';
import '../../css/l/lr2vlobkm.css';
import '../../css/y/y6nfipdrl.css';
import '../../css/b/bd0nzvbjr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jxh105bzq"/><path class="lr2vlobkm"/><path class="y6nfipdrl"/><path class="bd0nzvbjr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:rpg" {...props}></Icon>
