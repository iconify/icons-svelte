<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u70fy-sno.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="u70fy-sno"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:trees" {...props}></Icon>
