<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rqzuu5bav.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="rqzuu5bav"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:telescope-radio" {...props}></Icon>
