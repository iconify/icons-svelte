<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/so8jkf05e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="so8jkf05e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:tv" {...props}></Icon>
