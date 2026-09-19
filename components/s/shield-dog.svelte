<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bjhr-bb8r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="bjhr-bb8r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:shield-dog" {...props}></Icon>
