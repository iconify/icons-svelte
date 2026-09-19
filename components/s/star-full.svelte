<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/no6vztd3x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="no6vztd3x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:star-full" {...props}></Icon>
