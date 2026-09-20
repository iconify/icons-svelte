<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/epd4lwbvd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="epd4lwbvd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:sidebar-left-16-solid" {...props}></Icon>
