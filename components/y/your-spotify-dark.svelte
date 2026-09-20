<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/trb9ibbhz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="trb9ibbhz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:your-spotify-dark" {...props}></Icon>
