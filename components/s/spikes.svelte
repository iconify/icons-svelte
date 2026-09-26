<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cnly0yy0l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="cnly0yy0l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="at-icons:spikes" {...props}></Icon>
