<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kmg9kobid.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="kmg9kobid"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:settings" {...props}></Icon>
