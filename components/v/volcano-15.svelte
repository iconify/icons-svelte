<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tps-tw1ja.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="tps-tw1ja"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="maki:volcano-15" {...props}></Icon>
