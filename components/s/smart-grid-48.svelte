<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rsjqddezd.css';
import '../../css/d/ds9x_zbhf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="rsjqddezd"/><path class="ds9x_zbhf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:smart-grid-48" {...props}></Icon>
