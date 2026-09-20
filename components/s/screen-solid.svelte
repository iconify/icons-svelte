<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kova1rb8c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="kova1rb8c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:screen-solid" {...props}></Icon>
