<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m20auyf3s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":432,"height":472};
const content = `<path class="m20auyf3s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:rss-icon" {...props}></Icon>
