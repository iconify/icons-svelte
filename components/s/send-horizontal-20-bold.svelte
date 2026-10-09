<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/akipzwbge.css';
import '../../css/e/eimh7-87y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="akipzwbge"/><path class="eimh7-87y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:send-horizontal-20-bold" {...props}></Icon>
