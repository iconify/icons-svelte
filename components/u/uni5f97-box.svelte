<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e-eb4i-dl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="e-eb4i-dl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:uni5f97-box" {...props}></Icon>
