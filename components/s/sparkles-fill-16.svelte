<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mscab2bma.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="mscab2bma"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:sparkles-fill-16" {...props}></Icon>
