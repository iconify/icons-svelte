<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/unx9o7nog.css';
import '../../css/y/ycx93acmx.css';
import '../../css/i/ihmii9b0s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="unx9o7nog"/><path class="ycx93acmx"/><path class="ihmii9b0s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:wildfire-48-bold" {...props}></Icon>
