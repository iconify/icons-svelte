<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vsqhrhbep.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="vsqhrhbep"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:utility-meter-with-droplet" {...props}></Icon>
