<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qiy6cs5ry.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="qiy6cs5ry"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:squat-rock-with-inscription" {...props}></Icon>
