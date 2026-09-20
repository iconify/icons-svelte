<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yfyluc_9u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="yfyluc_9u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:scaleway-light" {...props}></Icon>
