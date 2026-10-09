<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dny5eubpk.css';
import '../../css/l/l2cqzcbfa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="dny5eubpk"/><path class="l2cqzcbfa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:user-lock-20-bold" {...props}></Icon>
