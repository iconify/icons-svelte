<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vmz2nobkl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="vmz2nobkl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:square-16-solid" {...props}></Icon>
