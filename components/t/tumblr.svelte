<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gcuh318km.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":960,"height":1664};
const content = `<path class="gcuh318km"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:tumblr" {...props}></Icon>
