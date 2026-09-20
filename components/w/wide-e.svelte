<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mmllqbc3i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="mmllqbc3i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:wide-e" {...props}></Icon>
