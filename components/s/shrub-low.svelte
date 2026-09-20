<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hgkw-vbvi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="hgkw-vbvi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="temaki:shrub-low" {...props}></Icon>
