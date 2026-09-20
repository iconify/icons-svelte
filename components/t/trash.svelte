<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xqn9hibsu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="xqn9hibsu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oui:trash" {...props}></Icon>
