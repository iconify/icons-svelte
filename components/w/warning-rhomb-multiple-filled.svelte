<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s2gjix1mg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="s2gjix1mg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:warning-rhomb-multiple-filled" {...props}></Icon>
