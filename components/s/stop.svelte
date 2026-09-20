<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tba065b6y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="tba065b6y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oui:stop" {...props}></Icon>
