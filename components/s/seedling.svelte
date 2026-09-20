<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hil72j73a.css';
import '../../css/j/ji2y3-dyw.css';
import '../../css/u/ub6hd3a0n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="hil72j73a"/><path class="ji2y3-dyw"/><path class="ub6hd3a0n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:seedling" {...props}></Icon>
