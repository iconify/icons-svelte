<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m0elrnbcf.css';
import '../../css/j/j5257yb9v.css';
import '../../css/y/ydnb04iod.css';
import '../../css/y/ymie1nvqo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="m0elrnbcf"/><circle class="j5257yb9v"/><path class="ydnb04iod"/><path class="ymie1nvqo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:temperature-celsius" {...props}></Icon>
