<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xv61dmbjf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="xv61dmbjf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:vr-headset-outline" {...props}></Icon>
