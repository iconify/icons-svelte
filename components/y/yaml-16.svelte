<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f89eheb4g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="f89eheb4g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nonicons:yaml-16" {...props}></Icon>
