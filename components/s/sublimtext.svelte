<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mlyur0l4y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="mlyur0l4y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:sublimtext" {...props}></Icon>
