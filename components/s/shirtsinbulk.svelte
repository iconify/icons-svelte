<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uxh3rob4u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1536,"height":1760};
const content = `<path class="uxh3rob4u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:shirtsinbulk" {...props}></Icon>
