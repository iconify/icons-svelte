<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s934moo8g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="s934moo8g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:slider-horizontal-48" {...props}></Icon>
