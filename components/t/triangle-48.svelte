<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rn67wgblz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="rn67wgblz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:triangle-48" {...props}></Icon>
