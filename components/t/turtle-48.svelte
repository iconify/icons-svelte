<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/goe_lpbge.css';
import '../../css/f/fq6fmdr9f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="goe_lpbge"/><path class="fq6fmdr9f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:turtle-48" {...props}></Icon>
