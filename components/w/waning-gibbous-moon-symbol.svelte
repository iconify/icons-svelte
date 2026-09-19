<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q1z8q8b9y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="q1z8q8b9y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:waning-gibbous-moon-symbol" {...props}></Icon>
