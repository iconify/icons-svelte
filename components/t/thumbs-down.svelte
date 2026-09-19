<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h6nmeno7s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="h6nmeno7s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:thumbs-down" {...props}></Icon>
