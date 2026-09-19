<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sf5_5ebiv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1536,"height":1664};
const content = `<path class="sf5_5ebiv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:text-width" {...props}></Icon>
