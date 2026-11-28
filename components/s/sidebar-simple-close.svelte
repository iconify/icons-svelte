<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mbi79f4ad.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="mbi79f4ad"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pullo:sidebar-simple-close" {...props}></Icon>
