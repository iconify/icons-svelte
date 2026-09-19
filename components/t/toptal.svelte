<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m9-ew6bma.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="m9-ew6bma"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:toptal" {...props}></Icon>
