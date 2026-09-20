<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jr0ri2bsc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="jr0ri2bsc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:water-tap-with-drinking-glass" {...props}></Icon>
