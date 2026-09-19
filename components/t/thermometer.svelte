<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t-6--gb1e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="t-6--gb1e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:thermometer" {...props}></Icon>
