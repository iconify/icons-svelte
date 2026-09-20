<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rhdv5acbv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="rhdv5acbv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:shark" {...props}></Icon>
