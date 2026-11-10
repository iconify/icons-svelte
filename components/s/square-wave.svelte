<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ie-z9d60e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ie-z9d60e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="at-icons:square-wave" {...props}></Icon>
