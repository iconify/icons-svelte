<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lal__dzbo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="lal__dzbo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:text-right" {...props}></Icon>
