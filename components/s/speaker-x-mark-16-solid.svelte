<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m6xsvfb5o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="m6xsvfb5o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:speaker-x-mark-16-solid" {...props}></Icon>
