<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m7wo_9l7m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="m7wo_9l7m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:shield" {...props}></Icon>
