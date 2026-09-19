<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ig-sq8kjs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":832};
const content = `<path class="ig-sq8kjs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:webhostinghub" {...props}></Icon>
