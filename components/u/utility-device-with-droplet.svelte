<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eb5nd5bnv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="eb5nd5bnv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:utility-device-with-droplet" {...props}></Icon>
