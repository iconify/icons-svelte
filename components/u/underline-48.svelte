<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/izgvhmbwi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="izgvhmbwi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:underline-48" {...props}></Icon>
