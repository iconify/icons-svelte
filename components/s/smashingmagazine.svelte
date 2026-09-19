<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u7avee-fi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="u7avee-fi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:smashingmagazine" {...props}></Icon>
