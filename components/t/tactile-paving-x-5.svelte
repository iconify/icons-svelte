<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mny6kj1pr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="mny6kj1pr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:tactile-paving-x-5" {...props}></Icon>
