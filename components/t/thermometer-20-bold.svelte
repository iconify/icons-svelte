<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rbl6phbau.css';
import '../../css/o/ostwlt0as.css';
import '../../css/g/gh3kikb4e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="rbl6phbau"/><path class="ostwlt0as"/><path class="gh3kikb4e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:thermometer-20-bold" {...props}></Icon>
