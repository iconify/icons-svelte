<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/ds994zbvl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ds994zbvl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:social-rewards-flag" {...props}></Icon>
