<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/abaj0hbvo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="abaj0hbvo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:tsdproxy-dark" {...props}></Icon>
