<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oe_46l15z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="oe_46l15z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nonicons:tmux-16" {...props}></Icon>
