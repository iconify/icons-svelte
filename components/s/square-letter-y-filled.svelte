<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wcm4wp_7m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wcm4wp_7m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:square-letter-y-filled" {...props}></Icon>
