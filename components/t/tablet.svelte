<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vuj4p-a8q.css';
import '../../css/j/j8hs3szgb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="vuj4p-a8q"/><path class="j8hs3szgb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:tablet" {...props}></Icon>
