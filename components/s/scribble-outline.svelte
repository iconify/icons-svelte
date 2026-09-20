<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zoba4e2xk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="zoba4e2xk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:scribble-outline" {...props}></Icon>
