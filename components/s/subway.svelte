<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vvj_c3ucr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1536,"height":1792};
const content = `<path class="vvj_c3ucr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:subway" {...props}></Icon>
