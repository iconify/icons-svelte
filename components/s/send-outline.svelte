<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aq9h4pbcf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="aq9h4pbcf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:send-outline" {...props}></Icon>
