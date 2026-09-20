<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sxi5sdbal.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="sxi5sdbal"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:wordpress-light" {...props}></Icon>
