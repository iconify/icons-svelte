<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/as3aqyb5d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="as3aqyb5d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:tipi-campsite-and-droplet" {...props}></Icon>
